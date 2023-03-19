---
layout: post
title: Installation tutorial
date: 2021-01-14
categories: workshop
author: Iván Huelves Illas
---
The following apps are needed to create an interactive prototype that relates variable fonts to Arduino sensors in a web environment.

**For Mac and Windows users:**
- Visit [https://code.visualstudio.com/download](https://code.visualstudio.com/download) download and install your Os version.
- Visit [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software) download and install your Os version.
- Visit [https://nodejs.org/es/download/](https://nodejs.org/es/download/) download and install your Os version. During Windows installation the app will ask to “Automatically install the necessary tools…” Check that option.

**Now only for Window users:**
- Visit [https://git-scm.com/download/win](https://git-scm.com/download/win) and install your Os version.
- Visit [https://classic.yarnpkg.com/en/docs/install#windows-stable](https://classic.yarnpkg.com/en/docs/install#windows-stable) your Os version
- Run PowerShell as administrator (right-click) and write:
`yarn global add windows-build-tools`

**Now only for Mac users:**
Open the terminal (Open Launchpad and look for Terminal) write and press intro after:
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Now write and press into after:
`brew install git`

Now write and press into after:
`brew install yarn`

*If during the installation on the Terminal you are asked for administrator permissions, write “sudo” in front of the above codes.

Well done!!! Now you are ready to start the workshop
