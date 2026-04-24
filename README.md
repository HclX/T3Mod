# T3Mod

This repository contains the standalone HTML sync tool for Tech Tree Tower.

## Obtaining Firebase Secrets

To use the sync tool, you need to obtain the **API Key** and **Project ID** from the game's APK file.

1.  **Decompress the APK**: The APK is essentially a ZIP file. You can unzip it or open it with any archive manager.
2.  **Locate the Configuration File**: Navigate to the `assets/` directory in the extracted files. Look for `google-services-desktop.json` (or `google-services.json`).
3.  **Extract the Values**: Open the JSON file and look for the following fields:
    -   **Project ID**: Usually found as `"project_id"`.
    -   **API Key**: Usually found in the `"api_key"` object under `"current_key"`.
