# Automatic Systemd Service File
This repo provides a systemd service file for [Automatic](https://github.com/1100101/Automatic), which is an automatic RSS downloader for transmission. After having it installed make sure to check if the path set at `ExecStart=` is the same as `which automatic`. 

Finally give it to systemd:
```
sudo mv automatic.service /etc/systemd/system
```

You will now able to manage Automatic with `systemctl start/stop/enable/disable/reload automatic`
