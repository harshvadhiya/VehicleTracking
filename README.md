
# Vehicle Tracking using YOLOv8 and DeepSORT

This is a vehicle tracking project that uses YOLOv8 for object detection and DeepSORT for tracking the detected vehicles. The project also has a GUI built using Streamlit, which makes it easy to use and visualize the results.

<img src="img/of-2.gif">

## Usage

You can view or test app at: https://vehicletracking.streamlit.app

This project is built using following resources

- Python 3
- YOLO v8
- DeepSORT
- PyTorch
- OpenCV
- Streamlit

Run the following command to start the Streamlit app:

```
streamlit run main.py
```

You can now open the app in your web browser at localhost:8051.

The app provides the following functionality:

- Detect Vehicle from image
- Track vehicles from video
- Count Vehicle (in/out) from video


## References

This project is using following resources:

- [YOLOv8](https://github.com/ultralytics/ultralytics)
- [DeepSORT](https://github.com/nwojke/deep_sort)
- [Streamlit](https://streamlit.io/)
- [PyTorch](https://pytorch.org/)
