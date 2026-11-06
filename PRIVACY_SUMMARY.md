# DayArc privacy summary

## Data collection

DayArc has no account system, analytics SDK, advertising SDK, tracking code, or remote backend. The app does not transmit user content to the developer and does not use data for tracking. For App Store privacy answers, the intended selection is **Data Not Collected**.

## On-device data

Events and tasks created locally are stored in `NSUserDefaults` on the device. This content can include titles, dates, locations or call links, notes, categories, repeat settings, alerts, and task completion state. It remains on the device unless the user explicitly exports or shares a PDF.

## Optional system calendar access

Calendar access is not requested at launch. It is requested only after the user taps Connect Calendars. If permission is granted, EventKit is used on-device to read events for the displayed date range and to add or update events in the user's system calendar. DayArc does not access Reminders, Contacts, Photos, Location Services, microphone, camera, or network services.

## User-controlled sharing

PDF export writes a temporary file and presents the standard iOS share sheet. The user chooses whether and where to send it. The destination's privacy terms apply after the user shares the file.

## App Store privacy declaration checklist

- Data used to track the user: No
- Data linked to the user and collected by the developer: No
- Third-party analytics or advertising: No
- Calendar permission: Optional, feature-triggered, processed on device
- Privacy manifest required for included third-party SDKs: No SDK beyond source-only Masonry; review again if dependencies change
