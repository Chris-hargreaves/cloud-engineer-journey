Linux Service Boot Behaviour - Day 7

Linux separates current service state from boot behaviour.

Key distinctions:
- start / stop affect the service right now
- enable / disable affect what happens at system boot

Commands:
- systemctl start <service>
- systemctl stop <service>
- systemctl enable <service>
- systemctl disable <service>
- systemctl is-enabled <service>

A service can be:
- running but disabled at boot
- stopped but enabled at boot

systemd manages this using symbolic links tied to boot targets.

Safe service used:
- cron.service

Cron was disabled and re-enabled to demonstrate boot behaviour control without affecting the running system.
