# GoDark
## Deep Dark theme for Gophers  
The theme *Deep Dark Material Theme* by *Nimda*  on VSCode is really good for the Holy Trinity of Web Development: HTML, CSS, and Javascript\
**BUT** its support/theme for Go **sucks donkey balls** (almost every letter of text was white)  
  
So, what do you do when you have a good theme that doesn't support something you want it to support?  
**YOU FIX IT YOURSELF**  
I took matters into my own hands and edited the json file that controls the theme's scopes and colors to support Go syntax  

If you want to install it, I recommend:  
1. Downloading the Deep Dark theme on Visual Studio Code (aka VSCode)
   - You can keep your VSCode window open, just know that **you will have to restart the window after the changes are applied**
   - To restart the window, open the command palette (*CTRL+SHIFT+P*) and enter "reload window" and click on it or hit enter
3. Go into your *.vscode* directory in your computer's home directory (i.e. the ~ directory)
4. Enter the *extensions* directory
5. Find the deep dark theme directory and enter it
   - The name of the theme's directory should be ***nimda.deepdark-material-3.3.0***
6. Once you're in, enter the *themes* directory
7. Then, replace the *fullblack-deepdark-material.json* file with the one stored in this repo
   - Download this repo's file by clicking on the file and then after getting redirected, clicking on the **CODE** button
   - Download however you want, you could even just copy the text in the file and paste it into file directly 
8. And that's it! 
   - If you had a VSCode window open the whole time:
     1. Make sure that the theme is installed and applied
     2. Reload the window if the Go theme hasn't applied as detailed under Step 1 
