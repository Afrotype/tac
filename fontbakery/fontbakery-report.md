## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[21] Festac-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 984, but got 830 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 431, but got 370 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.1, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* 🔥 **FAIL** name id 257 missing from name table
* 🔥 **FAIL** name id 258 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: eth	Expected: 2

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni02C8	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: fraction	Expected: 1

	- Glyph name: uni2153	Expected: 3

	- Glyph name: uni2154	Expected: 1 or 3

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Lslash	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: eth	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lslash	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni02C8	Expected: 1

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: numbersign	Contours detected: 3	Expected: 2

	- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 2	Expected: 3

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01AC	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: numbersign	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 2	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01AC	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni024E	Contours detected: 1	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, canadian-aboriginal, tifinagh, old-permic, coptic, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, tifinagh, gothic, caucasian-albanian, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- t + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ("Seventy Seven") that differs from the currently used family name (Festac), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- ampersand.001

	- asterisk_node

	- dotlessi_ogonek

	- infinity.001

	- strokelongY.comb

	- uni004A0301
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 278 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 380:
plusminus, plus

Width = 414:
minus, notequal, equal

Width = 250:
greater

Width = 514:
logicalnot

Width = 403:
multiply

Width = 424:
divide

Width = 362:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment B<<97.0,541.5>-<106.0,554.0>-<106.0,554.0>>

	* ampersand (U+0026) contains a short segment B<<378.0,554.0>-<378.0,554.0>-<389.0,542.0>>

	* two (U+0032) contains a short segment L<<253.0,554.0>--<253.0,554.0>>

	* five (U+0035) contains a short segment L<<65.0,0.0>--<64.0,2.0>>

	* eight (U+0038) contains a short segment L<<224.0,-1.0>--<224.0,-1.0>>

	* eight (U+0038) contains a short segment B<<172.0,261.5>-<166.0,265.0>-<161.0,268.0>>

	* X (U+0058) contains a short segment L<<342.0,315.0>--<345.0,312.0>>

	* s (U+0073) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* s (U+0073) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* section (U+00A7) contains a short segment B<<256.0,176.0>-<260.0,172.0>-<265.0,167.0>>

	* uni00B2 (U+00B2) contains a short segment L<<253.0,554.0>--<253.0,554.0>>

	* eng (U+014B) contains a short segment L<<290.0,0.0>--<292.0,0.0>>

	* sacute (U+015B) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* sacute (U+015B) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* scircumflex (U+015D) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* scircumflex (U+015D) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* scedilla (U+015F) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* scedilla (U+015F) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* scaron (U+0161) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* scaron (U+0161) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* uni0190 (U+0190) contains a short segment L<<301.0,554.0>--<301.0,549.0>>

	* uni019B (U+019B) contains a short segment L<<208.0,400.0>--<209.0,400.0>>

	* uni01AD (U+01AD) contains a short segment L<<235.0,280.0>--<235.0,270.0>>

	* uni01B8 (U+01B8) contains a short segment L<<315.0,322.0>--<314.0,322.0>>

	* uni01B9 (U+01B9) contains a short segment L<<249.0,168.0>--<248.0,168.0>>

	* uni0219 (U+0219) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* uni0219 (U+0219) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* uni0266 (U+0266) contains a short segment L<<29.0,385.0>--<30.0,385.0>>

	* uni0266 (U+0266) contains a short segment L<<30.0,385.0>--<30.0,387.0>>

	* lambda (U+03BB) contains a short segment L<<208.0,400.0>--<209.0,400.0>>

	* uni1E61 (U+1E61) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* uni1E61 (U+1E61) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* uni1E63 (U+1E63) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* uni1E63 (U+1E63) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* uni1E65 (U+1E65) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* uni1E65 (U+1E65) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* uni1E67 (U+1E67) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* uni1E67 (U+1E67) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* uni1E69 (U+1E69) contains a short segment L<<29.0,0.0>--<27.0,2.0>>

	* uni1E69 (U+1E69) contains a short segment L<<229.0,400.0>--<231.0,398.0>>

	* uni1E8A (U+1E8A) contains a short segment L<<342.0,315.0>--<345.0,312.0>>

	* uni1E8C (U+1E8C) contains a short segment L<<342.0,315.0>--<345.0,312.0>>

	* uni2075 (U+2075) contains a short segment L<<65.0,0.0>--<64.0,2.0>>

	* uni2078 (U+2078) contains a short segment L<<224.0,-1.0>--<224.0,-1.0>>

	* uni2078 (U+2078) contains a short segment B<<172.0,261.5>-<166.0,265.0>-<161.0,268.0>>

	* uni2082 (U+2082) contains a short segment L<<253.0,554.0>--<253.0,554.0>>

	* uni2085 (U+2085) contains a short segment L<<65.0,0.0>--<64.0,2.0>>

	* uni2088 (U+2088) contains a short segment L<<224.0,-1.0>--<224.0,-1.0>>

	* uni2088 (U+2088) contains a short segment B<<172.0,261.5>-<166.0,265.0>-<161.0,268.0>>

	* colonmonetary (U+20A1) contains a short segment L<<121.0,0.0>--<115.0,0.0>>

	* uni20A8 (U+20A8) contains a short segment L<<544.0,0.0>--<542.0,2.0>>

	* uni20A8 (U+20A8) contains a short segment L<<744.0,400.0>--<746.0,398.0>>

	* Euro (U+20AC) contains a short segment B<<259.0,284.0>-<259.0,277.0>-<259.0,271.0>>

	* uni20B4 (U+20B4) contains a short segment B<<355.0,391.0>-<355.0,386.0>-<354.0,381.0>>

	* uni20B4 (U+20B4) contains a short segment B<<323.0,281.0>-<320.0,275.0>-<318.0,271.0>>

	* uni2206 (U+2206) contains a short segment L<<554.0,120.0>--<552.0,120.0>>

	* uniA727 (U+A727) contains a short segment L<<290.0,0.0>--<292.0,0.0>>

	* uniA7B3 (U+A7B3) contains a short segment L<<187.0,260.0>--<187.0,261.0>>

	* uniA7B3 (U+A7B3) contains a short segment L<<203.0,554.0>--<206.0,550.0>>

	* uniA7B3 (U+A7B3) contains a short segment L<<284.0,314.0>--<283.0,312.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* arrowboth (U+2194): L<<280.0,362.0>--<334.0,362.0>> -> L<<334.0,362.0>--<532.0,363.0>>

	* arrowupdn (U+2195): L<<216.0,166.0>--<216.0,190.0>> -> L<<216.0,190.0>--<215.0,418.0>>

	* arrowupdn (U+2195): L<<356.0,417.0>--<356.0,363.0>> -> L<<356.0,363.0>--<357.0,165.0>>

	* eng (U+014B): L<<463.0,200.0>--<463.0,0.0>> -> L<<463.0,0.0>--<462.0,-63.0>>

	* two (U+0032): L<<253.0,554.0>--<253.0,554.0>> -> L<<253.0,554.0>--<367.0,553.0>>

	* two (U+0032): L<<87.0,554.0>--<253.0,554.0>> -> L<<253.0,554.0>--<253.0,554.0>>

	* uni00B2 (U+00B2): L<<253.0,554.0>--<253.0,554.0>> -> L<<253.0,554.0>--<367.0,553.0>>

	* uni00B2 (U+00B2): L<<87.0,554.0>--<253.0,554.0>> -> L<<253.0,554.0>--<253.0,554.0>>

	* uni0199 (U+0199): L<<30.0,0.0>--<30.0,324.0>> -> L<<30.0,324.0>--<31.0,387.0>>

	* uni2082 (U+2082): L<<253.0,554.0>--<253.0,554.0>> -> L<<253.0,554.0>--<367.0,553.0>>

	* uni2082 (U+2082): L<<87.0,554.0>--<253.0,554.0>> -> L<<253.0,554.0>--<253.0,554.0>>

	* uniA727 (U+A727): L<<463.0,200.0>--<463.0,0.0>> -> L<<463.0,0.0>--<462.0,-63.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eight (U+0038): L<<224.0,-1.0>--<224.0,-1.0>>/L<<224.0,-1.0>--<65.0,0.0>> = 0.36034606338677005

	* hookabovecomb (U+0309): B<<64.0,601.5>-<43.0,614.0>-<19.0,619.0>>/L<<19.0,619.0>--<150.0,619.0>> = 11.768288932020628

	* uni1EA2 (U+1EA2): B<<199.0,778.5>-<178.0,791.0>-<154.0,796.0>>/L<<154.0,796.0>--<285.0,796.0>> = 11.768288932020628

	* uni1EA3 (U+1EA3): B<<157.0,624.5>-<136.0,637.0>-<112.0,642.0>>/L<<112.0,642.0>--<243.0,642.0>> = 11.768288932020628

	* uni1EA8 (U+1EA8): B<<199.0,932.5>-<178.0,945.0>-<154.0,950.0>>/L<<154.0,950.0>--<285.0,950.0>> = 11.768288932020628

	* uni1EA9 (U+1EA9): B<<157.0,778.5>-<136.0,791.0>-<112.0,796.0>>/L<<112.0,796.0>--<243.0,796.0>> = 11.768288932020628

	* uni1EB2 (U+1EB2): B<<188.0,926.5>-<167.0,939.0>-<143.0,944.0>>/L<<143.0,944.0>--<279.0,944.0>> = 11.768288932020628

	* uni1EB3 (U+1EB3): B<<146.0,772.5>-<125.0,785.0>-<101.0,790.0>>/L<<101.0,790.0>--<237.0,790.0>> = 11.768288932020628

	* uni1EBA (U+1EBA): B<<154.0,778.5>-<133.0,791.0>-<109.0,796.0>>/L<<109.0,796.0>--<240.0,796.0>> = 11.768288932020628

	* uni1EBB (U+1EBB): B<<180.0,624.5>-<159.0,637.0>-<135.0,642.0>>/L<<135.0,642.0>--<266.0,642.0>> = 11.768288932020628

	* uni1EC2 (U+1EC2): B<<154.0,932.5>-<133.0,945.0>-<109.0,950.0>>/L<<109.0,950.0>--<240.0,950.0>> = 11.768288932020628

	* uni1EC3 (U+1EC3): B<<180.0,778.5>-<159.0,791.0>-<135.0,796.0>>/L<<135.0,796.0>--<266.0,796.0>> = 11.768288932020628

	* uni1EC8 (U+1EC8): B<<74.0,778.5>-<53.0,791.0>-<29.0,796.0>>/L<<29.0,796.0>--<160.0,796.0>> = 11.768288932020628

	* uni1EC9 (U+1EC9): B<<54.0,624.5>-<33.0,637.0>-<9.0,642.0>>/L<<9.0,642.0>--<140.0,642.0>> = 11.768288932020628

	* uni1ECE (U+1ECE): B<<204.0,778.5>-<183.0,791.0>-<159.0,796.0>>/L<<159.0,796.0>--<290.0,796.0>> = 11.768288932020628

	* uni1ECF (U+1ECF): B<<200.0,624.5>-<179.0,637.0>-<155.0,642.0>>/L<<155.0,642.0>--<286.0,642.0>> = 11.768288932020628

	* uni1ED4 (U+1ED4): B<<204.0,932.5>-<183.0,945.0>-<159.0,950.0>>/L<<159.0,950.0>--<290.0,950.0>> = 11.768288932020628

	* uni1ED5 (U+1ED5): B<<200.0,778.5>-<179.0,791.0>-<155.0,796.0>>/L<<155.0,796.0>--<286.0,796.0>> = 11.768288932020628

	* uni1EDE (U+1EDE): B<<204.0,778.5>-<183.0,791.0>-<159.0,796.0>>/L<<159.0,796.0>--<290.0,796.0>> = 11.768288932020628

	* uni1EDF (U+1EDF): B<<188.0,624.5>-<167.0,637.0>-<143.0,642.0>>/L<<143.0,642.0>--<274.0,642.0>> = 11.768288932020628

	* uni1EE6 (U+1EE6): B<<201.0,778.5>-<180.0,791.0>-<156.0,796.0>>/L<<156.0,796.0>--<287.0,796.0>> = 11.768288932020628

	* uni1EE7 (U+1EE7): B<<184.0,624.5>-<163.0,637.0>-<139.0,642.0>>/L<<139.0,642.0>--<270.0,642.0>> = 11.768288932020628

	* uni1EEC (U+1EEC): B<<201.0,778.5>-<180.0,791.0>-<156.0,796.0>>/L<<156.0,796.0>--<287.0,796.0>> = 11.768288932020628

	* uni1EED (U+1EED): B<<184.0,624.5>-<163.0,637.0>-<139.0,642.0>>/L<<139.0,642.0>--<270.0,642.0>> = 11.768288932020628

	* uni1EF6 (U+1EF6): B<<174.0,778.5>-<153.0,791.0>-<129.0,796.0>>/L<<129.0,796.0>--<260.0,796.0>> = 11.768288932020628

	* uni1EF7 (U+1EF7): B<<312.0,624.5>-<291.0,637.0>-<267.0,642.0>>/L<<267.0,642.0>--<398.0,642.0>> = 11.768288932020628

	* uni2078 (U+2078): L<<224.0,-1.0>--<224.0,-1.0>>/L<<224.0,-1.0>--<65.0,0.0>> = 0.36034606338677005

	* uni2088 (U+2088): L<<224.0,-1.0>--<224.0,-1.0>>/L<<224.0,-1.0>--<65.0,0.0>> = 0.36034606338677005 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* ampersand (U+0026): L<<405.0,282.0>--<552.0,281.0>>

	* arrowboth (U+2194): L<<334.0,362.0>--<532.0,363.0>>

	* arrowboth (U+2194): L<<507.0,222.0>--<279.0,221.0>>

	* arrowdown (U+2193): L<<239.0,318.0>--<240.0,546.0>>

	* arrowdown (U+2193): L<<380.0,546.0>--<379.0,319.0>>

	* arrowleft (U+2190): L<<280.0,370.0>--<507.0,371.0>>

	* arrowleft (U+2190): L<<507.0,231.0>--<279.0,230.0>>

	* arrowright (U+2192): L<<267.0,232.0>--<40.0,231.0>>

	* arrowright (U+2192): L<<40.0,371.0>--<268.0,372.0>>

	* arrowup (U+2191): L<<240.0,56.0>--<239.0,284.0>>

	* arrowup (U+2191): L<<379.0,283.0>--<380.0,56.0>>

	* arrowupdn (U+2195): L<<216.0,190.0>--<215.0,418.0>>

	* arrowupdn (U+2195): L<<356.0,363.0>--<357.0,165.0>>

	* eight (U+0038): L<<224.0,-1.0>--<65.0,0.0>>

	* filledbox (U+25A0): L<<20.0,65.0>--<18.0,619.0>>

	* filledbox (U+25A0): L<<570.0,619.0>--<572.0,65.0>>

	* sterling (U+00A3): L<<174.0,554.0>--<381.0,553.0>>

	* uni018F (U+018F): L<<218.0,408.0>--<38.0,409.0>>

	* uni01A5 (U+01A5): L<<30.0,-154.0>--<31.0,387.0>>

	* uni01A9 (U+01A9): L<<353.0,554.0>--<352.0,436.0>>

	* uni02B7 (U+02B7): L<<624.0,-1.0>--<47.0,0.0>>

	* uni1E87 (U+1E87): L<<624.0,-1.0>--<47.0,0.0>>

	* uni1E89 (U+1E89): L<<624.0,-1.0>--<47.0,0.0>>

	* uni1E8B (U+1E8B): L<<165.0,0.0>--<-1.0,-1.0>>

	* uni1E8B (U+1E8B): L<<270.0,400.0>--<434.0,399.0>>

	* uni1E8D (U+1E8D): L<<165.0,0.0>--<-1.0,-1.0>>

	* uni1E8D (U+1E8D): L<<270.0,400.0>--<434.0,399.0>>

	* uni2078 (U+2078): L<<224.0,-1.0>--<65.0,0.0>>

	* uni2088 (U+2088): L<<224.0,-1.0>--<65.0,0.0>>

	* uni25A1 (U+25A1): L<<20.0,65.0>--<18.0,619.0>>

	* uni25A1 (U+25A1): L<<511.0,126.0>--<510.0,558.0>>

	* uni25A1 (U+25A1): L<<570.0,619.0>--<572.0,65.0>>

	* uni25A1 (U+25A1): L<<79.0,558.0>--<80.0,126.0>>

	* uni25AA (U+25AA): L<<340.0,366.0>--<341.0,65.0>>

	* uni25AA (U+25AA): L<<41.0,65.0>--<40.0,366.0>>

	* uni25AB (U+25AB): L<<362.0,388.0>--<363.0,65.0>>

	* uni25AB (U+25AB): L<<41.0,65.0>--<40.0,388.0>>

	* uniA7B3 (U+A7B3): L<<423.0,315.0>--<284.0,314.0>>

	* uniA7B3 (U+A7B3): L<<63.0,261.0>--<187.0,260.0>>

	* w (U+0077): L<<624.0,-1.0>--<47.0,0.0>>

	* wacute (U+1E83): L<<624.0,-1.0>--<47.0,0.0>>

	* wcircumflex (U+0175): L<<624.0,-1.0>--<47.0,0.0>>

	* wdieresis (U+1E85): L<<624.0,-1.0>--<47.0,0.0>>

	* wgrave (U+1E81): L<<624.0,-1.0>--<47.0,0.0>>

	* x (U+0078): L<<165.0,0.0>--<-1.0,-1.0>>

	* x (U+0078): L<<270.0,400.0>--<434.0,399.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Ebira (Latn, 2,200,000 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Dan (Latn, 1,099,244 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 15 | 122 | 7 | 102 | 0 |
| 0% | 2% | 6% | 48% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**