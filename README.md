# domoticz-scripts
Virtual switch for Milight v6 for use in Domoticz

Full color support ( hex and RGB )

Full brightness support ( 0 - 100 )

Full device and zone support

#### Usage:
 milight-home.py [DEVICE (0,7,8)] [ZONE (0,1,2,3,4)] [COMMAND ...]

#### Commands are:
* ON
* OFF
* DISCO[1-9]
* DISCOFASTER
* DISCOSLOWER
* WHITE
* BRIGHT (0-100)
* SPECTRUM                     Animates lamps through full color spectrum
* COLOR (hex color)            ie. #ff0000 for red, #0000ff for blue
* COLOR (red) (green) (blue)   ie. 255 0 0 for red, 0 0 255 for blue
