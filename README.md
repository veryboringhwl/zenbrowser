# Zen Browser tweaks
A customisable Zen Browser tweaks

## Installation

### Manual Installation

1. Clone/download the repository
2. Navigate to your Zen Browser root profile (You can access this by typing `about:profiles`)
3. Create a folder in your directory called `chrome`
4. Copy the contents the `chrome` folder of the downloaded repo into your Zen Browser profile's chrome folder.
5. Restart Zen Browser to apply changes

### Customization

To enable tweaks, you need to create a custom boolean preference in about:config.

To enable a config:

1. Go to about:config.
2. Create a custom boolean preference by typing the preference name 
3. Click the plus button and set to true

To disable a config:

1. Go to about:config.
2. Search by name and delete the preference or toggle preference state to false.

Available Configs

| Configs                               | Value        |  Screenshot                                   |
|---------------------------------------|--------------|-----------------------------------------------|
| tweaks.sidebar-url                    | true         | ![(placeholder)](assets/lightplaceholder.png) |
| browser.toolbars.bookmarks.visibility | never        | ![(placeholder)](assets/darkplaceholder.png)  |
| browser.tabs.allow_transparent_browser| true         | ![(placeholder)](assets/lightplaceholder.png) |
| devtools.debugger.prompt-connection   | false        | ![(placeholder)](assets/darkplaceholder.png)  |
| devtools.debugger.remote-enabled      | true         | ![(placeholder)](assets/lightplaceholder.png) |
| zen.view.use-single-toolbar           | true         | ![(placeholder)](assets/darkplaceholder.png)  |
| zen.view.hide-window-controls         | false        | ![(placeholder)](assets/lightplaceholder.png) |
| zen.tab-unloader.excluded-urls        | example.com, | ![(placeholder)](assets/darkplaceholder.png)  | 

