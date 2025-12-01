# **TZ-AR Framework (UE5)**  
High-Performance Augmented Reality Framework for Unreal Engine 5

[![Watch the Demo](https://img.youtube.com/vi/QFIBqX6NG38/hqdefault.jpg)](https://youtu.be/QFIBqX6NG38)

The **TZ-AR Framework** is a modular, production-grade AR system built for **Unreal Engine 5**.

It provides developers with a ready-to-use AR foundation optimized for performance, scalability, and real-world deployment on Android devices supporting ARCore.

This framework is designed, maintained, and used internally by **The Zenith AVGC-XR LLP** for AR pipelines and client-grade production apps.

---

# **Features**

### **Core AR Functionality**
- ARCore-based session tracking
- Plane detection (horizontal and vertical)
- Light estimation
- Hit-test and surface interaction
- Real-time camera feed integration

### **Interaction System**
- Tap-to-place system  
- Drag, rotate, and scale interactions  
- Object manipulation Blueprint utilities  
- Optional persistent anchors  

### **Optimized UX**
- Clean modular Blueprints  
- Lightweight UI components  
- Minimal runtime overhead for mobile  

### **Performance Optimized for Android (ARCore)**
- Uses Unreal’s ARSessionConfig  
- Auto-resolution scaling for smooth framerate  
- Low-latency tracking pipeline  
- Mobile-friendly post-processing  

---

# **Demo Video**

Full walkthrough, features, and runtime demo:

**https://youtu.be/QFIBqX6NG38**

---

# **Repository Structure**

TZ-AR-Framework-UE5/
├─ Config/                     # Project configs
├─ Content/
│  ├─ AR/                      # AR Blueprints, UI, scripts
│  ├─ UI/                      # Mobile UI widgets
│  ├─ Demo/                    # Demo scene assets
│  └─ ...                      # Other content
├─ Source/                     # C++ modules (if any)
├─ Plugins/                    # Optional plugin integrations
├─ TZD_AR_FRAMEWORK.uproject   # Unreal project file
└─ README.md


---

# **Requirements**

### **Software**
- Unreal Engine **5.3+** (recommended: 5.4 or 5.5)
- Android Studio with NDK
- ARCore-supported Android device

### **Hardware**
- Any ARCore-compatible smartphone (Pixel, Samsung S series, etc.)

---

# **How to Run**

### 1. Clone the repository
git clone https://github.com/rajwardhan1920/TZ-AR-Framework-UE5.git


### 2. Open the Project
Open `TZD_AR_FRAMEWORK.uproject` in Unreal Engine.

If prompted:
- Install missing plugins  
- Update project files  

### 3. Enable Required Plugins  
Inside Unreal Engine:


Enable:
- **Augmented Reality**
- **ARCore**
- **GoogleARCore Services**
- **OpenXR** (optional)

Restart the editor afterward.

### 4. Package for Android

Ensure:
- SDK/NDK configured  
- Minimum SDK 24  
- ARCore plugin enabled  

---

# **Usage Guide**

### **Place an Object**
1. Scan the environment until AR planes appear  
2. Tap on a detected plane  
3. Object will spawn at the tapped location  

### **Manipulate Object**
- Drag to move  
- Two-finger rotate  
- Pinch to scale  

### **Reset Session**
A Blueprint utility resets tracking and refreshes the AR scene.

---

# **Project Goals**
- Provide a **plug-and-play AR system** for developers  
- Maintain clean, enterprise-grade architecture  
- Serve as a foundation for commercial AR apps  
- Accelerate prototyping and production timelines  

---

# **Roadmap**
- Gesture-based advanced interaction  
- Shared AR session (multiplayer)  
- Cloud anchor support  
- Improved UX widgets  
- Surface classification  
- Occlusion and depth integration  
- AR mesh reconstruction  
- API hooks for external extensions  

---

# **Contributors**

**The Zenith AVGC-XR LLP**

Lead Developers:
- **Rajwardhan Shinde**
- **Rish Hiray**

For queries, collaborations, or licensing:  
**infodesk@thezenithstudio.com**

Visit our website:  
**https://www.thezenithstudio.in**

---

# **License**

This project is released under **Zenith AVGC-XR LLP License**, unless otherwise noted.

You may use, modify, or extend it for **non-commercial projects**.

For **commercial licensing**, contact:  
**infodesk@thezenithstudio.com**

LOL raj
