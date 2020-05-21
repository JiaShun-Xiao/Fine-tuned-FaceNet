# Fine-tuned-FaceNet
Fine-tuned FaceNet model 

We fine-tuned the open-source FaceNet model (version [20170512-110547](https://drive.google.com/file/d/0B5MzpY9kBtDVZ2RpVDYwWmxoSUk)), which is trained on the MS-Celeb-1M dataset, with the VGGFace2 dataset via a combination of softmax and center loss. 

The detail implementation is provided in log dir.

We also provide modified train_softmax.py that allows you to perform fine-tuning with FaceNet model
