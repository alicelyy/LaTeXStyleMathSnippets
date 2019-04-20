

## LaTeXStyleMathSnippets

For fast math typing in the study of math/CS theory. 
This project contains only math related components. I found it more favorable to work with markdown becuase you don't get distracted by too much LaTeX formatting code. 

These snippets come with two different versions: 
#### UltiSnips 
is amazingly fast and is very enjoyable to use, especially for experienced Vimers. 
https://github.com/SirVer/ultisnips
Checkout Zathura for dynamic rendering of LaTeX code.
https://wikimatze.de/vimtex-the-perfect-tool-for-working-with-tex-and-vim/

#### VSCode 
VSCode snippets work as a part of the auto-completion dynamic. VSCode has convenient open-source packages for real-time rendering which can save you tons of time of configuring Zathura..
However, VSCode would not pop up snippets by default(other than C/C++ on my end). You can press ^+space for suggestions, or set quickSuggestions to true for a language you'd like to use snippets often.
To do that, press command+shift+P and choose Preferences: Configure Language Specific Setting and make sure you have the following JSON component(on MacOS): 

"[markdown]": {
        "editor.quickSuggestions": true,
},

The motivation of this repo is for math homework at UC Berkeley. 
Contribution would be welcome and appreciated!  


