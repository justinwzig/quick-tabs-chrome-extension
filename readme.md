# Firefox Port of Quick-Tabs

This is still in development. The vast majority of the chrome extension (built by @babyman) works perfectly in the Firefox version, and almost everythng remains unchanged.

Various updates have been made to comply with Firefox extension standards.

Several styling adjustments have been made.

## TODO

* Add hotkey adjustments (firefox and chrome use `Command`, but firefox lets the extension remap hotkeys mapped to `Command` while Chrome adjusts them externally)
* Re-implement autofocus of searchbox -- `autofocus` HTML5 element apparently doesn't function correctly in Firefox popups.
* Update options page to reflect context & reimplement full functionality

## What works
The base extension works fine - open the popup, search tabs, etc. I've not done much debugging beyond base compadability so there are liekly some huge broken parts.

Ctrl+Space to open tab search popup.

# Please Contribute!
This is very far from marketplace-ready. Please contribute if you want to see this on the Firefox platform!


# LICENSE
Per https://github.com/babyman/quick-tabs-chrome-extension

Copyright (c) 2009 - 2017, Evan Jehu All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

    Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
    Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
    Neither the name of the author nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL EVAN JEHU BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.