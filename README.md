# Cam_Feild_Setting_UI
an UI that can do
1. camera distortion calibration
2. camera-to-real_world projection by perspective tramsform
3. polygon painting on camrea view

## Calibration
> `python realtime.py`

每三秒擷取一張frame，且用累計下來的frame去做calibration

## polygon
> `python lab_main.py`
- 完成: 讀檔、存檔(picture/ xml file)、新增資料(由於繪圖功能尚未完成，按下 add row 就會跳過繪圖，直接到增加屬性的步驟)
- TODO: Polygon 相關功能

## transform
> `python3 main.py`
- [demo video](https://drive.google.com/file/d/1grmb-mPa8ZBuAXVyfZ3c7Ut5CvvRO44C/view?usp=sharing)

## Reference
- [PySide2教學](https://medium.com/bucketing/pyside2-pyqt-tutorial-3c2be590bc6a)
- [OpenCV Camera Calibration](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_calib3d/py_calibration/py_calibration.html)

## Contributors
[詹家欣 Chia-Hsin Chan](https://sites.google.com/site/terry0201/)、

## Meeting markdown document
[link](https://hackmd.io/1zHg7h21TXWCPbuK0SQ4MA?both)
