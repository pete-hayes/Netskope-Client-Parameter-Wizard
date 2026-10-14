# Netskope Client Parameter Wizard
Streamline your Netskope Client deployments. This interactive tool replaces error-prone manual configuration with a clean UI, letting IT admins select parameters and instantly generate production-ready installation commands for Windows and macOS.

## Features
- **Broad Parameter Support:** Supports all major and ~90% of available Netskope Client installation parameters.
- **Key Feature Compatibility:** Includes full support for Enrollment Mode, Secure Enrollment, Enforce Enrollment, and Private Access (NPA) Prelogon.
- **Automated Output:** Automatically generates parameter strings and includes ready-to-use Windows installation command examples.
- **One-Click Actions:** Features a one-click copy-to-clipboard button for generated parameters and direct download buttons for Netskope Client (Windows and macOS).

<img width="800" src="https://github.com/user-attachments/assets/d1585808-0daa-4e42-a57f-6691fe81710f" />

## Usage
1. [Download](https://github.com/pete-hayes/Netskope-Client-Parameter-Wizard/archive/refs/heads/main.zip) the Netskope Client Parameter Wizard.
2. Open `Netskope Client Parameter Wizard.html` in your browser.
3. Enter your Netskope parameters as required.
4. Copy the generated command or parameters and use either in your software deployment solution or from the command line.

## Change Log
### Version: 1.53 - Oct 14 2026
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
