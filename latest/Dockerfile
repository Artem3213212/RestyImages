FROM openresty/openresty:bionic

RUN luarocks install etlua
RUN luarocks install lua-resty-http
RUN luarocks install lua-resty-mail

CMD ["openresty", "-c", "/etc/nginx/nginx.conf"]
