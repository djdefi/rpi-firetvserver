# rpi-firetvserver

RPi Docker Image for https://github.com/happyleavesaoc/python-firetv

# Usage

```
docker run -p 5556:5556 -it djdefi/rpi-firetvserver firetv-server -d X.X.X.X:5555
```

To connect to multiple FireTV's, run multiple containers specifying a different host port, or use the [API](https://github.com/happyleavesaoc/python-firetv#add-a-device)

