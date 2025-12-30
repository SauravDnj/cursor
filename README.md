# cursor

Windows cursor pack with multiple animated and static cursor types.

This repository contains a collection of custom mouse cursors for Windows (.ani and .cur) and a few animated styles so you can change and preview different cursor animations.

Contents
- /cursors: cursor files (.ani, .cur) and any supporting files
- README.md: this file with installation and usage instructions

Features
- Multiple animated cursor styles (.ani)
- Static cursor variants (.cur)
- Ready-to-install cursor files and example pointer schemes

Supported formats
- .cur — static cursor file (single image + hotspot)
- .ani — animated cursor file (sequence of frames with timing)

Important: Windows Version
These instructions apply to Windows 10 and Windows 11. The exact Settings UI may vary slightly between Windows releases, but the Mouse Properties (Control Panel) dialog and the Pointers tab are available on all modern Windows versions.

How to install and set cursors in Windows (detailed)

1) Prepare the cursor files
- Option A (recommended, requires admin rights): copy the cursor files into the system cursors folder so they are available to all users:
  - Open File Explorer and navigate to the folder that contains the downloaded cursor files from this repo.
  - Select the .ani and .cur files you want to install, right-click and choose Copy.
  - Navigate to C:\Windows\Cursors. If prompted, approve the Administrator permission to paste files.
  - Right-click into the folder and Paste. You might be asked to confirm; this requires admin privileges.

- Option B (no admin rights required): keep the cursor files in a folder inside your user profile (for example, Documents\My Cursors). Note: some system dialogs behave better when files are in C:\Windows\Cursors, so copying there is preferred.

2) Open Mouse Properties (Pointers tab)
- Method A (Settings -> Additional mouse options):
  - Open Settings (Win + I) -> Personalization -> Themes.
  - Scroll down and click "Mouse cursor" (or "Additional mouse settings" / "Mouse settings"). This opens the Mouse Properties dialog.

- Method B (Control Panel):
  - Open Control Panel -> Hardware and Sound -> Mouse.
  - In the Mouse Properties dialog, switch to the "Pointers" tab.

3) Apply a custom cursor to a pointer role
- In the "Scheme" / "Customize" area you will see pointer roles such as "Normal Select", "Help Select", "Working In Background", etc.
- Click the pointer role you want to change (for example, "Normal Select").
- Click Browse.
- Navigate to C:\Windows\Cursors (or the folder where you saved the files), select the desired .cur or .ani file, and click Open.
- The preview pane will show the cursor. For animated .ani files you should see the animation in the preview.
- Click Apply to use the cursor immediately. Click OK to close the dialog.

4) Save a pointer scheme (optional)
- In the Mouse Properties dialog, after assigning multiple custom cursors to roles, click "Save As..." and give the scheme a name (for example, "My Animated Pack").
- This makes it easy to re-apply the same set of cursors later.

5) Revert to defaults or change schemes
- To revert to the default Windows cursors, choose the "Windows Default (system scheme)" from the Scheme dropdown and click Apply.
- To remove a custom cursor from one role, select the role and click Browse -> choose the appropriate default file or select "Use Default" if available.

Alternative quick install (right-click install)
- Some .cur and .ani files allow a quick install: right-click the file and if you see an "Install" option, clicking it will register the cursor with Windows and make it selectable in the Mouse Properties dialog. This behavior depends on file associations and Windows version.

Permissions and common issues
- Permission denied when copying to C:\Windows\Cursors: you must use an Administrator account or approve the UAC prompt.
- Animations not playing: make sure the file is a valid .ani; test in the Mouse Properties preview. If it still does not animate, try copying to C:\Windows\Cursors and reselecting the file.
- Cursor looks offset or has the wrong hotspot: cursor hotspot controls the active pixel. If the pointer click position is wrong, the cursor file's hotspot may be set incorrectly — edit or re-export the cursor with the correct hotspot using a cursor editor.

Tools to create or edit cursors
- RealWorld Cursor Editor (free) — create and edit .cur and .ani files, set hotspots, export animated cursors.
- IcoFX, Axialis CursorWorkshop — other popular tools for designing cursors.
- Online converters and image editors can help convert GIFs to .ani, but a dedicated cursor editor gives more control over frame timing and hotspots.

Tips and best practices
- Back up the original pointer scheme: before making many changes, note the current scheme name or save it with "Save As...".
- Test one role at a time to ensure animation and hotspot behave as expected.
- Keep your custom cursor files in a permanent folder or in C:\Windows\Cursors so they are not accidentally removed.
- Use reasonable frame sizes and frame rates for .ani files — very large frames or many frames can hurt performance.

Contributing
- Contributions are welcome. If you add new cursor designs, please include:
  - The cursor files (.ani/.cur)
  - A short description and author credit
  - Any source artwork or frames if licensing allows
- Open a GitHub issue or create a pull request with your additions.

License
- Include a license file in this repo (for example, MIT or CC0) and indicate the license for each cursor asset if it differs from the repository default.

Support and feedback
- If something doesn't work, open an issue describing:
  - Windows version (Windows 10 / 11 and build if known)
  - The cursor file name you tried to install
  - A short description of the problem and steps to reproduce

Enjoy your new cursors!

— cursor pack by the repository owner
