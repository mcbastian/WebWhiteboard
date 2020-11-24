# Simple HTML Whiteboard with TeX
During the Codiv-19 pandemic, I needed a simple whiteboard tool to pre-record my math lessons. I played around with a few ones, but none of them had the feature set I wanted. So I googled around and found:
- JSXGraph
- MathJax (3) (plus canvg for SVG rendering)
- Konva
for HTML/JavaScript which provide everything I need. I just needed to plug it together with a bit of BOOTSTRAP beauty and jQuery... The aim was to have one single HTML-File to put "somewhere on a webserver" and start whiteboarding. As little as possible installation.
This project aims to bring this simple whiteboard with the following 
## Features
- pen/brush drawing
  - change colours
  - change line width
  - eraser
- insert mathematical formulas using TeX (LaTeX)
- insert images (PNG/JPEG)
- insert arrows
- plot graphs
  - enter formula
  - multiple graphs in one image
  - tangent
  - equation of derivative
- transform objects on the board
  - move (translate)
  - scale
  - rotate
- save screen to some image format (PNG) 
- delete stuff
- single file

## Installation
Just download/clone the HTML files and put it on a webserver in some directory. The libraries are loaded via CDN (cloudflare, jsdelivr, unpkg, bootstrapcdn, polyfill).
- index.en.html is the english translation
- index.de.html is the german original

## License
The used libraries are using the Apache, LGPL and MIT license, so I decided to go with the Apache 2.0 license:
(c) 2020 by Sebastian Buntin
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
