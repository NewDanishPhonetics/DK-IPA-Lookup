# DK-IPA-Lookup
Lookup the IPA of a word in any Danish text with a hotkey

# Description

Double click any word in any text and look up the word in udtaleordbog.dk with a hotkey (default ALT+q).

The AHK script copies the selected word, sends it to udtaleordbog.dk's simple API, and feeds back the IPA in a message box.

# Installation and use

AHK must be installed first: https://www.autohotkey.com/

Download the UOBLookup.ahk file and run it.

Double click any word in any text and press ALT+q.

Change the hotkey in line 1 if desired. Refer to https://www.autohotkey.com/docs/v2/howto/WriteHotkeys.htm. 

# Issues

Doesn't handle heterophonous homographs very well. This is due to the simple API. I'm working on making the API select the most common word for homographs.
