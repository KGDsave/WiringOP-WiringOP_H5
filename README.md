# wiringOP README

This is a modified WiringPi for OrangePi-PC2 in AllWinner H5. We call it WiringOP.
Test fo Orangepi pc

## Installation

    git clone https://github.com/KGDsave/WiringOP/WiringOP_H5.git
    cd WiringOP
    sudo sh build
    gpio -v
    gpio readall

```    
root@orangepipc2:~# gpio readall
 +-----+-----+----------+------+---+-Orange Pi-PC2+---+------+---------+-----+--+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 |     |     |     3.3v |      |   |  1 || 2  |   |      | 5v       |     |     |
 |  12 |   8 |    SDA.0 | ALT3 | 0 |  3 || 4  |   |      | 5V       |     |     |
 |  11 |   9 |    SCL.0 | ALT3 | 0 |  5 || 6  |   |      | 0v       |     |     |
 |   6 |   7 |   GPIO.7 | ALT3 | 0 |  7 || 8  |   |      | TxD3     |     |     |
 |     |     |       0v |      |   |  9 || 10 |   |      | RxD3     |     |     |
 |   1 |   0 |     RxD2 | ALT3 | 0 | 11 || 12 | 0 | ALT3 | GPIO.1   | 1   | 110 |
 |   0 |  -1 |     TxD2 |      |   | 13 || 14 |   |      | 0v       |     |     |
 |   3 |   3 |     CTS2 | ALT3 | 0 | 15 || 16 | 0 | ALT3 | GPIO.4   | 4   | 68  |
 |     |     |     3.3v |      |   | 17 || 18 | 0 | ALT3 | GPIO.5   | 5   | 71  |
 |  64 |  -1 |     MOSI |      |   | 19 || 20 |   |      | 0v       |     |     |
 |  65 |  -1 |     MISO |      |   | 21 || 22 | 0 | ALT3 | RTS2     | 6   | 2   |
 |  66 |  16 |     SCLK | ALT3 | 0 | 23 || 24 | 0 | ALT3 | CE0      | 15  | 67  |
 |     |     |       0v |      |   | 25 || 26 | 0 | ALT3 | GPIO.11  | 11  | 21  |
 |  19 |  30 |    SDA.1 | ALT3 | 0 | 27 || 28 | 0 | ALT3 | SCL.1    | 31  | 18  |
 |   7 |  21 |  GPIO.21 | ALT3 | 0 | 29 || 30 |   |      | 0v       |     |     |
 |   8 |  22 |  GPIO.22 | ALT3 | 0 | 31 || 32 | 0 | ALT3 | RTS1     | 26  | 200 |
 |   9 |  23 |  GPIO.23 | ALT3 | 0 | 33 || 34 |   |      | 0v       |     |     |
 |  10 |  24 |  GPIO.24 | ALT3 | 0 | 35 || 36 | 0 | ALT3 | CTS1     | 27  | 201 |
 |  20 |  -1 |  GPIO.25 |      |   | 37 || 38 | 0 | ALT3 | TxD1     | 28  | 198 |
 |     |     |       0v |      |   | 39 || 40 | 0 | ALT3 | RxD1     | 29  | 199 |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+-Orange Pi-PC2+------+----------+-----+-----+
root@orangepipc2:~# 

```    
Thanks!
