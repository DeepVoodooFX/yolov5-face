## Install

```
virtualenv -p /usr/bin/python3.8 venv-yolov5face
. venv-yolov5face/bin/activate

pip install torch==1.10.0+cu113 torchvision==0.11.1+cu113 torchaudio==0.10.0+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html

git clone https://github.com/chuanli11/yolov5-face.git
cd pytorch-benchmark

pip install -r requirements.txt
```



## Usage

```
python3 ./models/export2.py --weights ./weights/yolov5n-0.5.pt
python3 ./models/export2.py --weights ./weights/yolov5s-face.pt 
python3 ./models/export2.py --weights ./weights/yolov5m-face.pt 
python3 ./models/export2.py --weights ./weights/face.pt
```
