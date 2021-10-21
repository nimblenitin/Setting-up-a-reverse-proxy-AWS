# Setting-up-a-reverse-proxy-AWS

Ever tried setting up multiple web applications under the same domain? Where users can access applications running on the same server with different path names? For instance, you hosted a react app at www.example.com and desire to have a Wordpress blog at www.example.com/blog. This is where the concept of reverse proxy kicks in and helps you accomplish what you are looking for.

A simple definition for “proxy” means that data is passing through a third party, before reaching to the actual location. Forward or regular proxies are servers that encapsulate the original identity of the requestor i.e., users stay anonymous to the host server.

Reverse proxy as the name suggests does the opposite of what a forward proxy can do. It takes requests from the user and forwards them to the host web servers acting as a load balancer. We can leverage this behaviour to serve different apps under the same hood.

To summarise, the forward proxy hides the clients whereas a reverse proxy hides the servers.
