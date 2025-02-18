**Service Management:**

Effective server management relies on specific commands, often referred to as service management commands. These commands enable administrators to control and monitor the state and behavior of server services. Below are some commonly used commands for managing the Nginx web server:

1. **Check the Status of Nginx:**
   - Command: `sudo systemctl status nginx`
   - This command provides detailed information about the current state of the Nginx service, including whether it is active (running) or inactive (stopped), along with additional logs.

2. **Start the Nginx Service:**
   - Command: `sudo systemctl start nginx`
   - Use this command to initiate the Nginx service. It will start the service if it is not already running.

3. **Stop the Nginx Service:**
   - Command: `sudo systemctl stop nginx`
   - This command halts the running Nginx service. It is useful when you need to temporarily disable the web server.

4. **Restart the Nginx Service:**
   - Command: `sudo systemctl restart nginx`
   - This command stops and then starts the Nginx service. It is useful for applying configuration changes without having to stop the service completely.

5. **Reboot the System:**
   - Command: `sudo reboot`
   - This command reboots the entire server. Use it when system-wide changes require a restart.

6. **Enable Nginx to Start on Boot:**
   - Command: `sudo systemctl enable nginx`
   - This command configures the system to automatically start the Nginx service at boot time, ensuring the web server is always available after a restart.

Using these commands effectively will help maintain the performance and reliability of your server's services.

