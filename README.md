# osu!novideo
This **Python 3.5** script is designed to remove all video files from 
your `osu!/Songs` directory. It specifically made for videos, although 
it will work with any extension.

## Version
osu!novideo **only supports Python 3.5**

## Installing
The easiest way to install is to [download as ZIP][zip]. Since this
script is not designed to be run as a packaged python script, you will
need to download and run it from some directory. You could put it in 
your `osu!/Songs` directory if you so wanted.

## Running
osu!novideo can be ran by simply running the python file.
```sh
python osu!novideo.py -h
```
`-h` or `--help` will show all script parameters. Running with no 
parameters **performs deletion in the current directory.**

## Extensions
osu!novideo removes every `avi` extension by default, although another 
common extension is `flv`.

## Example usage
```sh
python osu!novideo.py --path D:\Games\osu!\Songs\ --ext flv
```

## Logging
osu!novideo will save a log of the output in `/osu!novideo.log`

[zip]: https://github.com/PcBoy111/osu-novideo/archive/master.zip
