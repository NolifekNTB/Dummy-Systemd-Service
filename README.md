Create a long-running systemd service that logs to a file.

task: https://roadmap.sh/projects/dummy-systemd-service

1. Create a script ``dummy.sh``
2. Move using command `` sudo mv dummy.sh /usr/local/bin ``
3. Add permissions using command: ``sudo chmod + x dummy.sh``
4. Create ``dummy.service`` file in ``/etc/systemd/system``
5. Enable service using command: `` sudo systemctl enable dummy ``
6. Check whether service is working `` sudo systemctl status dummy ``
