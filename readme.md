# Real Tabs Userchrome for Firefox

This is a pair of CSS files to correct several modish shortcomings of Firefox's Proton (v89-current) interface that did not previously exist in the Australis (v29-56) and Photon (v57-88) interfaces. It features:

* Contrast between functional areas – viz. active and inactive tabs, and the preferences sidebar – a nice feature of the Photon era that's been squeezed out by Light/Dark modes
* Crisp 1px borders and inset shadow for contrast on text boxes
* Subtle embossing of text and icons for added contrast
* Connection of functional elements – viz. the tab to the titlebar, as opposed to Proton's disconnected floating tabs
* Gentle gradients and highlights

This userchrome is intended to be used with the [Firefox Colors plugin](https://addons.mozilla.org/en-US/firefox/addon/firefox-color/) and [this theme](https://color.firefox.com/?theme=XQAAAAIPAQAAAAAAAABBKYhm849SCia2CaaEGccwS-xMDPsquqWmWr6U_-J9Sk2zluBv0zSwMyKaAShHBfVaSjHe4S-QTZGGSWTDW3GJBaw52IuYFpk7GR12YCt7svbegS0W-lRKiZhfzG14OaRI3_gMy_gA0MF_nsUePY6mp_9pQVs8-Tr3k8GTtrj4zQB4czyVQlUKovwZ9JwdJMhwgAZzwiY6Y1j9h6cFOtjG8ahrCjP7213g) but of course it'll look fine with a wide variety of colors.

If you find bugs or want to suggest improvements, feel free to open an issue or submit a pull request.

### [See what it looks like](https://twitter.com/C_Harwick/status/1740066979963400220).

## How to install

_See also [more detailed instructions](https://www.userchrome.org/how-create-userchrome-css.html)._

1. Navigate to about:config
2. Search for the `toolkit.legacyUserProfileCustomizations.stylesheets` preference and set it to `true`
3. Create a folder called `Chrome` in your Firefox user profile folder and add these two CSS files
4. Restart Firefox

I also recommend setting the `widget.non-native-theme.enabled` preference to `false` to disable Firefox's custom widgets and use the native system widgets.