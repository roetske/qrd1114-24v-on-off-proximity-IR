# qrd1114-24v-on-off-proximity-IR
Found this sensor qrt1114 IR sensor from youtube sensing in sumobots.<br />

This is a low range proximity sensor IR. Mostly used with analogue signal.<br />
I wondered if I can make a small range on off proximity switch with it? <br />
I made the sensor circuit in 2 parts.<br /> 
1)qrd1114 sensor to be put in tube.<br />
2)output module which processes the signal to 24v on/off <br />
This was a good practical exercise for me using comparator and npn and pnp switching. <br />

Optical sensors have one downside compared to inductive sensors,
they stop working good when dirty or scratched.


#Testing

Detects nicely within the range.<br />
Sensor circuit 24v with led and 24v output.<br />
First test showed works as proximity switch range 7-9 mm.<br />
Tested it with relay 24v for the output side works nicely. <br />
Unwanted detection when flame is closeby, does not detect black objects.<br />
Probably because of range setting in comparator of 2.5V.<br />
Influence of other IR sources like lights is minimal.


