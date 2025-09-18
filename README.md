<div align="center">

# Sandesh Kumar

**Perception for outdoor robots** — crop · weed · soil · lane

[Jeonbuk National University](https://www.jbnu.ac.kr/) · [Core Research Institute of Intelligent Robots](https://robot.jbnu.ac.kr/)

[GitHub](https://github.com/Sandesh1764) · [LinkedIn](https://www.linkedin.com/in/sandesh-kumar-77ab25209) · [Paper](https://doi.org/10.1016/j.compag.2025.110990)

</div>

<br/>

I build **real-time vision** that runs on machines in the field — not demos in a lab.  
Most of my work sits on one loop: **see the plant → separate crop from weed → act precisely**.

---

## Featured — field weeding robot (KBS)

Our institute’s autonomous **crop-management robot** was covered by **KBS News** (Sep 2025).  
It drives crop rows, segments bean vs weed from onboard cameras, and sprays **only the weed** with a micro-dose — built for Korea’s narrow, sloped fields.

| | |
| :--- | :--- |
| **Broadcast** | [“제초도 스스로”… 피지컬 AI, 농업에서 성과 낼까? — KBS](https://news.kbs.co.kr/news/pc/view/view.do?ncd=8365296) |
| **Paper** | [Pin-precision weeding with densely placed needle nozzles](https://doi.org/10.1016/j.compag.2025.110990) · *Computers and Electronics in Agriculture*, 2025 |
| **Role** | Perception & deep-learning stack for pin-precision weeding (co-author) |

```text
  camera  ──►  crop / weed perception  ──►  pin nozzles  ──►  field robot
```

---

## Selected work

A short public line of repositories — same problem family, increasing difficulty.

| Year | Repository | What it is |
| :---: | :--- | :--- |
| 2025 | [**pidnet-cropweed**](https://github.com/Sandesh1764/pidnet-cropweed) | Real-time PIDNet-S · **0.887 mIoU** · ~91 FPS @ 1080p |
| 2025 | [**cropweed-kd**](https://github.com/Sandesh1764/cropweed-kd) | Knowledge distillation · DeepLab teacher → fast student |
| 2025 | [**advent-cropweed**](https://github.com/Sandesh1764/advent-cropweed) | Unsupervised domain adaptation (ADVENT) across fields |
| 2024 | [**road-lane-detection**](https://github.com/Sandesh1764/road-lane-detection) | Ego-camera lane segmentation · DeepLabV3 |
| 2023 | [**crop-weed-segmentation**](https://github.com/Sandesh1764/crop-weed-segmentation) | UAV Bonn U-Net baseline · Grad-CAM |
| 2020 | [**face-mask-detection**](https://github.com/Sandesh1764/face-mask-detection) | Early CV prototype · SSD + MobileNetV2 |

---

## Focus

- **Real-time semantic segmentation** for agriculture and outdoor robots  
- **Domain shift** — models that still work on a new farm / weather / camera  
- **Edge deployment** — FPS and parameter budgets that fit a robot PC  
- **ROS-facing systems** — perception that closes the loop with actuation  

Stack I use day to day: **PyTorch · OpenCV · ROS · Python · C++**

---

<div align="center">

*Quiet page on purpose. Code lives in the repos above.*

</div>
