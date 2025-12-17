# AutomationZ Server Health

AutomationZ Server Health is a lightweight, no-mod monitoring tool for game servers and other FTP-accessible servers.

It continuously checks server log files, crash indicators, and restart behavior — and alerts you only when something actually goes wrong.

Designed primarily for DayZ server owners, but flexible enough for any game or service that writes logs to disk.

---

## Why this tool exists

Server owners cannot watch logs 24/7.

Crashes, script errors, infinite restart loops, or broken configs often happen when:
- You are asleep
- You are away for the weekend
- The server restarts automatically

AutomationZ Server Health acts as a silent watchdog.
You only get notified when something important changes.

---

## Key features

- No DayZ mod required
- FTP / FTPS based
- Multi-server profiles
- Error / warning detection
- Discord webhook alerts
- Manual fetch or continuous monitoring

---

## How event tracking works

- Events show only NEW warnings or errors
- Clearing events acknowledges them
- If nothing new happens, no events appear (this is correct behavior)

---

The application automatically creates its working folders
(logs, reports, log_cache) on startup.
These folders store runtime logs, detected events, and cached
log positions to ensure only new issues are reported.


## License

MIT License

Created by Danny van den Brande
AutomationZ
