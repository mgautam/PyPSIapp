PyGMCapp
--------

Controlling Galil motion controllers remotely.

Installing
----------
sudo apt-get install -y \
python-pip \
build-essential \
git \
python \
python-dev \
ffmpeg \
libsdl2-dev \
libsdl2-image-dev \
libsdl2-mixer-dev \
libsdl2-ttf-dev \
libportmidi-dev \
libswscale-dev \
libavformat-dev \
libavcodec-dev \
zlib1g-dev

# Install gstreamer for audio, video (optional)
sudo apt-get install -y \
libgstreamer1.0 \
gstreamer1.0-plugins-base \
gstreamer1.0-plugins-good

pip install -r dependencies.txt

