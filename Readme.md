Compress all files in a specified folder using 7z.

usage: zip-files.py [-h] -d DIR [-s [SPLIT]] [-a]

optional arguments:
  -h, --help            show this help message and exit

  -d DIR, --dir DIR     Directory path

  -s [SPLIT], --split [SPLIT]
                        Maximum split size in MB, default is 300 MB

  -a, --abs             Use absolute 7z.exe path C:\Program Files\7-Zip\7z.exe