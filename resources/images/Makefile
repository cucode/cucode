build/code_logo.png: src/code.svg
	inkscape -e build/code_logo_full.png 		-j -i Code_Logo_Full 	src/code.svg
	inkscape -e build/code_logo.png 		 		-j -i Code_Logo 			src/code.svg
	inkscape -e build/code_avatar_full.png 	-j -i Code_Avatar			src/code.svg
	convert build/code_avatar_full.png -gravity center -extent 260x260 build/code_avatar.png 
clean:
	rm -rf build/*
