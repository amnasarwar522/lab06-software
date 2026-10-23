# Challenge: Install It Yourself

1. Command: sudo apt install -y htop, then htop
   Answer: htop shows CPU and memory (RAM) usage of the server.
2. Command: apt show apache2 | head -4
   Answer: Version 2.4.66-2ubuntu2.6
3. Command: apt list --installed | wc -l
   Answer: 734 packages
4. Command: sudo docker run --rm alpine echo "Hello from Alpine"
   Answer: It printed Hello from Alpine
5. Command: ls -l /etc/apt/keyrings/ and cat /etc/apt/sources.list.d/docker.sources
   Answer: Key: /etc/apt/keyrings/docker.asc, Sources: /etc/apt/sources.list.d/docker.sources
6. Command: sudo apt remove -y htop, hash -r, htop
   Answer: htop now says Command not found, so it is removed.      written with vim by Amna

