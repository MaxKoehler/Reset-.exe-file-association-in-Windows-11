# 🔧 Reset `.exe` File Association in Windows 11

If Windows suddenly stops opening executable files (`.exe`) correctly or the default association has been changed, this can cause significant problems. This guide and the provided registry file help **reset the default association** safely.

---

## 🧩 What Does the `.reg` File Do?

The registry file performs the following actions:

1. **Removes all user-specific overrides** for the `.exe` extension in the current user profile.  
2. **Restores the default registry entries** for the file type **"executable file"** (ProgID: `exefile`).

---

## ⚙️ How to Use It

1. **Download** the file: [`reset_exe_associations.reg`](./reset_exe_associations.reg)  
2. **Create a system restore point** or back up your registry.  
3. **Apply the file**:  
   - Right-click → **Merge**, or  
   - Open it in a text editor and apply manually.  
4. **Restart your PC** to apply the changes.

---

## ⚠️ Disclaimer

These instructions and files are provided **without any warranty**.  
Editing the Windows registry can cause your system to stop working properly.  
Please **back up your data and registry** before making any modifications.

---

**Author:** Maximilian Köhler  
**File:** `reset_exe_associations.reg`  
**Compatibility:** Windows 11  
**License:** Free to use at your own risk
