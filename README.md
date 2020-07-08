# Multiple Subdomain/Domain on One Public IP
1. Create your subdomains in your domain and point it to your Public IP
   - if you have dynamic public ip, use ddns
2. In your router, create  DMZ pointing to your reverse proxy [mikrotik or nginx server]
   - if you have dynamix publix IP, also set ddns configurations in router
