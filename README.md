Create a long-running systemd service that logs to a file.

task: https://roadmap.sh/projects/dummy-systemd-service

1. Create a script ``dummy.sh``
2. Add permissions using command: ``chmod + x dummy.sh``
3. Create ``dummy.service`` file in ``/etc/systemd/system``
4. Enable service using command: `` sudo systemctl enable dummy ``
5. Check whether service is working `` sudo systemctl status dummy ``
