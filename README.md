# TMC2130 connection board (SPI) for RAMPS 1.4

This is my simple board to connect TMC2130 drivers to RAMPS 1.4 using 10p flat cable to enable the SPI mode. Board has 10p IDC female connector and the flat cable is split on the RAMPS end to 10p and 8p IDC female connectors which I have connected to RAMPS AUX-2 and AUX-3 (SPI) connectors. Drivers have 4pin Dupont connectors with wires directly soldered to the driver boards.

CS pins for X, Y, Z, E0 and E1 in RAMPS: 
X = 65
Y = 42
Z = 40
E0 = 64
E1 = 44

My PCBs were manufactured by Aisler and can be ordered here: https://aisler.net/p/MLBWSEVN

Completed board with all connectors:
<img src=https://raw.githubusercontent.com/JPTa/RAMPS-TMC2130-board/master/images/Board.png>

Connected to RAMPS:
<img src=https://raw.githubusercontent.com/JPTa/RAMPS-TMC2130-board/master/images/Connections.png>
