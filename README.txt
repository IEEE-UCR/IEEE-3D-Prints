** IEEE UCR 3D Printing Profile **

* Information *
Hello everybody, here is the 3D printing profile for IEEE UCR's Replicator 2.

The profile is tuned for printing with the "Natural" Makerbot filament.
This is purportedly the hardest filament to actually print with.
The theory behind this is that if we can print with the hardest filament to work with, we can print with anything.

* Details *
This profile has supports and raft printing.

The raft is slightly optimized to use less material and has proven mostly necessary to ensure a good print.

Supports are not as optimized but are necessary for good prints.

*How to prepare a profile*
The profiles by default are generally "unconfigured".  They are just left over from what the previous print had.

So, there are a few things that you need to do before you prepare for prints.

(1) Choose whether you want a raft or not (Warp reduce should *always* be printed with a raft to reduce warp.) ... The doRaft variable is set to "false" if you do not want a raft and "true" if you do want a raft.

(2) Choose which filament you want to print with... You only need to copy the filament diameter and Feed Stock Ratio into the profile from your respective filament name.  Do this for each extruder (because nobody really knows which one we actually use... ... ...).

(3) (optional) Turn Supports on or off.  Use the doSupport variable for this.  It works the same way as the doRaft variable.

* Contact *
For further questions, you may contact Brandon.  blu006 at ucr dot edu.