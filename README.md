# My Firefox userChrome.css File

Features:

- Disable the blue dot on pinned tabs. From [here](https://support.mozilla.org/en-US/questions/1270061)

Installation:

1. In Firefox, go to `about:support`.
2. Copy the value of "Profile Directory".
3. In bash, change to that directory.
4. `ln -s /path/to/mozilla-chrome chrome`.
5. Back in Firefox, go to `about:config`.
6. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
7. Restart Firefox.
