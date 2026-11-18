<img align="right" width="104" height="104" src="https://github.com/SazidAhmedTonmoy.png?size=208" alt="Sazid’s GitHub profile picture">

# Md Sazid Ahmed Tonmoy

**Software Engineer** · ATPL Dhaka, Ampec Technologies  
Dhaka, Bangladesh

[Portfolio ↗](https://sazidahmedtonmoy.github.io/)　·　[LinkedIn](https://www.linkedin.com/in/sazidahmedtonmoy/)　·　[Email](mailto:sanzidtonmoy@gmail.com)

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&amp;weight=500&amp;size=18&amp;duration=2200&amp;pause=2300&amp;color=439B9E&amp;width=345&amp;height=32&amp;lines=Python+backend+development;Edge+AI+%26+IoT;Embedded+systems;Workflow+automation" width="345" alt="Python backend development · Edge AI and IoT · Embedded systems · Workflow automation">

Most days I work on Python backends. Sometimes the output is an electrical estimate a team can send to a builder. Sometimes it’s a roadside sign showing the silhouette of the vehicle that just triggered it.

## Selected work

### TEC EstiDoc

Electrical estimators build a quote from catalogue items, material costs and labour hours. I work on the Python and SQLite workflows behind that process, from the first estimate line to the tender team’s next follow-up.

> **4,029** active catalogue items　 ·　 **41** estimate projects　 ·　 **408** builder submissions  
> <sub>EstiDoc 3.8.0 · 18 November 2026 snapshot</sub>

[Explore the database diagram ↗](https://sazidahmedtonmoy.github.io/#projects)

### Over-height vehicle detection

A LiDAR scan gives us a height. A camera frame tells us which vehicle it belongs to. The controller matches the two, uses YOLO to isolate the vehicle and sends its silhouette to a roadside LED display.

```mermaid
flowchart LR
    A[LiDAR height event] --> C[Match by time]
    B[Camera snapshot] --> C
    C --> D[Segment vehicle]
    D --> E[Roadside LED]
    classDef accent fill:#12343b,stroke:#498b90,color:#e4f4f3
    class C,E accent
```

<p><img src="https://skillicons.dev/icons?i=py,opencv,pytorch,linux&amp;theme=dark" width="140" alt="Python, OpenCV, PyTorch and Linux"></p>

<details>
<summary><strong>Four more field systems</strong> · roadside control and traffic monitoring</summary>

- **School Zone Alert Sign System** — a Raspberry Pi validates timetables, switches warning lanterns and reports battery voltage and LED current.
- **Advanced Warning System** — a single controller handles radar, radio, wired and off-road modes, with local flash tests and fault logs.
- **Crowd Management System** — directional camera counts track occupancy and activate a digital output when the configured threshold is reached.
- **Vehicle Counting System** — camera events are grouped by lane and vehicle class, producing rolling counts and configurable output pulses.

</details>

## Experience

**Software Engineer · ATPL Dhaka**  
*February 2024 – present*  
Python services and operator dashboards for estimating teams and roadside equipment. My work also covers Excel and PDF automation, sensor integration and field diagnostics.

**R&D Engineer · Shanghai BDCOM InfoTech**  
*March – December 2023*  
I wrote a TFTP server in embedded C for the S2510-P switch on VxWorks, including option negotiation and block-size extensions. [View the networking project ↗](https://github.com/SazidAhmedTonmoy/Professional-Project)

## Toolkit

**Python · FastAPI · Flask · SQLite · MySQL**  
My main tools for building APIs, modelling project data and connecting web interfaces to field devices.

<details>
<summary>Explore the full toolkit</summary>

| Area | Tools and interfaces |
| --- | --- |
| **Backend & databases** | Python, FastAPI, Flask, REST APIs, SQLite, MySQL |
| **Edge AI & computer vision** | OpenCV, YOLO, PyTorch, TensorFlow, scikit-learn |
| **Embedded systems** | C, C++, Embedded Linux, VxWorks, Raspberry Pi, NVIDIA Jetson, GPIO, UART |
| **IoT & connectivity** | TCP/IP, UDP, MQTT, LoRa, LoRaWAN, AWS IoT Core |
| **Data & automation** | pandas, NumPy, openpyxl, Bash, Gemini API |
| **Web interfaces & delivery** | JavaScript, HTML, CSS, Git, Docker, Postman |

</details>

## Education

**North South University** · BS in Computer Engineering · January 2019 – November 2022  
**Cum Laude · CGPA 3.52**  
I specialized in artificial intelligence, minored in computer networks and participated in problem-solving and Kaggle competitions.

<details>
<summary><strong>Undergraduate research and software projects</strong></summary>

- **Tooth decay detection** — used YOLOv6 and OpenCV to locate decay in dental images.
- **Ocular disease recognition** — built a ResNet50 classifier with a Streamlit interface for cataracts, glaucoma and myopia.
- **Chest X-ray classification** — applied MobileNetV2 transfer learning to a dataset of 5,000 images for pneumonia and COVID-19 classification.
- **Heart disease and diabetes prediction** — explored clinical datasets and compared supervised classifiers with scikit-learn.
- **NSU Internship Management System** — built application, evaluation and advisor-reporting workflows with PHP, MySQL and JavaScript.
- **Formula_Pro and Vivid Letter** — developed Python and Jupyter utilities for engineering calculations and document formatting.

[Browse my university projects ↗](https://github.com/SazidAhmedTonmoy/Projects)

</details>
