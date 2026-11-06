# BeatForge privacy summary

## Data collection

BeatForge has no account system, analytics SDK, advertising SDK, tracking code, or remote backend. The app does not transmit projects, recordings, samples, or other user content to the developer and does not use data for tracking. For App Store privacy answers, the intended selection is **Data Not Collected**.

## On-device data

Projects, samples, recordings, and exported files are created and stored locally on the device. BeatForge processes audio on-device. This content remains on the device unless the user explicitly exports or shares a file.

## Optional microphone access

Microphone access is not requested at launch. It is requested only after the user chooses to record audio. If permission is granted, BeatForge uses the microphone to capture audio for the selected project and stores the recording locally. If permission is denied, the rest of the app remains available.

## User-controlled file access and sharing

Importing files uses the standard iOS document picker, and exporting uses the standard iOS share sheet. The user chooses which files BeatForge may access and whether and where to send exported audio or project content. A destination's privacy terms apply after the user shares a file.

## App Store privacy declaration checklist

- Data used to track the user: No
- Data linked to the user and collected by the developer: No
- Third-party analytics or advertising: No
- Microphone permission: Optional, feature-triggered, processed on device
- File access and sharing: User initiated through standard iOS system interfaces
- Privacy manifest required for included third-party SDKs: No SDK beyond source-only Masonry; review again if dependencies change
