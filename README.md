<pre>
https://stackoverflow.com/questions/38656842/i-need-makefile-for-fdk-aac
sudo apt-get install pkg-config autoconf automake libtool
git clone https://github.com/mstorsjo/fdk-aac.git
cd fdk-aac
./autogen.sh
./configure --enable-shared --enable-static
make
sudo make install
sudo ldconfig

</pre>
