## FontBakery report

fontbakery version: 0.11.2

<h2>Experimental checks</h2><p>These won't break the CI job for now, but will become effective after some time if nobody raises any concern.</p><details><summary><b>[1] TacOne-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure the font supports case swapping for all its glyphs. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/case_mapping">com.google.fonts/check/case_mapping</a>)</summary><div>


* 🔥 **FAIL** The following glyphs lack their case-swapping counterparts:

| Glyph present in the font | Missing case-swapping counterpart |
| :--- | :--- |
| U+03BB: GREEK SMALL LETTER LAMDA | U+039B: GREEK CAPITAL LETTER LAMDA |
| U+03C7: GREEK SMALL LETTER CHI | U+03A7: GREEK CAPITAL LETTER CHI |

 [code: missing-case-counterparts]
</div></details><br></div></details><h2>All other checks</h2><details><summary><b>[11] TacOne-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_African glyphset:

| Language | FAIL messages |
| :--- | :--- |
| nus_Latn (Nuer) | Shaper didn't attach uni0331 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni0331 |
|  ^  | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0331 to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni0331 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni0331 to uni025B |
|  ^  | Shaper didn't attach uni0331 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0331 to uni025B |
|  ^  | Shaper didn't attach uni0331 to uni0190 |
|  ^  | Shaper didn't attach uni0331 to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni0331 |
|  ^  | Shaper didn't attach uni0331 to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni0331 |
|  ^  | Shaper didn't attach uni0331 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni0331 |
|  ^  | Shaper didn't attach uni0331 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni0331 |
| nnh_Latn (Ngiemboon) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
| bsq_Latn (Bassa) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| bax_Latn (Bamun, Latin) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni018F |
| ln_Latn (Lingala) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
| tbz_Latn (Ditammari) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| yav_Latn (Yangben) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
| vai_Latn (Vai (Latin)) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| nnw_Latn (Southern Nuni) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
| mcp_Latn (Makaa) | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0327 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0327 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
| nga_Latn (Ngbaka) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni030D to uni025B |
|  ^  | Shaper didn't attach uni030D to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| nmg_Latn (Kwasio) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
| ife_Latn (Ifè) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| bba_Latn (Baatonum) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| sld_Latn (Sissala) | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
| byv_Latn (Medumba) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni2C6D |
|  ^  | Shaper didn't attach uni0302 to uni0251 |
|  ^  | Shaper didn't attach gravecomb to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni2C6D |
|  ^  | Shaper didn't attach uni030C to uni2C6D |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni2C6D |
|  ^  | Shaper didn't attach uni0302 to uni2C6D |
|  ^  | Shaper didn't attach uni030C to uni2C6D |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0251 |
|  ^  | Shaper didn't attach uni0302 to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni0251 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
| lob_Latn (Lobi) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
| ewo_Latn (Ewondo) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
| tik_Latn (Tikar) | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to Eng |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to Eng |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
| dnj_Latn_LR (Dan) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uniA78D |
|  ^  | Shaper didn't attach gravecomb to uniA78D |
|  ^  | Shaper didn't attach tildecomb to uniA78D |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uniA78D |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
| lol_Latn (Mongo) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
| btt_Latn (Bete-Bendi) | Shaper didn't attach uni1DC6 to A |
|  ^  | Shaper didn't attach uni1DC6 to O |
|  ^  | Shaper didn't attach uni1DC6 to E |
|  ^  | Shaper didn't attach uni1DC6 to a |
|  ^  | Shaper didn't attach uni1DC5 to U |
|  ^  | Shaper didn't attach uni1DC5 to A |
|  ^  | Shaper didn't attach uni1DC5 to E |
|  ^  | Shaper didn't attach uni1DC6 to I |
|  ^  | Shaper didn't attach uni1DC6 to e |
|  ^  | Shaper didn't attach uni1DC6 to o |
|  ^  | Shaper didn't attach uni1DC5 to e |
|  ^  | Shaper didn't attach uni1DC6 to u |
|  ^  | Shaper didn't attach uni1DC5 to a |
|  ^  | Shaper didn't attach uni1DC5 to u |
|  ^  | Shaper didn't attach uni1DC5 to o |
|  ^  | Shaper didn't attach uni1DC6 to U |
|  ^  | Shaper didn't attach uni1DC5 to dotlessi |
|  ^  | Shaper didn't attach uni1DC6 to dotlessi |
|  ^  | Shaper didn't attach uni1DC5 to O |
|  ^  | Shaper didn't attach uni1DC5 to I |
|  ^  | Shaper didn't attach uni1DC5 to a |
|  ^  | Shaper didn't attach uni1DC5 to A |
|  ^  | Shaper didn't attach uni1DC6 to a |
|  ^  | Shaper didn't attach uni1DC6 to A |
|  ^  | Shaper didn't attach uni1DC5 to e |
|  ^  | Shaper didn't attach uni1DC5 to E |
|  ^  | Shaper didn't attach uni1DC6 to e |
|  ^  | Shaper didn't attach uni1DC6 to E |
|  ^  | Shaper didn't attach uni1DC5 to dotlessi |
|  ^  | Shaper didn't attach uni1DC5 to I |
|  ^  | Shaper didn't attach uni1DC6 to dotlessi |
|  ^  | Shaper didn't attach uni1DC6 to I |
|  ^  | Shaper didn't attach uni1DC5 to o |
|  ^  | Shaper didn't attach uni1DC5 to O |
|  ^  | Shaper didn't attach uni1DC6 to o |
|  ^  | Shaper didn't attach uni1DC6 to O |
|  ^  | Shaper didn't attach uni1DC5 to u |
|  ^  | Shaper didn't attach uni1DC5 to U |
|  ^  | Shaper didn't attach uni1DC6 to u |
|  ^  | Shaper didn't attach uni1DC6 to U |
| mwm_Latn (Sar) | Shaper didn't attach uni0304 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0304 to uni018F |
| etu_Latn (Ejagham) | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
| dnj_Latn (Dan) | Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏ |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper produced a .notdef |
|  ^  | Shaper didn't attach uni030F to uni025B |
|  ^  | Shaper didn't attach uni030F to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni030B to uni025B |
|  ^  | Shaper didn't attach uni030B to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper produced a .notdef |
| loq_Latn (Lobala) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
| teo_Latn (Teso) | Some base glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᶶ |
|  ^  | Shaper produced a .notdef |
| bqv_Latn (Koro Wachi) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| dua_Latn (Duala) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
| mnf_Latn (Mundani) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
| kpe_Latn (Kpelle) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
| lnl_Latn (South Central Banda) | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni0308 to uni018F |
| gna_Latn (Kaansa) | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni030C to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
| emk_Latn (Maninkakan, Eastern) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
| din_Latn (Dinka) | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
| xsm_Latn_BF (Kasem) | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
| kzc_Latn (Bondoukou Kulango) | Shaper didn't attach tildecomb to uniA7AE |
|  ^  | Shaper didn't attach tildecomb to uniA7AE |
| myk_Latn (Mamara Senoufo) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
| mev_Latn (Mano) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni0330 |
|  ^  | Shaper didn't attach gravecomb to Eng |
|  ^  | Shaper didn't attach acutecomb to Eng |
|  ^  | Shaper didn't attach uni0304 to Eng |
| bwj_Latn (Láá Láá Bwamu) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| etx_Latn (Iten) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
| ddn_Latn (Dendi) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
| soy_Latn (Miyobe) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| wwa_Latn (Waama) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| jgo_Latn (Ngomba) | Shaper didn't attach uni0304 to Eng |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to Eng |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach gravecomb to Eng |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to Eng |
|  ^  | Shaper didn't attach gravecomb to Eng |
|  ^  | Shaper didn't attach uni0304 to Eng |
| bum_Latn (Bulu) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
| fmp_Latn (Fe’fe’) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni2C6D |
|  ^  | Shaper didn't attach uni0304 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni2C6D |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach uni0304 to uni2C6D |
|  ^  | Shaper didn't attach gravecomb to uni2C6D |
|  ^  | Shaper didn't attach uni0304 to uni0251 |
|  ^  | Shaper didn't attach acutecomb to uni0251 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0251 |
|  ^  | Shaper didn't attach acutecomb to uni2C6D |
|  ^  | Shaper didn't attach gravecomb to uni0251 |
|  ^  | Shaper didn't attach gravecomb to uni2C6D |
|  ^  | Shaper didn't attach uni030C to uni0251 |
|  ^  | Shaper didn't attach uni030C to uni2C6D |
|  ^  | Shaper didn't attach uni0304 to uni0251 |
|  ^  | Shaper didn't attach uni0304 to uni2C6D |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach uni0304 to uni018F |
| mdt_Latn (Mbere) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
| biv_Latn (Birifor, Southern) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to Upsilonlatin |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to Upsilonlatin |
| kib_Latn (Koalib) | Shaper produced a .notdef |
| pnz_Latn (Pana (Central African Republic)) | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0327 |
| ee_Latn (Ewe) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| ozm_Latn (Koonzime) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to oe |
|  ^  | Shaper didn't attach uni0302 to oe |
|  ^  | Shaper didn't attach acutecomb to oe |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to oe |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to oe |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to oe |
| gkp_Latn (Kpelle, Guinea) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni0328 to uni018F |
|  ^  | Shaper didn't attach uni0328 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0328 |
|  ^  | Shaper didn't attach uni0328 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0328 |
|  ^  | Shaper didn't attach uni0328 to uni025B |
|  ^  | Shaper didn't attach uni0328 to uni0190 |
|  ^  | Shaper didn't attach uni0328 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0328 |
|  ^  | Shaper didn't attach uni0328 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0328 |
|  ^  | Shaper didn't attach uni0328 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0328 |
|  ^  | Shaper didn't attach uni0328 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0328 |
|  ^  | Shaper didn't attach uni0328 to uni0254 |
|  ^  | Shaper didn't attach uni0328 to uni0254 |
|  ^  | Shaper didn't attach uni0328 to uni0254 |
| lu_Latn (Luba-Katanga) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
| mor_Latn (Moro) | Some base glyphs were missing: Ꟈ, ꟈ |
|  ^  | Shaper produced a .notdef |
| gvl_Latn (Gulay) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
| bom_Latn (Berom) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
| mge_Latn (Mango) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach uni0304 to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach uni0304 to uni0330 |
| yba_Latn (Yala) | Shaper didn't attach uni030D to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni030D to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni030D to uni025B |
|  ^  | Shaper didn't attach uni030D to uni0190 |
| tvu_Latn (Tunen) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
| dgi_Latn (Northern Dagara) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| bas_Latn (Basaa) | Shaper didn't attach uni1DC6 to A |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni1DC7 to uni0186 |
|  ^  | Shaper didn't attach uni1DC6 to uni025B |
|  ^  | Shaper didn't attach uni1DC7 to O |
|  ^  | Shaper didn't attach uni1DC7 to dotlessi |
|  ^  | Shaper didn't attach uni1DC7 to uni0190 |
|  ^  | Shaper didn't attach uni1DC7 to uni025B |
|  ^  | Shaper didn't attach uni1DC6 to I |
|  ^  | Shaper didn't attach uni1DC6 to e |
|  ^  | Shaper didn't attach uni1DC6 to o |
|  ^  | Shaper didn't attach uni1DC7 to a |
|  ^  | Shaper didn't attach uni1DC7 to u |
|  ^  | Shaper didn't attach uni1DC6 to u |
|  ^  | Shaper didn't attach uni1DC7 to I |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach uni1DC6 to uni0186 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni1DC7 to A |
|  ^  | Shaper didn't attach uni1DC6 to O |
|  ^  | Shaper didn't attach uni1DC6 to E |
|  ^  | Shaper didn't attach uni1DC6 to a |
|  ^  | Shaper didn't attach uni1DC7 to e |
|  ^  | Shaper didn't attach uni1DC7 to o |
|  ^  | Shaper didn't attach uni1DC7 to uni0254 |
|  ^  | Shaper didn't attach uni1DC6 to uni0190 |
|  ^  | Shaper didn't attach uni1DC7 to U |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni1DC6 to uni0254 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni1DC6 to U |
|  ^  | Shaper didn't attach uni1DC6 to dotlessi |
|  ^  | Shaper didn't attach uni1DC7 to E |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni1DC6 to a |
|  ^  | Shaper didn't attach uni1DC7 to a |
|  ^  | Shaper didn't attach uni1DC6 to A |
|  ^  | Shaper didn't attach uni1DC7 to A |
|  ^  | Shaper didn't attach uni1DC6 to e |
|  ^  | Shaper didn't attach uni1DC7 to e |
|  ^  | Shaper didn't attach uni1DC6 to E |
|  ^  | Shaper didn't attach uni1DC7 to E |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni1DC6 to uni025B |
|  ^  | Shaper didn't attach uni1DC7 to uni025B |
|  ^  | Shaper didn't attach uni1DC6 to uni0190 |
|  ^  | Shaper didn't attach uni1DC7 to uni0190 |
|  ^  | Shaper didn't attach uni1DC6 to dotlessi |
|  ^  | Shaper didn't attach uni1DC7 to dotlessi |
|  ^  | Shaper didn't attach uni1DC6 to I |
|  ^  | Shaper didn't attach uni1DC7 to I |
|  ^  | Shaper didn't attach uni1DC6 to o |
|  ^  | Shaper didn't attach uni1DC7 to o |
|  ^  | Shaper didn't attach uni1DC6 to O |
|  ^  | Shaper didn't attach uni1DC7 to O |
|  ^  | Shaper didn't attach uni1DC6 to uni0254 |
|  ^  | Shaper didn't attach uni1DC7 to uni0254 |
|  ^  | Shaper didn't attach uni1DC6 to uni0186 |
|  ^  | Shaper didn't attach uni1DC7 to uni0186 |
|  ^  | Shaper didn't attach uni1DC6 to u |
|  ^  | Shaper didn't attach uni1DC7 to u |
|  ^  | Shaper didn't attach uni1DC6 to U |
|  ^  | Shaper didn't attach uni1DC7 to U |
| bfo_Latn (Malba Birifor) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
| bbj_Latn (Ghomala) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
| agq_Latn (Aghem) | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
| kss_Latn (Southern Kisi) | Shaper didn't attach uni1DC4 to a |
|  ^  | Shaper didn't attach uni1DC4 to A |
|  ^  | Shaper didn't attach uni1DC5 to a |
|  ^  | Shaper didn't attach uni1DC5 to A |
|  ^  | Shaper didn't attach uni1DC4 to e |
|  ^  | Shaper didn't attach uni1DC4 to E |
|  ^  | Shaper didn't attach uni1DC5 to e |
|  ^  | Shaper didn't attach uni1DC5 to E |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni030D to uni025B |
|  ^  | Shaper didn't attach uni030D to uni0190 |
|  ^  | Shaper didn't attach uni1DC4 to uni025B |
|  ^  | Shaper didn't attach uni1DC4 to uni0190 |
|  ^  | Shaper didn't attach uni1DC5 to uni025B |
|  ^  | Shaper didn't attach uni1DC5 to uni0190 |
|  ^  | Shaper didn't attach uni1DC4 to dotlessi |
|  ^  | Shaper didn't attach uni1DC4 to I |
|  ^  | Shaper didn't attach uni1DC5 to dotlessi |
|  ^  | Shaper didn't attach uni1DC5 to I |
|  ^  | Shaper didn't attach uni0304 to Eng |
|  ^  | Shaper didn't attach uni030D to Eng |
|  ^  | Shaper didn't attach uni1DC4 to o |
|  ^  | Shaper didn't attach uni1DC4 to O |
|  ^  | Shaper didn't attach uni1DC5 to o |
|  ^  | Shaper didn't attach uni1DC5 to O |
|  ^  | Shaper didn't attach uni1DC4 to uni0254 |
|  ^  | Shaper didn't attach uni1DC4 to uni0186 |
|  ^  | Shaper didn't attach uni1DC5 to uni0254 |
|  ^  | Shaper didn't attach uni1DC5 to uni0186 |
|  ^  | Shaper didn't attach uni1DC4 to u |
|  ^  | Shaper didn't attach uni1DC4 to U |
|  ^  | Shaper didn't attach uni1DC5 to u |
|  ^  | Shaper didn't attach uni1DC5 to U |
| sba_Latn (Ngambay) | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0330 to uni018F |
| kst_Latn (Winyé) | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
| nyb_Latn (Nyangbo) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| dip_Latn (Dinka, Northeastern) | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni0190 |
| ksf_Latn (Bafia) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
| tuz_Latn (Turka) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| box_Latn (Buamu) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| ksp_Latn (Kabba) | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni0308 to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
| pug_Latn (Phuie) | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni01B2 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni028B |
|  ^  | Shaper didn't attach tildecomb to uni028B |
| neb_Latn (Toura) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
| bfd_Latn (Bafut) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
| bqp_Latn (Bisã) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| ntm_Latn (Nateni) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
|  ^  | Shaper didn't attach uni0330 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0330 |
| gej_Latn (Gen) | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
| gur_Latn (Frafra) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| gov_Latn (Goo) | Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂ |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper produced a .notdef |
| kkj_Latn (Kako) | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0327 to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0327 to uni0190 |
| lee_Latn (Lyélé) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| mgo_Latn (Metaʼ) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni018F |
| nfu_Latn (Mfumte) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0302 to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
| nmz_Latn (Nawdm) | Shaper didn't attach uni0308 to Eng |
|  ^  | Shaper didn't attach uni0308 to Eng |
| dya_Latn (Dyan) | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
| tcd_Latn (Tafi) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni1DC6 to a |
|  ^  | Shaper didn't attach uni1DC6 to A |
|  ^  | Shaper didn't attach uni1DC6 to e |
|  ^  | Shaper didn't attach uni1DC6 to E |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach uni0304 to uni025B |
|  ^  | Shaper didn't attach uni0304 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni0304 to uni0269 |
|  ^  | Shaper didn't attach uni030C to uni0269 |
|  ^  | Shaper didn't attach uni1DC6 to uni0269 |
|  ^  | Shaper didn't attach uni1DC6 to Iotalatin |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni1DC6 to tildecomb |
|  ^  | Shaper didn't attach tildecomb to uni0269 |
|  ^  | Shaper didn't attach uni1DC6 to tildecomb |
|  ^  | Shaper didn't attach uni1DC6 to tildecomb |
|  ^  | Shaper didn't attach uni1DC6 to tildecomb |
|  ^  | Shaper didn't attach acutecomb to Eng |
|  ^  | Shaper didn't attach uni1DC5 to o |
|  ^  | Shaper didn't attach uni1DC5 to O |
|  ^  | Shaper didn't attach uni1DC6 to o |
|  ^  | Shaper didn't attach uni1DC6 to O |
|  ^  | Shaper didn't attach uni1DC6 to uni0254 |
|  ^  | Shaper didn't attach uni1DC6 to uni0186 |
|  ^  | Shaper didn't attach uni1DC6 to u |
|  ^  | Shaper didn't attach uni1DC6 to U |
|  ^  | Shaper didn't attach uni1DC6 to utilde |
|  ^  | Shaper didn't attach uni1DC6 to Utilde |
|  ^  | Shaper didn't attach acutecomb to Upsilonlatin |
|  ^  | Shaper didn't attach tildecomb to Upsilonlatin |
|  ^  | Shaper didn't attach uni0304 to Upsilonlatin |
|  ^  | Shaper didn't attach uni030C to Upsilonlatin |
|  ^  | Shaper didn't attach tildecomb to Upsilonlatin |
|  ^  | Shaper didn't attach tildecomb to Upsilonlatin |
| sbd_Latn (Southern Samo) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0308 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni030C to uni018F |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni0308 to uni025B |
| apd_Latn (Sudanese Arabic) | Some mark glyphs were missing: ◌͟ |
| ybb_Latn (Yemba) | Shaper didn't attach uni0304 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0304 to uni018F |
|  ^  | Shaper didn't attach uni0308 to uni018F |
| goa_Latn (Guro) | Shaper didn't attach uni030C to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach uni030C to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach uni030C to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach uni030C to uni0269 |
|  ^  | Shaper didn't attach acutecomb to uni028B |
|  ^  | Shaper didn't attach acutecomb to uni01B2 |
|  ^  | Shaper didn't attach gravecomb to uni028B |
|  ^  | Shaper didn't attach gravecomb to uni01B2 |
|  ^  | Shaper didn't attach uni0302 to uni028B |
|  ^  | Shaper didn't attach uni0302 to uni01B2 |
|  ^  | Shaper didn't attach uni030C to uni028B |
|  ^  | Shaper didn't attach uni030C to uni01B2 |
| dur_Latn (Dii) | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni018F |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach gravecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
|  ^  | Shaper didn't attach uni0327 to uni018F |
|  ^  | Shaper didn't attach acutecomb to uni0327 |
| grb_Latn (Grebo) | Shaper didn't attach uni0308 to uni0190 |
|  ^  | Shaper didn't attach uni0308 to uni025B |
|  ^  | Shaper didn't attach uni030C to uni0190 |
|  ^  | Shaper didn't attach uni030C to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
| blo_Latn (Anii) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to Upsilonlatin |
|  ^  | Shaper didn't attach acutecomb to Upsilonlatin |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach gravecomb to Upsilonlatin |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach uni0302 to uni025B |
|  ^  | Shaper didn't attach uni0302 to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0269 |
|  ^  | Shaper didn't attach gravecomb to uni0269 |
|  ^  | Shaper didn't attach uni0302 to uni0269 |
|  ^  | Shaper didn't attach acutecomb to Upsilonlatin |
|  ^  | Shaper didn't attach gravecomb to Upsilonlatin |
|  ^  | Shaper didn't attach uni0302 to Upsilonlatin |
| udu_Latn (Uduk) | Some base glyphs were missing: T͟H, t͟h |
|  ^  | Some mark glyphs were missing: ◌͟ |
|  ^  | Shaper produced a .notdef |
|  ^  | Shaper produced a .notdef |
| bqc_Latn (Boko) | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni025B |
|  ^  | Shaper didn't attach acutecomb to uni0190 |
|  ^  | Shaper didn't attach gravecomb to uni025B |
|  ^  | Shaper didn't attach gravecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni025B |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
|  ^  | Shaper didn't attach tildecomb to uni0190 |
| bkm_Latn (Kom) | Shaper didn't attach uni0302 to oe |
|  ^  | Shaper didn't attach gravecomb to oe |
|  ^  | Shaper didn't attach gravecomb to oe |
|  ^  | Shaper didn't attach uni0302 to oe |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_African glyphset:

