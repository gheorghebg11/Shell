# Shell
Recognizing shell gas stations

TODO:
- hyperparam tuning : batch_size, factorreduceLR, LR, architecture, at padding min_ratio, crop dimensions
- create cell to load a pretrained model for the pres to do live testing

TODO FOR PRES:
- try all themes
- convert normal to html
- open in firefox and fix end to html?print-pdf
- print as pdf

- Do the one with 8, around 70% !
- add link on githbut so that they can just open the html in their browser from the chat there

Slideshow:
1) Choose theme: FOR PRES
jt -t gruvboxd -nfs 10 -ofs 13 -dfs 15 -tfs 14 -altp -T -N -kl
1) Choose theme: FOR PDF
jt -t solarizedd -nfs 10 -ofs 13 -dfs 15 -tfs 14 -altp -T -N -kl
2) Convert to slides:
jupyter nbconvert /home/bogdan/Downloads/Shell_with_slides.ipynb --to slides --post serve --SlidesExporter.reveal_theme=serif --SlidesExporter.reveal_scroll=True
3) Add width and height in the .html, just after Reveal.initialize({, say after 'history: true,', add the following: 
width: 1600, height:900,

Discussion for pres:
- 

