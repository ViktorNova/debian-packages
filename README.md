debian-packages
===============

Build scripts and binary packages I've made for software that doesn't exist in Debian

Most of these are packages I built using PKGBUILDs from Arch Linux/AUR using my tool
Architect https://github.com/ViktorNova/architect
And FPM https://github.com/jordansissel/fpm

For now the deb packages don't list any dependencies, so you can install em, but need to track down the dependencies yourself ;) However I plan on adding proper dependencies, possibly by converting the PKGBUILDs into DEBBUILDs (since the syntax is almost exactly the same so it'd be easy), or maybe utilize a feature of FPM that I don't know about yet


GitHub is not the ideal place for this, I ideally want to find a build service that does all of this automatically. Possibilities are 

1. OpenSuSE Build Service - though apparently they can only use official repos for dependecies - not ideal
2. Launchpad? https://launchpad.net/debian - However I have no idea if this really works, because I don't see anyone doing it
3. I know there are more! Suggestions are extremely welcome

