Linux Services Control - Day 6

Linux services are managed by systemd.

Core service actions:
- status   : check health and state
- stop     : stop the service now
- start    : start a stopped service
- restart  : stop and start cleanly

Important distinction:
- start/stop affect the current session
- enable/disable affect behaviour at boot

Stopping a service does not damage the system if done deliberately.
Status output always reflects the true state.

Safe service used:
- cron.service

Cron was stopped, verified inactive, restarted, and verified running again.
