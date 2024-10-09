# Screen Shot Text Extracator Using YOLOv8 & Tesseract
- Developed a web element detection system using YOLOv8 for computer vision tasks.
- Data Labeling:
Manually labeled the dataset to ensure accurate training for object detection.
- Implemented data preprocessing and management:
Mounted Google Drive for seamless data access.
- Created functions to check and maintain dataset integrity.
Deleted unnecessary image files to clean the dataset.
- Configured a custom dataset:
Defined classes for various web elements and common objects.
Generated a YAML configuration file for the dataset structure.
- Trained a YOLOv8 model:
Utilized transfer learning from a pre-trained YOLOv8n model.
Customized training parameters including epochs, batch size, and image size.
Implemented data augmentation techniques for improved model generalization.
- Set up performance monitoring:
Integrated TensorBoard for real-time training visualization.
Tracked key metrics such as box loss, class loss, and detection frequency loss.
- Achieved initial training results:
Completed multiple epochs of training with observed improvements in mean Average Precision (mAP) scores.
