🍎 Nhận dạng vật thể bằng Faster R-CNN

Dự án này sử dụng Faster R-CNN (ResNet-50 backbone) để phát hiện và phân loại các loại trái cây trong ảnh.
Mô hình được huấn luyện trên tập dữ liệu tuỳ chỉnh (custom dataset) và thực nghiệm trên Kaggle bằng PyTorch.
🧠 Giới thiệu

Dự án này triển khai mô hình Faster R-CNN để nhận dạng và phát hiện vật thể (trái cây).
Mục tiêu là giúp máy tính có khả năng phát hiện vị trí và phân loại các đối tượng trong ảnh.

Mô hình được xây dựng bằng PyTorch, tận dụng mô hình pretrained từ COCO dataset và fine-tune trên tập dữ liệu riêng.
⚙️ Kiến trúc mô hình

Backbone: ResNet-50 pretrained trên COCO
Framework: PyTorch (torchvision.models.detection)
Optimizer: SGD
Loss: Kết hợp giữa classification loss và bounding box regression loss
