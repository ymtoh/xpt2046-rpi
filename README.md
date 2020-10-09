# xpt2046-rpi

## installing driver
sudo rm -rf LCD-show
git clone https://github.com/goodtft/LCD-show.git
chmod -R 755 LCD-show
cd LCD-show/

sudo ./LCD35-show # displaying on 3.5" LCD
sudo ./LCD-hdmi # displaying to HDMI


