Amoyly Xcode Themes

Installation

The preferred installation method for this Color Schemes is done using the Package (Plug-ins) Manager Alcatraz. Custom Color Schemes for Xcode are stored in the ~/Library/Developer/Xcode/UserData/FontAndColorThemes/ folder.

Installation using Alcatraz

All themes in this repository is or will soon be available on Alcatraz. Once you have Alcatraz installed, installing the theme is done in Xcode's menu Window -> Package Manager simply by clicking on the Color Scheme you want to add to Xcode. You may need to restart Xcode to see the new themes.

Manual Installation

In Terminal

git clone https://github.com/Br1an6/Amoyly-Xcode-Themes.git
cd Amoyly-Xcode-Themes/
mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
cp *.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
cd ..
rm -rf Amoyly-Xcode-Themes/
