If you want to test on local environment
Don't forget to add this 2 lines in your /etc/hosts file:

```
127.0.0.1	a.customdomain.com
127.0.0.1	b.customdomain.com
```
customize your docker-compose.yaml for every 
environment:
  VIRTUAL_HOST: with your custom domain in local

Other references
https://gbesar.com/main/baca/Multi%20Https%20pada%20satu%20VPS%20dengan%C2%A0Docker/all

other github
https://github.com/kassambara/nginx-multiple-https-websites-on-one-server


Sample running project
file:///home/lifepc/Pictures/custom-domain-docker.png![image](https://user-images.githubusercontent.com/56695534/159642087-88759e28-f200-4e6c-bfa6-c89ea135eaae.png)

