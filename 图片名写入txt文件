# -*- coding: utf-8 -*-
"""
Created on Tue Aug 28 14:47:37 2018

@author: Jeson
"""

import os
import os.path

pathh = "F:/yolo/darknet-master-bak/scripts/VOC2007/JPEGImages"
# pathh1 = "VOC2007/trainImages/"
# pathh2 = "VOC2007/trainxml/"
for filenames in os.walk(pathh):
    filenames = list(filenames)
    filenames = filenames[2]
    for filename in filenames:
        print(filename)
        with open ("train.txt",'a') as f:
            f.write(filename)
