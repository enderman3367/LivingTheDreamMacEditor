thank you Timimimi for making the original python app on windows
# INSTALLATION:
in releases (to your right), download and open macos-install.dmg, drag tool to applications and double click to launch.
apple may quarantine the file because i didnt sign it (its a simple fork of a python app, thank you Timimimi.) you can fix this by running 

xattr -dr com.apple.quarantine path/to/app

in your terminal.

# USAGE:

Other approaches to facepaint required switch toolbox to comporess/decompress. this app does it for you. 

- locate the original .canvas.zs file and .ugctex.zs from your save. 
the app will display the original image, and you can replace it by uploading your own. 
- The output location can be anywhere except the original placement of the files. this was intentional because I don’t want people to ruin their saves.
- replace the original folders with the new output, ensuring the names of the files match.

# FYI:
theres this weird bug where an image will look broken. this is because we didnt replace the _thumb. to fix this, go into the facepaint editor or palette house and open the design as if to edit it. your uploaded image should appear. save, and now you’re all done!


# in the future you can expect save editing outside of facepaint. including a better UI. map editor is next.
