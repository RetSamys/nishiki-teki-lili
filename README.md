For the original font, go to the website or go to the PDF directly to see what options are available for sitelen pona in the UCSUR codepoints only version: https://umihotaru.work/nishiki_sitelen.pdf 

# ASCII input (ligatures)

Nishiki-teki-lili is a version of Nishiki-teki by jan Umijotalu (umihotaru) that automatically converts words (typed in Latin/ASCII) to sitelen pona characters. For example, `pona` will turn into &#xF1954;/the sitelen pona character for "pona". So this works like most ligature fonts for sitelen pona. However, there are some quirks that I think I should document.

* You can escape any character by preceding it with a backslash. `a` will turn into &#xF1954;/the sitelen pona character for "a", but `\a` will allow you to use the Latin letter instead of the sitelen pona character.
* `zz`,`?`,`- `(hyphen space),`!`,`  `(space space),`|` will turn into an ideographic space. `/` will turn into a regular space
* Wiiiiiide characters include tasun, soweli, kijetesantakalu and wasoweli. Type the first vowel of the word several times instead of once, for example `taaaaaasun` instead of `tasun`
  * Same goes for silapa, but be aware that it stretches upwards instead of sidewards. You'll have to add preceding lines if you want to see all of it
  * Anything inside of `{` and `}` will be part of a reverse long extension of a character (with an underline), for example `{a a a}kama` [TO DO: list which ones have a reverse long extension]
* You can combine glyphs with `&` (zero width joiner), `-` (stacking joiner), `+` (scaling joiner)
  * Stacks are virtually infinite. Go wild. Make a soweli tower.
* cartouches:
  * `[` opens a cartouche and `]` ends it
  *  `=` turns into a cartouche extension line if you need to add one manually
  * `.` turns into a cartouche middot and `:` turns into a cartouch colon
  * `,` (or multiple) adds tally marks
  * `°` turns into゜ and `"` turns into ゛
* some punctuation:
  *  `;` turns into sideway emitters
  * `*` turns into upwards emitters
  * `te` and `to` turn into bracket quotation mark
* use `v`, `^`, `>`, `<` (and combinations) at the end of a word for rotate-able characters ("ni")
* use numbers at the end of a word for words that have alternative glyphs [TO DO: list which words have alts]
## tuki tiki
* for titi pula/titi tuki tiki, precede words with `tt`, for example `ttkiku`
* use `[=` to open cartouches and `]=` to end them
