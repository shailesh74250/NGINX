# NGINX
Web server 

- Nginx is a web server not application server (means it not going to run any application or project code like - nodejs code, python code, php code)
- Apache is a web server which is build for php application and run php application code 
- Apache is synchronies application server which can handle one request at a time 
- Nginx is asynchronise web server which act as reverse proxy server 
- Nginx act as middleware b/w client and application server 
- Nginx increase the security of application server because application server not going to expose itself to client 
- Client don't know about application server, client only know web server nginx and send request to nginx and then nginx send request to application server 
- Load balancers handle ingress traffic 

- Why we use nginx web server in b/w client and application server 
--> nginx perform many role 
1st -> reverse proxy 
2nd -> load balancing 
3rd -> Caching (it serve static content so no need to request application server for static content )

- nginx default LB algorithms Round Robin (one by one in each request)


Some common features seen in Nginx include:

Reverse proxy with caching
IPv6
Load balancing
FastCGI support with caching
WebSockets
Handling of static files, index files, and auto-indexing
TLS/SSL with SNI


Nginx vs Apache Usage Stats
Apache is another popular open-source web server. In terms of raw numbers, Apache is the most popular web server in existence and is used by 43.6% (down from 47% in 2018) of all websites with a known web server, according to W3Techs. Nginx comes in a close second at 41.8%.

Netcraft ran a survey across 233 million domains and found Apache usage at 31.54% and Nginx usage at 26.20%.


While Apache is the most popular overall option, Nginx is actually the most popular web server among high-traffic websites.

When you break down usage rates by traffic, Nginx powers:

60.9% of the 100,000 most popular sites (up from 56.1% in 2018)
67.1% of the 10,000 most popular sites (up from 63.2% in 2018)
62.1% of the 1,000 most popular sites (up from 57% in 2018)
In fact, Nginx is used by some of the most resource-intensive sites in existence, including Netflix, NASA, and even WordPress.com.

Apache’s usage, on the other hand, moves in the opposite direction as a site’s traffic increases. It powers:

24.0% of the 100,000 most popular sites (down from 27.1% in 2018)
18.8% of the 10,000 most popular sites (down from 21.5% in 2018)
16.6% of the 1,000 most popular sites (up from 16.2% in 2018)
If we take a look at Google Search terms since 2004 we can see that Apache has been on a steady decline, while NGINX has seen slight growth.

https://kinsta.com/blog/nginx-vs-apache/


Some streaming platforms like - Netflix also uses nginx