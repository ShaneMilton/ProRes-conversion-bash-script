# ProRes-conversion-bash-script
This is a script to use **FFMPEG** to convert videos to apple prores for use in video editors like **Davinci Resolve** on **Linux!**  This script will convert videos recursively in a directory.

#### This script works for any video resolution 1080P and up!

# How to use

Create a folder named **bin** in your home directory and add it to your path in the **~/.bashrc** using the text below.

`PATH="${PATH}:/home/username/bin"`  
**replace username with your user**

This is so you can execute the script from any ware on your system.

Then put the prores script into the bin folder and **chmod +x prores** to make executable.

# Changing the quality!

### The -profile:v # is for ProRes quality
#### 0: ProRes422 (Proxy)
#### 1: ProRes422 (LT)
#### 2: ProRes422 (Normal)
#### 3: ProRes422 (HQ)

Change the number in `-profile:v 2` to the quality level you wold like to use.
