# T3Mod

This repository contains a small tool to assist in modding an Android Game
(sorry, I can't mention the game names here because it might get this repo
taken down). You can access the tool via [https://hclx.github.io/T3Mod/](https://hclx.github.io/T3Mod/)

## Getting Started

### Setup Secrets

1.  **Decompress the APK**: The APK is essentially a ZIP file. You can unzip it
or open it with any archive manager.
2.  **Locate the Configuration File**: Navigate to the `assets/` directory in
the extracted files. Look for
google-services-desktop.json` (or `google-services.json`).
3.  **Extract the Values**: Open the JSON file and look for the following
fields:
    -   **Project ID**: Usually found as `"project_id"`.
    -   **API Key**: Usually found in the `"api_key"` object under
        `"current_key"`.
4. **Enter account name and password**: Enter your account name and password in
the respective fields. Your information will be kept locally on your device.


### Modifying the Game
0. Make sure you kill the app first
1. Use the "Fetch Data" button to pull the latest data from the cloud
2. Edit the data in the text boxes
3. Make sure you increase the "SaveRevision" number by at least 1 so the game
will reload your changes
4. Use the "Push Data" button to push the data to the cloud
5. Restart the app and you should see your changes

### Notes
- You can get banned for using this tool. 
- Backup your data using "Export" button before pushing any changes.
- You can also make arbitrary changes to the data in the text boxes, or import
a completely new JSON file if you want to and upload entire json file to the
cloud. The tool does not validate the JSON file.

