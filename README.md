# SmartBuild AI
###AI-based construction safety monitoring using computer vision and PPE detection

**Making construction sites smarter, safer, and more reliable with AI.**

SmartBuild AI is an AI-powered construction safety monitoring project that uses **YOLO-based object detection and computer vision** to analyze construction videos, detect personal protective equipment (PPE), and support safety monitoring through automated visual analysis.

The goal is to help identify potential safety concerns faster and make construction environments safer through intelligent monitoring.

---

## Why this project?

Construction sites involve dynamic environments, heavy machinery, and multiple safety requirements. Manual monitoring can be time-consuming.

SmartBuild AI brings computer vision into the picture by analyzing video footage and generating visual outputs and reports to support safety assessment.

### Key Features

- **PPE Detection** — Analyze construction footage for detectable personal protective equipment.
- **Video-Based Monitoring** — Run object detection on uploaded construction videos.
- **YOLO Object Detection** — Train and evaluate baseline and improved YOLO models.
- **Model Performance Comparison** — Compare evaluation metrics to understand model performance.
- **Annotated Video Output** — Generate video footage with detection results overlaid.
- **Automated Safety Reports** — Export detection results into CSV files.
- **Visual Analytics** — Display model evaluation plots and detection summaries.
- **Potential Safety Alerts** — Generate report-based alerts for configured detection conditions.
- **Streamlit Dashboard** — Provide an interactive interface for running the monitoring workflow.
- **Exportable Results** — Package project outputs for convenient sharing and review.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| YOLO / Ultralytics | Object detection and model training |
| OpenCV | Video processing |
| Pandas | Detection reports and data analysis |
| Matplotlib & Seaborn | Visualizations |
| Google Colab | Cloud-based development and model experiments |
| Streamlit | Interactive dashboard |

---

## How It Works

```text
Construction Video
        ↓
Video Upload & Preprocessing
        ↓
YOLO-Based Object Detection
        ↓
PPE Detection & Visual Analysis
        ↓
Annotated Video Generation
        ↓
Safety Report & Potential Alerts
        ↓
Graphs, Metrics & Dashboard
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Monisha287/SmartBuild-AI.git
cd SmartBuild-AI
```



### 2. Open the Google Colab Notebook

Open `SmartBuild_AI.ipynb` in Google Colab.

Upload the required dataset and construction video when prompted, then execute the notebook cells in order.

### 3. Train and Evaluate the Models

Run the baseline and improved YOLO training workflows. Review the available evaluation metrics and plots.

### 4. Generate Results

Run the video detection and reporting steps to generate annotated footage, CSV reports, visualizations, and other configured outputs.

### 5. Launch the Dashboard

Follow the notebook's Streamlit setup instructions to extract the dashboard files, verify the trained model path, and launch the application.

> **Note:** Exact dataset paths, model weights, video files, and runtime dependencies must be configured according to your environment.

---

## Project Structure

```text
SmartBuild-AI/
│
├── SmartBuild_AI.ipynb       # Main Google Colab workflow
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies (if included)
│
├── outputs/                  # Generated results (optional)
│   ├── annotated_video.mp4
│   ├── safety_detection_report.csv
│   └── evaluation_plots/
│
└── dashboard/                # Streamlit dashboard files (if included)
```

*The structure above is a suggested layout; actual files may differ depending on what you upload to GitHub.*

---

## Expected Outputs

Depending on the notebook configuration, the workflow can produce:

- Annotated construction videos
- CSV-based detection reports
- Potential PPE-related safety alerts
- Model evaluation plots
- Baseline-versus-improved model comparisons
- A ZIP archive of generated results

**Important:** Detection quality depends on the dataset, trained model, video quality, and configured detection classes. The system supports safety monitoring; it does not replace trained safety professionals or guarantee that every hazard will be detected.

---

## Project Objectives

- Apply computer vision to construction-site safety monitoring.
- Explore YOLO-based object detection and model improvement.
- Analyze construction videos and visualize detection results.
- Generate structured reports to support safety assessment.
- Demonstrate an AI-powered workflow using Google Colab and Streamlit.

---

## Future Enhancements

- Real-time camera-based monitoring
- Expanded PPE and unsafe-behavior detection
- Live notifications for configured safety events
- Multi-camera site monitoring
- Historical safety trends and dashboards
- Cloud deployment for scalable access
- Reliability testing across different lighting conditions, camera angles, and construction environments

---

## Real-World Impact

This AI based project explores how artificial intelligence can support safer construction environments, reduce the effort involved in reviewing video footage, and make safety-related observations easier to organize and analyze.

**Smarter monitoring. Better awareness. Safer construction.**

---

## Project Information

**Project:*AI-based construction safety monitoring using computer vision and PPE detection*  
**Domain:** Artificial Intelligence, Machine Learning, and Computer Vision  
**Application:** Construction Safety Monitoring  
**Development Environment:** Google Colab  
**Interface:** Streamlit  

---

## Support the Project

If you find this project interesting, consider giving the repository a star on GitHub.

*Built with Python, computer vision, and a vision for safer construction sites.*
