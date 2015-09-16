# async

Notes on asynchronous, digital logic assuming quasi-delay-insensitve (QDI) operation

## To run a test script

Using test/test\_ap1.act as an example,

From Code/

cflat test/test\_ap1.act > a.prs

prsim a.prs

Within prsim, execute

source ap.scr

cycle

Ctrl-c to stop the simulation

exit to exit the simulation
