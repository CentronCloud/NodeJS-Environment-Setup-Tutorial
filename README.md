# NodeJS-Environment-Setup-Tutorial
Step-by-step guide for setting up a Node.js development environment on Windows and Mac OS X. Includes installation instructions, system configuration, and verification steps to ensure a successful setup.


Overview
This tutorial covers the following topics:

Setting up the Node.js environment on Windows
Setting up the Node.js environment on Mac OS X
Verifying the installation and configuring system variables
Running Node.js from the command line
By following this tutorial, you'll have a fully functional Node.js development environment ready to start building your applications.

Node.js Base Environment Setup on Windows

Steps to Install Node.js on Windows:
Access the Node.js official website: Node.js
Download the latest stable version or choose a version based on your hardware and software requirements.
Double-click the downloaded .msi file to begin the installation.

Follow the installation wizard:
Click "Next" and accept the License Agreement.
Choose your installation location.
Click "Install" to begin the installation process.

Verify installation:
Open the Node.js installation directory (NODEJS_HOME).
Check for node.exe, npm.cmd, and the node_modules folder.

Additional Configuration (if needed):
If the installer does not automatically configure your system environment variables, you may need to manually add the following to your SYSTEM properties:
mathematica, (get code on tutorial website https://www.centron.de/en/tutorial/node-js-environment-setup-tutorial/)


Verify Installation:
Open Command Prompt and navigate to NODEJS_HOME.
Run node.exe and ensure the > prompt appears, indicating a successful setup.
Check Node.js version with node -v.
Exit Node.js CLI using process.exit(), Ctrl + D, or Ctrl + C twice.
Node.js Base Environment Setup on Mac OS X

Steps to Install Node.js on Mac OS X:
Download the .pkg installer from the Node.js official website.
Run the installer and follow the on-screen instructions.
Ensure /usr/local/bin is included in your PATH variable.
This can typically be checked and configured in your terminal settings.

Full Tutorial
For a detailed, step-by-step guide to setting up the Node.js environment on both Windows and Mac OS X, please visit the full tutorial on Centron's website. https://www.centron.de/en/tutorial/

Contributing
We welcome contributions to improve this tutorial or the associated code. Feel free to open an issue or submit a pull request.
