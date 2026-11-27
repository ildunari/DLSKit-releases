# DLSKit

DLSKit views and analyzes Malvern Zetasizer dynamic light scattering data on the Mac, iPad and iPhone. It reads `.dts` measurement files, ZS XPLORER `.zmes` files and Malvern text exports. It is a viewer: it never connects to or controls the instrument. DLSKit is not affiliated with Malvern Panalytical.

This repository hosts the Mac downloads, the Mac update feed, and the app's help, support and privacy pages. The app's source code is kept elsewhere.

## Getting started

1. Open a measurement: drop `.dts`, `.zmes` or text export files on the window, or use Import. On iPhone and iPad, choose Import or open a file from the Files app with "Open in DLSKit".
2. Pick a record in the list to see its correlogram and size distribution, the cumulants result (Z-average, PdI, intercept) and its quality checks.
3. Re-analyze, compare and export from the toolbar. Re-analysis adds a new record and never changes the original.
4. Save your work as a `.dlskit` project.

To try DLSKit without your own data, choose **Open Sample Data** on the welcome screen (on the Mac, it is also in the Help menu). The sample is a published Zetasizer Nano file of water (Zenodo 13860620, CC BY 4.0). Expect some of its records to be flagged by the quality checks: water alone scatters very little light.

## Download for the Mac

The latest signed and notarized disk image is on the [Releases](https://github.com/ildunari/DLSKit-releases/releases/latest) page. The Mac app needs macOS 15 or later and updates itself.

## Support

Report a problem or ask a question in [Issues](https://github.com/ildunari/DLSKit-releases/issues). Include the DLSKit version (shown in Settings > About or in the About window) and, if you can share it, the file that shows the problem.

## Privacy

DLSKit collects no data. See the [privacy policy](PRIVACY.md).
