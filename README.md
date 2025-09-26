# Elevate-Labs-Internship--Task-4
Task 4
1.Install UFW(Uncomplicated Firewall) in linux by entering the code "sudo apt install ufw"
2.Now to enable the UFW, Enter the code "sudo ufw enable"
3.Now to check the status, Enter the code "sudo ufw status"
4.To know the current firewall rules in UFW, Enter the code "sudo ufw status verbose"
5.Now to add rule to inbound traffic on port 23. Enter the code "sudo ufw deny 23/tcp"
6.Now to test the ruleby attempting to connect the port 23. Install telnet intially to connect
7.Enter "telnet 127.0.0.1 23" and it shows UNABLE TO CONNECT TO REMOTE HOST
8.To add rule to allow SSH(port 22) is "sudo ufw allow 22/tcp"
9.Now to remove the test block, Enter "sudo ufw delete deny 23/tcp". do the same to port 22 too.
10.How firewall Filters traffic:
              A firewall works like a security guard for your computer or network, standing at the “doors” (ports) where data enters and leaves. Every time traffic tries to pass through, the firewall checks it against a set of rules you’ve defined. If the rules say “allow,” the traffic is let in or out; if they say “deny,” the traffic is blocked. If no rule matches, the firewall follows its default policy (commonly allowing outgoing connections but denying incoming ones). In simple terms, it filters all network traffic to decide what’s safe to pass and what should be stopped.
