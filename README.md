# Chip.de Blocker
GitHub repository for the Chrome extension Chip.de Blocker. Keeps Chip.de from loading.

## Manual installation
1. Clone the repository or download it as a zip (and unpack it)
2. Open chrome://extensions/ (via url or omnibox/menu -> Tools -> Extensions) and tick the checkbox for developer mode in the upper right corner
3. Click "Load unpacked extension"
4. Select the directory containing the unpacked extension, that means the folder with the manifest.json directly in it.
5. To update the extension when it changed, click the reload button right next to the disable/enable extension switch in the extension overview (restart of the browser should update the extension too).
5. Note: In the standard channel for the Chrome, you will get a pop up with "Disable developer mode extensions" every time you open a new browser window. It can be quite annoying. You can go around that by downloading the dev or canary version of Chrome.
7. Of course, if the extension comes to the Web Store, there will be no warnings and no need to refresh/update the extension manually.

## Description
(copied from the Web Store draft)

This chrome extension works very simple: The JavaScript statement 'window.block();' keeps every HTML site on \*.chip.de from loading when you open it, just like you would press the stop loading button in your browser instantly when you open the site. It's just an empty white page then.

It should help users that are annoyed by Chip.de with not opening the site uninentionally and giving CHIP any ad revenues.

Please do not install the extension, if you don't know what it does or what Chip.de is, or you do want to use Chip.de sometimes.

You can view the source code here and contribute, if you'd like to: https://github.com/gregthwuen/chip.de-blocker
(right now the extension has no more features than the described above, but that can change of course)
