# Shell
Recognizing shell gas stations

TODO:


- STRUCTURED INTERVIEW   --->   It is recommended that you come prepared to discuss specific tasks/projects you have worked on
The Structured Interview should take approximately 60 minutes and will explore your working styles and
preferences in relation to the attributes. The interviewers will ask you a series of questions to learn more
about some of your relevant past experiences and, in particular, how you dealt with specific situations. It
is recommended that you come prepared to discuss specific tasks/projects you have worked on in the
past 18 months, or which you worked on in your last role if you have not been working in the last 18
months.  

- THE PROCESS  --->   Please be prepared to introduce yourself and give a brief explanation of your current role and main responsibilities.
Before you start your presentation on the assessment day, you will be given a few minutes to prepare
yourself (for example, organising any materials or visual aids you may want to use). The assessors will
start with some short introductions. Please be prepared to introduce yourself and give a brief
explanation of your current role and main responsibilities.
You will then have up to 20 minutes to present. The session will be followed by a discussion to clarify the
information you have presented. You may also be asked additional questions that are not directly
related to the content of your presentation in order to help us understand more broadly your skills,
knowledge and expertise outside the project you presented.  


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
