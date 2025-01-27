# Real Time Portrait Video Matting
Portrait Matting (Videos, Images, and Webcam) based on MODNet Algorithm

### Requirements
- Ubuntu System
- Python 3+
- Webcam

### Usage
- Create Virtual Environment
```bash
conda create -n matting python==3.11.9
conda activate matting
```
- Clone Repository
```bash
git clone https://github.com/Zeeshann1/Real-Time-Portrait-Video-Matting.git
cd Real-Time-Portrait-Video-Matting.git
```

- Install Requirements <p>
Install the required python dependencies (please make sure your CUDA version is supported by the PyTorch version installed):

```bash
pip install -r demo/video_matting/custom/requirements.txt
pip install -r demo/video_matting/webcam/requirements.txt
```
### Execute the main code
- Webcam Matting <p>
Real-time portrait video matting demo based on WebCam. It will call your local WebCam and display the matting results in real time. The demo can run under CPU or GPU.

```bash
python -m demo.video_matting.webcam.run
```
- Local Video Matting <p>
Real-time portrait video matting demo that allows you to process custom videos.
```bash
python -m demo.video_matting.custom.run --video YOUR_VIDEO_PATH
```
- Image Matting <p>
Please try MODNet portrait image matting demo through online Colab demo.
[Image Demo](https://colab.research.google.com/drive/1GANpbKT06aEFiW-Ssx0DQnnEADcXwQG6?usp=sharing)






