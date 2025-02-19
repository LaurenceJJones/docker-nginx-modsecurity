# NGINX with libModSecurity + ModSecurity-nginx connector + CRS 3.0 RuleSet

The dockerfile of this container has been copied from the [official nginx repo (alpine-perl variant)](https://github.com/nginxinc/docker-nginx/blob/1.15.9/mainline/alpine-perl/Dockerfile) and has been modified to add [ModSecurity library (v3)](https://github.com/SpiderLabs/ModSecurity/tree/v3/master) + [ModSecurity nginx connector](https://github.com/SpiderLabs/ModSecurity-nginx) + [CoreRuleSet 3.0](https://github.com/coreruleset/coreruleset).

You can refer to the [official nginx image documentation](https://hub.docker.com/_/nginx/) for instructions on how to use this image.

When you provide your configuration you can enable modsecurity. Please refer to [their wiki](https://github.com/SpiderLabs/ModSecurity/wiki) for documentation.
