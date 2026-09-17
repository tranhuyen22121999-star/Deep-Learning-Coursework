# COCO Object Detection Coursework

This package contains a complete, reproducible coursework implementation of object detection on COCO 2017 using a ResNet50 backbone, Feature Pyramid Network, and educational YOLO-style detection head.

## Contents

- `COCO_Object_Detection_Coursework.ipynb` — complete coursework notebook.
- `requirements.txt` — Python dependencies.
- `SUBMISSION_CHECKLIST.md` — checks to complete before submission.

## Dataset structure

Place COCO 2017 files as follows:

```text
data/coco2017/
├── val2017/
│   └── 000000000139.jpg
└── annotations/
    └── instances_val2017.json
```

Alternatively, set `AUTO_DOWNLOAD=True` in the notebook.

## Run

1. Install packages with `pip install -r requirements.txt`.
2. Open the notebook and select a GPU runtime.
3. Set `FAST_DEV_RUN=True` for a short validation run.
4. Set `FAST_DEV_RUN=False`, restart the kernel, and run all cells for the final experiment.
5. Confirm that `outputs/` contains the best model, training history, metrics, predictions, and figures.

The notebook intentionally does not contain invented mAP values. Final numerical results appear only after training and evaluation are executed.
