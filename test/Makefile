all:
	./xk6 build v0.38.3 --with github.com/AlexF4Dev/xk6-oauth-pkce="$(shell pwd)/.."
	./k6 run plain.js
	./k6 run s256.js
