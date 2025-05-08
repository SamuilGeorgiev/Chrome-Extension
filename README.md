# Link Saver - Your Simple Link Management Extension

This Chrome extension allows you to easily save and manage website links. Whether you want to quickly save the current tab or manually input a URL, Link Saver provides a simple and efficient way to keep track of important web pages.

## Features

* **Save Current Tab:** With a single click, save the URL of your currently active tab.
* **Save Inputted Links:** Manually type or paste URLs into the input field and save them.
* **View Saved Links:** All your saved links are displayed in a clear, clickable list. Clicking a link will open it in a new tab.
* **Delete All Links:** Easily clear all your saved links with a double-click of the "DELETE ALL" button.
* **Persistent Storage:** Your saved links are stored locally in your browser's local storage, ensuring they persist across browser sessions.

## How to Install

1.  Download the extension files (you'll likely have `manifest.json`, `index.html`, `index.js`, and `index.css`).
2.  Open Google Chrome and navigate to `chrome://extensions/`.
3.  Enable "Developer mode" in the top right corner.
4.  Click the "Load unpacked" button in the top left corner.
5.  Select the folder containing the extension files and click "Open".

The Link Saver extension icon should now appear in your Chrome toolbar.

## How to Use

1.  **Save Current Tab:** When you are on a webpage you want to save, simply click the Link Saver extension icon in your toolbar. The URL of the current tab will be automatically saved to your list.
2.  **Save Inputted Links:** Click the extension icon to open the popup. In the input field, type or paste the URL you want to save and then click the "SAVE INPUT" button.
3.  **View Saved Links:** All your saved links will be displayed in the popup window as a list. Click on any link in the list to open it in a new tab.
4.  **Delete All Links:** To clear all your saved links, double-click the "DELETE ALL" button in the popup window.

## File Structure

* `manifest.json`: Defines the extension's metadata, permissions, and scripts.
* `index.html`: The main HTML structure for the extension's popup.
* `index.js`: Contains the JavaScript logic for handling user interactions and managing the saved links.
* `index.css`: Provides the styling for the extension's popup.

## Permissions

This extension requests the following permission:

* `activeTab`: Allows the extension to access information about the currently active tab, which is needed to save its URL.
* `storage`: Allows the extension to store and retrieve data in the browser's local storage.
