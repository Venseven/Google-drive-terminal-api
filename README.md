# Google-drive-terminal-api

Go to GCP console and enable google drive api in APIs &Services<br>

Now under APIs &Services go to credentials and download a client_secrent.json <br>

## Usage
```
usage: drive.py [-h] [--datapath DATAPATH] [--action ACTION]

Pass the configurations here

optional arguments:
  -h, --help           show this help message and exit
  --datapath DATAPATH  if upload - provide the file path| if download provide
                       the filename to save
  --action ACTION      upload/download
```

## Upload
``` python3 drive.py --action upload --datapath <datafile to upload> ```

## Download
``` python3 drive.py --action download --datapath <dataname to save> ```
