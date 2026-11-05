# VEXORMU PC

[Download the PC installer](https://github.com/crypto-20/vexormu-updater/releases/download/pc-v1.0.1-20261104/VEXORMU-Installer.exe).

Download **VEXORMU-Installer.exe** only. Choose an install folder and click **Install**. The installer downloads and verifies the complete PC client from GitHub Releases. Interrupted downloads resume when you retry.

After installation, click **Open launcher**. The launcher checks for PC updates before Play. Use **Verify files** for a complete file scan and repair. An OpenGL fallback is included for computers without Vulkan support.

Full installations use ZIP packages. With a newly prepared release, the launcher downloads only missing or changed files from an existing client. It requests each file's compressed bytes from the ZIP, verifies the decoded file with SHA-256, then installs it. Interrupted file downloads resume on retry. Existing graphics and audio preferences are preserved.

Older release manifests remain compatible and use ZIP downloads until a release with the file download index is activated. Older launchers can install the new launcher through the existing ZIP update process. File updates require HTTP byte-range support; the launcher reports an error if the server ignores a range instead of silently downloading a whole ZIP.

Requires Windows with .NET Framework 4.5 or newer. Close the game before an update.
