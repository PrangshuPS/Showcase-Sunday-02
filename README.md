# Showcase-Sunday-02
# Object Recognition with ESP32-CAM using TinyML
This project demonstrates real-time object recognition using **Edge Impulse** on an **ESP32-CAM**. The model was trained to recognize two physical objects:  
- **Eraser**  
- **ESP32 Microcontroller**

No internet. No cloud. Just a tiny camera doing smart stuff all by itself.

## Tech Stack
- **Hardware :** ESP32-CAM (AI Thinker module)
- **Software :** Arduino IDE
- **ML Framework :** Tensorflow lite
- **Camera Format :** OV2640


---

## How It Works

1. **Dataset Creation:**  
   Custom images of an eraser and an ESP32 board were captured and uploaded to Edge Impulse.

2. **Model Training:**  
   Object Detection model was trained using Edge Impulse Studio with bounding boxes.

3. **Model Deployment:**  
   The trained `.tflite` model was compiled into an Arduino library and deployed directly to the ESP32-CAM.

4. **Real-time Inference:**  
   On boot, the ESP32-CAM captures images, runs inference, and prints bounding box results via Serial Monitor.

---

---
### For more details, refer to the [Edge Impulse](https://docs.edgeimpulse.com/docs)
---
