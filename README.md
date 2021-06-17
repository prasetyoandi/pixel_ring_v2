Pixel Ring
==========

The library is for pixel ring based on APA102, ReSpeaker series pixel ring.

## Hardware
+ ReSpeaker 4 Mic Array or ReSpeaker V2
+ ReSpeaker V2
+ ReSpeaker USB 6+1 Mic Array
+ ReSpeaker USB 4 Mic Array

## Install & run
```
git clone --depth 1 https://github.com/respeaker/pixel_ring.git
cd pixel_ring
pip install -U -e .
python examples/respeaker_4mic_array.py
```

# Or manual respeaker core V2 pixel ring & mraa install
```
sudo apt-get update
pip3 install pixel-ring
sudo apt-get install libmraa1 libmraa-dev mraa-tools python-mraa python3-mraa
```


## Credits
+ [APA102_Pi](https://github.com/tinue/APA102_Pi)
