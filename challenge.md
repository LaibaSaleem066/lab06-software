
# Challenge: Install It Yourself

1. Job: Install htop and write one thing it shows.
Command: sudo apt install -y htop
Answer: htop shows real-time CPU usage, memory usage, and process list.

2. Job: Version of apache2 offered without installing.
Command: apt show apache2 | head -n 5
Answer: Shows available apache2 version in Ubuntu repository.

3. Job: Count of installed packages on server.
Command: apt list --installed | wc -l
Answer: Total count of installed packages.

4. Job: Run alpine image with Docker to print "Hello from Alpine".
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Answer: Hello from Alpine

5. Job: Full path of Docker key file and sources file.
Command: ls /etc/apt/keyrings/docker.asc /etc/apt/sources.list.d/docker.sources
Answer: Key file: /etc/apt/keyrings/docker.asc, Sources file: /etc/apt/sources.list.d/docker.sources

6. Job: Remove htop and prove it is gone.
Command: sudo apt remove -y htop && hash -r && htop
Answer: Command 'htop' not found message returned.

