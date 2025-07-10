# 📧 ps_modern_smtp_m365 — Microsoft 365 SMTP with OAuth2 for PrestaShop

A secure and modern PrestaShop module for sending transactional emails through Microsoft 365 using **OAuth2 (MFA-compatible)** and the **Microsoft Graph API**.

> 🔐 No need for legacy SMTP passwords — fully supports Modern Authentication (OAuth2) and complies with Microsoft security requirements.

---

## ✨ Features

- ✅ Send email using Microsoft 365 accounts via Graph API
- 🔐 OAuth2 authentication with support for MFA (multi-factor auth)
- 📤 Supports "Send As" address override (with permission check)
- 🔄 Auto-refresh tokens (no need to reauthorize frequently)
- 🧪 Built-in test email function
- 🛡️ Secure credential handling and token encryption
- 💬 Spanish and English UI localization

---

## 🛍️ Purchase the Module

🎉 Available now for commercial use:

👉 **[Buy Now](https://payhip.com/b/VGn7b{:target="_blank"})**

---

## 📦 Installation

1. Upload the module `.zip` file via your PrestaShop admin panel.
2. Configure the Microsoft 365 credentials:
   - Tenant ID
   - Client ID
   - Client Secret
   - Redirect URI (automatically generated)
3. Click **Authorize with Microsoft** to connect your account.
4. Optionally enable **Send As override** and set the From address.
5. Send a test email to verify your configuration.

---

## 🔧 Microsoft Azure Setup

1. Register an app at [Azure Portal](https://portal.azure.com)
2. Set up the following **permissions**:
   - `Mail.Send (delegated)`
   - `SMTP.Send (delegated)`
   - `User.Read`
   - `offline_access`
   - `openid`, `email`
3. Add your PrestaShop redirect URI
4. Generate a **client secret**
5. Paste credentials into module settings

---

## 📚 Documentation

Full documentation is included in the module ZIP and also available on my [Portfolio Page](https://fomencuccini.tech/MyProjects/ModernSMTP.html#documentation {:target="_blank"}.
---

## 🤝 Support

Need help or custom features?

📩 Contact me: [fo.mencuccini@gmail.com](mailto:fo.mencuccini@gmail.com)

---

## 📌 Requirements

- PrestaShop  8.x (Soon for Presta 9)
- Microsoft 365 account with proper API access

---

## 📃 License

Commercial license — lifetime access with unlimited domain usage included.

---

© 2025 Federico Mencuccini — All rights reserved.
