# dxfbox

simple python based dxf box generator


## demo-video
[![Demo-Video](http://img.youtube.com/vi/BPYZ8CipDVA/0.jpg)](https://www.youtube.com/watch?v=BPYZ8CipDVA "Demo-Video")


## quikstart

### install with pip
```
pip3 install dxfbox
```

### get code
```
git clone git@github.com:multigcs/dxfbox.git
cd dxfbox
pip3 install -r requirements.txt
```

### dxfbox example
```
./bin/dxfbox -n box -s 1 -x 330 -y 120 -z 250 -t 4 -l 15 --bhole "c10+10+110" --hole "r100x40+30+20:c20+260" -r 1.5
```
this command line will generate a box.dxf and box.scad file

you can use the dxf file for you cnc and the scad file to preview the box

## screenshots

![gcodepreview](https://raw.githubusercontent.com/multigcs/dxfbox/main/docs/dxf.png)
![gcodepreview](https://raw.githubusercontent.com/multigcs/dxfbox/main/docs/scad.png)
![gcodepreview](https://raw.githubusercontent.com/multigcs/dxfbox/main/docs/dogbone.png)

