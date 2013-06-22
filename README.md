Loopy-lemur-templates
=====================

This Lemur template (created with Lemur 4.0.3) allows control over Loopy HD (version 1.4.4) in a way that better suited me.

The template can either be on the same device as Loopy HD or a remote device on the same network.  The template requires a laborious number of MIDI bindings and a partcular Loopy set up (No count in etc.).  So, I have attached com.atastypixel.loopy-hd.plist.  This is the preference file with all the configurations in.

On a Mac, you may use iFunBox to upload the plist to your device.  Go to:

Loopy HD > Library > Preferences

Make sure you back up you original plist in case you want to revert to your configuration.  Also, check the version number of your Loopy HD so you don't break anything!

## Local usage

You need to run Lemur, MidiBridge and Loopy HD.  

* Set the input and output target of Lemur to be MidiBridge.
* In MidiBridge, link the MidiBridge input and output
* You should be ready to go 

## Remote usage

* Simply enable network midi in Loopy
* When your remote device appears in the list of Network Hosts, check it to enable control
* Open Lemur on your remote device and set the target to the network session

The remote usage may not work if your remote session is named anything other than Network Session 1.

![Screenshot](/Loopy iPad.png)
