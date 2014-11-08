ansible-magento
===============

Ansible role for installing Magento on Nginx, using php-fpm, behind varnish, with APC, memcached

SSL
===
Varnish does not support SSL, I have read a lot of posts about using tools like
Pound, or even nginx to proxy_pass, but for right now im just going to allow
requests coming through on 443 to go straight to nginx, no varnish caching.
