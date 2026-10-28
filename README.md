# Netskope Client Parameter Wizard
Streamline your Netskope Client deployments with this interactive tool, replacing error-prone manual parameter building with a clean interface, letting IT admins enter parameter values and instantly generate production-ready installation parameters for Windows and macOS.

## Features
- **Broad Parameter Support:** Supports all major and ~90% of available Netskope Client installation parameters.
- **Key Feature Compatibility:** Includes full support for Enrollment Mode, Secure Enrollment, Enforce Enrollment, and Private Access (NPA) Prelogon.
- **Automated Output:** Automatically generates valid parameters and values and includes ready-to-use Windows installation command examples.
- **One-Click Actions:** Features a one-click copy-to-clipboard button for generated parameters and direct download buttons for Netskope Client (Windows and macOS).

<img width="800" src="https://github.com/user-attachments/assets/4ce4b18f-eca5-4183-93c3-5d0d25975f4a" />


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

- No Netskope tokens or other sensitive information is transmitted externally. The Netskope token information is critical security data and must remain private at all times.
- The page makes two external HTTPS requests to load the Bootstrap CSS and Font Awesome icon libraries, protected with [Subresource Integrity](https://en.wikipedia.org/wiki/Subresource_Integrity) (SRI).

## License
Licensed under MIT — free to use, modify, and share, with no warranty.

## Disclaimer
This project is **not affiliated with or supported by Netskope**. It may be incomplete, outdated, or inaccurate. Use at your own risk.
