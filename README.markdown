This is a Bash completion script for the `android`, `adb`, `emulator`, `fastboot` and `repo`
command-line tools from the Google Android SDK.  If you'd like to add
completions for other Android tools, please let me know.

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

MIT license:

Copyright &copy; 2009 Matt Brubeck

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
