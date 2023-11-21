## Submission Rules

### Video Evidence

- Single segment video evidence is required.
- Videos should be uploaded to a permanent host site; Twitch VODs are not accepted.
  - Acceptable hosts include Youtube, Twitch Highlights and Bilibili.
  - The video must remain accessible; runs with videos removed or privated after verification may be removed from the boards.
- Video evidence must show the Title Screen either at the start of the run, or at a timestamp given in the run description.
  - The Title Screen must be clearly visible, with a legible version number.
  - IL runs may omit the timestamp, but must still show the Title Screen.
- Video evidence is expected to be of a watchable quality, without frequent or extensive frame drops.
- Game audio must be present (sound necessary, music optional) and game sounds should be audible over any background noise (voice, music etc.) at all times.
  - Runs will be rejected at the verifier's discretion if listening clearly to the game sounds requires uncomfortable levels of background noise.
- HUD elements must be clearly visible at all times. This includes the soul meter, masks, and geo and essence counts. Where required for verification, there must be at least one clear frame of the Title Screen where the patch number and modding API text would be seen ([visual guide](https://imgur.com/a/XgK6qDJ)). Runs will be rejected at the verifier's discretion if significant amounts of the active portion of the game window are covered.

### Timing

- Use of the load remover integrated into LiveSplit is required for loadless timing. LiveSplit should be clearly visible.
- If loadless time isn't used or is unverifiable, real time will be used instead.
- If a console run is submitted to a PC leaderboard then it will be manually timed to the same start/stop points as the autosplitter.
- Pausing the timer manually is not acceptable and any paused time will be added to your run as a penalty.
- Modifying the game is not allowed, this includes just having the modding API installed.
- Milliseconds are only to be included for the Time Without Loads of a run on one of two cases:

  1.  The run's Time Without Loads is under 10 minutes.
  2.  The run is a tied WR.

- Milliseconds should never be included in the Time With Loads.

## Settings Rules

### Game modifications

- Game modifications, including the Modding API, are banned, with the below exceptions:
  - [ScreenShakeModifier](https://github.com/hk-speedrunning/HK-Resources/blob/main/README.md#screenshakemodifier) for 1221 and 1432 is allowed.
  - The standalone [load normaliser](https://github.com/hk-speedrunning/HK-Resources/blob/main/README.md#loadnormaliser) used for races is allowed for No Major Glitches and 1.4.3.2+ NMG runs. It is banned for NMMS and AG runs.
  - The [load extender](https://github.com/hk-speedrunning/HK-Resources/blob/main/README.md#loadextender) is allowed for NMMS and AG runs.
  - [Minisavestates](https://github.com/hk-speedrunning/HK-Resources/blob/main/README.md#minisavestates) is allowed **_only_** in IL runs, and only if a savestate is not loaded during the run itself.

### Game Settings

- The following values in _[game location]/[hollow_knight_data]/Config.ini_ may be edited:
  - **FrameRateCap**: May be set to any value above 50.
  - **CameraShakeMultiplier**: May be set to any value.
- Using in-game Vsync to limit framerate is allowed so long as the target monitor's refresh rate remains consistent during the run.
- Using in-game Frame Rate Cap to limit framerate is allowed so long as the target framerate is 50fps or above and remains consistent during the run. If this option is used in your run then you must have a clearly visible FPS display in your recording.

### Third-party programs

- Using a third-party program to limit framerate is allowed so long as the target framerate is 50fps or above and remains consistent during the run.
- Macros and turbo functions are not allowed, with the below exceptions:
  - "SOCD cleaners", used to adjust the behaviour of overlapping left+right inputs (see [socd_cleaner.exe](https://github.com/valignatev/socd/releases/download/0.0.8/socd_cleaner.exe))
  - Macros used to map mouse inputs 1-to-1 to keyboard inputs (see [blue.exe](https://github.com/hk-speedrunning/HK-Resources/raw/main/External%20Tools/Blue/blue.exe))
  - Analog remappers used to bind keyboard keys to a virtual joystick
- Each player input can be mapped to a maximum of one game input. Multiple player inputs can all be mapped to the same game input.

## **Gameplay Rules**

- Entering menus for the sole purpose of pausing the timer is not allowed.
- Force exiting the game (Alt-F4) is only allowed when game menus are permanently inaccessible.
- Inducing lag with Print Screen, moving the game window or any other method is not allowed.
