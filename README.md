ShrimPCB
========

A PCB for an arduino-clone based on the Shrimp project - http://shrimping.it/

UNTESTED AS YET - still fixing bugs in layout.

This is a great first project if you're thinking about trying your hand at DIY PCB manufacture.  Single sided board, through-hole components.

Ensure that for etching when you are looking at the copper, the LEDs are at the bottom and the ISP header (6pin) is on the Left.  See http://leedshackspace.org.uk/2013/02/14/diy-circuit-boards-and-what-to-do-when-it-all-goes-wrong/ for what happens if it's on the right!

The capacitors and resistors are approximate, at best ;-)

The LEDs are routed so that they are optional, but if you remove the reset button, connect pin 3 and 4 or the ISP header will have no reset connection.

Serial connection on the 5-pin header is (from top corner downward) :- Ground, RX, TX, +5V, DTR (reset)

Ignore the Schematic view, only the PCB view is valid in the Fritzing file.