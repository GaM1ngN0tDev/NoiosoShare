# NoiosoShare

> [!WARNING]
> This Project Was Used AI In The Process If You Don't Like AI Please Do Not Start Spamming Into My Issues Or Inbox AI Nor Starting Hate.
> This Project Is A Work In Progress 

# NoiosoShare

> **Zero-friction, privacy-first local file dropping between Windows and Android.**

NoiosoShare combines the convenience of a **compact taskbar tray flyout** with a **full-featured Material 3 desktop application**. Drag and drop files directly onto the app or tray to beam them at full local Wi-Fi speeds without cloud servers or subscriptions.

---

## Key Features

* **Dual-Mode UI**:
  * **Compact Tray Flyout**: Sits in your Windows taskbar tray. Click to toggle quick sending, 1-click clipboard beam, and a mini drop zone.
  * **Full Window Application**: Modern Material 3 dashboard with device radar, transfer manager, paired device whitelist, and settings.
* **Instant Drag-and-Drop**: Drag any file, photo, or document over the app window or tray drop zone to beam immediately.
* **One-Click Clipboard Beam**: Copy a text snippet, URL, or code on PC and send it directly to your phone's clipboard.
* **Trusted Device Auto-Accept**: Pair your phone once to skip manual confirmation prompts on every transfer.
* **100% Local & Private**: Direct peer-to-peer over your local Wi-Fi (no tracking, no cloud telemetry).

---

## 🏗️ Project Structure

```text
NoiosoShare/
├── app/                           # Flutter client application
│   ├── lib/
│   │   ├── models/                # Device & TransferItem models
│   │   ├── providers/             # ShareProvider reactive state
│   │   ├── services/              # TrayService (window & tray manager)
│   │   ├── theme/                 # Material 3 custom light & dark themes
│   │   ├── views/                 # FullAppView & TrayFlyoutView
│   │   └── main.dart              # App entry point
│   ├── assets/                    # Icons and assets
│   └── windows/                   # Native Windows C++ runner & CMake
└── flutter/                       # Self-contained Flutter SDK
The optimized `.exe` will be generated in `app\build\windows\x64\runner\Release\`.

