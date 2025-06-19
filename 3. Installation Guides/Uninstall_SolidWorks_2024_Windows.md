# Uninstalling SolidWorks 2024 – Windows Guide

This guide provides step-by-step instructions to fully uninstall **SolidWorks 2024** from a Windows system, including all associated components and registry entries (optional).

---

## ⚠️ Before You Begin

- 📂 Back up any custom templates, toolboxes, or macro files  
- 📝 Record your **serial number** for future use  
- 💾 Optional: Create a **System Restore Point**  

---

## 🔧 Method 1: Standard Uninstall via Control Panel

### 1. Open Control Panel
- Press `Win + R`, type `control`, and press Enter  
- Go to **Programs → Programs and Features**

### 2. Locate SolidWorks
- Find **SolidWorks 2024** in the list  
- Right-click → **Uninstall/Change**

### 3. Launch the Installation Manager
- Select **Remove** and click **Next**  
- Choose:
  - ✅ SolidWorks application  
  - ✅ Associated Add-ins (eDrawings, Composer, CAM, etc.)  
- Optional: Check **“Also remove the SOLIDWORKS installation directory”**

### 4. Complete the Process
- Click **Remove Now**  
- Wait for uninstallation to complete  
- Restart your computer when prompted  

---

## 🧹 Method 2: Complete Manual Removal (Advanced)

Use this if:
- You encounter uninstall errors  
- You want to fully clean out residual files and registry entries  

### 1. Delete Installation Folders

Remove the following directories (if they still exist):

```
C:\Program Files\SOLIDWORKS Corp\
C:\ProgramData\SOLIDWORKS\
C:\Users\YourUsername\AppData\Local\SOLIDWORKS\
```

> 💡 **Tip:** Enable hidden items in File Explorer to access `AppData`.

---

### 2. Clean the Windows Registry (Optional & Risky)

> ⚠️ Only proceed if you're comfortable with editing the registry. Mistakes can cause system instability.

- Press `Win + R`, type `regedit`, and press Enter  
- Navigate to and carefully delete these keys:

```
HKEY_CURRENT_USER\Software\SolidWorks
HKEY_LOCAL_MACHINE\SOFTWARE\SolidWorks
```

- Always back up your registry before making changes  

---

## 🧪 Verify Uninstall

After removal:
- Launch the **SolidWorks Installation Manager** — it should no longer detect any installed products  
- Check that no desktop shortcuts or start menu entries remain  
- Confirm available disk space has increased (~10–20 GB)  

---

## 📎 Additional Resources

- [How to Remove All SolidWorks Files](https://www.solidworks.com/support)  
- [SolidWorks Knowledge Base: Clean Uninstall Steps](https://www.solidworks.com/support/knowledge-base)  
- [Registry Backup Guide (Microsoft)](https://support.microsoft.com/en-us/help/322756)  

---

> 🧼 A clean uninstall ensures better results when reinstalling or upgrading future versions.
