# sd2iec-games-collection
My favourite C64 games collection put into an file system layout easy usable 
with a SD2IEC.

Single-disk games are on top level, multi-disk games in separate sub-folders 
with own swaplist.

## Change directory

    OPEN15,8,15,"CD/TEST":CLOSE15

## CCGMS for BBS access via Wifi-Modem

### Configuration

* F7 - Settings Menu, should be already configure for Userport with 2400 baud
* F8 - to enter Anscii Mode, important for correct encoding of SSID/Password

### AT Commands

* at$ssid=yourssid
* at$pass=yourwifipassword
* at&w # save config
* atdt hostname:port # dial your favourte BBS, e.g. rapidfire.hopto.org:64128

