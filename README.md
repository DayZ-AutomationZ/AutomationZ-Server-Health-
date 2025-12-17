# AutomationZ Server Health with (optional) discord webhook [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R51QD7BU)
[![Dashboard_Server_Health.png](https://i.postimg.cc/c46CBGny/Dashboard_Server_Health.png)](https://postimg.cc/mtfTTqj8)
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

## Credits

---

### 💚 Support the project

AutomationZ tools are built for server owners by a server owner.  
If these tools save you time or help your community, consider supporting development.

☕ Ko-fi: https://ko-fi.com/dannyvandenbrande  
💬 Discord: https://discord.gg/6g8EPES3BP  

Created by **Danny van den Brande**  
DayZ AutomationZ


Part of the **AutomationZ** project  
Built to reduce admin workload and remove unnecessary manual server management.

If this tool saves you time or stress, consider supporting development.
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R51QD7BU)
