# ONE WORLD Launcher

**[ดาวน์โหลดรุ่นล่าสุด / Latest release](https://github.com/Chain-Chan/owscum-release/releases/latest)**

## ภาษาไทย

### คืออะไร
mod เสริมฝั่งผู้เล่นสำหรับเซิร์ฟ SCUM **ONE WORLD**: **มินิแมพ** มุมขวาบน (`Home` เปิด / ปิด • `End` ซูม) และ **PDA ของทีม**
(`Insert`: สมาชิก squad, เรดาร์ 100 ม., ข้อความ squad + `/ping`) — ใส่และถอดให้โดย ONE WORLD Launcher บน Windows

### ติดตั้ง 3 ขั้น
1. โหลด `OneWorldLauncher-0.5.1.zip` (ชื่อไฟล์ใช้เลขรุ่นของ Launcher) จาก release ล่าสุด → คลิกขวา → Properties → ติ๊ก **Unblock** → OK
2. แตก zip ไว้ที่ไหนก็ได้ → ได้โฟลเดอร์ `ONE WORLD Launcher` + `LICENSE.txt` / `NOTICE.txt`
3. ในโฟลเดอร์นั้นดับเบิลคลิก **`ONE WORLD Launcher.exe`** → กด **"เข้าเล่น ONE WORLD"** • Windows ขึ้น "Windows protected your PC" (Launcher
   ไม่มีลายเซ็นโค้ด) → **More info → Run anyway** • อย่าปิดหน้าต่าง Launcher ระหว่างเล่น

### ⚠️ BattlEye
**"เข้าเล่น ONE WORLD"** เปิด SCUM **แบบไม่มี BattlEye** พร้อม mod — ใช้กับเซิร์ฟ ONE WORLD เท่านั้น **ห้ามเข้าเซิร์ฟอื่นจากเกมนั้น**
เล่นเซิร์ฟอื่นให้กด **"เล่นแบบปกติ (ถอด MOD)"** → ขึ้น `Game folder is clean` → เกมเปิดผ่าน Steam พร้อม BattlEye • ออกเกมแล้ว Launcher ถอด mod ให้เอง

### ปลอดภัยไหม
- ไม่มีตัวติดตั้ง ไม่ขอสิทธิ์ admin ไม่แก้การตั้งค่า Windows • ไฟล์ที่เขียน: ในโฟลเดอร์เกม `SCUM\Binaries\Win64\dwmapi.dll` +
  `SCUM\Binaries\Win64\ue4ss\` (UE4SS 4.0.0 + mod) เฉพาะตอนเล่น ONE WORLD • `%LOCALAPPDATA%\OneWorldLauncher` • `%LOCALAPPDATA%\OWMiniMap.ini` / `OWPDA.ini` (ตำแหน่งหน้าต่าง)
- ทุกไฟล์ที่โหลดอยู่ใน manifest ที่เซ็นไว้ (ECDSA P-256) พร้อม SHA-256 — ไม่ตรง = ไม่ใช้ • สคริปต์เป็น PowerShell ข้อความธรรมดา เปิดอ่านได้ •
  `ONE WORLD Launcher.exe` เป็นแค่หน้าต่างครอบสคริปต์ (ไม่มีลายเซ็นโค้ด — SHA-256 อยู่ใน `launcher.json` ที่เซ็นแล้ว + `SHA256SUMS.txt`)
- เทียบไฟล์ที่โหลดกับ `SHA256SUMS.txt` ใน release: `Get-FileHash .\OneWorldLauncher-0.5.1.zip`
- VirusTotal: https://www.virustotal.com/gui/file/f40ed53371a4ac19d69ca903d33a4f69c6f25b13747006649a44d797f1e42e8d (3 / 62 — heuristic / machine-learning flags on a new unsigned file)
  
### ข้อตกลงการใช้งาน (ย่อจาก `LICENSE.txt` — อ่านฉบับเต็มใน release)
ใช้ได้เพื่อเล่นบนเซิร์ฟ ONE WORLD เท่านั้น • ห้ามคัดลอก แจกต่อ อัปโหลดที่อื่น แก้ หรือใช้กับเซิร์ฟ / mod / ตัวเปิดเกมอื่น • แจกฟรี ห้ามขาย
หรือเก็บเงิน • ไม่ใช่ของทางการ • ใช้ตามสภาพ ไม่มีการรับประกัน

### เครดิต
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) 4.0.0 — MIT License, Copyright (c) 2022 Narknon (ข้อความเต็มใน `NOTICE.txt`) •
  Launcher โหลดจากหน้า release ทางการของ UE4SS (ล็อก SHA-256) • `UE4SS-settings.ini` ในชุดนี้ = ไฟล์ของ UE4SS ที่ปรับค่าบางตัว
- งานของแฟนเกม ไม่เกี่ยวข้องและไม่ได้รับการรับรองจากผู้พัฒนาหรือผู้จัดจำหน่าย SCUM — SCUM เป็นเครื่องหมายการค้าของเจ้าของ

## English

### What it is
Optional client mods for the **ONE WORLD** SCUM server: a **minimap** in the top right (`Home` show / hide • `End` zoom) and a team
**PDA** (`Insert`: squad members, 100 m radar, squad messages + `/ping`), put in and taken out by the ONE WORLD Launcher for Windows.

### Install (3 steps)
1. Download `OneWorldLauncher-0.5.1.zip` (named after the launcher version) from the latest release → right-click → Properties → tick **Unblock** → OK.
2. Unzip it anywhere → you get the `ONE WORLD Launcher` folder + `LICENSE.txt` / `NOTICE.txt`.
3. In that folder double-click **`ONE WORLD Launcher.exe`** → press **"เข้าเล่น ONE WORLD"** (Play ONE WORLD). If Windows says
   "Windows protected your PC" (the launcher is not code-signed): **More info → Run anyway**. Keep the launcher window open while you play.

### ⚠️ BattlEye
**"เข้าเล่น ONE WORLD"** starts SCUM **without BattlEye** and with the mods. Use it **only** for the ONE WORLD server — **never join any
other server from that game.** For other servers press **"เล่นแบบปกติ (ถอด MOD)"** (Play normal, mods removed) → `Game folder is clean` →
SCUM starts through Steam with BattlEye. The mods are also removed automatically when the game closes.

### Is it safe?
- No installer, no admin rights, no Windows setting changed. It writes: in the SCUM folder `SCUM\Binaries\Win64\dwmapi.dll` +
  `SCUM\Binaries\Win64\ue4ss\` (UE4SS 4.0.0 + the mods), only while you play ONE WORLD • `%LOCALAPPDATA%\OneWorldLauncher` •
  `%LOCALAPPDATA%\OWMiniMap.ini` / `OWPDA.ini` (window places).
- Every download is listed in a signed manifest (ECDSA P-256) with its SHA-256; anything that does not match is refused. The scripts are
  plain-text PowerShell — open and read them. `ONE WORLD Launcher.exe` is only a window over the scripts (not code-signed; its SHA-256 is in
  the signed `launcher.json` and in `SHA256SUMS.txt`).
- Check your download against `SHA256SUMS.txt` in the release: `Get-FileHash .\OneWorldLauncher-0.5.1.zip`
- VirusTotal: https://www.virustotal.com/gui/file/f40ed53371a4ac19d69ca903d33a4f69c6f25b13747006649a44d797f1e42e8d (3 / 62 — heuristic / machine-learning flags on a new unsigned file)

### Terms of use (short form of `LICENSE.txt` — read the full file in the release)
Only for playing on ONE WORLD servers • no copying, sharing, re-uploading, changing, or use with other servers / mods / launchers •
free, never sold or charged for • unofficial • provided "as is", without warranty.

### Credits
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) 4.0.0 — MIT License, Copyright (c) 2022 Narknon (full text in `NOTICE.txt`). The launcher
  downloads it from its official GitHub release (SHA-256 pinned). `UE4SS-settings.ini` here is its file with some settings changed.
- Unofficial fan-made content, not affiliated with or endorsed by the developers or publishers of SCUM. SCUM is a trademark of its owners.
