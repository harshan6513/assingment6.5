
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 24px 16px;
  font-family: Arial, sans-serif;
  color: #26344a;
  background: #eef2f8;
}

.page-container {
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
  text-align: center;
}

.page-container > h1 {
  color: #243b64;
  margin-bottom: 28px;
}

.profile-card {
  position: relative;
  width: 100%;
  max-width: 360px;
  margin: 0 auto;
  padding: 32px 24px 26px;
  background: white;
  border: 1px solid #d5deeb;
  border-radius: 18px;
  box-shadow: 0 10px 28px #243b6418;
  overflow-wrap: break-word;
}

.profile-badge {
  position: absolute;
  top: 16px;
  right: 16px;
  z-index: 1;
  padding: 6px 10px;
  border-radius: 20px;
  background: #d9f5e4;
  color: #176b3a;
  font-size: 11px;
  font-weight: bold;
  letter-spacing: 0.5px;
}

.profile-image {
  display: block;
  width: 120px;
  height: 120px;
  max-width: 100%;
  margin: 12px auto 18px;
  border: 4px solid #e2eaf7;
  border-radius: 50%;
  object-fit: cover;
}

.profile-name {
  margin: 10px 0 4px;
  color: #243b64;
  font-size: 26px;
}

.profile-role {
  margin: 0 0 18px;
  color: #4d72ac;
  font-weight: bold;
}

.profile-description {
  font-size: 14px;
  line-height: 1.7;
  color: #5d6879;
}

.skills-section {
  margin-top: 22px;
}

.skills-section h3 {
  font-size: 16px;
}

.skills-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 8px;
  padding: 0;
  list-style: none;
}

.skills-list li {
  padding: 7px 12px;
  border: 1px solid #d5e0f2;
  border-radius: 20px;
  background: #f1f5fc;
  font-size: 12px;
}

.contact-button {
  display: block;
  width: 100%;
  margin-top: 24px;
  padding: 13px 18px;
  border-radius: 8px;
  background: #315b9a;
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.2s ease;
}

.contact-button:hover {
  background: #243b64;
}

.footer-text {
  margin-top: 28px;
  color: #68758a;
  font-size: 13px;
}

@media (max-width: 400px) {
  body {
    padding: 16px 10px;
  }

  .profile-card {
    padding: 28px 18px 22px;
  }

  .profile-image {
    width: 100px;
    height: 100px;
  }
}
