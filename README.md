OSGAR
=====

Open Source Garden (Autonomous) Robot

![John Deere X300R](http://robotika.cz/competitions/roboorienteering/2016/jd-nav2.jpg)

References at
http://robotika.cz/robots/osgar/

Video: https://youtu.be/KiDnPsnLmLU

# Notes/Howto

To run demo with four cones use:

```
python ./navpat.py "short description of the test"
```

To replay existing log file use meta log, for example:
```
python ./navpat.py logs/meta_160821_160615.log
```

Current visualization is using **Eduro Viewer**.
The input is preprocessed viewer log file which can be generated by
```
python ./tools/meta2view.py logs/meta_160821_160615.log
```
and then
```
python ./tools/viewer.py view.log
```

