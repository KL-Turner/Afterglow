# Afterglow

*Fluorescence-lifetime voltage imaging -- the time of your life.*

Afterglow is the Moore lab's viewer for fluorescence-lifetime (FLIM) voltage imaging recorded on a
Leica STELLARIS FALCON and exported from LAS X: lifetime and intensity images, the phasor plot with
cursors, ROIs and their traces over time, projections, and motion correction.

This repository holds the **installers and release notes** only.

## Download

- **Windows:** **[Afterglow-Setup-Windows.exe](https://github.com/KL-Turner/Afterglow/releases/latest/download/Afterglow-Setup-Windows.exe)**
  (always the newest version)
- **Mac (Apple silicon):** coming soon

These links are all you need. The other files on the releases page are for Afterglow's automatic
updates.

## Install on Windows

You need Windows 10 or 11 (64-bit), an internet connection for the first install, and about 6 GB of
free disk space for it (the MATLAB Runtime; the Setup checks). No MATLAB licence is needed.

1. Download **[Afterglow-Setup-Windows.exe](https://github.com/KL-Turner/Afterglow/releases/latest/download/Afterglow-Setup-Windows.exe)**
   (the link above). The program is not signed, so the browser may hold the download:
   - Edge: *"... isn't commonly downloaded"* -- point at the download, choose **...** > **Keep**, then
     **Show more** > **Keep anyway**.
   - Chrome: *"... may be dangerous"* or *"... is not commonly downloaded"* -- choose **Keep**.
2. Run it. Windows may say *"Windows protected your PC"*: choose **More info**, then **Run anyway**.
   You see this once per download.
3. One screen: press **Install**. Tick *Add a desktop shortcut* first if you want one.
   - The first time, it also installs the free **MATLAB Runtime R2025b** from MathWorks, under
     MathWorks' MATLAB Runtime License (the screen's *licence* link says more; MathWorks installs the
     licence's text with the Runtime). Windows asks *"Do you want to allow this app from an unknown
     publisher to make changes to your device?"*, naming the program `AfterglowRuntime-R2025b-web.exe`
     (MathWorks' Runtime installer, made for Afterglow; it is not signed) -- press **Yes** (once). The
     download takes a while. A PC that already has MATLAB R2025b with the Image Processing Toolbox
     needs no Runtime.
   - Afterglow itself installs for your Windows account only (no administrator rights needed for it).
4. When it is done, Afterglow starts. Afterwards, start it from the **Start menu** (type
   *Afterglow*). To pin it, right-click it in the Start menu (or its button on the taskbar while it
   runs) and choose **Pin to taskbar**.

## Install on a Mac (Apple silicon)

When a release lists **`Afterglow-vNN.NN-maca64.dmg`** under *Assets*: download it, open it, and
follow *Install Afterglow.txt* inside (macOS asks once to allow the installer: System Settings >
Privacy & Security > **Open Anyway**; the installer also installs the free MATLAB Runtime R2025b and
asks for your Mac's password once). Intel Macs are not supported.

## Updates

Afterglow looks for a newer version each time it starts (and on **Help > Check for Updates...**). When
there is one, a small notice says what is new and offers **Update & Restart**: Afterglow closes, updates
itself and opens again with your series. Your recent series and folders are kept. (On a Mac the notice
offers **Download Installer**: run the new installer the same way.)

Running the newest Setup again also updates Afterglow in place.

If Afterglow says it needs the MATLAB Runtime (for example after MATLAB R2025b was removed from the PC,
or the Runtime was uninstalled), press **Yes**: it installs the Runtime and starts again. Without its
Setup at hand, running the latest Setup does the same.

## Uninstall

Windows: **Settings > Apps > Installed apps > Afterglow > Uninstall** (or run the Setup's uninstaller
from the same place). Your settings are kept unless you tick the box to delete them. The MATLAB Runtime
stays installed (other programs may use it); remove it separately from Settings > Apps if you want.

Mac: drag `/Applications/Afterglow` to the Bin.

## Privacy

The update check asks GitHub, anonymously, for the latest release of this repository; nothing about
you or your data is sent. Your data never leaves your computer.

---

Moore lab, Brown University (Kevin L. Turner, Eric Salter). Not affiliated with or endorsed by Leica
Microsystems; "LAS X" and "STELLARIS" are Leica's names for their software and microscopes. The MATLAB
Runtime is MathWorks' and is installed under MathWorks' licence.
