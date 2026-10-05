The DNS was configured to the wrong output. 192.168.73.2 -- found from connectivity-evidence.txt -- is not a valid IP for the ACME internal server to allow, it requires a DNS of 10.0.0.1. This causes all hostname resolutions to fail. The IP and Gateway were correct allowing connectivity to the outside but forbade connection to any ACME servers.

Escalation Note:

I would run the windows troubleshooter first and then ipconfig /release and ipconfig /renew. If either of these fail, I escalate to get permission to find the problem within the machine.
