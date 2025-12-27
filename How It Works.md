## How It Works

This project combines input automation and computer vision to simulate consistent, repeatable player behavior within the game.

I used Python libraries such as `pyautogui` and `keyboard` to programmatically control movement and actions. To ensure reliable automation, I remapped the in-game block-breaking action to a keyboard key, allowing the bot to hold the action continuously without relying on mouse input.

To make the bot spatially aware, I integrated OpenCV to read the on-screen coordinates of my character, which are displayed in the top-left corner of the screen using Lunar Client. By processing this visual information, the program can detect when the character reaches specific coordinates and respond accordingly.

When a predefined coordinate threshold is reached, the bot automatically changes layers within the farm, allowing it to navigate the structure efficiently and continue farming without manual intervention.

A demonstration video of the bot operating in real time is available on my YouTube channel.
