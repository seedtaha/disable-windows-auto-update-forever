# 🛠️ Disable or Enable Windows Automatic Updates via Registry

This repository provides two Windows Registry (.reg) files to help you **disable** or **enable** Windows automatic updates with a simple double-click.

## 📁 Files inside ZIP folder

- `disable_windows_auto_update.reg`  
  Disables Windows Automatic Updates by modifying a registry policy.

- `enable_windows_auto_update.reg`  
  Re-enables Windows Automatic Updates to allow your system to receive updates normally.

## 📦 How to Use

1. **Choose** the `.reg` file you wanna use.
2. **Double-click** on it.
3. If prompted, allow the Registry Editor to apply the changes.
4. **DONE.**

> ⚠️ **Important Notice**:
> - Disabling updates might expose your system to **security risks**.
> - Use this tweak only if you understand the consequences.
> - This tweak uses a supported method through the Windows registry under:
>   ```
>   HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU
>   ```

## ✅ Tested on

- Windows 11 (all editions)
- Windows 10 (Pro/Home)

> 💡 Tip: You can manually check for updates anytime via **Settings > Windows Update** even if automatic updates are disabled.

---

## 📜 License

This project is released under the [MIT License](LICENSE).

## Support

If you find this useful, feel free to star ⭐ the repo or suggest improvements via pull requests.

## Contact

Fb.com/seed.103
