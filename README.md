Package: XDEBUG Toolbar for Sublime Text
========================================

Copyright
---------
This file is part of XDEBUG Toolbar for Sublime Text - https://www.sublimetext.com/

Copyright © 2016 TNG Consulting Inc. - http://www.tngconsulting.ca/

XDEBUG Toolbar is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

XDEBUG Toolbar is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with XDEBUG Toolbar.  If not, see <http://www.gnu.org/licenses/>.

Authors
-------
Michael Milette - Lead Developer

Description
-----------
XDEBUG Toolbar adds a useful icons in Sublime Text's main menu to make it easier to use XDEBUG for PHP.

Requirements
------------
This user package requires:

* Sublime Text 2 or 3 - https://www.sublimetext.com/
* SublimeTextXdebug/XDebug Client package by Martomo. - https://packagecontrol.io/packages/Xdebug%20Client

Changes
-------
First BETA version publicly release on 2016-12-22.

For more information on releases since then, see CHANGELOG.txt.

Installation and Update
-----------------------
Download or clone the contents of this repository to a folder named exactly as the package name into the Packages/ folder of Sublime Text.

There are no special considerations required for updating the toolbar.

Uninstallation
--------------
From within Sublime Text > Package Control > Package Control: Remove Package > xdebug-toolbar

Usage & Settings
----------------
There are no configurable settings for this toolbar at this time.

Once installed, the XDEBUG toolbar will appear to the right of the Help menu.

![sublime-text-xdebug-toolbar-screenshot](https://cloud.githubusercontent.com/assets/3808579/21419467/bf04b5b8-c7f5-11e6-9d85-3538b5eb4566.png)

You can access less frequently used options by pressing alt-x or by clicking on XDEBUG. The following menu items are included however only some will
appear depending on the context of the editor:

* Start session in web browser
* Start session
* Restart session
* Close session
* Detach session
* Set conditional breakpoint
* Set conditional breakpoint
* Clear breakpoint
* Clear all breakpoints
* Set Watch Expression
* Edit Watch Expression
* Remove Watch Expression
* Clear Watch Expressions

## XDEBUG Toolbar icons

Here is the meaning of each of the icons in the toolbar:

  * ⬤ - Toggle breakpoint (on/off)
  * {➺} - Step over
  * {⤵} - Step into
  * {⤴} - Step out
  * ▶| - Run to line
  * ▶ - Run (to next breakpoint)
  * ■ - Stop debugging
  * ] - Close session

Security considerations
-----------------------
There are no known security issues at this time.

Motivation for this plugin
--------------------------
The development of this package was motivated through our own experience in using Sublime Text and other editors like NetBeans, Eclipse and Notepad++, and comments in the Sublime Text support forums. The project was inspired by the only other Sublime Text toolbar we could find:
https://github.com/titoBouzout/Toolbar

This project is supported by TNG Consulting Inc.

Limitations
-----------
Unlike menu items which are context aware, the icons in the toolbar remain visible at all times, even if a debug session has not yet started.

Compatibility testing status:    ✔ Windows 10    ✖ Windows 8.1    ✖ Windows 7    ✖ Linux    ✖ OS X

If you've successfully tested it on one of the operating systems listed above that have yet to be tested, let us know.

Future Releases
---------------
Let us know if you have any suggestions.

Further information
-------------------
For further information regarding the XDEBUG Toolbar package, for support or to report a bug, please visit the project page at:

http://github.com/michael-milette/xdebug-toolbar/
    
Language Support
----------------
This package only includes support for the English language. You may customize the text by editing the Main.sublime-menu file.

This package has not been tested for right-to-left (RTL) language support. If you want to use this package with a RTL language and it doesn't work as-is, feel free to prepare a pull request and submit it to the project page at:

http://github.com/michael-milette/xdebug-toolbar/

Frequently Asked Questions (FAQ)
--------------------------------
**Question: Can you add tooltips to the icons?**

Answer: No. Unfortunately this is a limitation of Sublime Text.

**Question: The icons do not appear correctly. What can I do?**

Answer: On Windows 7 you may need to download the font "Segoe UI symbol" ( http://support.microsoft.com/kb/2729094 ) and then change your Windows Font from "Segoe UI" to "Segoe UI Symbol".

**Question: Are there keyboard shortcuts/bindings available?**

Answer: This plugin simply adds the toolbar which uses the SublimeTextXdebug/XDebug Client package API.

**Question: Why don't the icons do anything?**

Answer: With the exception of the breakpoint toggle icon which always works, icons are only active once you've started a debugging session.

**Question: Why doesn't ________ work? / How do I _________ ?**

This toolbar depends 100% on the SublimeTextXdebug/XDebug Client package for all its functionality. For more information on that package, see its documentation:
https://packagecontrol.io/packages/Xdebug%20Client