# BibleData
Easy-to-use data files for developing great Bible study software.

# Contents
The file OSHB.db is a SQLite database file, containing every word of the Hebrew Text of the Old Testament.  The data is arranged by book, chapter, verse and word number.  Each entry shows the form of the word at this point in the Biblical text, the Strong's number for the lemma word and a morphology code (describing the grammar of the word).  This data is adapted from the OSHB Sword module.  The data was brought into this format by using the morphhbXML-to-JSON.pl script from the Open Scriptures Hebrew Bible Project to generate a JSON array of all the words with their parsing information, then a PHP script was used to convert this into SQL inserts for the database file you find here.  My hope is that creators of Bible study software will find this useful in providing better tools for studying the Hebrew text, with all the grammar and dictionary information available.  This data is originally from the Open Scriptures Hebrew Bible Project, and it is licensed as follows.

# License
Lemma and morphology data are licensed under a [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/) license. For attribution purposes, credit the Open Scriptures Hebrew Bible Project. The text of the WLC remains in the [Public Domain](http://creativecommons.org/publicdomain/mark/1.0/).

# Further Information
A guide to the characters used in the morphology codes is [here.](http://openscriptures.github.io/morphhb/parsing/HebrewMorphologyCodes.html)
