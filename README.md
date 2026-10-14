# Netskope Client Parameter Wizard
This interactive HTML/JavaScript wizard simplifies Netskope Client deployments for IT administrators. Instead of manually piecing together multiple parameters, users can select and configure options in a clean UI to instantly generate accurate, production-ready installation parameters.

## Features
- Auto-generated parameter output for Netskope Client installations
- Easy copy-to-clipboard button for generated parameter output
- Download buttons for the Netskope Client (Windows and macOS) 

<img width="800" height="1200" alt="Screenshot" src="https://github.com/user-attachments/assets/c5b924f7-d4cc-4453-a60e-cf5e1e626cd8" />

## Usage
1. Clone or download this repository.
2. Open `Netskope Client Parameter Wizard.html` in your browser.
3. Enter your Netskope parameters as required.
4. Copy the generated command or parameters and use either in your software deployment solution or from the command line.

## Change Log
### Version: 1.52 - Oct 14 2026
- Added tooltips for fields that may require more attention or clarification
- Updated to use the latest Bootstrap and Font Awesome libraries

### Version: 1.51 - Oct 13 2026
- Implemented cleaner responsive design
- Moved output to be to the right of the form, unless the page width is too narrow, in which case it moves to the original bottom position
- Cursor is now in the tenant field on page load
- Clarified Fail Close and Automatic Update field behaviors (they're overrides)
- Added Enforce Enrollment support (applicable to IdP enrollment mode)
- Added Device Tags support
- Netskope Client documentation link now opens in new tab/window, avoiding accidentally navigating away from form
- Download links for Netskope Client no longer unnecessarily open new tab/window

## Security
**This script is intended for local use only and should not be published or exposed on the public Internet.**

- The page makes a single external HTTPS request to load the Bootstrap CSS library, protected with Subresource Integrity (SRI).
- No Netskope tokens or other sensitive information is transmitted externally. The Netskope token information is critical security data and must remain private at all times.

## License
Licensed under MIT — free to use, modify, and share, with no warranty.

## Disclaimer
This project is **not affiliated with or supported by Netskope**. It may be incomplete, outdated, or inaccurate. Use at your own risk.
