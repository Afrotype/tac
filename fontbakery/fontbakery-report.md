## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[23] Festac23-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 💔 **ERROR** Failed with TypeError: 'NoneType' object is not subscriptable
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Afrotype. All rights reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "356" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Festac23-Bold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (574) and hhea ascent (930) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.1, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: currency	Expected: 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: brokenbar	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: cedilla	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: germandbls	Expected: 1

	- Glyph name: eth	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: thorn	Expected: 2

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: trademark	Expected: 2

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

	- Glyph name: AE	Expected: 2

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: approxequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: bar	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: brokenbar	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: currency	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: notequal	Expected: 1

	- Glyph name: ogonek	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: percent	Expected: 5

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plus	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: ring	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: summation	Expected: 1

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

	- Glyph name: trademark	Expected: 2

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

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

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01E2	Contours detected: 1	Expected: 3

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 1	Expected: 4

	- Glyph name: oslashacute	Contours detected: 1	Expected: 4

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

	- Glyph name: uni0306	Contours detected: 2	Expected: 1

	- Glyph name: uni0311	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 2	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E3F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E41	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 3	Expected: 2

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Oslashacute	Contours detected: 1	Expected: 4

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: oslashacute	Contours detected: 1	Expected: 4

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: uni01E2	Contours detected: 1	Expected: 3

	- Glyph name: uni01E3	Contours detected: 5	Expected: 4

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0306	Contours detected: 2	Expected: 1

	- Glyph name: uni0311	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 2	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E3F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E41	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} [code: found-duplicates]
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


	- 0x032E (COMBINING BREVE BELOW)


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
 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, math, canadian-aboriginal, tai-le, coptic, tifinagh, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
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
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, tifinagh, syriac, gothic, caucasian-albanian
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- A.ss01

	- A.ss02

	- F.ss10

	- M.ss01

	- N.ss01

	- N.ss02

	- Q.ss01

	- R.ss01

	- S.ss01

	- V.ss01

	- X.ss02

	- eight.osf

	- f.ss01

	- five.osf

	- five.ss01

	- four.osf

	- i.loclTRK

	- j.ss01

	- nine.osf

	- one.osf

	- one.ss01

	- one.ss02

	- one.ss03

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- seven.osf

	- six.osf

	- three.osf

	- two.osf

	- two.ss01

	- u.ss01

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03040300

	- uni03040301

	- v.ss01

	- w.ss01

	- x.ss01

	- z.ss01

	- zero.osf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=56.0,Y=553.0 (should be at cap-height 554?)

	* three (U+0033): X=408.0,Y=553.0 (should be at cap-height 554?)

	* four (U+0034): X=90.0,Y=552.0 (should be at cap-height 554?)

	* four (U+0034): X=304.0,Y=552.0 (should be at cap-height 554?)

	* eight (U+0038): X=67.0,Y=-1.0 (should be at baseline 0?)

	* eight (U+0038): X=67.0,Y=552.0 (should be at cap-height 554?)

	* eight (U+0038): X=417.0,Y=552.0 (should be at cap-height 554?)

	* eight (U+0038): X=417.0,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=24.0,Y=1.0 (should be at baseline 0?)

	* B (U+0042): X=24.0,Y=555.0 (should be at cap-height 554?)

	* B (U+0042): X=363.0,Y=555.0 (should be at cap-height 554?)

	* B (U+0042): X=365.0,Y=1.0 (should be at baseline 0?)

	* uni1E02 (U+1E02): X=24.0,Y=1.0 (should be at baseline 0?)

	* uni1E02 (U+1E02): X=24.0,Y=555.0 (should be at cap-height 554?)

	* uni1E02 (U+1E02): X=363.0,Y=555.0 (should be at cap-height 554?)

	* uni1E02 (U+1E02): X=365.0,Y=1.0 (should be at baseline 0?)

	* uni1E04 (U+1E04): X=24.0,Y=1.0 (should be at baseline 0?)

	* uni1E04 (U+1E04): X=24.0,Y=555.0 (should be at cap-height 554?)

	* uni1E04 (U+1E04): X=363.0,Y=555.0 (should be at cap-height 554?)

	* uni1E04 (U+1E04): X=365.0,Y=1.0 (should be at baseline 0?)

	* Bmacronbelow (U+1E06): X=24.0,Y=1.0 (should be at baseline 0?)

	* Bmacronbelow (U+1E06): X=24.0,Y=555.0 (should be at cap-height 554?)

	* Bmacronbelow (U+1E06): X=363.0,Y=555.0 (should be at cap-height 554?)

	* Bmacronbelow (U+1E06): X=365.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* five (U+0035) contains a short segment B<<410.5,15.0>-<404.0,0.0>-<404.0,0.0>>

	* W (U+0057) contains a short segment B<<292.5,530.0>-<292.0,554.0>-<292.0,554.0>>

	* W (U+0057) contains a short segment B<<558.0,531.5>-<559.0,554.0>-<559.0,554.0>>

	* W (U+0057) contains a short segment B<<641.5,21.0>-<629.0,0.0>-<629.0,0.0>>

	* Z (U+005A) contains a short segment L<<24.0,120.0>--<24.0,120.0>>

	* Z (U+005A) contains a short segment L<<458.0,434.0>--<458.0,434.0>>

	* w (U+0077) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* Wcircumflex (U+0174) contains a short segment B<<292.5,530.0>-<292.0,554.0>-<292.0,554.0>>

	* Wcircumflex (U+0174) contains a short segment B<<558.0,531.5>-<559.0,554.0>-<559.0,554.0>>

	* Wcircumflex (U+0174) contains a short segment B<<641.5,21.0>-<629.0,0.0>-<629.0,0.0>>

	* wcircumflex (U+0175) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* Zacute (U+0179) contains a short segment L<<24.0,120.0>--<24.0,120.0>>

	* Zacute (U+0179) contains a short segment L<<458.0,434.0>--<458.0,434.0>>

	* Zdotaccent (U+017B) contains a short segment L<<24.0,120.0>--<24.0,120.0>>

	* Zdotaccent (U+017B) contains a short segment L<<458.0,434.0>--<458.0,434.0>>

	* Zcaron (U+017D) contains a short segment L<<24.0,120.0>--<24.0,120.0>>

	* Zcaron (U+017D) contains a short segment L<<458.0,434.0>--<458.0,434.0>>

	* uni02B7 (U+02B7) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* Wgrave (U+1E80) contains a short segment B<<292.5,530.0>-<292.0,554.0>-<292.0,554.0>>

	* Wgrave (U+1E80) contains a short segment B<<558.0,531.5>-<559.0,554.0>-<559.0,554.0>>

	* Wgrave (U+1E80) contains a short segment B<<641.5,21.0>-<629.0,0.0>-<629.0,0.0>>

	* wgrave (U+1E81) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* Wacute (U+1E82) contains a short segment B<<292.5,530.0>-<292.0,554.0>-<292.0,554.0>>

	* Wacute (U+1E82) contains a short segment B<<558.0,531.5>-<559.0,554.0>-<559.0,554.0>>

	* Wacute (U+1E82) contains a short segment B<<641.5,21.0>-<629.0,0.0>-<629.0,0.0>>

	* wacute (U+1E83) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* Wdieresis (U+1E84) contains a short segment B<<292.5,530.0>-<292.0,554.0>-<292.0,554.0>>

	* Wdieresis (U+1E84) contains a short segment B<<558.0,531.5>-<559.0,554.0>-<559.0,554.0>>

	* Wdieresis (U+1E84) contains a short segment B<<641.5,21.0>-<629.0,0.0>-<629.0,0.0>>

	* wdieresis (U+1E85) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* uni1E86 (U+1E86) contains a short segment B<<292.5,530.0>-<292.0,554.0>-<292.0,554.0>>

	* uni1E86 (U+1E86) contains a short segment B<<558.0,531.5>-<559.0,554.0>-<559.0,554.0>>

	* uni1E86 (U+1E86) contains a short segment B<<641.5,21.0>-<629.0,0.0>-<629.0,0.0>>

	* uni1E87 (U+1E87) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* uni1E88 (U+1E88) contains a short segment B<<292.5,530.0>-<292.0,554.0>-<292.0,554.0>>

	* uni1E88 (U+1E88) contains a short segment B<<558.0,531.5>-<559.0,554.0>-<559.0,554.0>>

	* uni1E88 (U+1E88) contains a short segment B<<641.5,21.0>-<629.0,0.0>-<629.0,0.0>>

	* uni1E89 (U+1E89) contains a short segment B<<616.5,11.5>-<606.0,0.0>-<606.0,0.0>>

	* uni1E90 (U+1E90) contains a short segment L<<24.0,120.0>--<24.0,120.0>>

	* uni1E90 (U+1E90) contains a short segment L<<458.0,434.0>--<458.0,434.0>>

	* uni1E92 (U+1E92) contains a short segment L<<24.0,120.0>--<24.0,120.0>>

	* uni1E92 (U+1E92) contains a short segment L<<458.0,434.0>--<458.0,434.0>>

	* Zmacronbelow (U+1E94) contains a short segment L<<24.0,120.0>--<24.0,120.0>>

	* Zmacronbelow (U+1E94) contains a short segment L<<458.0,434.0>--<458.0,434.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Y (U+0059): L<<160.0,0.0>--<161.0,257.0>>

	* Y (U+0059): L<<346.0,257.0>--<345.0,0.0>>

	* Yacute (U+00DD): L<<160.0,0.0>--<161.0,257.0>>

	* Yacute (U+00DD): L<<346.0,257.0>--<345.0,0.0>>

	* Ycircumflex (U+0176): L<<160.0,0.0>--<161.0,257.0>>

	* Ycircumflex (U+0176): L<<346.0,257.0>--<345.0,0.0>>

	* Ydieresis (U+0178): L<<160.0,0.0>--<161.0,257.0>>

	* Ydieresis (U+0178): L<<346.0,257.0>--<345.0,0.0>>

	* Ygrave (U+1EF2): L<<160.0,0.0>--<161.0,257.0>>

	* Ygrave (U+1EF2): L<<346.0,257.0>--<345.0,0.0>>

	* l (U+006C): L<<25.0,147.0>--<24.0,574.0>>

	* lacute (U+013A): L<<25.0,147.0>--<24.0,574.0>>

	* lcaron (U+013E): L<<25.0,147.0>--<24.0,574.0>>

	* lmacronbelow (U+1E3B): L<<25.0,147.0>--<24.0,574.0>>

	* uni013C (U+013C): L<<25.0,147.0>--<24.0,574.0>>

	* uni0232 (U+0232): L<<160.0,0.0>--<161.0,257.0>>

	* uni0232 (U+0232): L<<346.0,257.0>--<345.0,0.0>>

	* uni1E37 (U+1E37): L<<25.0,147.0>--<24.0,574.0>>

	* uni1E39 (U+1E39): L<<25.0,147.0>--<24.0,574.0>>

	* uni1E3D (U+1E3D): L<<25.0,147.0>--<24.0,574.0>>

	* uni1E8E (U+1E8E): L<<160.0,0.0>--<161.0,257.0>>

	* uni1E8E (U+1E8E): L<<346.0,257.0>--<345.0,0.0>>

	* uni1EF8 (U+1EF8): L<<160.0,0.0>--<161.0,257.0>>

	* uni1EF8 (U+1EF8): L<<346.0,257.0>--<345.0,0.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i̊ i̋ i̍ i̐ i̓ i᷆ i᷇ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: ĭ i̇ i̒ i᷄ i᷅ ĭ̥ i̥̇ i̥̊ i̥̋ i̥̍ i̥̐ i̥̒ i̥̓ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊

Your font fully covers the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Nateni (Latn, 100,000 speakers), Avokaya (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ebira (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Lithuanian (Latn, 2,357,094 speakers), Igbo (Latn, 27,823,640 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Koonzime (Latn, 40,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dutch (Latn, 31,709,104 speakers), Ejagham (Latn, 120,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | 9 | 13 | 123 | 7 | 99 | 0 |
| 0% | 4% | 5% | 49% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
