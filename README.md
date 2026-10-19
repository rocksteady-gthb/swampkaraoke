# VRChat World Assets: Karaoke & Drinking Game Lists

This repository contains the text files used to power the interactive elements in my VRChat world, specifically the karaoke setup and the drinking game wheel.

## 📂 Repository Contents

*   `karaoke_songs.txt` – A curated list of track titles, artists, and search keywords for visitors to sing.
*   `drinking_wheel.txt` – A list of custom rules, prompts, and dares for the spin-the-wheel drinking game.
*   `supporters.txt` – A list of supporters who have contributed to the World through Patreon or other means.

## 🛠️ How to Use in Unity / VRChat

If you are using a VRChat world prefab (like a custom text parser, Udon, or a web-string loader):

1. Click on the text file inside this GitHub repository (e.g., `karaoke_songs.txt`).
2. Click the **Raw** button in the top right corner of the file view.
3. Copy the URL from your browser's address bar. 
4. Paste this URL into your VRChat world's URL loader component to dynamically stream the list in-game without having to re-upload the entire world when you add new songs!

## 📝 Editing the Lists

When updating the text files, ensure you keep the formatting strict:
*   **For Karaoke:** One song per line (`### | YouTube link | Artist - Song Title`).
*   **For the Wheel:** One prompt per line.
