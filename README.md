# Latchkey

A desktop toolkit for watching and troubleshooting SQL Server.

- Live activity: CPU per core, waits, memory, file I/O latency and running requests
- Blocking and deadlock incidents, captured and kept for later review
- Query Store browsing and regression spotting
- Database, file and index views

## Download

Get `latchkey.exe` from the [latest release](https://github.com/kjustinkeener/latchkey/releases/latest) and run it. The first run offers to install it for your user account (no admin rights needed). Installed copies update themselves.

Windows 10 or 11 is required, with the WebView2 runtime (included with Windows 11 and current Windows 10).

## Notes

- Connections need a login with `VIEW SERVER STATE`.
- The updater connects to GitHub directly and ignores proxy settings. On a network that only allows traffic through a proxy, download new releases by hand.
