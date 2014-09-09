## Synopsis

Demonstration meteor application that uses 'meteorhacks:npm' to include 'scraperjs':'0.3.0' module. Attempting to deploy this to modulus causes the following error:


	npm ERR! Error: version not found: sockjs-client@0.0.0-unreleasable
	npm ERR!     at /nave/installed/0.10.31/lib/node_modules/npm/lib/cache/add-named.js:125:12
	npm ERR!     at saved (/nave/installed/0.10.31/lib/node_modules/npm/node_modules/npm-registry-client/lib/get.js:167:7)
	npm ERR!     at Object.oncomplete (fs.js:107:15)
	npm ERR! If you need help, you may report this *entire* log,
	npm ERR! including the npm and node versions, at:
	npm ERR!     <http://github.com/npm/npm/issues>
	
	npm ERR! System Linux 3.8.0-44-generic
	npm ERR! command "/mnt/nave/installed/0.10.31/bin/node" "/mnt/nave/installed/0.10.31/bin/npm" "install" "--production" "--registry" "http://registry.npmjs.org" "--cache" "/mnt/data/.npm"
	npm ERR! cwd /mnt/data/2
	npm ERR! node -v v0.10.31
	npm ERR! npm -v 1.4.23
