## This is a project that creates a code using modules like media pipe and open-cv2 for movement of a robot using predefined gestures.
### **Features:**
* Real-time Hand Tracking – Uses MediaPipe to detect and analyze hand positions in live video.
* Predefined Gesture Recognition – Recognizes specific hand gestures for robot control.
* Smooth & Responsive – Optimized to process hand movements quickly for real-time response.
* Customizable Commands – Easily modify the code to add new gestures and map them to different actions.
* Expandable to Other Hardware – Can be integrated with Arduino, Raspberry Pi, or Bluetooth modules for real-world robotic applications.
### **It works in the following manner:**
* The system captures a live video feed and detects the hand using MediaPipe Hand Tracking, which identifies 21 key points on the hand.
* Specific finger positions are analyzed to determine gestures:
  * All fingers open → Move forward 
  * All fingers closed → Stop 
  * Index finger extended → Move sideways (left or right) 
* The webcam feed is processed in RGB format, and MediaPipe locates the finger positions.
* The detected gesture is mapped to a predefined robot command, which can be further customized.
### **Customization:**
* You can program different gestures to trigger custom robot actions (e.g., increasing speed, turning in a specific direction).
* The system can be extended to interact with other robotic hardware via Arduino, Raspberry Pi, or Bluetooth modules.
This project offers a natural and intuitive way to control robots using hand gestures. 
