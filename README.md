# Unraid CA Templates

This repository contains XML templates for the [Unraid Community Applications (CA)](https://forums.unraid.net/topic/38582-plug-in-community-applications/) store. 

## Available Applications

* **[Lodestar](https://github.com/dvortsis/lodestar)**: A beautiful, high-performance discovery interface for Bitmagnet. It features a bespoke discovery engine using PGroonga for blazingly fast deep-file searches, tiered relevance ranking, and a mobile-friendly progressive UI.

## Installation

Use this method if you want to keep a local, permanent copy of the template that will **not** be overwritten by remote updates.

1. Download the `.xml` file for the application from this repository.
2. Access your Unraid **Flash** drive (either via SMB share or by plugging the USB into a PC).
3. Navigate to the following directory on the flash drive:
   `config/plugins/dockerMan/templates-user/`
4. Copy your downloaded XML file into this folder.
   * *Optional: Rename the file to something unique like `my-lodestar.xml`.*
5. Go to the **Docker** tab in your Unraid Web UI.
6. Click **Add Container** at the bottom.
7. Your local template will now appear in the **Template** dropdown menu.

---

## Support

If you experience issues with the templates themselves, please open an issue in this repository. For application-specific bugs, database questions, or Lodestar feature requests, please visit the [Lodestar repository](https://github.com/dvortsis/lodestar).
