# Tactical-Analysis-from-Football-match-video
This project performs tactical analysis of football match videos using Computer Vision and Deep Learning techniques. The system is designed to automatically detect players, track their movement, and estimate body pose to understand formations, spacing, player roles, and tactical behaviors throughout the match.
# Tactical Analysis from Match Videos using Computer Vision

This project focuses on extracting **player movements, formations, and tactical insights** from football match videos using **Computer Vision** and **Deep Learning** techniques.  
The pipeline detects players, tracks their movement across frames, estimates body keypoints, and converts positions into pitch coordinates for tactical visualization.

---

## 🎯 Objectives

- Detect players and ball from broadcast match videos.
- Track each player consistently across frames.
- Estimate player body pose (17 keypoints).
- Map player locations to the pitch.
- Analyze formations, distances, heatmaps, and movement patterns.

---

## 🧠 Techniques Used

| Task | Method / Model |
|------|----------------|
| Player Detection | **YOLOv8 / YOLOv5** (Bounding Boxes) |
| Pose Estimation | **OpenPose / AlphaPose / MediaPipe** |
| Player Tracking | **SORT / DeepSORT / ByteTrack** |
| Field Calibration | **Homography transformation** |
| Tactical Insights | Position clustering, heatmaps, pass-lane mapping |

---

## 📁 Dataset

You can use any football match video as input, or download publicly available annotated datasets:

- **SoccerNet**: Full match footage + event labels  
- **SportsMOT**: Multi-object tracking in sports videos  
- **PoseTrack**: Multi-person pose estimation dataset  
- **COCO Keypoints**: Pretraining for pose estimation models  

## Output Examples
Player bounding box + ID tracking
Pose skeleton overlays
Formation diagrams
Heatmap of player positioning
Distance & speed charts
