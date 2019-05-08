# Shell
Recognizing shell gas stations

TODO:
- hyperparam tuning : batch_size, factorreduceLR, LR, architecture, at padding min_ratio, crop dimensions
- create cell to load a pretrained model for the pres to do live testing
- PRES:
  - new dist should be on the same slide!!
  - config rearrange attr

Presentation:
- select them: jt -t solarizedd -nfs 10 -ofs 13 -dfs 15 -tfs 14 -altp -T -N -kl
- convert normal to html
- open in chrome and fix end to html?print-pdf
- print as pdf

Slideshow:
1) Choose theme:
jt -t gruvboxd -nfs 10 -ofs 13 -dfs 15 -tfs 14 -altp -T -N -kl
2) Convert to slides:
jupyter nbconvert /home/bogdan/Downloads/Shell_with_slides.ipynb --to slides --post serve --SlidesExporter.reveal_theme=serif --SlidesExporter.reveal_scroll=True
3) Add width and height in the .html, just after Reveal.initialize({, say after 'history: true,', add the following: 
width: 1600, height:900,

Discussion for pres:
- 

