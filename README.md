# deblurring-video
A deep learning project using Temporal U-Net to remove motion blur from videos. Trained on the GoPro dataset, it deblurs frames by learning temporal consistency, and processes user-uploaded videos to produce clearer outputs.

# Video Deblurring using Temporal U-Net

A deep learning project that removes motion blur from videos.  
Trained on the GoPro dataset, the model uses a custom **Temporal U-Net** architecture that takes three consecutive blurry frames as input and predicts a clearer middle frame.  
Built with Python, PyTorch, and OpenCV in Google Colab, it can process your own uploaded videos to produce sharper outputs.

---

##  Features
- Train a Temporal U-Net model on GoPro dataset
- Validate and visualize deblurred frames vs. ground truth
- Upload and deblur your own videos in Colab
- Save and download the deblurred output video

---

##  Project Structure
- `video_deblurring_train.ipynb` – train the model
- `video_deblurring_validation.ipynb` – visualize validation results
- `user_input.ipynb` – deblur your own uploaded videos
- `README.md` – project info
- `requirements.txt` – required Python packages

---

## ⚙Requirements
- Python 3.x
- torch
- torchvision
- opencv-python
- numpy
- matplotlib
- tqdm
- google-colab (if using Colab)
Install all at once:
```bash
   pip install -r requirements.txt

## How to Use

