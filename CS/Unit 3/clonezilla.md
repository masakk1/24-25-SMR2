# Starting clonezilla
We'll begin at the start screen
![[B000 primera pantalla.png]]

Select your language and keyboard layout to use
![[B010 cambiar idioma.png]]
![[B020 change keyboard layout.png]]

Start clonezilla
![[B030 start clonezilla.png]]

## Selecting a destination or origin
Once we have [started clonezilla](#Starting clonezilla), choose to store the device as an image somewhere (device-image)
![[B040 tell clonezilla what to do.png]]
### Choosing what type of destination or origin
Choose the store destination to be `local_dev`.
![[B050 destination to store the img or restore from.png]]
Here we will be required to plug any disks that we would like to the image to. `Crtl-C` will continue.
![[B060 waiting for devices to be plugged in.png]]
Then, choose the partition of the destination
![[B070 choose partition.png]]
Lastly, choose the directory to store the image. Or just choose the `lost+found`, which will store it on the root of the partition
![[B090 where to store or restore img on the partition.png]]
And as always, it will ask for confirmation
![[B100 destination confirmation.png]]

# How to create an exact image of a system using clonezilla 
We wont need any expert options, so we'll choose Beginner
![[B110 Select wizard mode.png]]
We have to choose to 
![[B120 selection action.png]]

![[B130 img name.png]]

![[B140 select which disk to make an image of.png]]

![[B150 change compression algorithm.png]]

![[B160 choose to check the img before saving it.png]]

![[B170 Confirm whether to check if image is restorable.png]]

![[B180 choose to encrypt img or not.png]]

![[B190 action to perform after img is done.png]]

![[B200 Confirmation and logs.png]]

![[B210 Shows what is going to be stored and where and asks for confirmation.png]]

![[B220 example of popup screens during the backup process.png]]

# Restoring an image
Do every other step from the previous tutorial, until the step where you choose which action to tell clonezilla to do.

![[R020 Do B100 and select to restore disk.png]]

![[R030 Choose img to restore again.png]]

![[R040 Restoration partiton table mode .png]]

![[R050 Check image before restoring.png]]

![[R060 Example of restoration.png]]

![[R070 More and more confirmation warnings.png]]