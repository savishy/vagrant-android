# Tips and Troubleshooting 

### Always `ACPI Shutdown`, never `Poweroff`!

* The Virtualbox menu has two options: `Machine > Poweroff` and `Machine > ACPI Shutdown`. 
* `ACPI Shutdown` is the _right way_ to shutdown the Android VM. It is equivalent to long-pressing the power button.
* `Poweroff` on the other hand, wipes out all your initial setup and installed apps, and takes you back to the Initial Setup screen. 

### Enable Mouse Integration

After starting the VM you might notice that moving your mouse does not move the pointer inside the VM. If you click and drag inside the VM window, your mouse starts to move.

The solution is to click Input > Mouse Integration in the VM Window.

### Setting up ADB

:exclamation: ADB does not work on CM-14. The VM always shows up `unauthorized`.


If you wish to use ADB to control this VM:

Open up port 5555 on the VM (Port Forwarding)

![image](https://user-images.githubusercontent.com/13379978/35763132-76fafeae-08cb-11e8-9d1d-190d4484e030.png)

Next, enable ADB Debugging and ADB over WiFi on the Android VM's Developer Settings.

### Troubleshooting Audio

The audio stutters and plays very slow with this combination. 

* With 1 CPU and 2048MB allocated to the VM
* Settings > Audio: `PulseAudio` - `ICH-AC97`

The audio still stutters a lot (but is relatively better) with
* With 1 CPU and 2048MB allocated to the VM
* Settings > Audio: `PulseAudio` - `HD Audio`

