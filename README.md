# Inhouse Agents kurulumu

Bu depoda yalnız kurulum dosyası (`iasetup.exe`) durur. Kaynak kodu burada değildir.

## Kurulum

1. [Sürümler](../../releases) bölümünden en son `iasetup.exe` dosyasını indir.
2. İstersen dosyanın değişmediğini denetle: PowerShell'de `Get-FileHash .\iasetup.exe -Algorithm SHA256` çalıştır. Çıkan değer sürümdeki `iasetup.exe.sha256` ile aynı olmalı.
3. Dosyayı çift tıkla. Kurulum şifresini Kriter AI'dan alırsın. Uygulama dosyaları bu şifre olmadan açılmaz.

**Gereken:** Windows 10 ya da 11, 64 bit. Başka bir şey kurmak gerekmez.

**İmza uyarısı:** Kurulum dosyası henüz kod imzalı değil. Windows ilk açılışta "Windows bilgisayarınızı korudu" uyarısı gösterebilir. Dosyayı bu sayfadan indirdiysen ve SHA256 değeri tutuyorsa "Ek bilgi → Yine de çalıştır" ile devam edebilirsin.

---

This repository holds only the installer (`iasetup.exe`); the source code is not here. Download the latest `iasetup.exe` from Releases, optionally check its SHA256 against `iasetup.exe.sha256`, and double-click it. The setup password comes from Kriter AI. Requires Windows 10/11 (64-bit); nothing else.
