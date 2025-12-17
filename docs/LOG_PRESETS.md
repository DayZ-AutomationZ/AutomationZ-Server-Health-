# Log Presets (Copy/Paste)

This file is a **starter list** of log/watch ideas.  
Exact paths can differ per host, OS, and server setup — treat these as *templates*.

---

## DayZ (typical examples)

### Common “server console” style log
- Kind: `log`
- Source: `ftp`
- Path examples (varies by host):
  - `profiles/server_console.log`
  - `server_console.log`
  - `logs/server_console.log`

### Restart/maintenance script log (your custom scripts)
- Kind: `log`
- Source: `ftp`
- Path example:
  - `/restart.log`  
    (If your host drops a restart log in the FTP root)

### Crash-related
- Kind: `crash` (or `log` if you prefer)
- Source: `ftp`
- Path ideas (varies a LOT):
  - `profiles/*.rpt`
  - `crashlogs/`
  - `logs/`  

**Tip:** If you don't know the path, temporarily use FileZilla and search for:
- `.rpt`
- `crash`
- `diag`
- `console`

---

## Rust (generic ideas)

- Watch the console output log or crash log produced by your host
- Look for:
  - `oxide/logs/`
  - `server/logs/`
  - `logs/`

---

## ARK: Survival Evolved / Ascended (generic ideas)

- Common host folders:
  - `ShooterGame/Saved/Logs/`
  - `Saved/Logs/`

---

## Valheim (generic ideas)

- Dedicated server logs differ by host
- Look for:
  - `logs/`
  - `server/logs/`
  - startup scripts output

---

## How to add a preset quickly

1. Go to **Watches**
2. Press **New**
3. Set:
   - Name (example: `DayZ server_console`)
   - Enabled ✅
   - Source = `ftp`
   - Path = paste remote path
   - Kind = `log`
4. Save Changes
5. Dashboard → Fetch Now
