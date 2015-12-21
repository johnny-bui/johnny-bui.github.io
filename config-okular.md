Configure Okular to search backward a TeX file from a PDF file

Setting &ndash;> Configure Okular &ndash;> Editor &ndash;> 

Editor: Custom Text Editor
Command: There are some configurations for diverse not listed editor:

* gvim 
    `gvim --remote-tab-silent +%l %f`

* texmaker
    `texmaker -use -line %l -column %c`


