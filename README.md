CFS-AIPOLICE

## Created By CFS-SCRIPTS (CHAPO)

# install Guide

- 1. put cfs-aipolice in resources 
- 2. adjust config if needed 
- 3. MAKE SURE TO PUT TRIGGER EVENTS/EXPORTS IN THE SCRIPT you want this to trigger 

## CHANGE LOG 
ADD FULL WANTED SYSTEM ADDED MULTIPLE DIFFRENT Jail Locations via config THIS IS A STANDALONE JAIL SYSTEM NOW BUILT IN TO THE SCRIPT ENJOY HUGH SHOUTOUT TO SHAWN FOR THE CODE FOR THE LIGHTS AND SIRENS AND THE MULTIPLE JOBS ASWELL AS THE MULTIPLE PEDS AND PATROL CARS 
## PLEASE READ THIS PART 
YOU MUST GO TURN ON A FEW THINGS IN qb-smallresouces turn on the spawning of cop peds vehicles that are black listed etc 

there is a command to test the script 
/commitcrime

```
From the client-side of the same script:

CommitCrime("PUTCRIMEHERE")

From the client-side of another script:

exports["ai-police"]:CommitCrime("PUTCRIMEHERE")

From the server-side of any script:

exports["ai-police"]:CommitCrimeServer(playerId, "PUTCRIMEHERE")

You can still use the event if you prefer:

TriggerServerEvent('ai-police:server:commitCrime', "PUTCRIMEHERE")

```

## Notes
- 1. May not work with newer qbcore please let me know if it dont and we will fix it 
- 2. THIS IS A BETA OF THIS RESOUCE IM NO WHERE NEAR DONE WITH IT I WILL UPDATE IT AS TIME GOES 
- 3. PLEASE LET ME KNOW ANY IDEAS THAT YOU MAY HAVE TO IMPROVE THIS SCRIPT / or you can help contribute to this code as you wish just make sure to give credit to me and i will do the same 
- 4. i hope you enjoy this release :) 

# discord
https://discord.gg/CjwtjJA2hg

# Tebex
https://cfs-scripts.tebex.io/

# Preview
-Coming Soon

/**
 
Copyright (c) 2024 CFS-SCRIPT (aka TheRealElchapo ) Discord:michiganlove18769*
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, BUT NOT TO EVER SELL
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
*
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
*
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
*/
