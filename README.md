# Gerber-to-G-Code-Conversion
# Aim
To convert the Gerber File into G-Code using Copper CAM.
# Software required
Copper CAM
# Procedure
1. Open your Gerber file (File → Open → New circuit)</br>
2. Open your Drill file (File → Open → Drill)</br>
3. Match the drill file and engraving file if not matched </br>
4. Right click the pad and set define as pad and then Right click and select edit all identical pads as set the drill size as 0.8mm,1mm.</br>
5. Open your Cutting file (File → Open → Additional Layer and load your cutting file</br>
6. Go to file/Orgin and set x=0,y=0 </br>
7. Go to file/offset and select the option shift manually</br>
8. Select the layer 6 and move the cutting file and set the border</br>
9. Go to parameter/ tool library and check the identifaication and specification</br>
10. Go to parameter/selected tool and check the engraving tool, cutting tool and drill tool</br>
11. Go to machine/ Contours/calculate Contours</br>
12. Go to machine/mill and select engraving you will get the g code,similarly for Drill and cut. </br>
13. Save the G code</br>
# Contours Output

![image](https://github.com/SubashM00/Gerber-to-G-Code-Conversion/assets/144870586/f9787f56-32a6-4bee-b6ed-2552c5c89ece)

# G Code
### Engraving G Code
```
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 23:35 )
( Workpiece dimensions: 35.357 x 25.882 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #1 "Basic Engraver" / Diameter 3.17 mm )
T1 M06
M03 S12000
M07
G00 X4.924 Y7.099
G00 Z0
G01 F60 Z-0.2
G01 F600 X5.11 Y7.117
G01 X5.289 Y7.172
G01 X5.454 Y7.26
G01 X5.598 Y7.378
G01 X5.717 Y7.523
G01 X5.805 Y7.688
G01 X5.859 Y7.867
G01 X5.877 Y8.053
G01 X5.859 Y8.239
G01 X5.805 Y8.418
G01 X5.717 Y8.582
G01 X5.598 Y8.727
G01 X5.454 Y8.845
G01 X5.289 Y8.934
G01 X5.11 Y8.988
G01 X4.924 Y9.006
G01 X3.124
G01 X2.938 Y8.988
G01 X2.759 Y8.934
G01 X2.594 Y8.845
G01 X2.45 Y8.727
G01 X2.331 Y8.582
G01 X2.243 Y8.418
G01 X2.189 Y8.239
G01 X2.17 Y8.053
G01 X2.189 Y7.867
G01 X2.243 Y7.688
G01 X2.331 Y7.523
G01 X2.45 Y7.378
G01 X2.594 Y7.26
G01 X2.759 Y7.172
G01 X2.938 Y7.117
G01 X3.124 Y7.099
G01 X4.924
G00 Z2
G00 Y12.179
G00 Z0
G01 F60 Z-0.2
G01 F600 X5.11 Y12.197
G01 X5.289 Y12.252
G01 X5.454 Y12.34
G01 X5.598 Y12.458
G01 X5.717 Y12.603
G01 X5.805 Y12.768
G01 X5.859 Y12.947
G01 X5.877 Y13.133
G01 X5.859 Y13.319
G01 X5.805 Y13.498
G01 X5.717 Y13.662
G01 X5.598 Y13.807
G01 X5.454 Y13.925
G01 X5.289 Y14.014
G01 X5.11 Y14.068
G01 X4.924 Y14.086
G01 X3.124
G01 X2.938 Y14.068
G01 X2.759 Y14.014
G01 X2.594 Y13.925
G01 X2.45 Y13.807
G01 X2.331 Y13.662
G01 X2.243 Y13.498
G01 X2.189 Y13.319
G01 X2.17 Y13.133
G01 X2.189 Y12.947
G01 X2.243 Y12.768
G01 X2.331 Y12.603
G01 X2.45 Y12.458
G01 X2.594 Y12.34
G01 X2.759 Y12.252
G01 X2.938 Y12.197
G01 X3.124 Y12.179
G01 X4.924
G00 Z2
G00 X17.552 Y13.641
G00 Z0
G01 F60 Z-0.2
G01 F600 Y15.165
G01 X17.537 Y15.326
G01 X17.489 Y15.482
G01 X17.413 Y15.625
G01 X17.31 Y15.751
G01 X17.184 Y15.854
G01 X17.041 Y15.93
G01 X16.886 Y15.977
G01 X16.724 Y15.993
G01 X16.562 Y15.977
G01 X16.407 Y15.93
G01 X16.264 Y15.854
G01 X16.138 Y15.751
G01 X16.035 Y15.625
G01 X15.958 Y15.482
G01 X15.911 Y15.326
G01 X15.895 Y15.165
G01 Y13.641
G01 X15.911 Y13.479
G01 X15.958 Y13.324
G01 X16.035 Y13.18
G01 X16.138 Y13.055
G01 X16.264 Y12.952
G01 X16.407 Y12.875
G01 X16.562 Y12.828
G01 X16.724 Y12.812
G01 X16.886 Y12.828
G01 X17.041 Y12.875
G01 X17.184 Y12.952
G01 X17.31 Y13.055
G01 X17.413 Y13.18
G01 X17.489 Y13.324
G01 X17.537 Y13.479
G01 X17.552 Y13.641
G00 Z2
G00 X17.69 Y6.345
G00 Z0
G01 F60 Z-0.2
G01 F600 X17.649
G01 X17.161 Y5.857
G01 Y5.168
G01 X17.649 Y4.68
G01 X18.339
G01 X18.368 Y4.709
G01 X19.049 Y4.028
G01 X19.095 Y3.99
G01 X19.148 Y3.962
G01 X19.205 Y3.945
G01 X19.264 Y3.939
G01 X24.344
G01 X24.403 Y3.945
G01 X24.46 Y3.962
G01 X24.513 Y3.99
G01 X24.559 Y4.028
G01 X25.829 Y5.298
G01 X25.866 Y5.344
G01 X25.894 Y5.396
G01 X25.912 Y5.453
G01 X25.918 Y5.513
G01 Y6.102
G01 X26.31 Y6.494
G01 Y7.049
G01 X27.099 Y7.838
G01 X27.136 Y7.884
G01 X27.164 Y7.936
G01 X27.182 Y7.993
G01 X27.188 Y8.053
G01 Y10.909
G01 X27.784
G01 X27.97 Y10.927
G01 X28.149 Y10.982
G01 X28.314 Y11.07
G01 X28.458 Y11.188
G01 X28.577 Y11.333
G01 X28.665 Y11.498
G01 X28.719 Y11.677
G01 X28.737 Y11.863
G01 X28.719 Y12.049
G01 X28.665 Y12.228
G01 X28.577 Y12.392
G01 X28.458 Y12.537
G01 X28.314 Y12.655
G01 X28.149 Y12.744
G01 X27.97 Y12.798
G01 X27.784 Y12.816
G01 X25.984
G01 X25.798 Y12.798
G01 X25.619 Y12.744
G01 X25.454 Y12.655
G01 X25.31 Y12.537
G01 X25.191 Y12.392
G01 X25.103 Y12.228
G01 X25.084 Y12.166
G01 X20.66
G01 X19.807 Y13.019
G01 X19.85 Y13.055
G01 X19.953 Y13.18
G01 X20.029 Y13.324
G01 X20.077 Y13.479
G01 X20.093 Y13.641
G01 Y15.165
G01 X20.077 Y15.326
G01 X20.029 Y15.482
G01 X19.953 Y15.625
G01 X19.85 Y15.751
G01 X19.724 Y15.854
G01 X19.581 Y15.93
G01 X19.426 Y15.977
G01 X19.264 Y15.993
G01 X19.102 Y15.977
G01 X18.947 Y15.93
G01 X18.804 Y15.854
G01 X18.678 Y15.751
G01 X18.575 Y15.625
G01 X18.498 Y15.482
G01 X18.451 Y15.326
G01 X18.435 Y15.165
G01 Y13.641
G01 X18.451 Y13.479
G01 X18.498 Y13.324
G01 X18.575 Y13.18
G01 X18.678 Y13.055
G01 X18.804 Y12.952
G01 X18.947 Y12.875
G01 X19.102 Y12.828
G01 X19.143 Y12.824
G01 X20.319 Y11.648
G01 X20.365 Y11.61
G01 X20.418 Y11.582
G01 X20.475 Y11.565
G01 X20.534 Y11.559
G01 X25.084
G01 X25.103 Y11.498
G01 X25.191 Y11.333
G01 X25.31 Y11.188
G01 X25.454 Y11.07
G01 X25.619 Y10.982
G01 X25.798 Y10.927
G01 X25.984 Y10.909
G01 X26.58
G01 Y8.178
G01 X25.88 Y7.478
G01 X25.326
G01 X24.918 Y7.071
G01 Y6.494
G01 X25.31 Y6.102
G01 Y5.638
G01 X24.218 Y4.546
G01 X19.39
G01 X18.797 Y5.139
G01 X18.827 Y5.168
G01 Y5.857
G01 X18.339 Y6.345
G01 X18.298
G01 Y9.323
G01 X18.292 Y9.382
G01 X18.274 Y9.439
G01 X18.246 Y9.491
G01 X18.209 Y9.537
G01 X16.939 Y10.807
G01 X16.893 Y10.845
G01 X16.84 Y10.873
G01 X16.783 Y10.89
G01 X16.724 Y10.896
G01 X5.824
G01 X5.805 Y10.958
G01 X5.717 Y11.122
G01 X5.598 Y11.267
G01 X5.454 Y11.385
G01 X5.289 Y11.474
G01 X5.11 Y11.528
G01 X4.924 Y11.546
G01 X3.124
G01 X2.938 Y11.528
G01 X2.759 Y11.474
G01 X2.594 Y11.385
G01 X2.45 Y11.267
G01 X2.331 Y11.122
G01 X2.243 Y10.958
G01 X2.189 Y10.779
G01 X2.17 Y10.593
G01 X2.189 Y10.407
G01 X2.243 Y10.228
G01 X2.331 Y10.063
G01 X2.45 Y9.918
G01 X2.594 Y9.8
G01 X2.759 Y9.712
G01 X2.938 Y9.657
G01 X3.124 Y9.639
G01 X4.924
G01 X5.11 Y9.657
G01 X5.289 Y9.712
G01 X5.454 Y9.8
G01 X5.598 Y9.918
G01 X5.717 Y10.063
G01 X5.805 Y10.228
G01 X5.824 Y10.289
G01 X16.598
G01 X17.69 Y9.197
G01 Y6.345
G00 Z2
G00 X16.308 Y5.513
G00 Z0
G01 F60 Z-0.2
G01 F600 X16.291 Y5.679
G01 X16.243 Y5.839
G01 X16.164 Y5.987
G01 X16.058 Y6.116
G01 X15.928 Y6.222
G01 X15.781 Y6.301
G01 X15.62 Y6.35
G01 X15.454 Y6.366
G01 X15.287 Y6.35
G01 X15.127 Y6.301
G01 X14.98 Y6.222
G01 X14.85 Y6.116
G01 X14.744 Y5.987
G01 X14.665 Y5.839
G01 X14.617 Y5.679
G01 X14.6 Y5.513
G01 X14.617 Y5.346
G01 X14.665 Y5.186
G01 X14.744 Y5.038
G01 X14.85 Y4.909
G01 X14.98 Y4.803
G01 X15.127 Y4.724
G01 X15.287 Y4.675
G01 X15.454 Y4.659
G01 X15.62 Y4.675
G01 X15.781 Y4.724
G01 X15.928 Y4.803
G01 X16.058 Y4.909
G01 X16.164 Y5.038
G01 X16.243 Y5.186
G01 X16.291 Y5.346
G01 X16.308 Y5.513
G00 Z2
G00 X23.77 Y7.071
G00 Z0
G01 F60 Z-0.2
G01 F600 X23.362 Y7.478
G01 X22.786
G01 X22.378 Y7.071
G01 Y6.494
G01 X22.786 Y6.087
G01 X23.362
G01 X23.77 Y6.494
G01 Y7.071
G00 Z2
G00 X25.084 Y14.099
G00 Z0
G01 F60 Z-0.2
G01 F600 X25.103 Y14.038
G01 X25.191 Y13.873
G01 X25.31 Y13.728
G01 X25.454 Y13.61
G01 X25.619 Y13.522
G01 X25.798 Y13.467
G01 X25.984 Y13.449
G01 X27.784
G01 X27.97 Y13.467
G01 X28.149 Y13.522
G01 X28.314 Y13.61
G01 X28.458 Y13.728
G01 X28.577 Y13.873
G01 X28.665 Y14.038
G01 X28.719 Y14.217
G01 X28.737 Y14.403
G01 X28.719 Y14.589
G01 X28.665 Y14.768
G01 X28.577 Y14.932
G01 X28.458 Y15.077
G01 X28.314 Y15.195
G01 X28.149 Y15.284
G01 X27.97 Y15.338
G01 X27.784 Y15.356
G01 X25.984
G01 X25.798 Y15.338
G01 X25.619 Y15.284
G01 X25.454 Y15.195
G01 X25.31 Y15.077
G01 X25.191 Y14.932
G01 X25.103 Y14.768
G01 X25.084 Y14.706
G01 X22.632
G01 Y15.165
G01 X22.617 Y15.326
G01 X22.569 Y15.482
G01 X22.493 Y15.625
G01 X22.39 Y15.751
G01 X22.264 Y15.854
G01 X22.121 Y15.93
G01 X21.966 Y15.977
G01 X21.804 Y15.993
G01 X21.642 Y15.977
G01 X21.487 Y15.93
G01 X21.344 Y15.854
G01 X21.218 Y15.751
G01 X21.115 Y15.625
G01 X21.038 Y15.482
G01 X20.991 Y15.326
G01 X20.975 Y15.165
G01 Y13.641
G01 X20.991 Y13.479
G01 X21.038 Y13.324
G01 X21.115 Y13.18
G01 X21.218 Y13.055
G01 X21.344 Y12.952
G01 X21.487 Y12.875
G01 X21.642 Y12.828
G01 X21.804 Y12.812
G01 X21.966 Y12.828
G01 X22.121 Y12.875
G01 X22.264 Y12.952
G01 X22.39 Y13.055
G01 X22.493 Y13.18
G01 X22.569 Y13.324
G01 X22.617 Y13.479
G01 X22.632 Y13.641
G01 Y14.099
G01 X25.084
G00 Z2
M09
M05
M02
%
```

### Drill G Code
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 23:36 )
( Workpiece dimensions: 35.357 x 25.882 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #3 "Basic Drill" / Diameter 0.8 mm )
T3 M06
M03 S12000
M07
G00 X4.024 Y13.133
G00 Z0
G01 F60 Z-1
G01 F300 X4.124
G02 I-0.1 J0 X4.124 Y13.133
G00 Z2
G00 X4.024 Y10.593
G00 Z0
G01 F60 Z-1
G01 F300 X4.124
G02 I-0.1 J0 X4.124 Y10.593
G00 Z2
G00 X4.024 Y8.053
G00 Z0
G01 F60 Z-1
G01 F300 X4.124
G02 I-0.1 J0 X4.124 Y8.053
G00 Z2
G00 X15.454 Y5.513
G00 Z0
G01 F60 Z-1
G01 F300 X15.554
G02 I-0.1 J0 X15.554 Y5.513
G00 Z2
G00 X17.994
G00 Z0
G01 F60 Z-1
G01 F300 X18.094
G02 I-0.1 J0 X18.094 Y5.513
G00 Z2
G00 X23.074 Y6.783
G00 Z0
G01 F60 Z-1
G01 F300 X23.174
G02 I-0.1 J0 X23.174 Y6.783
G00 Z2
G00 X25.614
G00 Z0
G01 F60 Z-1
G01 F300 X25.714
G02 I-0.1 J0 X25.714 Y6.783
G00 Z2
G00 X26.884 Y11.863
G00 Z0
G01 F60 Z-1
G01 F300 X26.984
G02 I-0.1 J0 X26.984 Y11.863
G00 Z2
G00 X26.884 Y14.403
G00 Z0
G01 F60 Z-1
G01 F300 X26.984
G02 I-0.1 J0 X26.984 Y14.403
G00 Z2
M09
M05
M02
%
```
### Cutting G Code
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 15/05/2024 at 23:39 )
( Workpiece dimensions: 35.357 x 25.882 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #2 "Basic Cutter" / Diameter 3 mm )
T2 M06
M03 S12000
M07
G00 X-1.874 Y-1.545
G00 Z0
G01 F60 Z-2
G01 F300 X31.276
G01 Y19.225
G01 X-1.874
G01 Y-1.545
G00 Z2
M09
M05
M02
%
```
# Result

Thus the Gerber File into G-Code using Copper CAM.
