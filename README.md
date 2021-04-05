## Base paths

    lua_package_path "/usr/share/lua/5.1/?.lua;/usr/share/lua/5.1/?/init.lua;;";
    lua_package_cpath "/usr/lib/lua/5.1/?.so;/usr/lib/lua/5.1/loadall.so;;";

## Build&upload 

	docker build -t artem3213212/resty-images:latest ./latest/
	docker build -t artem3213212/resty-images:dev ./dev/
	docker push artem3213212/resty-images