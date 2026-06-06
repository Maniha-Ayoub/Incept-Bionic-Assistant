# Incept Bionic Assistant 

A high-performance Progressive Web App (PWA) designed for universal accessibility, bridging the gap between human perception and AI-powered sensory modules.

## Key Features
* **Neural Vision (Incept-Sight):** Leverages the `coco-ssd` model via TensorFlow.js for real-time object detection through the device's lens.
* **PureVoice Audio:** Advanced Speech-to-Text transcription that generates compact "Neural Summaries" for quick cognitive processing.
* **Memory Bank:** A persistent, locally-stored archive of all sensory interactions, allowing users to "recall" past detections and transcriptions.
* **Haptic Pulse System:** Optimized for mobile immersion; uses the Vibration API to provide physical feedback (haptic pulses) during system events and sidebar interactions.
* **Neural Synthesis Kill-Switch:** A custom safety feature that instantly terminates background AI speech when navigating or refreshing to maintain system silence.

## Mobile-First Design (PWA)
* **Standalone UI:** Removes browser chrome for a native app feel.
* **Dynamic Navigation:** Includes a mobile-responsive hamburger menu and a dedicated 'X' close feature for small-screen ergonomics.
* **Offline Readiness:** Service Worker integration ensures the core "Bionic" shell remains accessible without a network.

## Technical Stack
* **Frontend:** Vanilla JavaScript (ES6+), CSS Grid/Flexbox.
* **Backend:** Node.js & Express.js.
* **Machine Learning:** TensorFlow.js / COCO-SSD.
* **APIs:** Web Speech (Recognition/Synthesis), Navigator Vibration API.
