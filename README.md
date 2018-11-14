## TMC2130 connection board (SPI) for RAMPS 1.4
Connecting the TMC2130 drivers to RAMPS and enabling them to use SPI mode ends up with nice mess of wires. I wanted to clean the mess a bit and created this simple board. I used 10p flat cable to connect the board to RAMPS. Board itself has 10p IDC male header and the flat cable is split to 10p and 8p IDC female headers connected to RAMPS AUX-2 and AUX-3 (SPI) headers. Drivers have 4pin Dupont connectors with wires directly soldered to the driver boards.

CS pins for X, Y, Z, E0 and E1 in RAMPS in my setup: 
X = 65
Y = 42
Z = 40
E0 = 64
E1 = 44

PCBs were manufactured by Aisler and can be ordered here: https://aisler.net/p/MLBWSEVN

Complete board with all connectors:
<img src=https://raw.githubusercontent.com/JPTa/RAMPS-TMC2130-board/master/images/Board.png>

Board connected to RAMPS:
<img src=https://raw.githubusercontent.com/JPTa/RAMPS-TMC2130-board/master/images/Connections.png>
