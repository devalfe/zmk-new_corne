## Corne keymap by layer
![Diagram of config/eyelash_corne.keymap](keymap-drawer/eyelash_corne.svg "generated by @caksoylar's Keymap Drawer")

[English](README_EN.md)

# Customising Corne

## Base Layer
Customising a base layer to hadle some basic needs

### QWERTY replacement with modified COLEMAK-DH
I replaced QWERTY with a faster layout—Colemak DH—but made a slight adjustment to the placement of the ', /, ; characters. This change was to make the accent giver (;:) key more accessible for my right pinky, as almost every Greek word requires accents. This small tweak significantly improves typing efficiency in Greek.

### EN/GR language switcher
Switching between my main languages (English/Greek) is seamless. I’ve set up an on-tap behavior on the middle left thumb key that triggers Win+Space (the language switcher in Windows). This allows me to effortlessly switch languages mid-sentence without losing speed, even in complex cases like:

"Το Project Plan μας αποτελείται από 4 sprints των 3 εβδομάδων."

This setup makes multilingual typing smooth and natural.

### Shortcuts
Used to have home row mods that made initiating combos slightly slower so I moved the home row located mods to symbol and number layer left half.
Moreover, in base layer their is sk_mo (sticky key on tap and momentarily layer on hold) behaviour to help me faster input shortcuts like ctrl+t,w,s,c,v etc. 
Ctrl sticky lives on inner right thumb key cluster.
Shift sticky lives on outer right thumb key cluster
Win mod is over pinky ;: key to help in combos like win+e,i,l,t win shift s etc.
On left half there is dedicated keys for ctrl in alt to have access to ribbon menu with keyboard instead of mouse.

