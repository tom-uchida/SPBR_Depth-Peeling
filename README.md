# SPBR_Depth_Peeling

## Visualization Results
<img src="figures/LayerLevel1-90.gif">

## New Command
```
#/LayerLevel 1
```

## Usage
```
$ cd SPBR_Depth_Peeling/src
$ cat .param.spbr
#/LayerLevel 10

$ ./spbr_dp input.ply

===== Stochastic Point-based Renderer (SPBR) =====
               Depth Peeling Version

                2020/09/02 (Depth Peeling Version)
              Tomomasa Uchida
           Ritsumeikan University

 USAGE : spbr file1.spbr file2.spbr ...
 HELP  : spbr -h

~~~

Doing Depth Peeling 10 times...

Automatically, snapshotted.
Saved image path: IMAGE_DATA/LAYER_IMAGES/LayerImageXXX.bmp
```

<!-- ## Visualization Results

|Layer1|Layer5|Layer10|
|:-:|:-:|:-:|
|<img src="figures/LayerLevel1.bmp">|<img src="figures/LayerLevel5.bmp">|<img src="figures/LayerLevel10.bmp">|

|Layer20|Layer30|Layer40|
|:-:|:-:|:-:|
|<img src="figures/LayerLevel20.bmp">|<img src="figures/LayerLevel30.bmp">|<img src="figures/LayerLevel40.bmp">|

|Layer50|Layer60|Layer70|
|:-:|:-:|:-:|
|<img src="figures/LayerLevel50.bmp">|<img src="figures/LayerLevel60.bmp">|<img src="figures/LayerLevel70.bmp">|

|Layer80|Layer90|Layer100|
|:-:|:-:|:-:|
|<img src="figures/LayerLevel80.bmp">|<img src="figures/LayerLevel90.bmp">|<img src="figures/LayerLevel100.bmp">| -->

## Layer Image Averaging
|Original|Layer1-5|Layer1-10|
|:-:|:-:|:-:|
|<img src="figures/LayerAvg/original.bmp">|<img src="figures/LayerAvg/Layer_Averaging_L1-5.png">|<img src="figures/LayerAvg/Layer_Averaging_L1-10.png">|