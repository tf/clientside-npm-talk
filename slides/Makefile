all: ender stylus

ender:
	node_modules/.bin/ender build --output build/ender.js .

stylus:
	node_modules/.bin/stylus --include-css --out build main.styl

stylus-watch:
	node_modules/.bin/stylus --watch --include-css --out build main.styl