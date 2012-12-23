### Compiling on Ubuntu
sudo apt-get install libjpeg-dev subversion imagemagick
make clean all

### Running
export LD_LIBRARY_PATH=.
./mjpg_streamer -i "input_uvc.so -f 60 -y" -o "output_http.so -w ./www"