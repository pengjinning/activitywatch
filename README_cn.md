# 使用说明

```bash
# https://docs.activitywatch.net/en/latest/installing-from-source.html
python -m venv venv
source venv/bin/activate
make build
# There are two ways to run ActivityWatch:
# Use the trayicon manager (Recommended for normal use)
Run from your terminal with: aw-qt
# Start each module separately (Recommended for developing)
Run from your terminal with: aw-server, aw-watcher-afk, and aw-watcher-window
# For the rust server, run with: aw-server-rust/target/package/aw-server-rust
# http://localhost:5600/
```
