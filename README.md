# JotterJoy Obsidian Plugin

The JotterJoy plugin helps enhance your Obsidian experience by providing advanced features such as proof-reading and tagging. This README will guide you through the installation and configuration process.

# Prerequisites

You will need Obsidian installed in your system for this to work. You can also download Obsidian [here](https://obsidian.md/).

Currently on available in MacOS devices with M1 chips or higher.
Windows version still WIP.

# Installation

### Step 1: Download the Plugin

1. Navigate to the [Jotterjoy Obsidian Plugin Repository](https://github.com/elevenyellow/JotterJoy-Obsidian-Plugin) on Github

2. Click on "Releases" located on the right side, that can also be found [here](https://github.com/elevenyellow/JotterJoy-Obsidian-Plugin/releases/tag/v0.0.2)

3. Download the latest version ```.zip``` file

### Step 2: Install the Plugin

1. Extract the downloaded ```.zip``` file on your Download folder

2. Open Obsidian and right-click on any of your notes and click on "Reveal in Finder" to open the root directory of your Obsidian Vault

3. Open the ```.obsidian``` folder.

4. Create a ```plugins``` folder if you don't have one yet.

5. Drag and drop the downloaded and extracted JotterJoy folder in to the ```plugins``` folder.

### Step 3: Enable the Plugin

1. In Obsidian, press  ``` `Command + p` ``` to open the search bar.

2. Type 'Settings' and open it

3. Navigate to the 'Community plugins' and click 'turn on Community plugins'

4. Enable "JotterJoy plugin"

### Step 4: Configure JotterJoy

1. Go to the Jotterjoy plugin settings.

2. Leave all settings as default except for the API key field.

3. To get an API key, visit [Grog](https://console.groq.com/keys),  create an account, and generate a key.

4. Paste the API key into the Jotterjoy plugin settings in Obsidian.

### Step 5: Download and Run the Server

1. Return to the Jotterjoy repository on GitHub.

2. Download the server ```.zip``` file from the releases section.
 
3. Extract the ```.zip``` file, and a new file will appear in your downloads folder.

4. Open the file. If you get an error when opening the file, hold ```Ctrl```, double-click it, and select "Open with Terminal".

5. Wait for the server to start. If you see a message indicating it is running, everything is set up correctly.

# Using JotterJoy

### Proofreading Your Notes

1. In Obsidian, open the note you want to proofread.

2. Press ````Command + P````, type "Jotterjoy", and select "Proofread note".

3. Wait for the note to be processed, it usually takes a few seconds. Then your note will be corrected.

### Generating Tags 

1. Open the note that you want to generate tags.

2. Press ````Command + P````, type "Jotterjoy", and select "Generate tags in front matter".

3. The plugin will analyze the document and add relevant tags.

### Advanced Configuration 

1. Open the Jotterjoy plugin settings by press  ```Command + p``` and typing Settings.

2. Under Community plugins, select JotterJoy

3. In the section LMM Model, you can select Grow Llama3 70 billion model instead of the 8 billion model for improved accuracy in proofreading and tag generation. 

Do note that the 70 billion model is limited on Grog and may take longer to process.

## Conclusion

With the Jotterjoy plugin, you can significantly enhance your note-taking experience in Obsidian by leveraging advanced AI features. Follow the steps outlined in this README to install, configure, and start using the plugin effectively. For more information, visit the [Jotterjoy repository](https://github.com/elevenyellow/JotterJoy-Obsidian-Plugin) on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/elevenyellow/JotterJoy-Obsidian-Plugin/blob/main/LICENSE) file for details

## Acknowledgments

* Support the project by buying us [coffee](https://buy.stripe.com/eVa9D6dS92y50KseV6)

