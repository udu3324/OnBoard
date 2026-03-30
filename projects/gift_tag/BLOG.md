# Gift Tag Results and Issues

Since the PCBA was only on one side, I had to solder the bottom side that included the MCU (seeed xiao) and two coin battery connectors.

My code worked perfectly, but I was super dissapointed that the battery circuit did not work. This would mean it would have to be tethered to a usb-c cable at all times to be lit up, and pretty much lost its purpose.       
<img width="4032" height="3024" alt="image" src="https://github.com/user-attachments/assets/d7b2eadc-e44a-4afe-916d-ee2b0099f08f" />        

I designed it to have two button cell batteries (2032, 3v) to be in series and make 6v total, so then I could use a ldo regulator to drop it to 5v. But somewhere in my schematic or components, it just doesn't work.       
<img width="1300" height="375" alt="image" src="https://github.com/user-attachments/assets/f3bb0198-9a98-4d7e-8ca4-2ee4028820b6" />         
