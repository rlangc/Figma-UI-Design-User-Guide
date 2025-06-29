# 👥 User Roles and Permissions Chart

This chart outlines common user roles in software systems and their associated permissions. Use it as a reference for user onboarding, troubleshooting, or defining access rights in documentation and support materials.

---

## 🔐 Role Definitions

| Role        | Description |
|-------------|-------------|
| **Admin**   | Full access to all system settings, users, content, and security options. Can install/uninstall software, manage licenses, and modify global configurations. |
| **Power User** | High-level permissions to use advanced features and settings. May not be able to manage users or licensing. |
| **Standard User** | Can access core system features necessary for day-to-day use. Cannot alter system-wide settings. |
| **Viewer**   | Read-only access. Can view data or dashboards but cannot make changes. |
| **Guest**    | Limited, temporary access to specific tools, content, or sessions. Often time-restricted or use-case-specific. |

---

## 🗂️ Permissions Matrix

| Feature / Action                  | Admin | Power User | Standard User | Viewer | Guest |
|----------------------------------|:-----:|:----------:|:-------------:|:------:|:-----:|
| Install/Uninstall Software       | ✅    | ❌         | ❌            | ❌     | ❌    |
| Access Admin Dashboard           | ✅    | ✅         | ❌            | ❌     | ❌    |
| Modify User Accounts             | ✅    | ❌         | ❌            | ❌     | ❌    |
| Change System Settings           | ✅    | ✅         | ❌            | ❌     | ❌    |
| Create/Edit Content              | ✅    | ✅         | ✅            | ❌     | ❌    |
| View Content                     | ✅    | ✅         | ✅            | ✅     | ✅    |
| Export/Download Data             | ✅    | ✅         | ✅            | ❌     | ❌    |
| Participate in Collaboration     | ✅    | ✅         | ✅            | ❌     | ✅    |

---

## 🧩 Use Case Scenarios

- **Admins** manage license activations, troubleshoot enterprise-wide issues, and audit user logs.
- **Standard Users** represent the majority of your user base using features but not altering system configurations.
- **Guests** are ideal for external reviewers or one-time contractors needing limited access.

---

## 📌 Notes

- Always apply the **Principle of Least Privilege**—only grant the minimum access necessary for a user to complete their role.
- Document user rights within your onboarding and setup guides for clarity and transparency.

