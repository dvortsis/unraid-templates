# Unraid CA Templates

This repository contains XML templates for the [Unraid Community Applications (CA)](https://forums.unraid.net/topic/38582-plug-in-community-applications/) store. 

## Available Applications

* **[Lodestar](https://github.com/dvortsis/lodestar)**: A beautiful, high-performance discovery interface for Bitmagnet. It features a bespoke discovery engine using PGroonga for blazingly fast deep-file searches, tiered relevance ranking, and a mobile-friendly progressive UI.

## Installation Methods

To prevent custom variables (like connection strings) from being overwritten during routine updates, it is recommended to install these templates locally on your Unraid server. Be sure to remove the `<TemplateURL>` line from the XML file before saving it to your server.

### Method 1: Manual Local Installation (via USB/SMB)
Use this method to transfer the file via your network or by physically moving the flash drive.

1. Download the raw `.xml` file for the application from this repository.
2. Access your Unraid **Flash** drive (either via SMB share or by plugging the USB into a PC).
3. Navigate to the following directory on the flash drive:
   `config/plugins/dockerMan/templates-user/`
4. Copy your downloaded XML file into this folder.
   * *Optional: Rename the file to something unique like `my-lodestar.xml`.*
5. Go to the **Docker** tab in your Unraid Web UI.
6. Click **Add Container** at the bottom.
7. Your local template will now appear in the **Template** dropdown menu.

---

### Method 2: Terminal Installation (via nano)
Use this method if you prefer working directly via the Unraid command line to create the template file.

1. Copy the raw XML content for the application directly from GitHub.
2. Open the Unraid **Terminal** (the `>_` icon in the top right of the Web UI) or connect to your server via SSH.
3. Open a new file using the `nano` text editor by running:
   `nano /boot/config/plugins/dockerMan/templates-user/my-lodestar.xml`
4. Paste the copied XML content into the terminal window.
5. Save the file by pressing **Ctrl+O**, then **Enter**.
6. Exit the editor by pressing **Ctrl+X**.
7. Go to the **Docker** tab in your Unraid Web UI.
8. Click **Add Container** at the bottom.
9. Your newly created template will now appear in the **Template** dropdown menu.

---

## Support

If you experience issues with the templates themselves, please open an issue in this repository. For application-specific bugs, database questions, or Lodestar feature requests, please visit the [Lodestar repository](https://github.com/dvortsis/lodestar).
