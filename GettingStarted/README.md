brew install npm
npm install -g react-tools
jsx --watch GettingStarted/src/ react/build/

npm install http-server -g
cd {$ROOT}
http-server ./ -p 8000

open http://localhost:8000/GettingStarted/helloworld.html on your browser.

