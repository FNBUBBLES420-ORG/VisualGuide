## VisualGuide™ – Quick Troubleshooting & Manual Fix Guide

If you are having any issues, you can **join our Discord** — new features and improvements will be based on **community feedback from you all**. 💙

---

## When the Desktop Icon or Install Isn’t Working

If:

* The **desktop icon is not working correctly**, or
* After installation you see errors like:

  * `python is not recognized` / **Python not in PATH**
  * **CUDA isn’t installed correctly**

You can use the **backup setup folder** to fix things manually.

---

## 1️⃣ Open the VisualGuide Backup Setup Folder

Go to:

```text
C:\Program Files\VisualGuide\visualguide-backup\setup
```

In this folder, you will find:

* `install_cuda.exe`
* The **Python installer EXE**
* The **cuDNN ZIP** file

You can rerun these manually if something didn’t install correctly.

---

## 2️⃣ Fixing CUDA / cuDNN (NVIDIA Only)

If CUDA or cuDNN didn’t install correctly:

1. In the `setup` folder, locate the **cuDNN ZIP** file.
2. Extract **all contents** of the cuDNN ZIP into this folder:

```text
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.8
```

> If asked to **replace files**, choose **Yes** / **Replace**.

You can also rerun:

* `install_cuda.exe` from the same `setup` folder if CUDA did not install.

---

## 3️⃣ Checking If Python Is in PATH

1. Open **Command Prompt (CMD.exe)**.
2. Type:

```text
python --version
```

3. If you see:

```text
Python 3.11.9
```

then Python is **installed correctly** and **in your PATH**.

If not, rerun the **Python installer EXE** from:

```text
C:\Program Files\VisualGuide\visualguide-backup\setup
```

and make sure to check **“Add python.exe to PATH”** during installation.

---

## 4️⃣ Manually Fixing the Desktop Shortcut (Recommended Fix)

If the **VisualGuide desktop icon exists but does not launch**, you can manually correct the shortcut target. This is the most reliable fix if the shortcut was created incorrectly during install.

### Step-by-Step Fix

1. Go to this folder:

```text
C:\Program Files\VisualGuide\visualguide-backup
```

2. Locate:

```text
run-application.bat
```

3. **Right-click** `run-application.bat`
   → Click **Copy as path**

4. On your **Desktop**, right-click the **VisualGuide** shortcut
   → Select **Properties**

5. In the **Target** field:

* Remove everything currently there
* **Paste the copied path** to `run-application.bat`

6. In the **Start in** field, make sure it is set to:

```text
C:\Program Files\VisualGuide
```

7. Click **Apply**, then **OK**

After this, launching VisualGuide from the **desktop icon** should work correctly.

---

## Need Help?

If you’re stuck at any step:

* Join our **Discord community** for support and updates:
  🔗 [https://fnbubbles420.org/discordinvite](https://fnbubbles420.org/discordinvite)

Our community and dev team are there to help, and your feedback will guide **future improvements** to VisualGuide™.
