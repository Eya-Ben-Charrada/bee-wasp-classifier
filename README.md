# 🐝 Bee vs Wasp Classifier  

This project uses an **Edge Impulse TinyML model** to classify bees and wasps in real time.  
The model was trained on bee/wasp images and exported for **Arduino** deployment.  

---

## 📂 Repository Structure
- `firmware/arduino/` : Arduino library exported from Edge Impulse.  
- `model/` : Trained `.eim` model file (optional, for other deployments).  
- `README.md` : Project documentation.  

---

## 🚀 How to Use  

### Requirements
- Arduino IDE (or PlatformIO)  
- ESP32 / Arduino-compatible board  
- Camera module (ESP32-CAM or similar)  

### Steps
1. Clone this repository:  
   ```bash
   git clone https://github.com/Eya-Ben-Charrada/bee-wasp-classifier.git
   ```

2. Open Arduino IDE → Sketch > Include Library > Add .ZIP Library → select the folder inside firmware/arduino/.

3. Open the example sketch provided inside the library.

3. Upload to your ESP32 and test!









