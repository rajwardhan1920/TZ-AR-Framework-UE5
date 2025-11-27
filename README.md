\\# \\\*\\\*TZ-AR Framework (UE5)\\\*\\\*







High-Performance Augmented Reality Framework for Unreal Engine 5







\\\[!\\\[Watch the Demo](https://img.youtube.com/vi/QFIBqX6NG38/hqdefault.jpg)](https://youtu.be/QFIBqX6NG38)







The \\\*\\\*TZ-AR Framework\\\*\\\* is a modular, production-grade AR system built for \\\*\\\*Unreal Engine 5\\\*\\\*.



It provides developers with a ready-to-use AR foundation optimized for performance, scalability, and real-world deployment on Android devices supporting ARCore.







This framework is designed, maintained, and used internally by \\\*\\\*The Zenith AVGC-XR LLP\\\*\\\* for AR/VR pipelines and client-grade production apps.







---







\\# \\\*\\\*Features\\\*\\\*







\\### \\\*\\\*Core AR Functionality\\\*\\\*







\\\* ARCore-based session tracking



\\\* Plane detection (horizontal/vertical)



\\\* Light estimation



\\\* Hit-test \\\& surface interaction



\\\* Real-time camera feed integration







\\### \\\*\\\*Interaction System\\\*\\\*







\\\* Tap-to-place system



\\\* Drag, rotate, and scale interactions



\\\* Object manipulation blueprint utilities



\\\* Persistent anchors (optional)







\\### \\\*\\\*Optimized UX\\\*\\\*







\\\* Clean modular Blueprints



\\\* Lightweight UI components



\\\* Minimal overhead for mobile







\\### \\\*\\\*Performance Optimized for Android (ARCore)\\\*\\\*







\\\* Uses Unreal’s built-in ARSessionConfig



\\\* Auto-resolution scaling for smooth framerate



\\\* Low-latency tracking pipeline



\\\* Mobile-friendly post-processing







---







\\# \\\*\\\*Demo Video\\\*\\\*







Full walkthrough, features, and runtime demo:



\\\*\\\*\\\[https://youtu.be/QFIBqX6NG38](https://youtu.be/QFIBqX6NG38)\\\*\\\*







---







\\# \\\*\\\*Repository Structure\\\*\\\*







```



TZ-AR-Framework-UE5/



│



├── Config/                # Project configs



├── Content/



│   ├── AR/                # AR Blueprints, UI, scripts



│   ├── UI/                # Mobile UI widgets



│   ├── Demo/              # Demo scene assets



│   └── ...



│



├── Source/                # C++ modules (if any)



│



├── Plugins/               # Optional plugin integrations



│



├── TZD\\\_AR\\\_FRAMEWORK.uproject



└── README.md



```







---







\\# \\\*\\\*Requirements\\\*\\\*







\\### \\\*\\\*Software\\\*\\\*







\\\* Unreal Engine \\\*\\\*5.3+\\\*\\\* (recommended 5.4 or 5.5)



\\\* Android Studio with NDK (installed via UE5 prerequisites)



\\\* ARCore-supported Android device







\\### \\\*\\\*Hardware\\\*\\\*







\\\* Any ARCore-compatible smartphone (Pixel, Samsung S series, etc.)







---







\\# \\\*\\\*How to Run\\\*\\\*







\\### 1. Clone the repository







```



git clone https://github.com/rajwardhan1920/TZ-AR-Framework-UE5.git



```







\\### 2. Open the Project







Open `TZD\\\_AR\\\_FRAMEWORK.uproject` in Unreal Engine.







If prompted, select:







\\\* "Install missing plugins"



\\\* "Update project files"







\\### 3. Enable Required Plugins







Inside UE5:







```



Edit → Plugins



```







Enable:







\\\* \\\*\\\*Augmented Reality\\\*\\\*



\\\* \\\*\\\*ARCore\\\*\\\*



\\\* \\\*\\\*GoogleARCore Services\\\*\\\*



\\\* \\\*\\\*OpenXR\\\*\\\* (if required)



\&nbsp; Restart editor.







\\### 4. Package for Android







```



Platforms → Android → Build



```







Make sure:







\\\* SDK/NDK are configured



\\\* Minimum SDK 24



\\\* ARCore plugin is enabled







---







\\# \\\*\\\*Usage Guide\\\*\\\*







\\### \\\*\\\*Place an Object\\\*\\\*







1\\. Scan the environment until AR planes appear



2\\. Tap on a detected plane



3\\. The selected AR object will spawn at that location







\\### \\\*\\\*Manipulate Object\\\*\\\*







\\\* Drag to move



\\\* Two-finger rotation



\\\* Pinch to scale







\\### \\\*\\\*Reset Session\\\*\\\*







A blueprint utility resets tracking and refreshes the AR scene.







---







\\# \\\*\\\*Project Goals\\\*\\\*







The framework aims to:







\\\* Provide a \\\*\\\*plug-and-play AR system\\\*\\\* for developers



\\\* Maintain clean, enterprise-grade architecture



\\\* Serve as a foundation for commercial AR apps



\\\* Accelerate prototyping and production development







---







\\# \\\*\\\*Roadmap\\\*\\\*







\\\* Gesture-based advanced interaction



\\\* Shared AR session (multiplayer)



\\\* Cloud anchor support



\\\* Improved UX widgets



\\\* Surface classification



\\\* Occlusion and depth integration



\\\* AR mesh reconstruction



\\\* API hooks for external modules







---







\\# \\\*\\\*Contributors\\\*\\\*







\\\*\\\*The Zenith AVGC-XR LLP\\\*\\\*



Lead Developers:







\\\* \\\*Rajwardhan Shinde\\\*



\\\* \\\*Rish Hiray\\\*







For queries, collaborations, or consulting:

\\\*infodesk@thezenithstudio.com\\\*





Visit our website @



\\\*\\\*\\\[https://www.thezenithstudio.in](https://www.thezenithstudio.in)\\\*\\\*







---







\\# \\\*\\\*License\\\*\\\*







This project is released under the \\\*\\\*Zenith AVGC-XR LLP\\\*\\\* unless otherwise noted.



You are free to modify, extend, and use it in your  non-commercial projects.





for commercial license contact us infodesk@thezenithstudio.com

------





