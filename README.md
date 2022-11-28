# Tìm hiểu cách dùng GAN để né tránh IDS bằng IDSGAN
Lớp: IE105.N11 <br/>
Giáo viên hướng dẫn: Nguyễn Tấn Cầm

| STT | Họ tên | MSSV | E-mail |
| :---: | --- | --- | --- |
| 1 | Lê Quang Thắng | 20521895 | 20521895@gm.uit.edu.vn |
| 2 | Nguyễn Thành Trung | 20522074 | 20522074@gm.uit.edu.vn |
| 3 | Đoàn Quốc Bảo | 20521097 | 20521097@gm.uit.edu.vn |

## Prerequisite

* Python 3.7
* Download the scipy v1.3.1 wheel file from [here](https://github.com/scipy/scipy/releases/tag/v1.3.1). Only Python 3.5-3.7 are supported, so pick the right version (cp35-cp37). Also pick the right OS and 32/64-bits version.
* Run pip install scipy-1.3.1-cp37-cp37m-win_amd64.whl (for example) from the folder where the .whl file is.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://github.com/photonrays/Intrusing-Detection-System-Attack)).
2. Navigate to repository folder
3. Install dependencies which are specified in requirements.txt. use `pip install -r requirements.txt` or `pip3 install -r requirements.txt`
4. Train ids first with `python train_all_ids.py`
5. Train wgan model with `python train_wgan.py` and test wgan model with `python test_wgan.py --config configs/[your-config].yaml` with your-config is your created config

## Credit

All credit for the repository goes to [ChrisFugl](https://github.com/ChrisFugl)
