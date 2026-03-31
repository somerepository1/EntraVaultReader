# EntraVault — Microsoft Entra ID Security Dashboard

**EntraVault** is a lightweight, browser-based security posture dashboard for Microsoft Entra ID (formerly Azure AD). It provides a read-only, real-time assessment of your tenant's security configuration, compliance against global frameworks (CIS, NIST, ISO), and identity hygiene.

Because EntraVault leverages a pre-configured multi-tenant application, it requires **zero installation, zero database, and zero app registration**. Just open the file and sign in.

---

## 🚀 Getting Started

It literally takes 5 seconds to run:

1. **Download** or clone the `index.html` file.
2. **Open** `index.html` directly in your web browser (Edge, Chrome, Safari, etc.).
3. **Sign in** with your Microsoft administrator account. 
4. **Grant read permissions** (if prompted) to view your tenant's security posture.

*That's it. No App Registrations, no client secrets, and no infrastructure required.*

---

## 🛡️ Security & Privacy First

EntraVault is designed with a **Zero-Trust** approach to your data:
* **100% Client-Side:** All logic, API calls, and rendering happen directly in your browser. Your data never leaves your local session or touches a third-party server.
* **Secure Authentication:** Uses Microsoft's OAuth2 PKCE (Proof Key for Code Exchange) flow.
* **Read-Only Access:** The tool requests `Read` permissions only. It is fundamentally incapable of modifying your tenant configuration.
* **No Persistence:** No tokens or tenant data are stored in permanent storage. Once you close the tab, the session is gone.

---

## ✨ Key Features

### 📊 Compliance Engine
Automatically maps your tenant configuration against:
* **CIS** Microsoft 365 Foundations Benchmark
* **NIST** 800-53
* **ISO** 27001
* **MITRE ATT&CK** (Cloud Matrix)

### 🔐 Identity & Access Monitoring
* **Conditional Access Audit:** Deep-dive into CA policies with an expandable view of inclusions, exclusions, and grant controls.
* **MFA Analysis:** Real-time check of Authentication Methods (FIDO2, Authenticator, SMS) and their enforcement.
* **Privileged Account Hygiene:** Monitoring for Global Admin sprawl and guest users holding administrative roles.

### 📈 Secure Score & Events
* **Improvement Actions:** Direct integration with Microsoft Secure Score to prioritize security gaps.
* **High-Severity Events:** A live feed of sensitive operations, including app consents and role changes.
* **Reporting:** Export your full compliance assessment to **CSV** or a professional **HTML Report** with one click.

---

## 🛠️ Built With
* **Vanilla HTML / CSS / JavaScript (ES6+):** Zero external frameworks or dependencies for maximum security and speed.
* **Microsoft Graph API:** Utilizes both v1.0 and Beta endpoints for comprehensive coverage.
* **Fluent UI Inspired Design:** Fully responsive interface that feels native to the Microsoft ecosystem.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

> **Disclaimer:** EntraVault is an independent tool and is not affiliated with, or endorsed by, Microsoft Corporation.
