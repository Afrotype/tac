## FontBakery report

fontbakery version: 0.12.7



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] TacOne-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[11] TacOne-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+03BB: GREEK SMALL LETTER LAMDA</td>
<td align="left">U+039B: GREEK CAPITAL LETTER LAMDA</td>
</tr>
<tr>
<td align="left">U+03C7: GREEK SMALL LETTER CHI</td>
<td align="left">U+03A7: GREEK CAPITAL LETTER CHI</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335

- uni0337
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">Shaper didn't attach gravecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dya_Latn (Dyan)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">Shaper didn't attach tildecomb to uniA7AE</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">eto_Latn (Eton (Cameroon))</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni019D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni019D</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bba_Latn (Baatonum)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">grb_Latn (Grebo)</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dow_Latn (Doyayo)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vut_Latn (Vute)</td>
<td align="left">Shaper didn't attach uni0327 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ksp_Latn (Kabba)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lnl_Latn (South Central Banda)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bwj_Latn (Láá Láá Bwamu)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bax_Latn (Bamun, Latin)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bom_Latn (Berom)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">btt_Latn (Bete-Bendi)</td>
<td align="left">Shaper didn't attach uni1DC5 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">box_Latn (Buamu)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ntm_Latn (Nateni)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">Some base glyphs were missing: T͟H, t͟h</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌͟</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqc_Latn (Boko)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni2C6D</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nga_Latn (Ngbaka)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">Shaper didn't attach uni0308 to Eng</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">din_Latn (Dinka)</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xsm_Latn_BF (Burkinabè Kasem)</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">etx_Latn (Iten)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bsq_Latn (Bassa, Latin)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ln_Latn (Lingala)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lob_Latn (Lobi)</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lol_Latn (Mongo)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tuz_Latn (Turka)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">apd_Latn (Sudanese Arabic)</td>
<td align="left">Some mark glyphs were missing: ◌͟</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tbz_Latn (Ditammari)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
<td align="left">Shaper didn't attach uni0302 to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sba_Latn (Ngambay)</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">teo_Latn (Teso)</td>
<td align="left">Some base glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᶶ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqp_Latn (Bisã)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mge_Latn (Mango)</td>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pnz_Latn (Pana (Central African Republic))</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfo_Latn (Malba Birifor)</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mwm_Latn (Sar)</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">Shaper didn't attach uni1DC4 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">Shaper didn't attach tildecomb to Upsilonlatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kpe_Latn (Kpelle)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gvl_Latn (Gulay)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kst_Latn (Winyé)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yba_Latn (Yala)</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to Upsilonlatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Upsilonlatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Upsilonlatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to Iotalatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to tildecomb</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Upsilonlatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to Upsilonlatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to Upsilonlatin</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to Upsilonlatin</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">goa_Latn (Guro)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lu_Latn (Luba-Katanga)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to I</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">Some base glyphs were missing: Ꟈ, ꟈ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gaa_Latn (Ga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01A9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01B7</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ekm_Latn (Elip)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfa_Latn (Bari)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mbo_Latn (Mbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bex_Latn (Jur Modo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wo_Latn (Wolof)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcu_Latn (Mambila, Cameroon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dje_Latn (Zarma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nku_Latn (Kulango, Bouna)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">saf_Latn (Safaliba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wan_Latn (Wan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gde_Latn (Gude)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sig_Latn (Paasaal)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Some auxiliary glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni0181</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mls_Latn (Masalit)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dop_Latn (Lukpa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sef_Latn (Cebaara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kqs_Latn (Kissi, Northern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gmm_Latn (Gbaya-Mbodomo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fvr_Latn (Fur)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">maw_Latn (Mampruli)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">daa_Latn (Dangaléat)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">eto_Latn (Eton (Cameroon))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vag_Latn (Vagla)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bjt_Latn (Balanta-Ganja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mur_Latn (Murle)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfd_Latn (Mendankwe-Nkwen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ted_Latn (Krumen, Tepo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">twq_Latn (Tasawaq)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">spp_Latn (Sénoufo, Supyire)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">krs_Latn (Gbaya (Sudan))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dow_Latn (Doyayo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cch_Latn (Atsam)</td>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vut_Latn (Vute)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ahl_Latn (Igo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">rub_Latn (Gungu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wci_Latn (Gbe, Waci)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sav_Latn (Saafi-Saafi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfv_Latn (Mandjak)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nhu_Latn (Noone)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kdh_Latn (Tem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tpm_Latn (Tampulma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgy_Latn (Mbunga)</td>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lgg_Latn (Lugbara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gng_Latn (Ngangam)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mas_Latn (Masai)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">anv_Latn (Denya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sok_Latn (Sokoro)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">giz_Latn (Southern Giziga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cae_Latn (Lehar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sil_Latn (Sisaala, Tumulung)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dts_Latn (Dogon, Toro So)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lns_Latn (Lamnso’)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">avu_Latn (Avokaya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">khq_Latn (Koyra Chiini)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bzx_Latn (Bozo, Hainyaxo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lok_Latn (Loko)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bax_Latn (Bamun, Latin)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">adj_Latn (Adioukrou)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mbu_Latn (Mbula-Bwazza)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yam_Latn (Yamba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ade_Latn (Adele)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lam_Latn (Lamba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">srr_Latn (Serer)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kyq_Latn (Kenga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqj_Latn (Bandial)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ses_Latn (Koyraboro Senni)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xuo_Latn (Kuo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">Some auxiliary glyphs were missing: T͟H, t͟h</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kia_Latn (Kim)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fod_Latn (Foodo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kye_Latn (Krache)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuf_Latn (Pular)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fue_Latn (Fulfulde, Borgu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pbi_Latn (Parkwa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ikx_Latn (Ik)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xon_Latn (Konkomba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lem_Latn (Nomaande)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cou_Latn (Wamey)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgc_Latn (Morokodo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bim_Latn (Bimoba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yat_Latn (Yambeta)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kao_Latn (Xaasongaxango)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mua_Latn (Mundang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kbp_Latn (Kabiyé)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kus_Latn (Kusaal)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">amo_Latn (Amo)</td>
<td align="left">No exemplar glyphs were defined for language Amo</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xrb_Latn (Karaboro, Eastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ncu_Latn (Chumburung)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bsp_Latn (Baga Sitemu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gux_Latn (Gourmanchéma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mzw_Latn (Deg)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">log_Latn (Logo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kyf_Latn (Kouya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gud_Latn (Dida, Yocoboué)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gjn_Latn (Gonja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">keu_Latn (Akebu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ach_Latn (Acoli)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">knf_Latn (Mankanya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuc_Latn (Pulaar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bsc_Latn (Bassari)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ahs_Latn (Ashe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">god_Latn (Godié)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xsm_Latn (Kasem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kpo_Latn (Ikposo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ktj_Latn (Krumen, Plapo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hag_Latn (Hanga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cko_Latn (Anufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">knp_Latn (Kwanja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">meq_Latn (Merey)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">syi_Latn (Seki)</td>
<td align="left">No exemplar glyphs were defined for language Seki</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">toq_Latn (Toposa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">azo_Latn (Awing)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ajg_Latn (Aja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lig_Latn (Ligbi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mmu_Latn (Mmaala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuh_Latn (Fulfulde, Western Niger)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kvf_Latn (Kabalai)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tem_Latn (Timne)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">avn_Latn (Avatime)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">teo_Latn (Teso)</td>
<td align="left">Some auxiliary glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᶶ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ndv_Latn (Ndut)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xwe_Latn (Gbe, Xwela)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mwk_Latn (Kita Maninkakan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pnz_Latn (Pana (Central African Republic))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcn_Latn (Masana)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyi_Latn (Sénoufo, Djimini)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tod_Latn (Toma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01B2</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nko_Latn (Nkonya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fub_Latn (Fulfulde, Adamawa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dno_Latn (Ndrulo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dtm_Latn (Tomo Kan Dogon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nhb_Latn (Beng)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ny_Latn (Nyanja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bbo_Latn (Northern Bobo Madaré)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">las_Latn (Lama (Togo))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bze_Latn (Jenaama Bozo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">taq_Latn (Tamasheq, Latin)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">naw_Latn (Nawuri)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tuq_Latn (Tedaga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">shz_Latn (Syenara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ntr_Latn (Delo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuq_Latn (Central-Eastern Niger Fulfulde)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sxw_Latn (Saxwe Gbe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">moa_Latn (Mwan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lmp_Latn (Limbum)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Some auxiliary glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nuv_Latn (Nuni, Northern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ndz_Latn (Ndogo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bav_Latn (Vengo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nza_Latn (Tigon Mbembe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bud_Latn (Ntcham)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">muy_Latn (Muyang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">snf_Latn (Noon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yas_Latn (Nugunu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">agc_Latn (Agatu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfq_Latn (Moba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nym_Latn (Nyamwezi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfi_Latn (Wandala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lun_Latn (Lunda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kfo_Latn (Koro)</td>
<td align="left">No exemplar glyphs were defined for language Koro</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bzw_Latn (Basa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tnr_Latn (Ménik)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cme_Latn (Cerma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bib_Latn (Bissa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bza_Latn (Bandi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fan_Latn (Fang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kzr_Latn (Karang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lia_Latn (Limba, West-Central)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">acd_Latn (Gikyode)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">laj_Latn (Lango [Uganda])</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ken_Latn (Kenyang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xed_Latn (Hdi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">csk_Latn (Jola-Kasa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kmy_Latn (Koma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bcw_Latn (Bana)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">boz_Latn (Tiéyaxo Bozo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hna_Latn (Mina)</td>
<td align="left">No exemplar glyphs were defined for language Mina</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nfr_Latn (Nafaanra)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyo_Latn (Jola-Fonyi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ffm_Latn (Maasina Fulfulde)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dzg_Latn (Dazaga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dag_Latn (Dagbani)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bss_Latn (Akoose)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pil_Latn (Yom)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mdj_Latn (Mangbetu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kqp_Latn (Kimré)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">Some auxiliary glyphs were missing: Ꟈ, ꟈ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">idu_Latn (Idoma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mnk_Latn (Mandinka)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

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
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 373 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 430:
plus</p>
<p>Width = 460:
notequal, equal</p>
<p>Width = 438:
logicalnot</p>
<p>Width = 431:
plusminus</p>
<p>Width = 441:
multiply</p>
<p>Width = 469:
divide</p>
<p>Width = 440:
minus</p>
<p>Width = 442:
approxequal</p>
<p>Width = 394:
greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- _bottomshortstroke.part

- _topshortstroke.part

- asterisk_node

- dotlessi_ogonek

- strokelongY.comb

- uni01C2.001

- uni025F.dotless
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Aogonek (U+0104): L&lt;&lt;305.0,0.0&gt;--&lt;378.0,0.0&gt;&gt;/B&lt;&lt;378.0,0.0&gt;-&lt;350.0,-7.0&gt;-&lt;334.0,-22.0&gt;&gt; = 14.036243467926484

* Eogonek (U+0118): L&lt;&lt;306.0,0.0&gt;--&lt;379.0,0.0&gt;&gt;/B&lt;&lt;379.0,0.0&gt;-&lt;351.0,-7.0&gt;-&lt;335.0,-22.0&gt;&gt; = 14.036243467926484

* Iogonek (U+012E): L&lt;&lt;144.0,0.0&gt;--&lt;217.0,0.0&gt;&gt;/B&lt;&lt;217.0,0.0&gt;-&lt;189.0,-7.0&gt;-&lt;173.0,-22.0&gt;&gt; = 14.036243467926484

* Uogonek (U+0172): L&lt;&lt;397.0,0.0&gt;--&lt;480.0,0.0&gt;&gt;/B&lt;&lt;480.0,0.0&gt;-&lt;452.0,-7.0&gt;-&lt;436.0,-20.5&gt;&gt; = 14.036243467926484

* aogonek (U+0105): L&lt;&lt;347.0,0.0&gt;--&lt;430.0,0.0&gt;&gt;/B&lt;&lt;430.0,0.0&gt;-&lt;402.0,-7.0&gt;-&lt;386.0,-20.5&gt;&gt; = 14.036243467926484

* dotlessi_ogonek: L&lt;&lt;114.0,0.0&gt;--&lt;197.0,0.0&gt;&gt;/B&lt;&lt;197.0,0.0&gt;-&lt;169.0,-7.0&gt;-&lt;153.0,-20.5&gt;&gt; = 14.036243467926484

* eogonek (U+0119): L&lt;&lt;182.0,0.0&gt;--&lt;265.0,0.0&gt;&gt;/B&lt;&lt;265.0,0.0&gt;-&lt;237.0,-7.0&gt;-&lt;221.0,-20.5&gt;&gt; = 14.036243467926484

* iogenek.dotless: L&lt;&lt;5074.0,0.0&gt;--&lt;5157.0,0.0&gt;&gt;/B&lt;&lt;5157.0,0.0&gt;-&lt;5129.0,-7.0&gt;-&lt;5113.0,-20.5&gt;&gt; = 14.036243467926484

* iogonek (U+012F): L&lt;&lt;114.0,0.0&gt;--&lt;197.0,0.0&gt;&gt;/B&lt;&lt;197.0,0.0&gt;-&lt;169.0,-7.0&gt;-&lt;153.0,-20.5&gt;&gt; = 14.036243467926484

* ogonek (U+02DB): L&lt;&lt;90.0,0.0&gt;--&lt;173.0,0.0&gt;&gt;/B&lt;&lt;173.0,0.0&gt;-&lt;145.0,-7.0&gt;-&lt;129.0,-20.5&gt;&gt; = 14.036243467926484

* uni01EA (U+01EA): L&lt;&lt;351.0,0.0&gt;--&lt;434.0,0.0&gt;&gt;/B&lt;&lt;434.0,0.0&gt;-&lt;406.0,-7.0&gt;-&lt;390.0,-20.5&gt;&gt; = 14.036243467926484

* uni01EB (U+01EB): L&lt;&lt;331.0,0.0&gt;--&lt;414.0,0.0&gt;&gt;/B&lt;&lt;414.0,0.0&gt;-&lt;386.0,-7.0&gt;-&lt;370.0,-20.5&gt;&gt; = 14.036243467926484

* uni01EC (U+01EC): L&lt;&lt;351.0,0.0&gt;--&lt;434.0,0.0&gt;&gt;/B&lt;&lt;434.0,0.0&gt;-&lt;406.0,-7.0&gt;-&lt;390.0,-20.5&gt;&gt; = 14.036243467926484

* uni01ED (U+01ED): L&lt;&lt;331.0,0.0&gt;--&lt;414.0,0.0&gt;&gt;/B&lt;&lt;414.0,0.0&gt;-&lt;386.0,-7.0&gt;-&lt;370.0,-20.5&gt;&gt; = 14.036243467926484

* uni0328 (U+0328): L&lt;&lt;90.0,0.0&gt;--&lt;173.0,0.0&gt;&gt;/B&lt;&lt;173.0,0.0&gt;-&lt;145.0,-7.0&gt;-&lt;129.0,-20.5&gt;&gt; = 14.036243467926484

* uni0328.case: L&lt;&lt;100.0,0.0&gt;--&lt;173.0,0.0&gt;&gt;/B&lt;&lt;173.0,0.0&gt;-&lt;145.0,-7.0&gt;-&lt;129.0,-22.0&gt;&gt; = 14.036243467926484

* uogonek (U+0173): L&lt;&lt;372.0,0.0&gt;--&lt;455.0,0.0&gt;&gt;/B&lt;&lt;455.0,0.0&gt;-&lt;427.0,-7.0&gt;-&lt;411.0,-20.5&gt;&gt; = 14.036243467926484
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition</li>
<li>U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition</li>
<li>U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition</li>
<li>U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition</li>
<li>U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition</li>
<li>U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition</li>
<li>U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition</li>
<li>U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal</li>
<li>U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition</li>
<li>U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, coptic, malayalam, syriac, math, tifinagh, canadian-aboriginal, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding old-permic</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, cherokee, gothic, syriac, tifinagh</li>
<li>U+0332 COMBINING LOW LINE: not included in any glyphset definition</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan</li>
<li>U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi</li>
<li>U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition</li>
<li>U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition</li>
<li>U+1D7B LATIN SMALL CAPITAL LETTER I WITH STROKE: not included in any glyphset definition</li>
<li>U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition</li>
<li>U+1DA4 MODIFIER LETTER SMALL I WITH STROKE: not included in any glyphset definition</li>
<li>U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition</li>
<li>U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+2081 SUBSCRIPT ONE: not included in any glyphset definition</li>
<li>U+2082 SUBSCRIPT TWO: not included in any glyphset definition</li>
<li>U+2083 SUBSCRIPT THREE: not included in any glyphset definition</li>
<li>U+2084 SUBSCRIPT FOUR: not included in any glyphset definition</li>
<li>U+2085 SUBSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2086 SUBSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2089 SUBSCRIPT NINE: not included in any glyphset definition</li>
<li>U+2126 OHM SIGN: not included in any glyphset definition</li>
<li>U+212E ESTIMATED SYMBOL: not included in any glyphset definition</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25AA BLACK SMALL SQUARE: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols</li>
<li>U+25C6 BLACK DIAMOND: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: duployan, thai, newa, syloti-nagri, bengali, pahawh-hmong, khudawadi, chakma, saurashtra, tagalog, telugu, yi, lepcha, mende-kikakui, nko, armenian, batak, elbasan, wancho, sogdian, mongolian, phags-pa, manichaean, old-permic, hebrew, oriya, math, rejang, tai-tham, bassa-vah, music, tirhuta, ahom, brahmi, warang-citi, hanifi-rohingya, thaana, marchen, syriac, myanmar, sharada, mahajani, adlam, coptic, grantha, lao, cham, javanese, khmer, dogra, siddham, balinese, osage, meetei-mayek, sundanese, tai-viet, limbu, caucasian-albanian, hanunoo, new-tai-lue, zanabazar-square, tai-le, buginese, symbols, tibetan, tamil, mandaic, psalter-pahlavi, miao, bhaiksuki, soyombo, kaithi, devanagari, gujarati, khojki, takri, canadian-aboriginal, modi, masaram-gondi, kayah-li, sinhala, malayalam, kannada, gurmukhi, kharoshthi, gunjala-gondi, tagbanwa, buhid, tifinagh</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math</li>
<li>U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + f

- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 9 | 113 | 7 | 116 | 0 | 
| 0% | 0% | 1% | 4% | 46% | 3% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
