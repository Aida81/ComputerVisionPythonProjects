# Challenge 1: Customer Footfall Count

The output of the challenge should be 
1. Able to give the total number of people of the place
2. Have bounding boxes around detected person
3. Have a near real time inference speed

## Demo of People Tracking/Counting
### Conda 

```bash
# Tensorflow CPU
conda env create -f conda-cpu.yml
conda activate yolov4-cpu
```
Run command 
```bash
python detect_video.py --weights ./checkpoints/yolov4-416 --model yolov4 --video ./data/video/test.mp4 --output ./detections/results.avi --count
```

# Challenge 2: Vehicle Type Identification

The output of the challenge should be 
1. Able to recognize whether a car isan EV/non-EV when given an image

## Demo of Image Classification of Electrical car and Non Electrical car

Run the Jupyter Lab for the result

# Challenge 3: Vehicle Tracking

The output of the challenge should be 
1. Able to track and count the number of vehicles in video 

## Demo of Vehicle Tracking 

Run the object_tracking.py file 

# Challenge 4: Image Processing

The output of the challenge should be
1. to improve the image quality

## Demo of Image processing 

### Environment Setup
```bash
conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cudatoolkit=11.3 -c pytorch
pip install opencv-python glob2
```
Run python test.py
