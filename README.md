# Material Monokai

A collection of my adapations of the vs code theme "Material Monokai" by Alessio Enrico (https://github.com/repeale/material-monokai)

## VS Code
Use the original theme https://github.com/repeale/material-monokai (found on the VSCode marketplace as Material Monokai)


## Stylus

Opinionated themes for many websites using the Stylus firefox/chrome extension

> ⚠️ **Warning:** Some of the stylus themes may break certain features of websites, if something doesn't work as expected you may need to toggle the theme off to use it
### Screenshots
(There are many sites covered by this site so I will show a few of the best ones)
![image](https://github.com/user-attachments/assets/9efbf6cc-6467-4936-921c-fe3987c8a5e7)
![image](https://github.com/user-attachments/assets/5e71d708-ce1c-4482-8ed9-07dc68fc77ee)
![image](https://github.com/user-attachments/assets/936a3123-d523-4c3b-a911-ce700ce0d479)
![image](https://github.com/user-attachments/assets/9ffb68bc-a228-4b65-98eb-e78b2293cd4e)



### Installation

1. Install the Stylus browser extension
2. Open the extension widget
3. Click New Style
4. Delete generated contents
5. Paste contents of material-monokai.css into the editor and save

## Firefox

Opinionated userchrome for firefox (theme the title bar, tabs etc)

I recommend using this along with stylus themes for a more consistent experience

> ⚠️ **Warning:** From my usage, I have not encountered any issues with the current version. However your mileage may vary as this significantly alters the css of firefox's built in UI and you may use features I don't

### Installation

1. Find your firefox profile directory (default profile is `~/.mozilla/firefox/default`)
2. Copy `firefox/userchrome/userChrome.css` to `(your firefox profile dir)/chrome`
3. Restart firefox (ensure all instances of firefox are closed, pkill them if unsure)

## GTK

Theme for any GTK based application

### Screenshots
![image](https://github.com/user-attachments/assets/800ae5e6-4b27-4fd9-af12-11f5c01abc49)
![image](https://github.com/user-attachments/assets/43d117d5-a3ea-4cfe-a406-7f103c4f45f3)
![image](https://github.com/user-attachments/assets/8cacd376-30ad-4a10-8548-cbcd79c830ab)

### Installation
Copy the contents of the gtk directory into your .config directory (gtk-3.0 and gtk-4.0)

## Helix

Material monokai for the Helix text editor (similar to neovim)

### Screenshots
![image](https://github.com/user-attachments/assets/083756e8-43e4-42b7-a2dd-911b0aa2d48f)
![image](https://github.com/user-attachments/assets/2d82207a-40dc-4642-8ca0-86df3f8b7a4c)

### Installation
1. Copy helix/materialMonokai.toml to ~/.config/helix/themes/ (create the directories if they don't exist)
2. Add the line ``theme = "materialMonokai"`` to the top of .config/helix/config.toml (creating it if it doesn't exist)

## Swaync
Material monokai for sway notification center

### Screenshots
![image](https://github.com/user-attachments/assets/0a6a6c3c-bd37-48b9-900c-c69037858063)
![image](https://github.com/user-attachments/assets/e328c95c-79bb-41fb-916e-a07a49f7dacf)
