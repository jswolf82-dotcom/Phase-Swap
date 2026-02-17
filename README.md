# Phase-Swap
Daggerheart Phase swap for multi phase adversaries

IMPORTANT:  Full disclosure this has been created with AI, as I have no coding experience.  I am more than happy for someone with coding knowledge to refine this, with no issue.


I wanted an automated way of controlling phased battles, and couldn't find this, so I set about finding a way to implement it.

Currently you place all the statblocks you wish to be a phase in the same folder, and these will be the options for swapping the token to.  Includes changing token, statblock and size.

Currently implemented but untested are automated thresholds for both HP and Stress.

No UI currently integration currently.


MACROS required

For Config:   
"PhaseSwapperConfig.open()"


For swapping:   
if(!globalThis.PhaseSwapper)
ui.notifications.error("Phase Swapper module not loaded.");
else
PhaseSwapper.open();


Drop folder into your ".../FoundryVTT/Data/Modules" folder.
