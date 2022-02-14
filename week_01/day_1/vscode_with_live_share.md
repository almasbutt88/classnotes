# Installing VSCode and Live Share

### Installing VSCode

Follow the installation instructions for MacOs [here] (https://code.visualstudio.com/docs/setup/mac) - ensure that you move your installation to the Application folder and install the shell commands to open files from the terminal in VSCode

### Installing Live Share Extension

Install the live share extension from [here] (https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)

### Adding your project to VSCode

There are a couple of ways you can add codebases to VSCode:

1. With VSCode open click File -> Add Folder to Workspace and find your project folder manually from Finder
2. Having added the shell commands after installing VSCode, navigate to your project directory and type `code .` to open the directory in VSCode

### Setting up Live Share

**Ensure you have your credentials to GitHub to hand before continuing**

1. With your codebase open in VSCode, also ensure you have the terminal open inside VSCode
2. Click on the Live Share link in the bottom bar
3. You will be prompted to link your Live Share account with your Github account.  This will generate a unique URL that you can share with others who can use that to access your VSCode Environment
4. So long as others have Live Share installed on their VSCode should then be able to access your project directory, your terminal and your code to help you.  They need to click on the Explorer tab to see your file structure
5. For any further guidance - refer to the [quick start guides for VSCode] (https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)

* You may see a warning message stating "You are running VS Code outside the Applications folder, so we cannot install support for joining sessions using a browser link. You can still join sessions manually."  This does not seem to impact the use of Live Share

### Other Quality of Life Options

Atom has a number of snippets you can utilise,  [Emmet is the equivalent] (https://code.visualstudio.com/docs/editor/emmet) out of the box and supports most of the common front-end syntaxes.  You can install snippets for Ruby, Python, Javascript etc. from [VSCode's wide extensions market] (https://code.visualstudio.com/docs/editor/extension-gallery)

For ERB files, you need to set up Emmet to suggest HTML snippets on erb files.  To do this, open up the settings.json file in VSCode via the command palette `(⇧⌘P)` and add the following:

`"emmet.includeLanguages": { "erb": "html" }`

Additionally [this article has all the information you need on setting up custom erb snippets] (https://medium.com/swlh/custom-vs-code-snippets-and-emmet-for-erb-files-d163917cce68) 

Change the colour theme with Code -> Preferences -> Color Theme.  You can even download and install a [lookalike Atom theme here] (https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

