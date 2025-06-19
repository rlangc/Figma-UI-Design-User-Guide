# Installing SolidWorks 2024 on macOS (Workaround Guide)

> ⚠️ **Important Note:** SolidWorks 2024 does not have a native macOS version.  
> This guide outlines methods for running SolidWorks on a Mac using virtualization or emulation. These are **unofficial** and may not be supported by Dassault Systèmes.

---

## 🖥️ Prerequisites

| Requirement              | Details                                             |
|--------------------------|-----------------------------------------------------|
| Mac Model                | Intel Mac (recommended) or Apple Silicon (M1/M2/M3) |
| RAM                      | 16 GB minimum (32 GB recommended)                   |
| Storage                  | At least 100 GB free                                |
| OS Version               | macOS 13 Ventura or later                           |
| Windows License          | Full retail copy of Windows 10/11 (64-bit)         |
| SolidWorks License       | SolidWorks 2024 serial number                       |

---

## 🛠️ Option 1: Install Using Parallels Desktop (Recommended for M1/M2/M3 Macs)

### Step 1: Install Parallels Desktop
- Download and install [Parallels Desktop for Mac](https://www.parallels.com/products/desktop/)
- Requires paid license for Pro features (recommended for SolidWorks)

### Step 2: Install Windows in Parallels
- Use the built-in wizard to install **Windows 11 ARM** (for Apple Silicon) or **Windows 10/11 x64** (for Intel Macs)
- Complete Windows setup and updates

### Step 3: Allocate Resources
- Open Parallels Control Center → Configure the VM:
  - CPU: Allocate at least 4 cores
  - RAM: Allocate 8–16 GB
  - Graphics: Enable **Auto or High Performance**

### Step 4: Install SolidWorks 2024
- Download the **SolidWorks Installation Manager** inside Windows
- Follow standard [Windows installation steps](./Install_SolidWorks_2024_Windows.md)
- Activate SolidWorks with your license key

---

## 🛠️ Option 2: Boot Camp (Intel Macs Only)

> ❗ **Boot Camp is not available on Apple Silicon Macs (M1/M2/M3)**

### Step 1: Use Boot Camp Assistant
- Open **Boot Camp Assistant** (Applications → Utilities)
- Partition your drive and install **Windows 10 x64**

### Step 2: Install SolidWorks
- Boot into Windows using the Boot Camp partition
- Install SolidWorks as you would on a Windows PC
- Use native GPU drivers for best performance

---

## 🛠️ Option 3: Cloud-Based Alternatives

- Use a **cloud-hosted SolidWorks environment**, such as:
  - [MySolidWorks Online](https://my.solidworks.com/)
  - [VDI or remote access to a SolidWorks workstation]
- These options require stable internet and enterprise setup

---

## ✅ Tips for Success

- 💾 Use SSD storage and plenty of RAM for smooth performance
- 🔁 Keep Windows and Parallels updated
- 🧰 Consider using SolidWorks **lightweight mode** for large assemblies
- 🖱️ External mouse recommended for CAD usability

---

## 🚫 Limitations & Known Issues

| Issue                            | Workaround/Notes                                      |
|----------------------------------|--------------------------------------------------------|
| No native Mac version            | Must use virtualization or cloud                      |
| Graphics performance may lag     | Use certified GPU drivers and allocate more VRAM      |
| ARM architecture incompatibility | Limited plugin/support for some add-ons               |
| No Boot Camp on Apple Silicon    | Use Parallels instead                                 |

---

## 📎 Additional Resources

- [Parallels + SolidWorks Support Thread (Forum)](https://forum.solidworks.com/)
- [Dassault Systemes: Supported Platforms](https://www.solidworks.com/support/hardware-certification)
- [Boot Camp Assistant User Guide](https://support.apple.com/guide/bootcamp-assistant)

---

> ℹ️ While not officially supported, many users successfully run SolidWorks on macOS using these methods. Performance will vary based on your Mac model and configuration.
