sudo apt-get install zip inotify-tools
git clone git://github.com/fontello/fontello.git
cd fontello
git submodule init
git submodule update
npm install
make dependencies