| Language | FAIL messages |
| :--- | :--- |
| toq_Latn (Toposa) | No variant glyphs were found for Eng |
| nus_Latn (Nuer) | No variant glyphs were found for Eng |
| mcn_Latn (Masana) | No variant glyphs were found for Eng |
| nnh_Latn (Ngiemboon) | No variant glyphs were found for Eng |
| csk_Latn (Jola-Kasa) | No variant glyphs were found for Eng |
| fub_Latn (Fulfulde, Adamawa) | No variant glyphs were found for Eng |
| ntr_Latn (Delo) | No variant glyphs were found for Eng |
| bze_Latn (Jenaama Bozo) | No variant glyphs were found for Eng |
| bzx_Latn (Bozo, Hainyaxo) | No variant glyphs were found for Eng |
| snf_Latn (Noon) | No variant glyphs were found for Eng |
| bax_Latn (Bamun, Latin) | No variant glyphs were found for Eng |
| maw_Latn (Mampruli) | No variant glyphs were found for Eng |
| krs_Latn (Gbaya (Sudan)) | No variant glyphs were found for Eng |
| lam_Latn (Lamba) | No variant glyphs were found for Eng |
| mfd_Latn (Mendankwe-Nkwen) | No variant glyphs were found for Eng |
| ahl_Latn (Igo) | No variant glyphs were found for Eng |
| sig_Latn (Paasaal) | No variant glyphs were found for Eng |
| hag_Latn (Hanga) | No variant glyphs were found for Eng |
| bib_Latn (Bissa) | No variant glyphs were found for Eng |
| yav_Latn (Yangben) | No variant glyphs were found for Eng |
| vai_Latn (Vai (Latin)) | No variant glyphs were found for Eng |
| nnw_Latn (Southern Nuni) | No variant glyphs were found for Eng |
| gnd_Latn (Zulgo-Gemzek) | No variant glyphs were found for Eng |
| ahs_Latn (Ashe) | No variant glyphs were found for Eng |
| mcp_Latn (Makaa) | No variant glyphs were found for Eng |
| bsp_Latn (Baga Sitemu) | No variant glyphs were found for Eng |
| mmu_Latn (Mmaala) | No variant glyphs were found for Eng |
| dzg_Latn (Dazaga) | No variant glyphs were found for Eng |
| nmg_Latn (Kwasio) | No variant glyphs were found for Eng |
| lgg_Latn (Lugbara) | No variant glyphs were found for Eng |
| mcu_Latn (Mambila, Cameroon) | No variant glyphs were found for Eng |
| agc_Latn (Agatu) | No variant glyphs were found for Eng |
| rub_Latn (Gungu) | No variant glyphs were found for Eng |
| ife_Latn (Ifè) | No variant glyphs were found for Eng |
| bud_Latn (Ntcham) | No variant glyphs were found for Eng |
| tod_Latn (Toma) | No variant glyphs were found for Eng |
|  ^  | No variant glyphs were found for uni028B |
|  ^  | No variant glyphs were found for uni01B2 |
| bim_Latn (Bimoba) | No variant glyphs were found for Eng |
| tem_Latn (Timne) | No variant glyphs were found for Eng |
| srr_Latn (Serer) | No variant glyphs were found for Eng |
| taq_Latn (Tamasheq, Latin) | No variant glyphs were found for Eng |
| adj_Latn (Adioukrou) | No variant glyphs were found for Eng |
| shz_Latn (Syenara Senoufo) | No variant glyphs were found for Eng |
| lmp_Latn (Limbum) | No variant glyphs were found for Eng |
| mwk_Latn (Kita Maninkakan) | No variant glyphs were found for Eng |
| mfq_Latn (Moba) | No variant glyphs were found for Eng |
| cae_Latn (Lehar) | No variant glyphs were found for Eng |
| mbu_Latn (Mbula-Bwazza) | No variant glyphs were found for Eng |
| ndv_Latn (Ndut) | No variant glyphs were found for Eng |
| sld_Latn (Sissala) | No variant glyphs were found for Eng |
| bbo_Latn (Northern Bobo Madaré) | No variant glyphs were found for Eng |
| mas_Latn (Masai) | No variant glyphs were found for Eng |
| byv_Latn (Medumba) | No variant glyphs were found for Eng |
| anv_Latn (Denya) | No variant glyphs were found for Eng |
| ewo_Latn (Ewondo) | No variant glyphs were found for Eng |
| tik_Latn (Tikar) | No variant glyphs were found for Eng |
| fue_Latn (Fulfulde, Borgu) | No variant glyphs were found for Eng |
| mdj_Latn (Mangbetu) | No variant glyphs were found for Eng |
| xuo_Latn (Kuo) | No variant glyphs were found for Eng |
| dts_Latn (Dogon, Toro So) | No variant glyphs were found for Eng |
| xon_Latn (Konkomba) | No variant glyphs were found for Eng |
| ggn_Latn (Eastern Gurung, Latin) | No exemplar glyphs were defined for language Eastern Gurung, Latin |
| bqj_Latn (Bandial) | No variant glyphs were found for Eng |
| daa_Latn (Dangaléat) | No variant glyphs were found for Eng |
| nuv_Latn (Nuni, Northern) | No variant glyphs were found for Eng |
| mfi_Latn (Wandala) | No variant glyphs were found for Eng |
| bza_Latn (Bandi) | No variant glyphs were found for Eng |
| muy_Latn (Muyang) | No variant glyphs were found for Eng |
| yas_Latn (Nugunu) | No variant glyphs were found for Eng |
| etu_Latn (Ejagham) | No variant glyphs were found for Eng |
| yat_Latn (Yambeta) | No variant glyphs were found for Eng |
| tpm_Latn (Tampulma) | No variant glyphs were found for Eng |
| lok_Latn (Loko) | No variant glyphs were found for Eng |
| dyi_Latn (Sénoufo, Djimini) | No variant glyphs were found for Eng |
| meq_Latn (Merey) | No variant glyphs were found for Eng |
| ncu_Latn (Chumburung) | No variant glyphs were found for Eng |
| xrb_Latn (Karaboro, Eastern) | No variant glyphs were found for Eng |
| lun_Latn (Lunda) | No variant glyphs were found for Eng |
| mbo_Latn (Mbo) | No variant glyphs were found for Eng |
| idu_Latn (Idoma) | No variant glyphs were found for Eng |
| dje_Latn (Zarma) | No variant glyphs were found for Eng |
| dnj_Latn (Dan) | Some auxiliary glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏ |
|  ^  | No variant glyphs were found for Eng |
|  ^  | No variant glyphs were found for uni0181 |
| cme_Latn (Cerma) | No variant glyphs were found for Eng |
| fuh_Latn (Fulfulde, Western Niger) | No variant glyphs were found for Eng |
| fvr_Latn (Fur) | No variant glyphs were found for Eng |
| loq_Latn (Lobala) | No variant glyphs were found for Eng |
| teo_Latn (Teso) | Some auxiliary glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᶶ |
| kqp_Latn (Kimré) | No variant glyphs were found for Eng |
| mgc_Latn (Morokodo) | No variant glyphs were found for Eng |
| pil_Latn (Yom) | No variant glyphs were found for Eng |
| mzw_Latn (Deg) | No variant glyphs were found for Eng |
| bqv_Latn (Koro Wachi) | No variant glyphs were found for Eng |
| dua_Latn (Duala) | No variant glyphs were found for Eng |
| kpo_Latn (Ikposo) | No variant glyphs were found for Eng |
| mnf_Latn (Mundani) | No variant glyphs were found for Eng |
| vut_Latn (Vute) | No variant glyphs were found for Eng |
| gmm_Latn (Gbaya-Mbodomo) | No variant glyphs were found for Eng |
| ikx_Latn (Ik) | No variant glyphs were found for Eng |
| lem_Latn (Nomaande) | No variant glyphs were found for Eng |
| nko_Latn (Nkonya) | No variant glyphs were found for Eng |
| avn_Latn (Avatime) | No variant glyphs were found for Eng |
| gna_Latn (Kaansa) | No variant glyphs were found for Eng |
| xsm_Latn (Kasem) | No variant glyphs were found for Eng |
| ffm_Latn (Maasina Fulfulde) | No variant glyphs were found for Eng |
| yam_Latn (Yamba) | No variant glyphs were found for Eng |
| ny_Latn (Nyanja) | No variant glyphs were found for Eng |
| ses_Latn (Koyraboro Senni) | No variant glyphs were found for Eng |
| emk_Latn (Maninkakan, Eastern) | No variant glyphs were found for Eng |
| kzc_Latn (Bondoukou Kulango) | No variant glyphs were found for Eng |
| ach_Latn (Acoli) | No variant glyphs were found for Eng |
| kbp_Latn (Kabiyé) | No variant glyphs were found for Eng |
| gux_Latn (Gourmanchéma) | No variant glyphs were found for Eng |
| lg_Latn (Ganda) | No variant glyphs were found for Eng |
| knp_Latn (Kwanja) | No variant glyphs were found for Eng |
| myk_Latn (Mamara Senoufo) | No variant glyphs were found for Eng |
| mev_Latn (Mano) | No variant glyphs were found for Eng |
| pbi_Latn (Parkwa) | No variant glyphs were found for Eng |
| bzw_Latn (Basa) | No variant glyphs were found for Eng |
| khq_Latn (Koyra Chiini) | No variant glyphs were found for Eng |
| mfv_Latn (Mandjak) | No variant glyphs were found for Eng |
| moa_Latn (Mwan) | No variant glyphs were found for Eng |
| ddn_Latn (Dendi) | No variant glyphs were found for Eng |
| soy_Latn (Miyobe) | No variant glyphs were found for Eng |
| gaa_Latn (Ga) | No variant glyphs were found for Eng |
|  ^  | No variant glyphs were found for uni01A9 |
|  ^  | No variant glyphs were found for uni01B7 |
| wwa_Latn (Waama) | No variant glyphs were found for Eng |
| jgo_Latn (Ngomba) | No variant glyphs were found for Eng |
| bum_Latn (Bulu) | No variant glyphs were found for Eng |
| fmp_Latn (Fe’fe’) | No variant glyphs were found for Eng |
| bjt_Latn (Balanta-Ganja) | No variant glyphs were found for Eng |
| kqs_Latn (Kissi, Northern) | No variant glyphs were found for Eng |
| mdt_Latn (Mbere) | No variant glyphs were found for Eng |
| log_Latn (Logo) | No variant glyphs were found for Eng |
| keu_Latn (Akebu) | No variant glyphs were found for Eng |
| biv_Latn (Birifor, Southern) | No variant glyphs were found for Eng |
| mnk_Latn (Mandinka) | No variant glyphs were found for Eng |
| xwe_Latn (Gbe, Xwela) | No variant glyphs were found for Eng |
| twq_Latn (Tasawaq) | No variant glyphs were found for Eng |
| ken_Latn (Kenyang) | No variant glyphs were found for Eng |
| kib_Latn (Koalib) | No variant glyphs were found for Eng |
| pnz_Latn (Pana (Central African Republic)) | No variant glyphs were found for Eng |
| ee_Latn (Ewe) | No variant glyphs were found for Eng |
| ozm_Latn (Koonzime) | No variant glyphs were found for Eng |
| kzr_Latn (Karang) | No variant glyphs were found for Eng |
| cko_Latn (Anufo) | No variant glyphs were found for Eng |
| gkp_Latn (Kpelle, Guinea) | No variant glyphs were found for Eng |
| sok_Latn (Sokoro) | No variant glyphs were found for Eng |
| tuq_Latn (Tedaga) | No variant glyphs were found for Eng |
| cch_Latn (Atsam) | No exemplar glyphs were defined for language Atsam |
| dyu_Latn (Dyula) | No variant glyphs were found for Eng |
| mor_Latn (Moro) | Some auxiliary glyphs were missing: Ꟈ, ꟈ |
|  ^  | No variant glyphs were found for Eng |
| knf_Latn (Mankanya) | No variant glyphs were found for Eng |
| god_Latn (Godié) | No variant glyphs were found for Eng |
| tvu_Latn (Tunen) | No variant glyphs were found for Eng |
| sil_Latn (Sisaala, Tumulung) | No variant glyphs were found for Eng |
| wci_Latn (Gbe, Waci) | No variant glyphs were found for Eng |
| ekm_Latn (Elip) | No variant glyphs were found for Eng |
| bfa_Latn (Bari) | No variant glyphs were found for Eng |
| dop_Latn (Lukpa) | No variant glyphs were found for Eng |
| sav_Latn (Saafi-Saafi) | No variant glyphs were found for Eng |
| dgi_Latn (Northern Dagara) | No variant glyphs were found for Eng |
| bss_Latn (Akoose) | No variant glyphs were found for Eng |
| dag_Latn (Dagbani) | No variant glyphs were found for Eng |
| kia_Latn (Kim) | No variant glyphs were found for Eng |
| kmy_Latn (Koma) | No variant glyphs were found for Eng |
| fuc_Latn (Pulaar) | No variant glyphs were found for Eng |
| nym_Latn (Nyamwezi) | No variant glyphs were found for Eng |
| naw_Latn (Nawuri) | No variant glyphs were found for Eng |
| dno_Latn (Ndrulo) | No variant glyphs were found for Eng |
| boz_Latn (Tiéyaxo Bozo) | No variant glyphs were found for Eng |
| kfo_Latn (Koro) | No exemplar glyphs were defined for language Koro |
| bas_Latn (Basaa) | No variant glyphs were found for Eng |
| nhb_Latn (Beng) | No variant glyphs were found for Eng |
| wo_Latn (Wolof) | No variant glyphs were found for Eng |
| dtm_Latn (Tomo Kan Dogon) | No variant glyphs were found for Eng |
| bm_Latn (Bambara) | No variant glyphs were found for Eng |
| xed_Latn (Hdi) | No variant glyphs were found for Eng |
| bbj_Latn (Ghomala) | No variant glyphs were found for Eng |
| agq_Latn (Aghem) | No variant glyphs were found for Eng |
| kss_Latn (Southern Kisi) | No variant glyphs were found for Eng |
| fuq_Latn (Central-Eastern Niger Fulfulde) | No variant glyphs were found for Eng |
| saf_Latn (Safaliba) | No variant glyphs were found for Eng |
| gjn_Latn (Gonja) | No variant glyphs were found for Eng |
| dow_Latn (Doyayo) | No variant glyphs were found for Eng |
| hna_Latn (Mina) | No exemplar glyphs were defined for language Mina |
| lia_Latn (Limba, West-Central) | No variant glyphs were found for Eng |
| nyb_Latn (Nyangbo) | No variant glyphs were found for Eng |
| mgy_Latn (Mbunga) | No exemplar glyphs were defined for language Mbunga |
| dip_Latn (Dinka, Northeastern) | No variant glyphs were found for Eng |
| ksf_Latn (Bafia) | No variant glyphs were found for Eng |
| vag_Latn (Vagla) | No variant glyphs were found for Eng |
| kdh_Latn (Tem) | No variant glyphs were found for Eng |
| sxw_Latn (Saxwe Gbe) | No variant glyphs were found for Eng |
| lig_Latn (Ligbi) | No variant glyphs were found for Eng |
| laj_Latn (Lango [Uganda]) | No variant glyphs were found for Eng |
| fan_Latn (Fang) | No variant glyphs were found for Eng |
| ktj_Latn (Krumen, Plapo) | No variant glyphs were found for Eng |
| ted_Latn (Krumen, Tepo) | No variant glyphs were found for Eng |
| kye_Latn (Krache) | No variant glyphs were found for Eng |
| azo_Latn (Awing) | No variant glyphs were found for Eng |
| pug_Latn (Phuie) | No variant glyphs were found for Eng |
| acd_Latn (Gikyode) | No variant glyphs were found for Eng |
| mur_Latn (Murle) | No variant glyphs were found for Eng |
| ttq_Latn (Tawallammat Tamajaq) | No variant glyphs were found for Eng |
| gde_Latn (Gude) | No variant glyphs were found for Eng |
| syi_Latn (Seki) | No exemplar glyphs were defined for language Seki |
| nza_Latn (Tigon Mbembe) | No variant glyphs were found for Eng |
| neb_Latn (Toura) | No variant glyphs were found for Eng |
| bfd_Latn (Bafut) | No variant glyphs were found for Eng |
| bcw_Latn (Bana) | No variant glyphs were found for Eng |
| ade_Latn (Adele) | No variant glyphs were found for Eng |
| spp_Latn (Sénoufo, Supyire) | No variant glyphs were found for Eng |
| gej_Latn (Gen) | No variant glyphs were found for Eng |
| gur_Latn (Frafra) | No variant glyphs were found for Eng |
| bex_Latn (Jur Modo) | No variant glyphs were found for Eng |
| gov_Latn (Goo) | Some auxiliary glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂ |
| mls_Latn (Masalit) | No variant glyphs were found for Eng |
| kkj_Latn (Kako) | No variant glyphs were found for Eng |
| nhu_Latn (Noone) | No variant glyphs were found for Eng |
| mua_Latn (Mundang) | No variant glyphs were found for Eng |
| ndz_Latn (Ndogo) | No variant glyphs were found for Eng |
| nfr_Latn (Nafaanra) | No variant glyphs were found for Eng |
| bav_Latn (Vengo) | No variant glyphs were found for Eng |
| kao_Latn (Xaasongaxango) | No variant glyphs were found for Eng |
| lee_Latn (Lyélé) | No variant glyphs were found for Eng |
| lns_Latn (Lamnso’) | No variant glyphs were found for Eng |
| amo_Latn (Amo) | No exemplar glyphs were defined for language Amo |
| gud_Latn (Dida, Yocoboué) | No variant glyphs were found for Eng |
| mgo_Latn (Metaʼ) | No variant glyphs were found for Eng |
| cou_Latn (Wamey) | No variant glyphs were found for Eng |
| sef_Latn (Cebaara Senoufo) | No variant glyphs were found for Eng |
| nfu_Latn (Mfumte) | No variant glyphs were found for Eng |
| nku_Latn (Kulango, Bouna) | No variant glyphs were found for Eng |
| nmz_Latn (Nawdm) | No variant glyphs were found for Eng |
| gng_Latn (Ngangam) | No variant glyphs were found for Eng |
| wan_Latn (Wan) | No variant glyphs were found for Eng |
| avu_Latn (Avokaya) | No variant glyphs were found for Eng |
| las_Latn (Lama (Togo)) | No variant glyphs were found for Eng |
| tnr_Latn (Ménik) | No variant glyphs were found for Eng |
| kvf_Latn (Kabalai) | No variant glyphs were found for Eng |
| tcd_Latn (Tafi) | No variant glyphs were found for Eng |
| sbd_Latn (Southern Samo) | No variant glyphs were found for Eng |
| ig_Latn (Igbo) | No variant glyphs were found for Eng |
| ybb_Latn (Yemba) | No variant glyphs were found for Eng |
| fod_Latn (Foodo) | No variant glyphs were found for Eng |
| dur_Latn (Dii) | No variant glyphs were found for Eng |
| ajg_Latn (Aja) | No variant glyphs were found for Eng |
| dyo_Latn (Jola-Fonyi) | No variant glyphs were found for Eng |
| blo_Latn (Anii) | No variant glyphs were found for Eng |
| kyf_Latn (Kouya) | No variant glyphs were found for Eng |
| bsc_Latn (Bassari) | No variant glyphs were found for Eng |
| udu_Latn (Uduk) | Some auxiliary glyphs were missing: T͟H, t͟h |
|  ^  | No variant glyphs were found for Eng |
| fuf_Latn (Pular) | No variant glyphs were found for Eng |
| kyq_Latn (Kenga) | No variant glyphs were found for Eng |
| bkm_Latn (Kom) | No variant glyphs were found for Eng |
| kus_Latn (Kusaal) | No variant glyphs were found for Eng |

 [code: warning-language-shaping]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1030 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni031B

	- uni0328

	- uni0334

	- uni0335

	- uni0337 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, canadian-aboriginal, tai-le, syriac, malayalam, coptic, tifinagh, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, gothic, caucasian-albanian, cherokee, tifinagh
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7B LATIN SMALL CAPITAL LETTER I WITH STROKE: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DA4 MODIFIER LETTER SMALL I WITH STROKE: not included in any glyphset definition
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
 * U+2071 SUPERSCRIPT LATIN SMALL LETTER I: not included in any glyphset definition
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
 * U+25CC DOTTED CIRCLE: try adding one of: bassa-vah, newa, kaithi, cham, tai-tham, saurashtra, dogra, tamil, sogdian, batak, wancho, phags-pa, mongolian, javanese, yi, mende-kikakui, balinese, caucasian-albanian, elbasan, mandaic, hebrew, chakma, nko, hanifi-rohingya, gurmukhi, modi, miao, khudawadi, sharada, canadian-aboriginal, khojki, symbols, osage, buginese, limbu, math, oriya, new-tai-lue, kharoshthi, soyombo, marchen, tagalog, takri, psalter-pahlavi, warang-citi, tai-viet, myanmar, khmer, old-permic, ahom, tifinagh, duployan, mahajani, tirhuta, lao, rejang, tagbanwa, brahmi, armenian, music, manichaean, bengali, kayah-li, thai, bhaiksuki, lepcha, adlam, siddham, tai-le, sinhala, coptic, gujarati, zanabazar-square, gunjala-gondi, kannada, malayalam, pahawh-hmong, sundanese, devanagari, hanunoo, syriac, tibetan, telugu, thaana, meetei-mayek, syloti-nagri, masaram-gondi, buhid, grantha
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _bottomshortstroke.part

	- _topshortstroke.part

	- asterisk_node

	- dotlessi_ogonek

	- strokelongY.comb

	- uni01C2.001

	- uni025F.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

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

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4 or 7

	- Glyph name: arrowboth	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowboth	Contours detected: 2	Expected: 1

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023B	Contours detected: 1	Expected: 2

	- Glyph name: uni023D	Contours detected: 2	Expected: 1

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

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

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4 or 7

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 373 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 430:
plus

