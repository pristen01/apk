# Align — automatic posture scan

[Download Align 0.2.0 APK](https://github.com/pristen01/apk/raw/refs/heads/main/Align-0.2.0.apk)

Requires Android 8 or newer with an updated Android System WebView. Install over 0.1.0; the package name and signing key are unchanged.

## What changed

- Actual MediaPipe Pose Landmarker inference, with 33 detected body landmarks and a live skeleton overlay. No manual landmark marking.
- Guided front, right-side, back and left-side captures with spoken prompts, confidence checks and a stable hold countdown. Follow the turn instructions: the model checks frontal vs side-on framing but does not establish front/back or left/right identity.
- Automatic shoulder-line, hip landmark-line, trunk and knee angle estimates, with ear-to-shoulder offset where reliable.
- Comfortable arm-raise and knee-bend observations with live angles and an observed movement range.
- Reports stored locally, with measurement export. Camera frames are not uploaded.
- Model, JavaScript and WebAssembly runtime bundled inside the APK.

## How to scan

1. Open Posture check. Read and confirm the symptom check.
2. Prop the phone upright and level around waist height; include your full body in good light.
3. Tap Start camera & scanner, allow camera access, and wait for the model.
4. Once tracked, tap Begin guided scan and follow the four turn prompts.
5. Review the estimates and use My progress to reopen reports.

## Limits and verification

Camera-plane estimates are affected by perspective, clothing and model error. They cannot diagnose pelvic tilt, spinal curvature, sciatica, tight muscles, leg length or the cause of pain. There is no clinical posture score or personalized medical exercise prescription. Do not move through pain.

The bundled model detected 33 landmarks in three frames from the reference video and no body in a blank-image test. Seven geometry and capture-quality unit tests pass. APK contents, update signing certificate and signature were verified. Live browser and physical Android camera testing have not been completed.

SHA-256: `ab17667d3a256875d5c5c2a9bd9ca16817bff413c879165d6a5a9644288ef3cb`

MediaPipe Tasks Vision 0.10.21 and Pose Landmarker Lite are bundled with license notices.
