# Acer-Nitro-5-AN517-51-Bios-Unlocking

## WIP...


#i have tested this only with 1.28 and 1.29 bios veriosn

In this Tutoral i will show you how you can unlock the bios for Acer Nitro 5 AN517-51 to disable CFG Lock to have better Power Managment and unlock a ton of hidden settings.

you may also buy a Programmer that support xm25qh128a chip as CH341a, you can skip buying the programmer but it will be better we do not know what can happen. 

first we need to backup our courrent bios using FTW64.exe as we need this to verify that the bios back up from CH341a programmer is the same as from FTW64.exe we will use WinMerge to see if there is any diffrent in 

bios bin that we dumped using a programmer if both are the same (it is not going to be 100% same but that is okay) then we are good to go, i will show you how to determined if the bios is correct or not.



#lets begin:


##1- dumping the Bios 

we need to backup the bios using a CH341A programmer, download the project and unzip CH341A.zip, after you unzip it go to Drivers folder and run SETUP and install it.

now you will see that there is 5 folders we have to dump the bios from 4 diffrent software and compare them all the dump should be all same if you connect the programmer in the 

correct way.

so now go to AsProgrammer_2.1.0.13 folder and run AsProgrammer and click on the icon as this picture shows :

                 PHOTO

you should be able to see that the bios chip has been detemind by the software if everything went okay you will see this :

                 PHOTO

now click on read icon to start reding from the bios chip and wait until it finishs :

                 PHOTO

when it finishs you have to save the dumped bios :

                 PHOTO

now you haev to do this with other software i thing it is clear i do not want to make this totural long anyway

when you done dumping the bios using a programmer we can now start comparing with the one that we dumped early with FTW64.exe to see if everything is okay 

### i will correct the mistakes when i finish
