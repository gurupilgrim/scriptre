# scriptre
scriptRE - Bible study application for bash in ncurses.

This project is currently in the conception and planning stage. scriptRE will be a simple text-oriented Bible study application focused on leveraging Linux and open source tools to view, search, filter, and study the text of the Bible.

The basic layout of scriptRE is divided into two parts, the storage mechanisms, and the display.

The core feature that will make scriptRE different is the way scripture is stored. The foundation is the original texts of the Masoretic Text Hebrew and the Textus Receptus Greek, which will be numbered by book, chapter, verse, and word, giving every word a unique number. Versions (translations) of the Bible will be made up of two parts, the text, which will be delimited and arranged in the order that matches the original text, and the numbering, which will provide the arrangment of the words for rendering.

The display will be built with ncurses, and will feature vim-like navigation with the ability to search and filter text based on criteria. 
