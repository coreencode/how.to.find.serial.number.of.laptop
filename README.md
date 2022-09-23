# How to Find Serial Number of Laptop?

[![how to find serial number of laptop](redd.png)](https://icncomputer.com/how-to-find-serial-number-of-laptop/)

Windows doesn’t display your PC’s serial number anywhere in its interface, and neither do popular system information tools. But you can often find a PC’s serial number with a simple command, a peek in your BIOS, or on the hardware itself.


## Run the WMIC Command
* Open a Command Prompt or PowerShell window to get started. On Windows 11, Windows 10, or Windows 8, right-click the Start button and select “Command Prompt,” “PowerShell,” or “Windows Terminal.” On Windows 7, press Windows + R, type “cmd” into the Run dialog, and then press Enter.

**At the Command Prompt, type the following command and then press Enter:**

* You’ll see the computer’s serial number displayed beneath the text “SerialNumber”. This command uses the Windows Management Instrumentation Command-line (WMIC) tool to pull the system’s serial number from its BIOS.
* If you don’t see your PC’s serial number, blame your PC’s manufacturer. The number will only appear here if the PC manufacturer saved it to your computer’s BIOS or UEFI firmware. PC manufacturers don’t always fill in the number properly. In that case, you’ll see something like “0,” “To be filled by O.E.M.” or blank space instead of an actual serial number.
* This is also true if you built your own PC because the PC itself won’t have a serial number. However, you can look up the serial number of your motherboard and other components.


## Check the BIOS

* You may also be able to find the serial number in the BIOS or UEFI firmware settings screen. This technique won’t get you a serial number if the wmic command didn’t, since the command pulls the serial number from the BIOS. However, checking the BIOS could be helpful if you can’t actually sign into Windows to run the wmic command.

* Access the BIOS or UEFI firmware settings screen and look around for a “Serial Number” somewhere on a system information screen. It’ll be in a different place on different PCs, but you can usually find it somewhere on the “Main” or “System” screen.

## Find the Serial Number On the PC’s Hardware, Box, or Elsewhere

* If you don’t see a serial number after running the wmic command—or if you just can’t turn the PC on or don’t have access to it—there are several other places you might find the serial number:

