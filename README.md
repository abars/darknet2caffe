# darknet2caffe-convert

This repository is forked from pytorch-caffe-darknet-convert.

# Convert darknet -> caffe

## Python2.7

python darknet2caffe27.py yolo-face.cfg yolo-face_final.weights out27.prototxt out27.caffemodel

## Python3.5

python darknet2caffe35.py yolo-face.cfg yolo-face_final.weights out35.prototxt out35.caffemodel

## Verify

diff out27.caffemodel out35.caffemodel

diff out27.prototxt out35.prototxt
