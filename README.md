# 🧠 Creative Fork — FastAI Learn Sprint

This repo documents my hands-on journey through the FastAI course, remixing the official notebooks with a creative and narrative twist.

## 📓 Day 1: Pet Breed Classifier 🐶🐱

Built a deep learning image classifier using `fastai` to identify 37 breeds of cats and dogs.  
Trained a ResNet model with transfer learning, visualized results, and tested on a custom image.

### ✅ Achievements
- Loaded and preprocessed Oxford-IIIT Pet dataset
- Trained a ResNet34 with `cnn_learner`
- Fine-tuned learning rate with `lr_find`
- Visualized top losses and confusion matrix
- Tested on custom image: nailed the prediction `shiba_inu` with 91% confidence 🔥

### 🧪 Next Steps
- Add more custom images for inference
- Experiment with data augmentation
- Try another architecture (like EfficientNet)

---

### 🗂️ Files
- `day1_pet_classifier.ipynb`: Notebook from Day 1 (based on `01_Pets.ipynb`)
- `stage_1.pth`: Trained model weights
- `Cane11.jpg`: My test image used for prediction

---

### 📸 Screenshot
![Prediction](./Cane11_screenshot.png)

---

Follow the repo as I iterate day by day 🌀  
Let’s learn, remix and build with FastAI ⚡
