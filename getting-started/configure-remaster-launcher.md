---
description: This tutorial will guide you through the steps to configure the launcher.
---

# ⑥ Configure Remaster Launcher

## Procedures

1. Right-click the <mark style="color:blue;">Remaster Launcher</mark> shortcut on your desktop. \
   Click <mark style="color:blue;">Properties</mark>. In the <mark style="color:blue;">Compatibility</mark> tab, enable <mark style="color:blue;">Run this program as an administrator</mark>. Click <mark style="color:blue;">Apply</mark> and then click <mark style="color:blue;">OK</mark>.
2. Double-click the <mark style="color:blue;">Remaster Launcher</mark> shortcut on your desktop to start the launcher.
3. Click <mark style="color:blue;">Yes</mark> when the dialogue <mark style="color:blue;">Do you want to allow this app from an unknown publisher to make changes to your device?</mark> pops up.
4. Navigate to the <mark style="color:blue;">Play</mark> page.
5. Disable the [<mark style="color:blue;">4GB Ram Patch</mark>](#user-content-fn-1)[^1] option under the <mark style="color:blue;">Launch-Settings</mark> section. \[Why?[^2]]
6. Navigate to the <mark style="color:blue;">Settings</mark> page.
7. Enable[^3] options like <mark style="color:blue;">Unlock FPS (120HZ)</mark>, <mark style="color:blue;">Widescreen Fix</mark>, [<mark style="color:blue;">HUD-Fix</mark>](#user-content-fn-4)[^4], <mark style="color:blue;">Blood Patch</mark> and <mark style="color:blue;">Reshade</mark> under the <mark style="color:blue;">General</mark> section. **DO NOT** touch the resolution settings yet! \[Why?[^5]]
8. Navigate to the <mark style="color:blue;">Help</mark> page.
9. Check whether the debug message contains the following lines:\
   <mark style="color:green;">Game version: v1.51 OK!</mark>\
   <mark style="color:red;">bf2142.exe: Not v1.51 or cracked.</mark>\ <mark style="color:red;">bf2142\_4gb.exe: Missing! Patch first.</mark>\
   <mark style="color:red;">RendDX9.dll: Wrong file version!</mark>\
   <mark style="color:green;">RendDX9\_ori.dll: OK!</mark>
10. Navigate to the <mark style="color:blue;">Play</mark> page.&#x20;
11. Click the button <mark style="color:blue;">Start Game!</mark> to start the game.
12. It may take a while for the game to start so you should expect a few seconds of [black screen](#user-content-fn-6)[^6] before the intro comes up.&#x20;
13. Once the login screen appears, click the <mark style="color:blue;">x</mark> button in the upper right-hand corner to close the game. \[Why?[^7]]
14. Repeat Step 2 - 3.
15. Navigate to the <mark style="color:blue;">Help</mark> page.
16. Check whether the debug message contains the following line:\
    <mark style="color:yellow;">Profile: Found, delete if stuck with a black screen.</mark>
17. Navigate to the <mark style="color:blue;">Settings</mark> page.
18. Configure the <mark style="color:blue;">Resolution</mark> from the drop-down menu under the <mark style="color:blue;">General</mark> section.
19. Close the launcher.
20. Read all the [remarks](configure-remaster-launcher.md#remarks) as they are important.

## Remarks

1. If you want to play an unmodded game or join an [unmodded server](#user-content-fn-8)[^8], simply **uncheck** everything under <mark style="color:blue;">Play</mark> -> <mark style="color:blue;">Launch-Settings</mark> and <mark style="color:blue;">Settings</mark> -> <mark style="color:blue;">General</mark> before launching the game. \[Why?[^9]]
2. [<mark style="color:blue;">Vanilla weapons</mark>](#user-content-fn-10)[^10] is a mini-mod of Project Remaster. You may enable this option if you want to play a Project Remaster game with weapons or gadgets having their vanilla stats[^11].
3. The <mark style="color:blue;">Play Offline</mark> page is a portal to launch the [<mark style="color:blue;">Offline Singleplayer</mark>](#user-content-fn-12)[^12] mini-mod. It is a derivative of the main mod that bypasses[^13] the master server while having the customisation feature disabled.
4. You can configure the Reshade overlay in-game using the shortcut <mark style="color:blue;">Shift+F2</mark>. You may need to turn off the LUT in [some of the maps](#user-content-fn-14)[^14] if the overlay is glitching the graphics.
5. **Whenever you run into a game issue, such as a game crash, game does not start or a graphics glitch, the troubleshooting and diagnosis tools provided in the **<mark style="color:blue;">**Help**</mark>** page becomes very helpful. The offline** [**manual**](further-readings.md) **that comes with the launcher may also give you some** [**insights**](#user-content-fn-15)[^15] **on how to get things fixed.**

[^1]: Battlefield 2142 is a 32-bit game so it can at most utilise 4GB of RAM. But better than not, the 4GB RAM Patch avoids the game from crashing from time to time due to memory overthrow.

[^2]: We have to disable this option because the OpenSpy patch from BF2142 Hub already integrates that fix by default.

[^3]: These options are optional, but you are encouraged to enable them.

[^4]: You must clear your shader-cache when enabling / disabling this setting, else the game will crash.



    To clear the shader cache:

    * Go to the <mark style="color:blue;">Settings</mark> page.
    * Click the <mark style="color:blue;">Clear Chache</mark> button.

[^5]: You still haven't launched the game for once, so there is no profile for the game to store your resolution settings.

[^6]: If you are using the full-screen mode, you may see the game blinking or resizing for a few times.

[^7]: We take this enter-and-exit step to force the game to create a default profile in your Documents folder at <mark style="color:blue;">C:\Users\xxxx\Documents\Battlefield 2142\\</mark>.

[^8]: e.g., Reclamation servers

[^9]: If you do not uncheck these options, your game is considered modded. You may not be able to join the server, or you may get kicked for modified content.

[^10]: [Project\_Remaster\_v14\_vanilla\_weapons](download-and-install-remaster-mod.md#more-about-mods)

[^11]: e.g., damage, recoil, rate of fire, amount of ammo, etc.

[^12]: [Project\_Remaster\_v14\_offline](download-and-install-remaster-mod.md#more-about-mods)

[^13]: The mod emulates the scenario when your computer loses connection to the internet. It makes use of an offline profile to pass through the login screen.

[^14]: The reshade overlay has an known graphics glitch issue on Suez Canal.

[^15]: The manual includes a very comprehensve FAQ section that teaches you how to fix a lot of known issues. For most of time, your issue can be fixed by following the instructions on the manual.
