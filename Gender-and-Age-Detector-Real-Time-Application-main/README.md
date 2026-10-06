# 👤 Gender and Age Detector: Real-Time Application

Detects a face from a live camera feed and predicts gender and age range in real time.

## Problem

Estimate gender and age group from a face in a video stream, fast enough to run live on a normal laptop.

## How it works

1. **Capture** frames from the webcam.
2. **Detect faces** in each frame. [FILL: e.g. OpenCV DNN face detector]
3. **Classify** each face crop for gender and age bucket. [FILL: model names / files]
4. **Draw** the label on the frame and display it live.

## Models

| Task | Model | Output |
|---|---|---|
| Face detection | [FILL] | Bounding box |
| Gender | [FILL] | Male / Female |
| Age | [FILL] | Age range, e.g. (25–32) |

## Demo

[FILL: add a GIF or screenshot, e.g. `![Demo](demo.gif)`]

## Run locally

```bash
pip install -r requirements.txt
python [FILL: main script name].py
```

Press `q` to quit the camera window.

## Limitations

- Age is predicted as a range, not an exact number.
- Accuracy drops in poor lighting, with occlusion, or at extreme angles.
- Predictions are statistical estimates. They should not be used for decisions about people.

## Tech stack

`Python` `OpenCV` `Deep Learning (pre-trained models)`

## Author

[Suman Jha](https://github.com/SumanJha-tech) · ✉️ sumanjha0906@gmail.com · [LinkedIn](https://linkedin.com/in/sumanjha-tech)
