# stereohack
Repo for code, notes, documentation, etc. from adventures with the NASA Ames Stereo Pipeline during the [2016 UW eScience Geohackweek](http://geohackweek.github.io/).

The Geohackweek results can be found on the [wiki](https://github.com/dshean/stereohack/wiki):
- step-by-step instructions for getting ASP running on Windows
- tutorial for new users working with sample DigitalGlobe image data

#Overview

Let's build some DEMs!  

#Goals

- Can we produce high-quality DEMs in only 2 days?
- Can we use Docker to get ASP running on Windows?
- Can we use the ASP GUI to select ground control points for bundle adjustment?
- Can we use ASP's current Structure from Motion functionality with arbitrary airborne camera images?

#Installation

[Stereo Pipeline official website: https://ti.arc.nasa.gov/tech/asr/intelligent-robotics/ngt/stereo/](https://ti.arc.nasa.gov/tech/asr/intelligent-robotics/ngt/stereo/)
- Download precompiled binaries for Linux and OS X
- Get latest documentation
- Sign up for mailing list

[Stereo Pileline source code on github](https://github.com/NeoGeographyToolkit/StereoPipeline)
- See what's under the hood

#Documentation

Official Documentation ([asp_book.pdf](http://byss.ndc.nasa.gov/stereopipeline/binaries/asp_book-2.5.3.pdf))
- See examples for processing DigitalGlobe data

Zach Moratto's blog (an appendix to the ASP manual): http://lunokhod.org/(http://lunokhod.org/
- Notes on using pc_aling for DEM co-registration: http://lunokhod.org/?p=1417
- Video recording of live ASP demo: http://lunokhod.org/?p=654

Shean, D. E., O. Alexandrov, Z. Moratto, B. E. Smith, I. R. Joughin, C. C. Porter, Morin, P. J. (2016), An automated, open-source pipeline for mass production of digital elevation models (DEMs) from very high-resolution commercial stereo satellite imagery, ISPRS J. Photogramm. Remote Sens, 116, 101-117, [doi: 10.1016/j.isprsjprs.2016.03.012](https://github.com/dshean/stereohack/blob/master/doc/sheanetal_2016_ISPRS.pdf).
- Outline of DigitalGlobe processing workflow
- Accuracy analysis for ASP DEMs from WorldView-1/2

