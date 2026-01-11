Linux Services - Day 5

A service is a program that the system is responsible for keeping running.

Key differences:
- A process is something running right now
- A service is a managed process that starts automatically and can restart

Linux uses systemd to manage services.

systemd responsibilities:
- Start services at boot
- Stop services cleanly
- Restart failed services
- Track service health
- Collect logs

Key commands:
- systemctl list-units --type=service
- systemctl status <service>

Service states:
- loaded     : systemd knows about the service
- active     : the service is considered healthy
- running    : the service has an active process
- exited     : the service completed its job successfully

Example:
cron.service runs scheduled background tasks and stays active without user interaction.

Services are how servers and cloud systems operate without logged-in users.
