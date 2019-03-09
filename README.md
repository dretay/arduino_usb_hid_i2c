## An simple Arduino project to interface with a MAX3421E USB Host Controller and expose it as a I2C perhiperal ##

### Overview ###

Mostly an example sketch from the [Ardunio USB Host Shield](https://github.com/felis/USB_Host_Shield_2.0) combined the built-in arduino wire library and some protocol buffer serialization courtesy of [NanoPB](https://github.com/nanopb/nanopb).

### Building the PB models ###

+ `build_models.bat`
- will generate hid.pb.c and hid.pb.h.
- note that in hid.options the x/y delta is being capped at a 16 bit signed number to cut down in transmission overhead.

