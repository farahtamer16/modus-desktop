# MoDUS: Desktop Eye-Tracking for Dementia Monitoring

### Overview
**MoDUS (Monitoring Dementia Using Smartphones/Desktop)** is a cross-platform cognitive assessment application that uses **real-time eye tracking** to evaluate executive function through the **antisaccade task**, a well-established measure of cognitive control.  

This project extends the original **mobile MoDUS** into a **desktop version** built with **Unity** and **MediaPipe**, enabling low-cost, accessible cognitive testing via standard webcams. It was developed in collaboration with the **School of Psychology** at the **University of Nottingham Malaysia**.

### Literature Context
Traditional dementia assessments rely on costly, clinic-bound setups with specialized eye-tracking hardware. Research has shown that **antisaccade tasks**—tests measuring the ability to look away from a visual stimulus—are reliable markers of executive function and early dementia detection. MoDUS bridges the gap between **clinical precision** and **real-world accessibility** by integrating webcam-based gaze tracking and MediaPipe’s iris detection framework. This approach democratizes cognitive testing, providing scalable and reliable home or clinical use without lab-grade hardware.

### Features
- **Webcam-based eye tracking** using MediaPipe Iris  
- **Real-time gaze classification** (Easy, Medium, Difficult antisaccade modes)  
- **Audio-visual feedback** to guide users  
- **Automatic CSV data logging** for trial analysis  
- **Configurable cloud upload system** (Google Drive, Firebase, Supabase)  
- **Offline functionality** for at-home or low-connectivity use  
- **User-friendly UI** optimized for older adults and clinicians  

### Technology Stack
- **Engine:** Unity 2021.3 LTS (C#)  
- **Libraries:** MediaPipe Iris, TextMeshPro  
- **Data Handling:** CSV Export, JSON Config  
- **Cloud Services:** Firebase Firestore, Google Drive API  
- **GUI Tools:** Python (Tkinter) for config editor  

### Evaluation Highlights
Validated across **466 trials**, achieving:
-  **92.3 % correct-response rate**
-  **226 ms mean saccade latency** (within clinical norms)
-  Reliable antisaccade classification under real-world conditions

These results demonstrate the feasibility of webcam-based cognitive testing comparable to lab-grade systems.

### Documentation
**Read the full technical report:**  
[MoDUS_Final_Report.pdf](./MoDUS_Final_Report.pdf)


### Author
**Farah Tamer Fathy Ahmed Elsaid**  
B.Sc. Computer Science with Artificial Intelligence (Hons)  
University of Nottingham (2025)

### Acknowledgements
Supervised by **Dr. Iman Liao**  
Developed in collaboration with the **School of Psychology**, University of Nottingham Malaysia.
