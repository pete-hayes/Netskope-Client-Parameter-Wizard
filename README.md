# Netskope Client MSI Wizard
This interactive HTML/JavaScript wizard simplifies Windows Netskope Client deployments for IT administrators. Instead of manually piecing together multiple MSI parameters, users can toggle options in a clean UI to instantly generate accurate, production-ready installation commands.

## Features
- Guided form for entering MSI parameter values
- Auto-generated `msiexec` command output
- Copy-to-clipboard functionality
- Download button for the Netskope Client (Windows) 

## Video
<img src="./Netskope_Client_MSI_Wizard.gif" width="500">

## Usage
1. Clone or download this repository.
2. Open `ns_client_msi_wizard.html` in your browser.
3. Enter your Netskope parameters as required.
4. Copy the generated command and use it in your deployment script or from the command line.

## Security
**This script is intended for local use only and should not be published or exposed on the public Internet.**

- The page makes a single external HTTPS request to load the Bootstrap CSS library, protected with Subresource Integrity (SRI).
- No Netskope tokens or other sensitive information is transmitted externally. The Netskope token information is critical security data and must remain private at all times.

## License
Licensed under MIT — free to use, modify, and share, with no warranty.

## Disclaimer
This project is **not affiliated with or supported by Netskope**. It may be incomplete, outdated, or inaccurate. Use at your own risk.
