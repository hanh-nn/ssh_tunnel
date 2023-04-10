Add server. create account which no permit( protect data)
sudo useradd -s /bin/false -M user3
sudo passwd user3

To create connect from node to server use
ssh -f -N -R 43022:localhost:22 user3@115.79.139.66 -p 2023

From server. If want to ssh node:
ssh hanh@localhost -p 43022

