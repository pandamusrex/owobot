# owobot (C++)

## Hardware
- Waveshare 64x32 2.5mm pitch LED matrix
- Raspberry Pi 4 (if you don't want Visual Studio Code support, you can use a Zero instead)

## Wiring
- Follow hzeller's instructions here: https://github.com/hzeller/rpi-rgb-led-matrix/blob/master/wiring.md
- For a single 64x32 matrix like here, you only need the Chain 1 (Smiley Face) connections

## Building
- (Not sure if needed - might be auto-installed by cpprestsdk) Install [Boost]()

```
sudo apt install libboost-dev
```

- Install [Microsoft's REST API toolkit for C++](https://github.com/microsoft/cpprestsdk)

```
sudo apt-get install libcpprest-dev
```

- Clone https://github.com/hzeller/rpi-rgb-led-matrix in a peer folder to this repo and make it

```
make
```

## Running
- Disable sound module first - see https://github.com/hzeller/rpi-rgb-led-matrix/tree/master?tab=readme-ov-file#bad-interaction-with-sound

```
sudo ./owobot
```
