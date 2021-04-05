FROM openresty/openresty:alpine-apk

# RUN luarocks install etlua
# RUN luarocks install inspect
# RUN luarocks install lua-resty-http
# RUN luarocks install lua-resty-mail

ADD lua /usr/share/

CMD ["openresty", "-c", "/etc/nginx/nginx.conf"]