Width = 460:
notequal, equal

Width = 438:
logicalnot

Width = 431:
plusminus

Width = 441:
multiply

Width = 469:
divide

Width = 440:
minus

Width = 442:
approxequal

Width = 394:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Aogonek (U+0104): L<<305.0,0.0>--<378.0,0.0>>/B<<378.0,0.0>-<350.0,-7.0>-<334.0,-22.0>> = 14.036243467926484

	* Eogonek (U+0118): L<<306.0,0.0>--<379.0,0.0>>/B<<379.0,0.0>-<351.0,-7.0>-<335.0,-22.0>> = 14.036243467926484

	* Iogonek (U+012E): L<<144.0,0.0>--<217.0,0.0>>/B<<217.0,0.0>-<189.0,-7.0>-<173.0,-22.0>> = 14.036243467926484

	* Uogonek (U+0172): L<<397.0,0.0>--<480.0,0.0>>/B<<480.0,0.0>-<452.0,-7.0>-<436.0,-20.5>> = 14.036243467926484

	* aogonek (U+0105): L<<347.0,0.0>--<430.0,0.0>>/B<<430.0,0.0>-<402.0,-7.0>-<386.0,-20.5>> = 14.036243467926484

	* eogonek (U+0119): L<<182.0,0.0>--<265.0,0.0>>/B<<265.0,0.0>-<237.0,-7.0>-<221.0,-20.5>> = 14.036243467926484

	* iogonek (U+012F): L<<114.0,0.0>--<197.0,0.0>>/B<<197.0,0.0>-<169.0,-7.0>-<153.0,-20.5>> = 14.036243467926484

	* ogonek (U+02DB): L<<90.0,0.0>--<173.0,0.0>>/B<<173.0,0.0>-<145.0,-7.0>-<129.0,-20.5>> = 14.036243467926484

	* uni01EA (U+01EA): L<<351.0,0.0>--<434.0,0.0>>/B<<434.0,0.0>-<406.0,-7.0>-<390.0,-20.5>> = 14.036243467926484

	* uni01EB (U+01EB): L<<331.0,0.0>--<414.0,0.0>>/B<<414.0,0.0>-<386.0,-7.0>-<370.0,-20.5>> = 14.036243467926484

	* uni01EC (U+01EC): L<<351.0,0.0>--<434.0,0.0>>/B<<434.0,0.0>-<406.0,-7.0>-<390.0,-20.5>> = 14.036243467926484

	* uni01ED (U+01ED): L<<331.0,0.0>--<414.0,0.0>>/B<<414.0,0.0>-<386.0,-7.0>-<370.0,-20.5>> = 14.036243467926484

	* uni0328 (U+0328): L<<90.0,0.0>--<173.0,0.0>>/B<<173.0,0.0>-<145.0,-7.0>-<129.0,-20.5>> = 14.036243467926484

	* uogonek (U+0173): L<<372.0,0.0>--<455.0,0.0>>/B<<455.0,0.0>-<427.0,-7.0>-<411.0,-20.5>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0 | 0 | 4 | 8 | 124 | 7 | 117 | 0 |
| 0% | 0% | 2% | 3% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
