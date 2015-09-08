#"Matrix" App
#####This app that we are creating will record Matrix-style video clips using many iPads.

Currently, we are considering using a Master / Slave system to take a picture on all of the slave iPads at the same time.

#####One of the main things we have to do is to get a way to time the pictures perfectly, and have all of the Slave iPads take their pictures all at the same time. (within a few milliseconds)

I think that the best way to synchronize the iPads is to syncronize all of the slaves to the clock of the master.  During the sync process, the master device would have a image on its screen that was a binary code of its current time.  This image would change every few milliseconds, depending on the speed of the iPad shutter.  The slave iPad would then sync its clock to the master and then stay in sync with the master.

This process would then be repeated with each slave iPad, and all iPads would be in sync (within a few milliseconds).  This system could run for a while, untill the iPads need to be-resynced again.

When it is time to shoot a clip, the master iPad will send a message to all of the slave iPads (over Wi-Fi or Bluetooth), telling them all to take a picture in exactly 3 seconds.  All of the slave iPads will take a picture within the same couple of milliseconds.  The pictures will be then sent from the slave iPads (numbered by position) to the master iPad.  The master iPad will then process the images and put them in the order that the user defined in the master app.  The video clip will then be played back on the master iPad.

Sharing:
After the video is played back, there will be an option to download it to their own device.(This will be good for people using our setup when we go Apple.) When this option is picked, the video will be uploaded to somewhere (I don't know for now), and the iPad will get the url back, and display it as a QR code for people to scan and download.
