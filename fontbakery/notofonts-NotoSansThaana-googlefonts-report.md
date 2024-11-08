## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[7] NotoSansThaana[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 1 start point differs in glyph 'javiyanithaana' between location wght=400 and location wght=100

- Contour 1 in glyph 'javiyanithaana': becomes underweight between wght=400 and wght=100.

- Contour 1 start point differs in glyph 'javiyanithaana' between location wght=100 and location wght=699

- Contour 1 in glyph 'javiyanithaana': becomes underweight between wght=100 and wght=699.

- Contour 1 point 8 in glyph 'javiyanithaana' has a kink between location wght=100 and location wght=699
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansThaana/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: hebrew, syriac, tifinagh, todhri, old-permic, tai-le, malayalam, canadian-aboriginal, duployan, math, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+066D ARABIC FIVE POINTED STAR: try adding arabic</li>
<li>U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic</li>
<li>U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic</li>
<li>U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>thaana</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mango (Latn, 77,000 speakers), Sar (Latn, 500,000 speakers), Vute (Latn, 21,000 speakers), Zapotec (Latn, 490,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mundani (Latn, 34,000 speakers), Han (Latn, 6 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Cicipu (Latn, 44,000 speakers), Kaska (Latn, 125 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Dan (Latn, 1,099,244 speakers), Bafut (Latn, 158,146 speakers), Mfumte (Latn, 79,000 speakers), Lugbara (Latn, 2,200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Nzakara (Latn, 50,000 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Southern Kisi (Latn, 360,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ejagham (Latn, 120,000 speakers), Nateni (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Makaa (Latn, 221,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Aghem (Latn, 38,843 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 6 | 97 | 7 | 140 | 0 | 
| 0% | 0% | 0% | 2% | 39% | 3% | 56% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG