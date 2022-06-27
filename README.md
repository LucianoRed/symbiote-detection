# symbiote-detection
Playbooks Ansible to detect Symbiote Malware
Checks:
- Check for hidden files
- Check for open suspicious ports
- Check if syslogk is present
- Check for LD_PRELOAD variable
- Check if /etc/ld.so.preload exists

# Populate files
In folder files/ you can fill files.txt, ports.txt and processes.txt with new discovered files

## TODO
For this version, we don't check hidden process yet.