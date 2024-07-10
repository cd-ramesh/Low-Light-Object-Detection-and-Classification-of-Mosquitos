# Low-Light-Object-Detection-and-Classification-of-Mosquitos
Mosquitoes, small yet perilous insects, are responsible for transmitting diseases that pose a serious threat to humans and the environment. With over 3600 known species, a few of them have the ability to transmit various pathogens, leading to widespread illnesses such as Zika, Dengue, and Chikungunya. Controlling mosquito populations is vital to prevent disease outbreaks and protect communities worldwide.

Traditional mosquito surveillance methods are expensive and time-consuming, but community-based approaches empower citizens to report and collect mosquito specimens. By leveraging machine learning and deep learning techniques, we aim to automate the labor-intensive image validation process, making mosquito identification more efficient and accurate.

## Dataset Description
The dataset for this challenge is derived from a citizen science project focused on mosquito identification. It comprises 8025 real-world images of mosquitos captured by participants using mobile phones in the dark(night-time environment). These images offer a diverse representation of mosquitos in various scenarios and locations. Each image is labeled with bounding box coordinates and mosquito class information.

The dataset has been split into training and testing sets, with 93.5% of the images allocated for training (7500 images) and 6.5% for testing (525 images). This division provides participants with ample training data to develop their models and a separate evaluation set to assess the performance and generalization of their AI algorithms.

### Files
- train_dark/images - the training images
- train_dark/labels - the training labels
- test_dark/images - the testing images
- sample_submission.csv - a sample submission file in the correct format

### Columns
In each .txt file in train_dark/labels/

- class_label - Label of the Image
- bbx_xcenter - X coordinate of center of Bounding Box
- bbx_ycenter - Y coordinate of center of Bounding Box
- bbx_width - Width of the Bounding Box
- bbx_height - Height of the Bounding Box

6 Classes: {
"aegypti": 0,
"albopictus": 1,
"anopheles": 2,
"culex": 3,
"culiseta": 4,
"japonicus/koreicus": 5
}