Most common keyboard shortcuts used
* win+arrow (from the joystick) to move app windows around
* win+number to activate the equivalent pinned item of windows taskbar
* win+shift+number to open a new session -//- 
* win+L to lock in windows
* win+r to run cmd etc
* win+i to access windows settings and connect to my wireless headset if not immediately connected (i find it faster than win+k that is searching devices)
* win+e to open file explorer
* win+shift+tilde(`) to access the windows power toys app zones editor
* win+shift+S to take a screenshot (might add a conditional layer on this to activate nav layer so that I can cut the part of the screen I want to capture directly after the trigger)
* win+alt+k as a combo stored in rotary encoder click to easy toggle mic mute accross system (yes overrides teams mute also) super handy
* ctr+t new tab in browsers, file explorer, format as table in excel
* ctr+n new window, new folder
* ctr+shift+r to hard refresh tab
* ctr+1 to open options in excel
* ctr+w to quit
* ctr+f to find
* ctr+L to access the address bar (combo this with win+number makes me super fast in opening new tabs or copying url to provide to another app)
* ctr+backspace to delete word by word (backspace is combo of n,e)
* ctr+tilde to reveal formulas in excel
* alt+arrow to navigate in file explorer 

_Why is there a dedicated Alt button when I already have Alt in my home row mods?_

The reason is that home row mods require holding down a key, which takes a bit of time. This can be inconvenient, especially in Excel, where pressing and releasing the Alt key gives you quick access to the ribbon, allowing you to navigate and select items by typing a series of keys.

While I can trigger these actions in Excel using the / key, in Windows, pressing Alt along with the underlined key in a menu provides keyboard access to any item in the context menu.

_Sticky shift, Caps, dtap/tap, combos_

Having a sticky Shift or a Caps dual-tap/tap mod on the right-hand thumb cluster is incredibly useful for capitalizing the first letter of each word with a single tap. This setup not only reduces the strain of holding down the Shift key but also improves typing speed, especially when punctuation is involved, as it seamlessly integrates into the typing flow.

Caps Lock is accessible through a two-key combo (C+D). Additionally, there's a Caps Word behavior mapped to the S+T combo, which is handy for typing in all caps briefly.

Initially, I was concerned about accidentally triggering Ctrl+Shift, but I was relieved to find that this issue didn’t occur.

I used to have Backspace and Delete on my thumb cluster, but now I’ve moved them to two-key combos on the home row: N+E for Backspace and E+I for Delete. N+E+I is ctrl. This setup is extremely convenient and makes deleting word by word with Ctrl+N+E very fast.

On the right thumb cluster, I’ve added Smart Num functionality. It provides num_word (numbers on tap) and mo (access to the num layer) on hold.

_Sticky Layer / Momentary Layer custom behavior_

I also introduced a custom behavior called sl_mo, which offers a sticky layer on tap and a momentary layer (mo) on hold. I used this on the right-hand cluster to type a single symbol with a tap or access a full symbol layer when held. I removed it and replaced it with a sk_mo on two of the right thumb cluster.

I’m considering designing a Smart Sym logic similar to Smart Num, but for now, I don’t encounter frequent cases of typing a series of symbols, except for double brackets or Markdown headers with hashtags.

## Number Layer

Revised version of number layer

_Left-Hand Side_

On the left hand side we have the numerical keypad equivalents. In some usecases they are the only keys that return the number inputs in some software instead of the 1-0 digits above a classic querty that double as symbols.
These keys surround the home row mods and a calculator app trigger. Thumb cluster reuses space by transition and adds dot and equal for the combo alt+= in excel that auto sums the above consequent cells.

_Right-Hand Side_

Includes numeric keys 1-9 in a classic 3 by 3 numpad setup, 0 on the side and % directly below and arithmetic operators (KP PLUS, KP MINUS, KP MULTIPLY, KP DIVIDE) in positions optimized for quick access.
A navigation cluster with arrow keys on joystick (↑, ↓, ←, →) is integrated, enhancing usability for editing spreadsheets or navigating code.
Modifier combinations such as Alt+= (for auto sum feature in excel) are mapped for additional functionality.

## Symbol Layer

_Left-Hand Side_

Contains frequently used symbols in a 1-5 logic on the bottom row.
Home mod rows for this side. * asterisk on the g location to easily created bulleted lists.
A toggle key labeled "COLEMAK" allows switching back to the primary layer.

_Right-Hand Side_

Features pairs of brackets ((, ), [, ]), as well as other common symbols like \, placed for convenient access.
Navigation arrows (↑, ↓, ←, →) are present for editing and navigation purposes.
Keys for special symbols and operations, such as the pipe | and backslash \, are also included.

## Navigation Layer

_Key Functions_

F1 - F5: General function keys for help, editing/renaming,  freezing named ranges, refreshing pages.
F11 - F12: for power query / vba (with alt) and browser quick actions.
Move Up/Down/Left/Right: Cursor movement commands for more efficient navigation surrounded by most used function keys.
Clipboard (Ctrl + C, X, V, Z, Y): Quick access to clipboard functions like copy, cut, paste, undo, and redo around the reversed T arrows navigation. Copy, paste being near the upwards arrow.
Media Controls: Includes scroll left, scroll up, scroll down, and scroll right for navigation within documents or web pages.
Mouse Functions: Includes mouse button 4 (MB4), left-click (LCLK), right-click (RCLK), middle-click (MCLK), mute (C_MUTE), and other mouse-related functionalities.

_Navigation Shortcuts_

Home/End/Page Up/Page Down/Insert/Pause/Break: Manage text navigation and system commands.
Context Menu: Activate the system context menu with K_CONTEXT_MENU. Maybe one of my most used flow if not the shift+F10 equivalent.
Win+shift+D mapped to the right index finger secondary position allows for the quick use of mouse jump feature of power toys. This creates a mini map of all the screens available at the current position of your cursor. This allows to utilize the mouse emulator even more accross screens without delays on cursor movement.

_System and Clipboard Keycodes_

Includes functions like INSERT, HOME, PAGE_UP, PAGE_DOWN, END.

## Bluetooth & RGB Layer

_Bluetooth Functions_

BT_CLR: Clears the current Bluetooth connection. I have assigned this action on right/uppermost part of the keyboard to avoid accidental trigger.
BT_SEL 0 to BT_SEL 4: Selects 5 different Bluetooth devices.

_RGB Controls_

RGB_HUI: Increases RGB brightness.
RGB_HUD: Decreases RGB brightness.

RGB_BRI: Adjusts overall RGB brightness.
RGB_BRD: Adjusts the RGB brightness mode or settings.

RGB_OFF: Turns off RGB lighting.
RGB_ON: Turns on RGB lighting.

RGB_SPI: Changes the RGB effects or pattern speed.
RGB_SPD: Adjusts RGB speed or other related settings.

RGB_EFR: Toggles RGB effects for more dynamic lighting.
RGB_EFF: Activates or changes RGB effects.

_Sensor Bindings_
The layer binds an RGB encoder (&rgb_encoder), allowing for additional dynamic control or configuration via an encoder (likely a hardware interface).

## Function & Multimedia Layer

_Function Keys_

F1 to F12: General function keys for various tasks. The assignment is similar to the num layer numbering with F11, F12 being on the lower movement of the index right finger to avoid any extened pinky actions.

_Media Controls_

C_STOP: Stop media playback.
C_PREVIOUS: Skip to the previous track.
C_NEXT: Skip to the next track.
C_PLAY_PAUSE: Toggle play/pause media playback.
Cursor and Mouse Functions:

_System Keys_

PRINTSCREEN: Take a screenshot. I usually prest win+shift+S for screenshot but i wanted to have at least one assignment of each key of a full keyboard in some layer.
SCROLLLOCK: Toggle the scroll lock feature.
PAUSE_BREAK: Pause or break functionality.

_Sensor Bindings_

The layer was configured with a scroll_encoder sensor binding, haven't managed to make it work for scrolling yet. Returned to volume rocker for the encoder.

## Minecraft & Numpad Layer

Tailored for a game-like layout (wasd), offering both letter-based navigation and number pad-like functionality, along with mouse and system controls.

_Key Functions_
The layer combines alphabetic keys, numeric keypad control, mouse navigation, and additional system functions:

_Alphabetic Keys_

E, W, F, L, A, S, D: Mapped for quick action commands, resembling gaming in a Minecraft environment.

_Numeric Keypad_

KP_NUMLOCK: Toggles the numeric keypad. This provides pg up, pg down, home, end and arrows functionality if toggled.

KP_NUMBER_7, KP_N8, KP_N9, 

KP_N4, KP_N5, KP_N6, 

KP_N1, KP_N2, KP_N3, 

KP_N0, KP_DOT, KP_ENTER 

Provides number-based input options, for calculation, navigation, or gaming purposes.

_Movement and Mouse Functions_

MOVE_UP, MOVE_LEFT, MOVE_RIGHT, MOVE_DOWN: Controls for cursor or player movement on joystick.
LCLK: Left-click mouse action.
RCLK: Right-click mouse action.

_System and Special Keys_

C_AL_CALCULATOR: Opens the calculator application and allows for a numpad experience.
There are combos for +, -, *, / on the top and bottom rows of the numpad.
LCTRL: Left control key, useful for various system shortcuts.
F1 to F4: General function keys for system tasks.
LSHFT: Left shift for modifier functions.
SPACE: Spacebar for general input.

Various combos available with f+u switching to base from any layer if lost.
