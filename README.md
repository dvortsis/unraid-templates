# Unraid CA Templates

This repository contains XML templates for the [Unraid Community Applications (CA)](https://forums.unraid.net/topic/38582-plug-in-community-applications/) store. 

## Available Applications

* **[Lodestar](https://github.com/dvortsis/lodestar)**: A beautiful, high-performance discovery interface for Bitmagnet. It features a bespoke discovery engine using PGroonga for blazingly fast deep-file searches, tiered relevance ranking, and a mobile-friendly progressive UI.

## How to Add Manually to Unraid

If you want to test the templates before they are officially approved in the CA store, you can add this repository manually to your Unraid server:

1. Log in to your Unraid Web UI.
2. Navigate to the **Docker** tab.
3. Scroll down to the bottom where it says **Template Repositories**.
4. Paste the following URL into the box:
   `https://github.com/dvortsis/unraid-templates`
5. Click **Save**.
6. Click **Add Container** at the bottom of the Docker page.
7. Select the desired template (e.g., `lodestar`) from the "Template" dropdown menu at the top.

## Support

If you experience issues with the templates themselves, please open an issue in this repository. For application-specific bugs, database questions, or Lodestar feature requests, please visit the [Lodestar repository](https://github.com/dvortsis/lodestar).
