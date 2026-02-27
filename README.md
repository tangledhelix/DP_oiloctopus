## The great oil octopus - 655502d477e2f ##

This is a [Distributed Proofreaders](http://www.pgdp.net/) post-processing project.

“The great oil octopus” by "Truth's" investigator

* [DP project page](http://www.pgdp.net/c/project.php?id=projectID655502d477e2f)
* [Forum thread](https://www.pgdp.net/phpBB3/viewtopic.php?t=80582)
* [Good words](good_words.txt)
* [Bad words](bad_words.txt)
* [Project Gutenberg listing]() (not posted yet)

Page references (e.g. `001`) refer to the scan numbers, not the original book's page numbers.

### Things to revisit ###

* [x] From project notes: Please use " for the low level ditto.
* [x] 007-008: ToC
* [x] (HTML) Chapters start with drop-caps; first instance on 005
* [x] (HTML) Many blockquotes have a font-size change to smaller font, though they don't indent margins.
* [x] (HTML) Paragraph is `noindent` after a blockquote or table:
  * [x] 016-018
  * [x] 020
  * [x] 038
  * [x] 060
  * [x] 118
  * [x] 119 (2)
  * [x] 184
  * [x] 193
  * [x] 199
  * [x] 236
* [x] (HTML) Some blockquotes are noindent
  * [x] 037
  * [x] 038 (2)
* [x] (HTML) Book divides into major sections; should these be h2, chapters h3?
  * [x] Or is the start of *every* chapter??
  * [x] Yes, it is. How very dramatic. Someone was flexing on how little they cared about the cost of paper, perhaps.
  * [x] 009-011 chapter 1
  * [x] 025-027 chapter 2
  * [x] 043-045 chapter 3
  * [x] 063-065 chapter 4
  * [x] 075-077 chapter 5
  * [x] 089-091 chapter 6
  * [x] 105-107 chapter 7
  * [x] 123-125 chapter 8
  * [x] 137-139 chapter 9
  * [x] 155-157 chapter 10
  * [x] 171-173 chapter 11
  * [x] 189-191 chapter 12
  * [x] 207-209 chapter 13
  * [x] 217-219 chapter 14
  * [x] 237-239 chapter 15
* [x] Tables:
  * [x] 020 (2)
  * [x] 022
  * [x] 115 (2) - smaller text on 116, part of table bits too?
  * [x] 181
  * [x] 197-199
  * [x] 239
  * [x] 240
* [s] Letters (blockquotes with special formatting inside)
  * [x] 078-081
  * [x] 083-087
  * [x] 100-101
  * [x] 182
* [x] Major-section starts with quotes; the signatures need offset or maybe right-align.
  * [x] 010
  * [x] 026
  * [x] 044
  * [x] 064
  * [x] 076
  * [x] 106
  * [x] 124
  * [x] 138
  * [x] 156
  * [x] 190
  * [x] 208
  * [x] 238
* [x] Poetry:
  * [x] 069
* [x] 173: F rounds have left section dividers here. are they h3 or h4?
* [x] 178, 180: some signature blocks after quoted text?
* [x] 251-255: index
* [x] A number of `Q.` and `A.` in italics here, should get `<abbr>` tags
  * [x] Add `Q.`, `A.` to abbr.json?
* [x] Add `v.` to abbr.json? `versus`, `lang="la"`

### Project manager notes ###

Alignment . . . . dots should be removed.

Please use " for the low level ditto.

----

Images from [TIA](https://archive.org/details/greatoiloctopus00trutrich).

### Forum notes ###

### General notes ###

### Illustrations ###

### Proofer's notes ###

### Joined hyphenated words ###

### Spellcheck ###

### Transcriber's notes ###

smallcaps in use.

(HTML, TN at front of book): Due to damage to the original book cover, this book contains a restored cover image created by the transcriber. The new cover art included with this eBook is granted to the public domain.

p. 7: changed location of quotation marks for Chapters VII, VIII entries to match the chapter titles

p. 72: changed “Insterstate” to “Interstate” (the Interstate Commerce Commission)

p. 112: changed “o” to “of” (pretty close track of companies)

p. 115: changed shares total from “722,507” to “722,509”, correcting a math error.

p. 129: changed “Stark’s” to “Starks’s” for consistency (cart it round after Starks’s wagon)

p. 144: changed “monoply” to “monopoly” (fighting this American monopoly)

p. 165: changed “Campany” to “Company” (the Vacuum Oil Company, of Rochester)

p. 178: changed “Engine F” to “Engine I” (Gas Engine I and Heavy” respectively)

p. 200: changed “varies” to “various” (the various groups of middlemen)

p. 224: changed “bankum” to “bunkum” (“merely advertising bunkum,”)

### HTML file review ###
The iPhone/iPad simulators can't use `file://` URLs. Start a local web server with `python3 -m http.server` in the project directory and going to `localhost:8000` in Safari on the device. 

* [x] Safari
* [x] Firefox
* [x] Chrome
* [x] iPhone simulator
* [x] iPad simulator

### Ebook review ###

* [ ] Can we do drop-caps on EPUB now? EPUB3, at least?
   * [ ] Could still drop with `.x-ebookmaker-drop-2`
* [ ] The letters that abut each other, perhaps `hr.r5` to separate them?
* [ ] The curly brace in a couple of tables for grouping doesn't render very well on Kindle, Kobo, etc. Need a different approach? The height isn't being honored by some of them. Maybe need to use `min-height` or something instead?
* [ ] Table on p.181 renders *very* wide on Kindle, seems wrong. Double-check code.
  * Seen on both Android tablet & phone simulator, so far.
* [ ] ToC: add more vertical spacing between rows.
* [ ] In many tables: fix cell wrapping? Hanging indent?

### Smooth Reading ###
