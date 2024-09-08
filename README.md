# dvd-rip

Rips the mounted DVD and stores the film under the NAME.mp4
Note that the extension .mp4 is always added to the NAME.
You can mount the disk in /mnt/dvd manually or use an automatic
mount in /run/media/$USER or specify the mounted directory in options.

It uses `ffmpeg` to do the job.

## Usage

To get the help run `dvd-rip -h`

## MakeMKV

If the .VOB files on the disk are encoded, you need to have the program
MakeMKV to be installed and the key `-k` used.
