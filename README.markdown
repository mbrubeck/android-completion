This is a Bash completion script for the "adb" and "emulator" command-line
tools from the Google Android SDK.  If you'd like to add completions for other
Android tools, please let me know.

Install
=======

1. Install bash-completion.  On many Linux distributions it is installed and
   enabled by default.  If you don't have it already, you can probably find it
   in your package repository (e.g. "aptitude install bash-completion").  Mac
   OS X users can find it in Fink or MacPorts.

2. Copy the "android" file from this directory into the /etc/bash_completion.d
   folder (under "/sw/etc" or "/opt/local/etc" on Mac OS X).

3. Restart your shell.

Note: If you can't install the bash-completion package, you can still use the
android completion script just by sourcing it from your bashrc or profile.

Author
======

Matt Brubeck <mbrubeck@limpet.net>.

License
=======

Released under the MIT license.  See the source code for details.
