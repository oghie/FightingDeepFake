## Fighting DeepFake RestAPI
Application of DeepFake detection with RestAPI services (Flask)

### Tested on:
```
OS: Ubuntu 20.04.5
Python: 3.9.5

```

### Install:
```
$ sudo apt install cmake python3.9-dev python3-pip libgl1
$ sudo pip3 install -r requirements.txt

```

### Run:

```
# python3 server.py --port 8282

```

### Test

```
curl -X POST -F video=@/path/yourTestVideoFile.mp4 'http://<yourIP>:8282/Detect'
```
