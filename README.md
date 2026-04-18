# Phát hiện Mũ Bảo Hiểm sử dụng Fast R-CNN và Faster R-CNN

## Giới thiệu
Khóa luận tốt nghiệp - Khoa học Dữ liệu
Trường Đại học Kinh tế - Kỹ thuật Công nghiệp

## Cấu trúc thư mục
#KLTN_HelmetDetection/
#├── datasets/               # Script xử lý dữ liệu
#│   ├── crop_dataset.ipynb
#│   └── data_for_CNN.ipynb
#├── models/
#│   ├── Train_FastRCNN.ipynb
#│   ├── Train_FasterRCNN.ipynb
#│   └── Evaluate_Models.ipynb
#└── README.md
## Kết quả
| Mô hình | mAP@0.5 | Recall | F1-Score |
|---------|---------|--------|----------|
| Faster R-CNN | 0.8697 | 0.9216 | 0.8624 |
| Fast R-CNN   | 0.7428 | 0.7958 | 0.8075 |

## Môi trường
- Python 3.x
- PyTorch 2.11.0
- GPU: NVIDIA GeForce RTX 4090
