## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[22] Festac23-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Afrotype. All rights reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 878, but got 830 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.1, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
* 🔥 **FAIL** name id 257 missing from name table
* 🔥 **FAIL** name id 258 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: plus	Expected: 1

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: at	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: currency	Expected: 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: brokenbar	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: multiply	Expected: 1

	- Glyph name: germandbls	Expected: 1

	- Glyph name: eth	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: thorn	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Eng	Expected: 1

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: notequal	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Eng	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: approxequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: at	Expected: 2

	- Glyph name: brokenbar	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: currency	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: notequal	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: percent	Expected: 5

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plus	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: section	Expected: 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: summation	Expected: 1

	- Glyph name: thorn	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 1	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 1	Expected: 3 or 4

	- Glyph name: gdotaccent	Contours detected: 1	Expected: 3 or 4

	- Glyph name: uni0123	Contours detected: 1	Expected: 3 or 4

	- Glyph name: oe	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01E2	Contours detected: 1	Expected: 3

	- Glyph name: gcaron	Contours detected: 1	Expected: 3 or 4

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01EF	Contours detected: 1	Expected: 2

	- Glyph name: uni01F5	Contours detected: 1	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 1	Expected: 4

	- Glyph name: uni0202	Contours detected: 4	Expected: 3

	- Glyph name: uni0203	Contours detected: 4	Expected: 3

	- Glyph name: uni0206	Contours detected: 3	Expected: 2

	- Glyph name: uni0207	Contours detected: 4	Expected: 3

	- Glyph name: uni020A	Contours detected: 3	Expected: 2

	- Glyph name: uni020B	Contours detected: 3	Expected: 2

	- Glyph name: uni020E	Contours detected: 4	Expected: 3

	- Glyph name: uni020F	Contours detected: 4	Expected: 3

	- Glyph name: uni0212	Contours detected: 4	Expected: 3

	- Glyph name: uni0213	Contours detected: 3	Expected: 2

	- Glyph name: uni0216	Contours detected: 3	Expected: 2

	- Glyph name: uni0217	Contours detected: 3	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni0311	Contours detected: 2	Expected: 1

	- Glyph name: uni1E03	Contours detected: 1	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0B	Contours detected: 1	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 1	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 1	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E21	Contours detected: 1	Expected: 3 or 4

	- Glyph name: uni1E57	Contours detected: 1	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Oslashacute	Contours detected: 1	Expected: 4

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: asterisk	Contours detected: 5	Expected: 1 or 4

	- Glyph name: dcaron	Contours detected: 1	Expected: 3

	- Glyph name: dcroat	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 1	Expected: 3 or 4

	- Glyph name: gcaron	Contours detected: 1	Expected: 3 or 4

	- Glyph name: gdotaccent	Contours detected: 1	Expected: 3 or 4

	- Glyph name: oe	Contours detected: 2	Expected: 3

	- Glyph name: uni0123	Contours detected: 1	Expected: 3 or 4

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01E2	Contours detected: 1	Expected: 3

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni01EF	Contours detected: 1	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni0311	Contours detected: 2	Expected: 1

	- Glyph name: uni1E03	Contours detected: 1	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0B	Contours detected: 1	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 1	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E21	Contours detected: 1	Expected: 3 or 4

	- Glyph name: uni1E57	Contours detected: 1	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0}
	* {'glyph': 'quotedblleft', 'component': 'quoteleft', 'x': 0, 'y': 0} and {'glyph': 'guillemotright', 'component': 'guilsinglright', 'x': 0, 'y': 0} [code: found-duplicates]
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
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
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
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, tai-le, syriac, math, old-permic, malayalam, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, cherokee, syriac, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- t + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- D.001

	- asterisk_node

	- d.001

	- z.ss01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** dcaron is composed of a single component and therefore could not be checked. Please check manually. [code: single-component]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* zero (U+0030) contains a short segment L<<238.0,554.0>--<238.0,554.0>>

	* zero (U+0030) contains a short segment L<<274.0,554.0>--<274.0,554.0>>

	* seven (U+0037) contains a short segment L<<215.0,554.0>--<215.0,554.0>>

	* eight (U+0038) contains a short segment L<<230.0,-1.0>--<230.0,-1.0>>

	* eight (U+0038) contains a short segment B<<177.5,261.5>-<172.0,265.0>-<167.0,268.0>>

	* X (U+0058) contains a short segment L<<356.0,306.0>--<363.0,301.0>>

	* x (U+0078) contains a short segment B<<290.0,0.0>-<290.0,0.0>-<290.5,5.5>>

	* uni01AD (U+01AD) contains a short segment L<<235.0,280.0>--<235.0,270.0>>

	* uni01B8 (U+01B8) contains a short segment L<<315.0,322.0>--<314.0,322.0>>

	* uni0266 (U+0266) contains a short segment L<<29.0,385.0>--<30.0,385.0>>

	* uni0266 (U+0266) contains a short segment L<<30.0,385.0>--<30.0,387.0>>

	* uni1E8A (U+1E8A) contains a short segment L<<356.0,306.0>--<363.0,301.0>>

	* uni1E8C (U+1E8C) contains a short segment L<<356.0,306.0>--<363.0,301.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* eng (U+014B): L<<456.0,200.0>--<456.0,0.0>> -> L<<456.0,0.0>--<455.0,-63.0>>

	* g (U+0067): L<<270.0,36.0>--<271.0,54.0>> -> L<<271.0,54.0>--<271.0,366.0>>

	* seven (U+0037): L<<10.0,553.0>--<215.0,554.0>> -> L<<215.0,554.0>--<215.0,554.0>>

	* seven (U+0037): L<<215.0,554.0>--<215.0,554.0>> -> L<<215.0,554.0>--<385.0,554.0>>

	* uni0199 (U+0199): L<<30.0,0.0>--<30.0,324.0>> -> L<<30.0,324.0>--<31.0,387.0>>

	* uni0233 (U+0233): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* uni1E8F (U+1E8F): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* uni1EF9 (U+1EF9): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* uniA727 (U+A727): L<<456.0,200.0>--<456.0,0.0>> -> L<<456.0,0.0>--<455.0,-63.0>>

	* y (U+0079): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* yacute (U+00FD): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* ycircumflex (U+0177): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* ydieresis (U+00FF): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* ygrave (U+1EF3): L<<275.0,31.0>--<276.0,52.0>> -> L<<276.0,52.0>--<276.0,400.0>>

	* zero (U+0030): L<<238.0,554.0>--<238.0,554.0>> -> L<<238.0,554.0>--<256.0,554.0>>

	* zero (U+0030): L<<238.0,554.0>--<256.0,554.0>> -> L<<256.0,554.0>--<274.0,554.0>>

	* zero (U+0030): L<<256.0,554.0>--<274.0,554.0>> -> L<<274.0,554.0>--<274.0,554.0>>

	* zero (U+0030): L<<274.0,554.0>--<274.0,554.0>> -> L<<274.0,554.0>--<432.0,553.0>>

	* zero (U+0030): L<<80.0,553.0>--<238.0,554.0>> -> L<<238.0,554.0>--<238.0,554.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Z (U+005A): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923

	* Zacute (U+0179): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923

	* Zcaron (U+017D): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923

	* Zdotaccent (U+017B): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923

	* Zmacronbelow (U+1E94): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923

	* eight (U+0038): L<<230.0,-1.0>--<230.0,-1.0>>/L<<230.0,-1.0>--<71.0,0.0>> = 0.36034606338677005

	* uni0190 (U+0190): L<<137.0,554.0>--<359.0,554.0>>/B<<359.0,554.0>-<317.0,550.0>-<284.5,527.0>> = 5.4403320310054815

	* uni01B5 (U+01B5): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923

	* uni1E90 (U+1E90): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923

	* uni1E92 (U+1E92): B<<227.0,142.0>-<197.0,120.0>-<158.0,113.0>>/L<<158.0,113.0>--<442.0,118.0>> = 9.166886532382923 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<417.0,-1.0>--<40.0,-2.0>>

	* Bmacronbelow (U+1E06): L<<417.0,-1.0>--<40.0,-2.0>>

	* C (U+0043): L<<129.0,554.0>--<354.0,553.0>>

	* C (U+0043): L<<354.0,-1.0>--<129.0,0.0>>

	* Cacute (U+0106): L<<129.0,554.0>--<354.0,553.0>>

	* Cacute (U+0106): L<<354.0,-1.0>--<129.0,0.0>>

	* Ccaron (U+010C): L<<129.0,554.0>--<354.0,553.0>>

	* Ccaron (U+010C): L<<354.0,-1.0>--<129.0,0.0>>

	* Ccedilla (U+00C7): L<<129.0,554.0>--<354.0,553.0>>

	* Ccedilla (U+00C7): L<<354.0,-1.0>--<129.0,0.0>>

	* Cdotaccent (U+010A): L<<129.0,554.0>--<354.0,553.0>>

	* Cdotaccent (U+010A): L<<354.0,-1.0>--<129.0,0.0>>

	* E (U+0045): L<<386.0,0.0>--<40.0,-2.0>>

	* E (U+0045): L<<40.0,552.0>--<376.0,554.0>>

	* Eacute (U+00C9): L<<386.0,0.0>--<40.0,-2.0>>

	* Eacute (U+00C9): L<<40.0,552.0>--<376.0,554.0>>

	* Ecaron (U+011A): L<<386.0,0.0>--<40.0,-2.0>>

	* Ecaron (U+011A): L<<40.0,552.0>--<376.0,554.0>>

	* Ecircumflex (U+00CA): L<<386.0,0.0>--<40.0,-2.0>>

	* Ecircumflex (U+00CA): L<<40.0,552.0>--<376.0,554.0>>

	* Edieresis (U+00CB): L<<386.0,0.0>--<40.0,-2.0>>

	* Edieresis (U+00CB): L<<40.0,552.0>--<376.0,554.0>>

	* Edotaccent (U+0116): L<<386.0,0.0>--<40.0,-2.0>>

	* Edotaccent (U+0116): L<<40.0,552.0>--<376.0,554.0>>

	* Egrave (U+00C8): L<<386.0,0.0>--<40.0,-2.0>>

	* Egrave (U+00C8): L<<40.0,552.0>--<376.0,554.0>>

	* Emacron (U+0112): L<<386.0,0.0>--<40.0,-2.0>>

	* Emacron (U+0112): L<<40.0,552.0>--<376.0,554.0>>

	* Eogonek (U+0118): L<<386.0,0.0>--<40.0,-2.0>>

	* Eogonek (U+0118): L<<40.0,552.0>--<376.0,554.0>>

	* G (U+0047): L<<323.0,34.0>--<324.0,288.0>>

	* G (U+0047): L<<493.0,288.0>--<492.0,-74.0>>

	* Gbreve (U+011E): L<<323.0,34.0>--<324.0,288.0>>

	* Gbreve (U+011E): L<<493.0,288.0>--<492.0,-74.0>>

	* Gcaron (U+01E6): L<<323.0,34.0>--<324.0,288.0>>

	* Gcaron (U+01E6): L<<493.0,288.0>--<492.0,-74.0>>

	* Gdotaccent (U+0120): L<<323.0,34.0>--<324.0,288.0>>

	* Gdotaccent (U+0120): L<<493.0,288.0>--<492.0,-74.0>>

	* Q (U+0051): L<<428.0,-127.0>--<215.0,-126.0>>

	* R (U+0052): L<<209.0,517.0>--<210.0,306.0>>

	* Racute (U+0154): L<<209.0,517.0>--<210.0,306.0>>

	* Rcaron (U+0158): L<<209.0,517.0>--<210.0,306.0>>

	* Rmacronbelow (U+1E5E): L<<209.0,517.0>--<210.0,306.0>>

	* W (U+0057): L<<304.0,199.0>--<301.0,554.0>>

	* W (U+0057): L<<474.0,554.0>--<475.0,199.0>>

	* Wacute (U+1E82): L<<304.0,199.0>--<301.0,554.0>>

	* Wacute (U+1E82): L<<474.0,554.0>--<475.0,199.0>>

	* Wcircumflex (U+0174): L<<304.0,199.0>--<301.0,554.0>>

	* Wcircumflex (U+0174): L<<474.0,554.0>--<475.0,199.0>>

	* Wdieresis (U+1E84): L<<304.0,199.0>--<301.0,554.0>>

	* Wdieresis (U+1E84): L<<474.0,554.0>--<475.0,199.0>>

	* Wgrave (U+1E80): L<<304.0,199.0>--<301.0,554.0>>

	* Wgrave (U+1E80): L<<474.0,554.0>--<475.0,199.0>>

	* Y (U+0059): L<<256.0,204.0>--<91.0,203.0>>

	* Y (U+0059): L<<359.0,-1.0>--<151.0,0.0>>

	* Yacute (U+00DD): L<<256.0,204.0>--<91.0,203.0>>

	* Yacute (U+00DD): L<<359.0,-1.0>--<151.0,0.0>>

	* Ycircumflex (U+0176): L<<256.0,204.0>--<91.0,203.0>>

	* Ycircumflex (U+0176): L<<359.0,-1.0>--<151.0,0.0>>

	* Ydieresis (U+0178): L<<256.0,204.0>--<91.0,203.0>>

	* Ydieresis (U+0178): L<<359.0,-1.0>--<151.0,0.0>>

	* Ygrave (U+1EF2): L<<256.0,204.0>--<91.0,203.0>>

	* Ygrave (U+1EF2): L<<359.0,-1.0>--<151.0,0.0>>

	* Z (U+005A): L<<442.0,-2.0>--<14.0,0.0>>

	* Zacute (U+0179): L<<442.0,-2.0>--<14.0,0.0>>

	* Zcaron (U+017D): L<<442.0,-2.0>--<14.0,0.0>>

	* Zdotaccent (U+017B): L<<442.0,-2.0>--<14.0,0.0>>

	* Zmacronbelow (U+1E94): L<<442.0,-2.0>--<14.0,0.0>>

	* eight (U+0038): L<<230.0,-1.0>--<71.0,0.0>>

	* ij (U+0133): L<<440.0,400.0>--<439.0,-7.0>>

	* j (U+006A): L<<203.0,400.0>--<202.0,-7.0>>

	* seven (U+0037): L<<10.0,553.0>--<215.0,554.0>>

	* seven (U+0037): L<<226.0,434.0>--<10.0,433.0>>

	* seven (U+0037): L<<282.0,0.0>--<82.0,-1.0>>

	* uni0122 (U+0122): L<<323.0,34.0>--<324.0,288.0>>

	* uni0122 (U+0122): L<<493.0,288.0>--<492.0,-74.0>>

	* uni0156 (U+0156): L<<209.0,517.0>--<210.0,306.0>>

	* uni018F (U+018F): L<<222.0,408.0>--<42.0,409.0>>

	* uni01A5 (U+01A5): L<<30.0,-154.0>--<31.0,387.0>>

	* uni01A9 (U+01A9): L<<353.0,554.0>--<352.0,436.0>>

	* uni01B5 (U+01B5): L<<442.0,-2.0>--<14.0,0.0>>

	* uni01F4 (U+01F4): L<<323.0,34.0>--<324.0,288.0>>

	* uni01F4 (U+01F4): L<<493.0,288.0>--<492.0,-74.0>>

	* uni0204 (U+0204): L<<386.0,0.0>--<40.0,-2.0>>

	* uni0204 (U+0204): L<<40.0,552.0>--<376.0,554.0>>

	* uni0206 (U+0206): L<<386.0,0.0>--<40.0,-2.0>>

	* uni0206 (U+0206): L<<40.0,552.0>--<376.0,554.0>>

	* uni0210 (U+0210): L<<209.0,517.0>--<210.0,306.0>>

	* uni0212 (U+0212): L<<209.0,517.0>--<210.0,306.0>>

	* uni0228 (U+0228): L<<386.0,0.0>--<40.0,-2.0>>

	* uni0228 (U+0228): L<<40.0,552.0>--<376.0,554.0>>

	* uni0232 (U+0232): L<<256.0,204.0>--<91.0,203.0>>

	* uni0232 (U+0232): L<<359.0,-1.0>--<151.0,0.0>>

	* uni0237 (U+0237): L<<252.0,400.0>--<251.0,-27.0>>

	* uni023B (U+023B): L<<129.0,554.0>--<354.0,553.0>>

	* uni023B (U+023B): L<<354.0,-1.0>--<129.0,0.0>>

	* uni0243 (U+0243): L<<417.0,-1.0>--<40.0,-2.0>>

	* uni0246 (U+0246): L<<386.0,0.0>--<40.0,-2.0>>

	* uni0246 (U+0246): L<<40.0,552.0>--<376.0,554.0>>

	* uni024C (U+024C): L<<209.0,517.0>--<210.0,306.0>>

	* uni024E (U+024E): L<<256.0,204.0>--<91.0,203.0>>

	* uni024E (U+024E): L<<359.0,-1.0>--<151.0,0.0>>

	* uni1E02 (U+1E02): L<<417.0,-1.0>--<40.0,-2.0>>

	* uni1E04 (U+1E04): L<<417.0,-1.0>--<40.0,-2.0>>

	* uni1E08 (U+1E08): L<<129.0,554.0>--<354.0,553.0>>

	* uni1E08 (U+1E08): L<<354.0,-1.0>--<129.0,0.0>>

	* uni1E14 (U+1E14): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1E14 (U+1E14): L<<40.0,552.0>--<376.0,554.0>>

	* uni1E16 (U+1E16): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1E16 (U+1E16): L<<40.0,552.0>--<376.0,554.0>>

	* uni1E18 (U+1E18): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1E18 (U+1E18): L<<40.0,552.0>--<376.0,554.0>>

	* uni1E1A (U+1E1A): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1E1A (U+1E1A): L<<40.0,552.0>--<376.0,554.0>>

	* uni1E1C (U+1E1C): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1E1C (U+1E1C): L<<40.0,552.0>--<376.0,554.0>>

	* uni1E20 (U+1E20): L<<323.0,34.0>--<324.0,288.0>>

	* uni1E20 (U+1E20): L<<493.0,288.0>--<492.0,-74.0>>

	* uni1E58 (U+1E58): L<<209.0,517.0>--<210.0,306.0>>

	* uni1E5A (U+1E5A): L<<209.0,517.0>--<210.0,306.0>>

	* uni1E5C (U+1E5C): L<<209.0,517.0>--<210.0,306.0>>

	* uni1E86 (U+1E86): L<<304.0,199.0>--<301.0,554.0>>

	* uni1E86 (U+1E86): L<<474.0,554.0>--<475.0,199.0>>

	* uni1E88 (U+1E88): L<<304.0,199.0>--<301.0,554.0>>

	* uni1E88 (U+1E88): L<<474.0,554.0>--<475.0,199.0>>

	* uni1E8E (U+1E8E): L<<256.0,204.0>--<91.0,203.0>>

	* uni1E8E (U+1E8E): L<<359.0,-1.0>--<151.0,0.0>>

	* uni1E90 (U+1E90): L<<442.0,-2.0>--<14.0,0.0>>

	* uni1E92 (U+1E92): L<<442.0,-2.0>--<14.0,0.0>>

	* uni1EB8 (U+1EB8): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1EB8 (U+1EB8): L<<40.0,552.0>--<376.0,554.0>>

	* uni1EBC (U+1EBC): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1EBC (U+1EBC): L<<40.0,552.0>--<376.0,554.0>>

	* uni1EC6 (U+1EC6): L<<386.0,0.0>--<40.0,-2.0>>

	* uni1EC6 (U+1EC6): L<<40.0,552.0>--<376.0,554.0>>

	* uni1EF8 (U+1EF8): L<<256.0,204.0>--<91.0,203.0>>

	* uni1EF8 (U+1EF8): L<<359.0,-1.0>--<151.0,0.0>>

	* zero (U+0030): L<<256.0,0.0>--<80.0,-1.0>>

	* zero (U+0030): L<<274.0,554.0>--<432.0,553.0>>

	* zero (U+0030): L<<432.0,-1.0>--<256.0,0.0>>

	* zero (U+0030): L<<80.0,553.0>--<238.0,554.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅ i̧᷆ i̧᷇ i̩᷄ i̩᷅ i̩᷆ i̩᷇ i̭᷄ i̭᷅

Your font fully covers the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Dan (Latn, 1,099,244 speakers), Lugbara (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Nateni (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Basaa (Latn, 332,940 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Kom (Latn, 360,685 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 14 | 122 | 7 | 101 | 0 |
| 0% | 3% | 6% | 48% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
