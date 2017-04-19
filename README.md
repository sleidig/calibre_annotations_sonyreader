# Sony Reader App for Calibre's Annotations plugin
This script extends the ["Annotations" plugin](https://www.mobileread.com/forums/showthread.php?p=2853161) of the [Calibre](https://calibre-ebook.com/) ebook manager. It enables the plugin to fetch annotations and notes made on a Sony Reader and add them to Calibre.


## Setup
1. Install the ["Annotations" plugin](https://www.mobileread.com/forums/showthread.php?p=2853161) in your Calibre software.
2. Download the python scripts from this repository to your computer.
3. Edit the "Annotations" plugin's config file (in Ubuntu it is located at `~/.config/calibre/plugins/annotations.json`) and add the file location of this script to `"additional_readers": [ ... ]`.
