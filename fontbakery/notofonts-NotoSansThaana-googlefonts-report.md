## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[10] NotoSansThaana-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* ellipsis
	* exclam
	* parenleft
	* parenright
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesinglbase
	* semicolon
	* uni061B
	* uni061F
	* uni0663
	* uni066A
	* uniFDF2 and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<164.0,78.0>--<164.0,76.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* a (U+0061) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* d (U+0064) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* m (U+006D) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* n (U+006E) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* p (U+0070) contains a short segment L<<169.0,463.0>--<173.0,463.0>>

	* r (U+0072) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* u (U+0075) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ntilde (U+00D1) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* germandbls (U+00DF) contains a short segment B<<382.0,412.0>-<382.0,399.0>-<388.5,388.0>>

	* agrave (U+00E0) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aacute (U+00E1) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* acircumflex (U+00E2) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* atilde (U+00E3) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* adieresis (U+00E4) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aring (U+00E5) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* ntilde (U+00F1) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* ugrave (U+00F9) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* amacron (U+0101) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* abreve (U+0103) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aogonek (U+0105) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* dcaron (U+010F) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<445.0,72.0>--<441.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Nacute (U+0143) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* nacute (U+0144) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* uni0145 (U+0145) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* uni0145 (U+0145) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* uni0146 (U+0146) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Ncaron (U+0147) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ncaron (U+0147) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* ncaron (U+0148) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Eng (U+014A) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Eng (U+014A) contains a short segment L<<582.0,142.0>--<586.0,142.0>>

	* eng (U+014B) contains a short segment L<<170.0,463.0>--<175.0,463.0>>

	* racute (U+0155) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* uni0157 (U+0157) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* rcaron (U+0159) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* umacron (U+016B) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uring (U+016F) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<539.5,-158.5>-<551.0,-156.0>-<559.0,-155.0>>

	* uogonek (U+0173) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Wcircumflex (U+0174) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* uni0668 (U+0668) contains a short segment L<<321.0,680.0>--<321.0,680.0>>

	* uni0668 (U+0668) contains a short segment L<<321.0,680.0>--<322.0,680.0>>

	* uni066D (U+066D) contains a short segment L<<102.0,0.0>--<97.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<17.0,279.0>--<19.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<254.0,458.0>--<261.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<496.0,287.0>--<498.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<418.0,3.0>--<413.0,-1.0>>

	* noonuthaana (U+0782) contains a short segment L<<310.0,303.0>--<310.0,303.0>>

	* raathaana (U+0783) contains a short segment B<<256.0,270.0>-<255.0,273.0>-<255.0,277.0>>

	* dhaaluthaana (U+078B) contains a short segment B<<265.0,236.0>-<265.0,234.0>-<265.0,232.0>>

	* zaviyanithaana (U+0792) contains a short segment B<<208.0,278.0>-<207.0,282.0>-<207.0,288.0>>

	* thaaluthaana (U+079B) contains a short segment B<<275.0,236.0>-<275.0,234.0>-<275.0,232.0>>

	* zaathaana (U+079C) contains a short segment B<<256.0,270.0>-<255.0,273.0>-<255.0,277.0>>

	* Wgrave (U+1E80) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wacute (U+1E82) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wdieresis (U+1E84) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Euro (U+20AC) contains a short segment B<<184.0,390.0>-<183.0,380.0>-<183.0,371.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,371.0>-<183.0,362.0>-<183.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,352.0>-<183.0,343.0>-<183.0,332.5>>

	* Euro (U+20AC) contains a short segment B<<183.0,332.5>-<183.0,322.0>-<184.0,311.0>>

	* Euro (U+20AC) contains a short segment B<<95.0,311.0>-<94.0,323.0>-<94.0,331.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,331.0>-<94.0,339.0>-<94.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,352.0>-<94.0,363.0>-<94.5,373.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,373.5>-<95.0,384.0>-<95.0,390.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<321.0,680.0>--<321.0,680.0>> -> L<<321.0,680.0>--<322.0,680.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nine
	* one
	* parenleft
	* parenright
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* uni0661
	* uni0662
	* uni0663
	* uni0664
	* uni0665
	* uni0666
	* uni0667
	* uni0668
	* uni0669
	* uniFDF2 and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thaana SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<209.0,113.0>--<209.0,109.0>>

	* at (U+0040) contains a short segment B<<628.0,295.0>-<628.0,282.0>-<627.5,272.5>>

	* at (U+0040) contains a short segment B<<627.5,272.5>-<627.0,263.0>-<627.0,260.0>>

	* M (U+004D) contains a short segment L<<206.0,582.0>--<202.0,582.0>>

	* M (U+004D) contains a short segment L<<460.0,155.0>--<463.0,155.0>>

	* N (U+004E) contains a short segment L<<205.0,558.0>--<201.0,558.0>>

	* N (U+004E) contains a short segment L<<588.0,160.0>--<591.0,160.0>>

	* Q (U+0051) contains a short segment B<<411.0,-10.0>-<407.0,-10.0>-<403.5,-10.0>>

	* Q (U+0051) contains a short segment B<<403.5,-10.0>-<400.0,-10.0>-<396.0,-10.0>>

	* a (U+0061) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* d (U+0064) contains a short segment L<<423.0,71.0>--<418.0,71.0>>

	* m (U+006D) contains a short segment L<<198.0,472.0>--<205.0,472.0>>

	* n (U+006E) contains a short segment L<<198.0,472.0>--<205.0,472.0>>

	* p (U+0070) contains a short segment L<<203.0,471.0>--<209.0,471.0>>

	* r (U+0072) contains a short segment L<<198.0,449.0>--<204.0,449.0>>

	* u (U+0075) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* Ntilde (U+00D1) contains a short segment L<<205.0,558.0>--<201.0,558.0>>

	* Ntilde (U+00D1) contains a short segment L<<588.0,160.0>--<591.0,160.0>>

	* germandbls (U+00DF) contains a short segment B<<441.0,409.0>-<441.0,396.0>-<449.5,385.5>>

	* agrave (U+00E0) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aacute (U+00E1) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* acircumflex (U+00E2) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* atilde (U+00E3) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* adieresis (U+00E4) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aring (U+00E5) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* ntilde (U+00F1) contains a short segment L<<198.0,472.0>--<205.0,472.0>>

	* ugrave (U+00F9) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* uacute (U+00FA) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* ucircumflex (U+00FB) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* udieresis (U+00FC) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* amacron (U+0101) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* abreve (U+0103) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aogonek (U+0105) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* dcaron (U+010F) contains a short segment L<<423.0,71.0>--<418.0,71.0>>

	* dcroat (U+0111) contains a short segment L<<423.0,71.0>--<418.0,71.0>>

	* Nacute (U+0143) contains a short segment L<<205.0,558.0>--<201.0,558.0>>

	* Nacute (U+0143) contains a short segment L<<588.0,160.0>--<591.0,160.0>>

	* nacute (U+0144) contains a short segment L<<198.0,472.0>--<205.0,472.0>>

	* uni0145 (U+0145) contains a short segment L<<205.0,558.0>--<201.0,558.0>>

	* uni0145 (U+0145) contains a short segment L<<588.0,160.0>--<591.0,160.0>>

	* uni0146 (U+0146) contains a short segment L<<198.0,472.0>--<205.0,472.0>>

	* Ncaron (U+0147) contains a short segment L<<205.0,558.0>--<201.0,558.0>>

	* Ncaron (U+0147) contains a short segment L<<588.0,160.0>--<591.0,160.0>>

	* ncaron (U+0148) contains a short segment L<<198.0,472.0>--<205.0,472.0>>

	* Eng (U+014A) contains a short segment L<<205.0,558.0>--<201.0,558.0>>

	* Eng (U+014A) contains a short segment L<<588.0,230.0>--<591.0,230.0>>

	* eng (U+014B) contains a short segment L<<198.0,472.0>--<206.0,472.0>>

	* racute (U+0155) contains a short segment L<<198.0,449.0>--<204.0,449.0>>

	* uni0157 (U+0157) contains a short segment L<<198.0,449.0>--<204.0,449.0>>

	* rcaron (U+0159) contains a short segment L<<198.0,449.0>--<204.0,449.0>>

	* umacron (U+016B) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* ubreve (U+016D) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* uring (U+016F) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* Uogonek (U+0172) contains a short segment B<<550.5,-151.5>-<564.0,-149.0>-<573.0,-146.0>>

	* uogonek (U+0173) contains a short segment L<<446.0,70.0>--<439.0,70.0>>

	* uni0668 (U+0668) contains a short segment L<<351.0,683.0>--<351.0,683.0>>

	* uni0668 (U+0668) contains a short segment L<<351.0,683.0>--<352.0,683.0>>

	* uni066D (U+066D) contains a short segment L<<99.0,0.0>--<94.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<14.0,279.0>--<16.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<251.0,458.0>--<258.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<492.0,287.0>--<494.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<414.0,3.0>--<409.0,-1.0>>

	* raathaana (U+0783) contains a short segment B<<250.0,276.0>-<248.0,280.0>-<248.0,286.0>>

	* lhaviyanithaana (U+0785) contains a short segment B<<181.0,264.0>-<178.0,264.0>-<174.0,264.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<264.0,315.0>-<269.0,315.0>-<275.0,315.0>>

	* zaathaana (U+079C) contains a short segment B<<250.0,276.0>-<248.0,280.0>-<248.0,286.0>>

	* Euro (U+20AC) contains a short segment B<<219.0,382.0>-<219.0,376.0>-<218.5,368.5>>

	* Euro (U+20AC) contains a short segment B<<218.5,368.5>-<218.0,361.0>-<218.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<218.0,352.0>-<218.0,344.0>-<218.5,335.5>>

	* Euro (U+20AC) contains a short segment B<<218.5,335.5>-<219.0,327.0>-<219.0,318.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<351.0,683.0>--<351.0,683.0>> -> L<<351.0,683.0>--<352.0,683.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* W (U+0057): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* Wacute (U+1E82): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* Wcircumflex (U+0174): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* Wdieresis (U+1E84): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* Wgrave (U+1E80): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* ellipsis
	* exclam
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* uni061F
	* uni0660
	* uni0661
	* uni0662
	* uni0663
	* uni0664
	* uni0665
	* uni0666
	* uni0667
	* uni0668
	* uni0669
	* uni066A
	* uniFDF2 and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=236.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=343.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=440.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=545.0,Y=713.0 (should be at cap-height 714?)

	* three (U+0033): X=130.5,Y=1.0 (should be at baseline 0?)

	* four (U+0034): X=335.0,Y=715.0 (should be at cap-height 714?)

	* four (U+0034): X=476.0,Y=715.0 (should be at cap-height 714?)

	* six (U+0036): X=499.0,Y=715.0 (should be at cap-height 714?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=543.0,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

	* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=295.0,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=288.5,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=481.0,Y=536.5 (should be at x-height 536?)

	* m (U+006D): X=627.5,Y=537.0 (should be at x-height 536?)

	* n (U+006E): X=291.5,Y=537.0 (should be at x-height 536?)

	* sterling (U+00A3): X=444.5,Y=712.5 (should be at cap-height 714?)

	* Ccedilla (U+00C7): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=758.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=0.5 (should be at baseline 0?)

	* ccedilla (U+00E7): X=394.5,Y=-0.5 (should be at baseline 0?)

	* egrave (U+00E8): X=432.5,Y=-0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=432.5,Y=-0.5 (should be at baseline 0?)

	* abreve (U+0103): X=249.0,Y=713.5 (should be at cap-height 714?)

	* abreve (U+0103): X=348.5,Y=714.5 (should be at cap-height 714?)

	* Cacute (U+0106): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cacute (U+0107): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=394.5,Y=-0.5 (should be at baseline 0?)

	* emacron (U+0113): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=432.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gbreve (U+011F): X=555.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=261.0,Y=713.5 (should be at cap-height 714?)

	* gbreve (U+011F): X=360.5,Y=714.5 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gdotaccent (U+0121): X=555.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=527.5,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=543.0,Y=712.0 (should be at cap-height 714?)

	* uni0123 (U+0123): X=555.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=591.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

	* ubreve (U+016D): X=276.0,Y=713.5 (should be at cap-height 714?)

	* ubreve (U+016D): X=375.5,Y=714.5 (should be at cap-height 714?)

	* breve (U+02D8): X=179.0,Y=713.5 (should be at cap-height 714?)

	* breve (U+02D8): X=278.5,Y=714.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=-50.0,Y=713.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=49.5,Y=714.5 (should be at cap-height 714?)

	* uni0661 (U+0661): X=262.0,Y=1.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=262.0,Y=1.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=259.0,Y=1.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=259.0,Y=1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=259.0,Y=1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=259.0,Y=1.0 (should be at baseline 0?)

	* uni066D (U+066D): X=407.0,Y=-1.0 (should be at baseline 0?)

	* thaathaana (U+078C): X=221.0,Y=1.0 (should be at baseline 0?)

	* chaviyanithaana (U+0797): X=231.0,Y=1.0 (should be at baseline 0?)

	* ttaathaana (U+0798): X=251.0,Y=1.0 (should be at baseline 0?)

	* saadhuthaana (U+079E): X=527.5,Y=-2.0 (should be at baseline 0?)

	* tothaana (U+07A0): X=221.0,Y=1.0 (should be at baseline 0?)

	* zothaana (U+07A1): X=221.0,Y=1.0 (should be at baseline 0?)

	* ebefilithaana (U+07AC): X=185.0,Y=713.0 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=232.0,Y=713.0 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=400.0,Y=713.0 (should be at cap-height 714?)

	* uni1E9E (U+1E9E): X=371.5,Y=-1.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=685.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1718.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=378.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=263.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1382.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.0,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1158.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1135.0,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<232.0,130.0>--<232.0,126.0>>

	* at (U+0040) contains a short segment B<<636.0,296.0>-<635.0,286.0>-<635.0,275.5>>

	* at (U+0040) contains a short segment B<<635.0,275.5>-<635.0,265.0>-<635.0,262.0>>

	* at (U+0040) contains a short segment B<<646.5,207.5>-<658.0,194.0>-<672.0,194.0>>

	* M (U+004D) contains a short segment L<<220.0,560.0>--<216.0,560.0>>

	* M (U+004D) contains a short segment L<<465.0,168.0>--<468.0,168.0>>

	* N (U+004E) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* N (U+004E) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* Q (U+0051) contains a short segment L<<409.0,-10.0>--<398.0,-10.0>>

	* W (U+0057) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* a (U+0061) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* d (U+0064) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* m (U+006D) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* n (U+006E) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* p (U+0070) contains a short segment L<<220.0,475.0>--<227.0,475.0>>

	* r (U+0072) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* u (U+0075) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ordfeminine (U+00AA) contains a short segment L<<242.0,589.0>--<242.0,597.0>>

	* Ntilde (U+00D1) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Ntilde (U+00D1) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* agrave (U+00E0) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aacute (U+00E1) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* acircumflex (U+00E2) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* atilde (U+00E3) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* adieresis (U+00E4) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aring (U+00E5) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* ntilde (U+00F1) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* ugrave (U+00F9) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uacute (U+00FA) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ucircumflex (U+00FB) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* udieresis (U+00FC) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* amacron (U+0101) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* abreve (U+0103) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aogonek (U+0105) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* dcaron (U+010F) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* dcroat (U+0111) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* hbar (U+0127) contains a short segment L<<227.0,584.0>--<227.0,575.0>>

	* Nacute (U+0143) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Nacute (U+0143) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* nacute (U+0144) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* uni0145 (U+0145) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* uni0145 (U+0145) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* uni0146 (U+0146) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* Ncaron (U+0147) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Ncaron (U+0147) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* ncaron (U+0148) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* Eng (U+014A) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Eng (U+014A) contains a short segment L<<591.0,274.0>--<594.0,274.0>>

	* eng (U+014B) contains a short segment L<<212.0,476.0>--<221.0,476.0>>

	* racute (U+0155) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* uni0157 (U+0157) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* rcaron (U+0159) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* umacron (U+016B) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ubreve (U+016D) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uring (U+016F) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uogonek (U+0173) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* Wcircumflex (U+0174) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* uni0668 (U+0668) contains a short segment L<<366.0,685.0>--<366.0,685.0>>

	* uni0668 (U+0668) contains a short segment L<<366.0,685.0>--<367.0,685.0>>

	* uni066D (U+066D) contains a short segment L<<98.0,0.0>--<93.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<13.0,279.0>--<15.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<249.0,458.0>--<256.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<490.0,287.0>--<492.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<412.0,3.0>--<407.0,-1.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<273.0,322.0>-<277.0,322.0>-<282.0,322.0>>

	* Wgrave (U+1E80) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Wacute (U+1E82) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Wdieresis (U+1E84) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Euro (U+20AC) contains a short segment B<<237.0,378.0>-<237.0,374.0>-<236.5,367.5>>

	* Euro (U+20AC) contains a short segment B<<236.5,367.5>-<236.0,361.0>-<236.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<236.0,352.0>-<236.0,345.0>-<236.0,337.5>>

	* Euro (U+20AC) contains a short segment B<<236.0,337.5>-<236.0,330.0>-<237.0,322.0>>

	* Euro (U+20AC) contains a short segment B<<88.0,352.0>-<88.0,360.0>-<88.0,367.0>>

	* Euro (U+20AC) contains a short segment B<<88.0,367.0>-<88.0,374.0>-<89.0,378.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* uniFDFD (U+FDFD) contains a short segment B<<1484.0,399.0>-<1484.0,390.0>-<1489.5,383.5>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<366.0,685.0>--<366.0,685.0>> -> L<<366.0,685.0>--<367.0,685.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wdieresis (U+1E84): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wgrave (U+1E80): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* kaafuthaana (U+0786): L<<230.0,220.0>--<223.0,212.0>>/B<<223.0,212.0>-<248.0,240.0>-<278.5,275.0>> = 0.5743745381882183 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* parenleft
	* uni0663
	* uni0664 and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thaana Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniFDFD (U+FDFD): L<<479.0,369.0>--<479.0,373.0>> -> L<<479.0,373.0>--<476.0,452.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* lhaviyanithaana (U+0785): B<<245.5,269.5>-<278.0,307.0>-<300.0,333.0>>/B<<300.0,333.0>-<276.0,315.0>-<254.5,306.0>> = 12.89374404488216 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* ellipsis
	* exclam
	* period
	* periodcentered
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* quotesingle
	* semicolon
	* uni061B
	* uni061F
	* uni0660
	* uni0661
	* uni0662
	* uni0663
	* uni0664
	* uni0665
	* uni0666
	* uni0667
	* uni0668
	* uni0669
	* uni066A
	* uniFDF2 and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thaana Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* six (U+0036): X=510.0,Y=716.0 (should be at cap-height 714?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=506.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=143.0,Y=716.0 (should be at cap-height 714?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?)

	* r (U+0072): X=311.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=363.0,Y=-1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=506.0,Y=712.0 (should be at cap-height 714?)

	* agrave (U+00E0): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=447.5,Y=715.5 (should be at cap-height 714?)

	* acircumflex (U+00E2): X=179.5,Y=716.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=282.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=282.0,Y=-1.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=-1.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=444.5,Y=715.5 (should be at cap-height 714?)

	* ecircumflex (U+00EA): X=176.5,Y=716.0 (should be at cap-height 714?)

	* icircumflex (U+00EE): X=298.5,Y=715.5 (should be at cap-height 714?)

	* icircumflex (U+00EE): X=30.5,Y=716.0 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=454.5,Y=715.5 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=186.5,Y=716.0 (should be at cap-height 714?)

	* ucircumflex (U+00FB): X=470.5,Y=715.5 (should be at cap-height 714?)

	* ucircumflex (U+00FB): X=202.5,Y=716.0 (should be at cap-height 714?)

	* amacron (U+0101): X=282.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=282.0,Y=-1.5 (should be at baseline 0?)

	* Cacute (U+0106): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cacute (U+0106): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Cdotaccent (U+010A): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Ccaron (U+010C): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Gbreve (U+011E): X=545.5,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=386.0,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=545.5,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=386.0,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=545.5,Y=2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=577.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=386.0,Y=1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=363.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=590.5,Y=715.5 (should be at cap-height 714?)

	* wcircumflex (U+0175): X=322.5,Y=716.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=440.5,Y=715.5 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=172.5,Y=716.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=363.0,Y=-1.0 (should be at baseline 0?)

	* circumflex (U+02C6): X=396.5,Y=715.5 (should be at cap-height 714?)

	* circumflex (U+02C6): X=128.5,Y=716.0 (should be at cap-height 714?)

	* uni0302 (U+0302): X=129.5,Y=715.5 (should be at cap-height 714?)

	* uni0302 (U+0302): X=-138.5,Y=716.0 (should be at cap-height 714?)

	* uni066D (U+066D): X=403.0,Y=-1.0 (should be at baseline 0?)

	* gaafuthaana (U+078E): X=78.5,Y=-0.5 (should be at baseline 0?)

	* gnaviyanithaana (U+078F): X=69.5,Y=-1.0 (should be at baseline 0?)

	* zaviyanithaana (U+0792): X=105.0,Y=-0.5 (should be at baseline 0?)

	* javiyanithaana (U+0796): X=53.5,Y=-0.5 (should be at baseline 0?)

	* qaafuthaana (U+07A4): X=108.5,Y=-0.5 (should be at baseline 0?)

	* obofilithaana (U+07AE): X=396.5,Y=716.0 (should be at cap-height 714?)

	* uni1E9E (U+1E9E): X=401.0,Y=-1.0 (should be at baseline 0?)

	* quoteright (U+2019): X=227.0,Y=712.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=35.0,Y=715.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=227.0,Y=712.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=35.0,Y=715.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=474.0,Y=712.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=282.0,Y=715.0 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=686.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1719.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=378.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=261.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1383.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1258.0,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1159.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1137.0,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<396.0,689.0>--<396.0,689.0>> -> L<<396.0,689.0>--<397.0,689.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wdieresis (U+1E84): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wdieresis (U+1E84): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wdieresis (U+1E84): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wgrave (U+1E80): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wgrave (U+1E80): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wgrave (U+1E80): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* ainuthaana (U+07A2): B<<299.5,121.0>-<305.0,160.0>-<310.0,209.0>>/L<<310.0,209.0>--<309.0,205.0>> = 8.209901438370684

	* alifuthaana (U+0787): B<<299.5,121.0>-<305.0,160.0>-<310.0,209.0>>/L<<310.0,209.0>--<309.0,205.0>> = 8.209901438370684

	* ghainuthaana (U+07A3): B<<319.5,121.0>-<325.0,160.0>-<330.0,209.0>>/L<<330.0,209.0>--<329.0,205.0>> = 8.209901438370684

	* uni0667 (U+0667): L<<405.0,12.0>--<238.0,-10.0>>/L<<238.0,-10.0>--<238.0,-10.0>> = 7.504732450611929 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansThaana-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Cdotaccent
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Eth
	* F
	* G
	* Gbreve
	* Gdotaccent
	* H
	* Hbar
	* I
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* J
	* K
	* L
	* Lacute
	* Lcaron
	* Lslash
	* M
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohungarumlaut
	* Omacron
	* Oslash
	* Otilde
	* P
	* Q
	* R
	* Racute
	* Rcaron
	* S
	* Sacute
	* Scaron
	* Scedilla
	* T
	* Tcaron
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Uring
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* a
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* amacron
	* ampersand
	* aogonek
	* aring
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* bar
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* c
	* cacute
	* ccaron
	* ccedilla
	* cdotaccent
	* cent
	* copyright
	* d
	* dcaron
	* dcroat
	* dollar
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* emacron
	* emdash
	* eng
	* eogonek
	* equal
	* eth
	* f
	* five
	* four
	* g
	* gbreve
	* gdotaccent
	* germandbls
	* h
	* hbar
	* iacute
	* icircumflex
	* idieresis
	* imacron
	* iogonek
	* j
	* k
	* l
	* lacute
	* lcaron
	* lslash
	* m
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* ntilde
	* numbersign
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohungarumlaut
	* omacron
	* one
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* percent
	* q
	* question
	* questiondown
	* r
	* racute
	* rcaron
	* registered
	* s
	* sacute
	* scaron
	* scedilla
	* section
	* seven
	* six
	* sterling
	* t
	* tcaron
	* thorn
	* three
	* trademark
	* two
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhungarumlaut
	* umacron
	* uni0661
	* uni0662
	* uni0663
	* uni0664
	* uni0665
	* uni0666
	* uni0667
	* uni0668
	* uni0669
	* uniFDF2
	* uniFDFD
	* uogonek
	* uring
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent and zero
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thaana Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<141.0,61.0>--<141.0,59.0>>

	* at (U+0040) contains a short segment B<<606.0,309.0>-<605.0,291.0>-<604.5,277.5>>

	* at (U+0040) contains a short segment B<<604.5,277.5>-<604.0,264.0>-<604.0,253.0>>

	* M (U+004D) contains a short segment L<<161.0,644.0>--<158.0,644.0>>

	* M (U+004D) contains a short segment L<<439.0,102.0>--<443.0,102.0>>

	* N (U+004E) contains a short segment L<<161.0,614.0>--<157.0,614.0>>

	* N (U+004E) contains a short segment L<<577.0,102.0>--<580.0,102.0>>

	* Q (U+0051) contains a short segment B<<415.0,-9.0>-<408.0,-9.0>-<400.5,-9.5>>

	* Q (U+0051) contains a short segment B<<400.5,-9.5>-<393.0,-10.0>-<386.0,-10.0>>

	* a (U+0061) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* d (U+0064) contains a short segment L<<454.0,86.0>--<451.0,86.0>>

	* m (U+006D) contains a short segment L<<151.0,453.0>--<155.0,453.0>>

	* n (U+006E) contains a short segment L<<151.0,448.0>--<155.0,448.0>>

	* p (U+0070) contains a short segment L<<151.0,443.0>--<154.0,443.0>>

	* r (U+0072) contains a short segment L<<150.0,434.0>--<154.0,434.0>>

	* u (U+0075) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* Ntilde (U+00D1) contains a short segment L<<161.0,614.0>--<157.0,614.0>>

	* Ntilde (U+00D1) contains a short segment L<<577.0,102.0>--<580.0,102.0>>

	* agrave (U+00E0) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* aacute (U+00E1) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* acircumflex (U+00E2) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* atilde (U+00E3) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* adieresis (U+00E4) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* aring (U+00E5) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* ntilde (U+00F1) contains a short segment L<<151.0,448.0>--<155.0,448.0>>

	* ugrave (U+00F9) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* uacute (U+00FA) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* ucircumflex (U+00FB) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* udieresis (U+00FC) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* amacron (U+0101) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* abreve (U+0103) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* aogonek (U+0105) contains a short segment L<<400.0,85.0>--<397.0,85.0>>

	* dcaron (U+010F) contains a short segment L<<454.0,86.0>--<451.0,86.0>>

	* dcroat (U+0111) contains a short segment L<<453.0,86.0>--<450.0,86.0>>

	* eogonek (U+0119) contains a short segment B<<479.0,24.0>-<477.0,23.0>-<475.0,22.0>>

	* Nacute (U+0143) contains a short segment L<<161.0,614.0>--<157.0,614.0>>

	* Nacute (U+0143) contains a short segment L<<577.0,102.0>--<580.0,102.0>>

	* nacute (U+0144) contains a short segment L<<151.0,448.0>--<155.0,448.0>>

	* uni0145 (U+0145) contains a short segment L<<161.0,614.0>--<157.0,614.0>>

	* uni0145 (U+0145) contains a short segment L<<577.0,102.0>--<580.0,102.0>>

	* uni0146 (U+0146) contains a short segment L<<151.0,448.0>--<155.0,448.0>>

	* Ncaron (U+0147) contains a short segment L<<161.0,614.0>--<157.0,614.0>>

	* Ncaron (U+0147) contains a short segment L<<577.0,102.0>--<580.0,102.0>>

	* ncaron (U+0148) contains a short segment L<<151.0,448.0>--<155.0,448.0>>

	* Eng (U+014A) contains a short segment L<<161.0,614.0>--<157.0,614.0>>

	* Eng (U+014A) contains a short segment L<<577.0,115.0>--<580.0,115.0>>

	* eng (U+014B) contains a short segment L<<152.0,448.0>--<156.0,448.0>>

	* racute (U+0155) contains a short segment L<<150.0,434.0>--<154.0,434.0>>

	* uni0157 (U+0157) contains a short segment L<<150.0,434.0>--<154.0,434.0>>

	* rcaron (U+0159) contains a short segment L<<150.0,434.0>--<154.0,434.0>>

	* umacron (U+016B) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* ubreve (U+016D) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* uring (U+016F) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* Uogonek (U+0172) contains a short segment B<<531.0,-169.0>-<543.0,-167.0>-<552.0,-165.0>>

	* uogonek (U+0173) contains a short segment L<<451.0,84.0>--<447.0,84.0>>

	* uni0668 (U+0668) contains a short segment L<<306.0,678.0>--<306.0,678.0>>

	* uni0668 (U+0668) contains a short segment L<<306.0,678.0>--<307.0,678.0>>

	* uni066D (U+066D) contains a short segment L<<103.0,0.0>--<98.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<18.0,279.0>--<20.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<256.0,458.0>--<263.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<498.0,287.0>--<500.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<420.0,3.0>--<415.0,-1.0>>

	* shaviyanithaana (U+0781) contains a short segment B<<300.0,306.0>-<300.0,304.0>-<300.0,304.0>>

	* noonuthaana (U+0782) contains a short segment B<<300.0,306.0>-<300.0,302.0>-<300.0,298.0>>

	* raathaana (U+0783) contains a short segment B<<256.0,266.0>-<255.0,269.0>-<255.0,272.0>>

	* dhaaluthaana (U+078B) contains a short segment B<<249.0,235.0>-<249.0,231.0>-<249.0,227.0>>

	* seenuthaana (U+0790) contains a short segment B<<231.0,287.0>-<231.0,285.0>-<231.0,284.0>>

	* seenuthaana (U+0790) contains a short segment B<<208.0,224.0>-<206.0,221.0>-<204.0,217.0>>

	* zaviyanithaana (U+0792) contains a short segment B<<204.0,275.0>-<203.0,278.0>-<203.0,282.0>>

	* javiyanithaana (U+0796) contains a short segment B<<200.0,261.0>-<202.0,256.0>-<202.0,250.0>>

	* thaaluthaana (U+079B) contains a short segment B<<256.0,235.0>-<256.0,231.0>-<256.0,227.0>>

	* zaathaana (U+079C) contains a short segment B<<256.0,266.0>-<255.0,269.0>-<255.0,272.0>>

	* sheenuthaana (U+079D) contains a short segment B<<231.0,287.0>-<231.0,285.0>-<231.0,284.0>>

	* sheenuthaana (U+079D) contains a short segment B<<208.0,224.0>-<206.0,221.0>-<204.0,217.0>>

	* saadhuthaana (U+079E) contains a short segment B<<231.0,287.0>-<231.0,285.0>-<231.0,284.0>>

	* saadhuthaana (U+079E) contains a short segment B<<208.0,224.0>-<206.0,221.0>-<204.0,217.0>>

	* daadhuthaana (U+079F) contains a short segment B<<231.0,287.0>-<231.0,285.0>-<231.0,284.0>>

	* daadhuthaana (U+079F) contains a short segment B<<208.0,224.0>-<206.0,221.0>-<204.0,217.0>>

	* Euro (U+20AC) contains a short segment B<<177.0,397.0>-<176.0,387.0>-<175.5,375.5>>

	* Euro (U+20AC) contains a short segment B<<175.5,327.0>-<176.0,315.0>-<177.0,304.0>>

	* Euro (U+20AC) contains a short segment B<<107.5,376.5>-<108.0,390.0>-<108.0,397.0>>

	* trademark (U+2122) contains a short segment L<<362.0,647.0>--<359.0,647.0>>

	* uniFDFD (U+FDFD) contains a short segment L<<476.0,373.0>--<476.0,373.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<306.0,678.0>--<306.0,678.0>> -> L<<306.0,678.0>--<307.0,678.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansThaana-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Cdotaccent
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Eth
	* F
	* G
	* Gbreve
	* Gdotaccent
	* H
	* Hbar
	* I
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* J
	* K
	* L
	* Lacute
	* Lcaron
	* Lslash
	* M
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohungarumlaut
	* Omacron
	* Oslash
	* Otilde
	* P
	* Q
	* R
	* Racute
	* Rcaron
	* S
	* Sacute
	* Scaron
	* Scedilla
	* T
	* Tcaron
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Uring
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* a
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* amacron
	* ampersand
	* aogonek
	* aring
	* asterisk
	* at
	* atilde
	* b
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* c
	* cacute
	* ccaron
	* ccedilla
	* cdotaccent
	* cent
	* copyright
	* d
	* dcaron
	* dcroat
	* dollar
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* emacron
	* eng
	* eogonek
	* eth
	* f
	* five
	* four
	* g
	* gbreve
	* gdotaccent
	* germandbls
	* h
	* hbar
	* j
	* k
	* lacute
	* lcaron
	* lslash
	* m
	* n
	* nacute
	* ncaron
	* nine
	* ntilde
	* numbersign
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohungarumlaut
	* omacron
	* one
	* oslash
	* otilde
	* p
	* paragraph
	* percent
	* q
	* racute
	* rcaron
	* registered
	* s
	* sacute
	* scaron
	* scedilla
	* section
	* seven
	* six
	* sterling
	* t
	* tcaron
	* thorn
	* three
	* trademark
	* two
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhungarumlaut
	* umacron
	* uni0661
	* uni0662
	* uni0663
	* uni0664
	* uni0665
	* uni0667
	* uni0668
	* uni0669
	* uni066A
	* uniFDF2
	* uniFDFD
	* uogonek
	* uring
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent and zero
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thaana ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<118.0,43.0>--<118.0,42.0>>

	* M (U+004D) contains a short segment L<<146.0,661.0>--<143.0,661.0>>

	* M (U+004D) contains a short segment L<<428.0,75.0>--<431.0,75.0>>

	* N (U+004E) contains a short segment L<<145.0,634.0>--<143.0,634.0>>

	* N (U+004E) contains a short segment L<<572.0,82.0>--<575.0,82.0>>

	* a (U+0061) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* d (U+0064) contains a short segment L<<462.0,99.0>--<459.0,99.0>>

	* k (U+006B) contains a short segment L<<133.0,227.0>--<133.0,227.0>>

	* m (U+006D) contains a short segment L<<133.0,442.0>--<136.0,442.0>>

	* n (U+006E) contains a short segment L<<133.0,432.0>--<136.0,432.0>>

	* p (U+0070) contains a short segment L<<133.0,422.0>--<136.0,422.0>>

	* r (U+0072) contains a short segment L<<134.0,431.0>--<136.0,431.0>>

	* u (U+0075) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* Ntilde (U+00D1) contains a short segment L<<145.0,634.0>--<143.0,634.0>>

	* Ntilde (U+00D1) contains a short segment L<<572.0,82.0>--<575.0,82.0>>

	* agrave (U+00E0) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* aacute (U+00E1) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* acircumflex (U+00E2) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* atilde (U+00E3) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* adieresis (U+00E4) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* aring (U+00E5) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* ntilde (U+00F1) contains a short segment L<<133.0,432.0>--<136.0,432.0>>

	* ugrave (U+00F9) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* uacute (U+00FA) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* ucircumflex (U+00FB) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* udieresis (U+00FC) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* amacron (U+0101) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* abreve (U+0103) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* aogonek (U+0105) contains a short segment L<<401.0,94.0>--<398.0,94.0>>

	* dcaron (U+010F) contains a short segment L<<462.0,99.0>--<459.0,99.0>>

	* dcroat (U+0111) contains a short segment L<<462.0,99.0>--<459.0,99.0>>

	* eogonek (U+0119) contains a short segment B<<469.0,24.0>-<464.0,22.0>-<460.0,20.0>>

	* uni0137 (U+0137) contains a short segment L<<133.0,227.0>--<133.0,227.0>>

	* Nacute (U+0143) contains a short segment L<<145.0,634.0>--<143.0,634.0>>

	* Nacute (U+0143) contains a short segment L<<572.0,82.0>--<575.0,82.0>>

	* nacute (U+0144) contains a short segment L<<133.0,432.0>--<136.0,432.0>>

	* uni0145 (U+0145) contains a short segment L<<145.0,634.0>--<143.0,634.0>>

	* uni0145 (U+0145) contains a short segment L<<572.0,82.0>--<575.0,82.0>>

	* uni0146 (U+0146) contains a short segment L<<133.0,432.0>--<136.0,432.0>>

	* Ncaron (U+0147) contains a short segment L<<145.0,634.0>--<143.0,634.0>>

	* Ncaron (U+0147) contains a short segment L<<572.0,82.0>--<575.0,82.0>>

	* ncaron (U+0148) contains a short segment L<<133.0,432.0>--<136.0,432.0>>

	* Eng (U+014A) contains a short segment L<<145.0,634.0>--<143.0,634.0>>

	* Eng (U+014A) contains a short segment L<<572.0,88.0>--<575.0,88.0>>

	* eng (U+014B) contains a short segment L<<133.0,432.0>--<136.0,432.0>>

	* racute (U+0155) contains a short segment L<<134.0,431.0>--<136.0,431.0>>

	* uni0157 (U+0157) contains a short segment L<<134.0,431.0>--<136.0,431.0>>

	* rcaron (U+0159) contains a short segment L<<134.0,431.0>--<136.0,431.0>>

	* umacron (U+016B) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* ubreve (U+016D) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* uring (U+016F) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* Uogonek (U+0172) contains a short segment B<<523.5,-180.0>-<536.0,-178.0>-<544.0,-175.0>>

	* Uogonek (U+0172) contains a short segment B<<544.0,-210.0>-<534.0,-213.0>-<520.5,-215.5>>

	* uogonek (U+0173) contains a short segment L<<453.0,98.0>--<451.0,98.0>>

	* uni0668 (U+0668) contains a short segment L<<291.0,676.0>--<291.0,676.0>>

	* uni0668 (U+0668) contains a short segment L<<291.0,676.0>--<291.0,676.0>>

	* uni066D (U+066D) contains a short segment L<<104.0,-1.0>--<99.0,3.0>>

	* uni066D (U+066D) contains a short segment L<<19.0,279.0>--<21.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<257.0,458.0>--<264.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<500.0,287.0>--<502.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<422.0,3.0>--<417.0,-1.0>>

	* shaviyanithaana (U+0781) contains a short segment B<<290.0,308.0>-<290.0,304.0>-<289.0,300.0>>

	* raathaana (U+0783) contains a short segment B<<255.0,262.0>-<254.0,265.0>-<254.0,267.0>>

	* thaathaana (U+078C) contains a short segment B<<214.0,36.0>-<214.0,33.0>-<213.5,26.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<227.0,297.0>-<227.0,294.0>-<227.0,292.0>>

	* seenuthaana (U+0790) contains a short segment B<<209.0,294.0>-<209.0,290.0>-<209.0,287.0>>

	* taviyanithaana (U+0793) contains a short segment L<<208.0,199.0>--<208.0,199.0>>

	* chaviyanithaana (U+0797) contains a short segment B<<345.0,414.0>-<350.0,414.0>-<354.0,414.0>>

	* chaviyanithaana (U+0797) contains a short segment B<<215.0,36.0>-<215.0,33.0>-<214.5,26.0>>

	* chaviyanithaana (U+0797) contains a short segment B<<214.5,26.0>-<214.0,19.0>-<212.0,14.0>>

	* ttaathaana (U+0798) contains a short segment B<<247.0,36.0>-<247.0,33.0>-<246.5,26.0>>

	* zaathaana (U+079C) contains a short segment B<<255.0,262.0>-<254.0,265.0>-<254.0,267.0>>

	* sheenuthaana (U+079D) contains a short segment B<<209.0,294.0>-<209.0,290.0>-<209.0,287.0>>

	* saadhuthaana (U+079E) contains a short segment B<<209.0,294.0>-<209.0,290.0>-<209.0,287.0>>

	* daadhuthaana (U+079F) contains a short segment B<<209.0,294.0>-<209.0,290.0>-<209.0,287.0>>

	* tothaana (U+07A0) contains a short segment B<<214.0,36.0>-<214.0,33.0>-<213.5,26.0>>

	* zothaana (U+07A1) contains a short segment B<<226.0,36.0>-<226.0,33.0>-<225.5,26.0>>

	* trademark (U+2122) contains a short segment L<<339.0,661.0>--<336.0,661.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<291.0,676.0>--<291.0,676.0>> -> L<<291.0,676.0>--<291.0,676.0>>

	* uniFDFD (U+FDFD): L<<478.0,371.0>--<478.0,373.0>> -> L<<478.0,373.0>--<475.0,450.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaana-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* ellipsis
	* exclam
	* nine
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* quotesingle
	* semicolon
	* uni061F
	* uni0660
	* uni0661
	* uni0662
	* uni0663
	* uni0664
	* uni0665
	* uni0666
	* uni0667
	* uni0668
	* uni0669
	* uni066A
	* uniFDF2 and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thaana ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 579 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<255.0,147.0>--<255.0,143.0>>

	* at (U+0040) contains a short segment B<<642.0,302.0>-<642.0,294.0>-<641.5,282.0>>

	* at (U+0040) contains a short segment B<<641.5,282.0>-<641.0,270.0>-<641.0,262.0>>

	* at (U+0040) contains a short segment B<<650.0,218.5>-<659.0,207.0>-<672.0,207.0>>

	* M (U+004D) contains a short segment L<<231.0,537.0>--<227.0,537.0>>

	* M (U+004D) contains a short segment L<<474.0,188.0>--<478.0,188.0>>

	* N (U+004E) contains a short segment L<<232.0,522.0>--<228.0,522.0>>

	* N (U+004E) contains a short segment L<<590.0,199.0>--<593.0,199.0>>

	* Q (U+0051) contains a short segment L<<407.0,-10.0>--<398.0,-10.0>>

	* W (U+0057) contains a short segment B<<534.0,343.0>-<532.0,353.0>-<527.5,374.5>>

	* W (U+0057) contains a short segment B<<476.5,374.5>-<472.0,353.0>-<470.0,343.0>>

	* a (U+0061) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* d (U+0064) contains a short segment L<<402.0,71.0>--<396.0,71.0>>

	* m (U+006D) contains a short segment L<<225.0,481.0>--<232.0,481.0>>

	* n (U+006E) contains a short segment L<<224.0,478.0>--<232.0,478.0>>

	* p (U+0070) contains a short segment L<<234.0,479.0>--<242.0,479.0>>

	* r (U+0072) contains a short segment L<<226.0,460.0>--<234.0,460.0>>

	* u (U+0075) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* ordfeminine (U+00AA) contains a short segment L<<239.0,589.0>--<239.0,595.0>>

	* Ntilde (U+00D1) contains a short segment L<<232.0,522.0>--<228.0,522.0>>

	* Ntilde (U+00D1) contains a short segment L<<590.0,199.0>--<593.0,199.0>>

	* agrave (U+00E0) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* aacute (U+00E1) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* acircumflex (U+00E2) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* atilde (U+00E3) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* adieresis (U+00E4) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* aring (U+00E5) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* ntilde (U+00F1) contains a short segment L<<224.0,478.0>--<232.0,478.0>>

	* ugrave (U+00F9) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* uacute (U+00FA) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* ucircumflex (U+00FB) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* udieresis (U+00FC) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* amacron (U+0101) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* abreve (U+0103) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* aogonek (U+0105) contains a short segment L<<393.0,74.0>--<389.0,74.0>>

	* dcaron (U+010F) contains a short segment L<<402.0,71.0>--<396.0,71.0>>

	* dcroat (U+0111) contains a short segment L<<395.0,71.0>--<389.0,71.0>>

	* hbar (U+0127) contains a short segment L<<247.0,577.0>--<247.0,563.0>>

	* Nacute (U+0143) contains a short segment L<<232.0,522.0>--<228.0,522.0>>

	* Nacute (U+0143) contains a short segment L<<590.0,199.0>--<593.0,199.0>>

	* nacute (U+0144) contains a short segment L<<224.0,478.0>--<232.0,478.0>>

	* uni0145 (U+0145) contains a short segment L<<232.0,522.0>--<228.0,522.0>>

	* uni0145 (U+0145) contains a short segment L<<590.0,199.0>--<593.0,199.0>>

	* uni0146 (U+0146) contains a short segment L<<224.0,478.0>--<232.0,478.0>>

	* Ncaron (U+0147) contains a short segment L<<232.0,522.0>--<228.0,522.0>>

	* Ncaron (U+0147) contains a short segment L<<590.0,199.0>--<593.0,199.0>>

	* ncaron (U+0148) contains a short segment L<<224.0,478.0>--<232.0,478.0>>

	* Eng (U+014A) contains a short segment L<<232.0,522.0>--<228.0,522.0>>

	* Eng (U+014A) contains a short segment L<<590.0,297.0>--<594.0,297.0>>

	* eng (U+014B) contains a short segment L<<223.0,481.0>--<234.0,481.0>>

	* racute (U+0155) contains a short segment L<<226.0,460.0>--<234.0,460.0>>

	* uni0157 (U+0157) contains a short segment L<<226.0,460.0>--<234.0,460.0>>

	* rcaron (U+0159) contains a short segment L<<226.0,460.0>--<234.0,460.0>>

	* umacron (U+016B) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* ubreve (U+016D) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* uring (U+016F) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* uogonek (U+0173) contains a short segment L<<441.0,70.0>--<431.0,70.0>>

	* Wcircumflex (U+0174) contains a short segment B<<534.0,343.0>-<532.0,353.0>-<527.5,374.5>>

	* Wcircumflex (U+0174) contains a short segment B<<476.5,374.5>-<472.0,353.0>-<470.0,343.0>>

	* uni0667 (U+0667) contains a short segment L<<240.0,-8.0>--<240.0,-8.0>>

	* uni0667 (U+0667) contains a short segment L<<240.0,-8.0>--<239.0,-8.0>>

	* uni0668 (U+0668) contains a short segment L<<381.0,687.0>--<381.0,687.0>>

	* uni0668 (U+0668) contains a short segment L<<381.0,687.0>--<382.0,687.0>>

	* uni066D (U+066D) contains a short segment L<<97.0,0.0>--<92.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<12.0,279.0>--<14.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<248.0,458.0>--<255.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<488.0,287.0>--<490.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<410.0,3.0>--<405.0,-1.0>>

	* noonuthaana (U+0782) contains a short segment B<<360.0,325.0>-<366.0,325.0>-<373.0,325.0>>

	* raathaana (U+0783) contains a short segment B<<254.0,286.0>-<253.0,290.0>-<253.0,295.0>>

	* zaathaana (U+079C) contains a short segment B<<254.0,286.0>-<253.0,290.0>-<253.0,295.0>>

	* Wgrave (U+1E80) contains a short segment B<<534.0,343.0>-<532.0,353.0>-<527.5,374.5>>

	* Wgrave (U+1E80) contains a short segment B<<476.5,374.5>-<472.0,353.0>-<470.0,343.0>>

	* Wacute (U+1E82) contains a short segment B<<534.0,343.0>-<532.0,353.0>-<527.5,374.5>>

	* Wacute (U+1E82) contains a short segment B<<476.5,374.5>-<472.0,353.0>-<470.0,343.0>>

	* Wdieresis (U+1E84) contains a short segment B<<534.0,343.0>-<532.0,353.0>-<527.5,374.5>>

	* Wdieresis (U+1E84) contains a short segment B<<476.5,374.5>-<472.0,353.0>-<470.0,343.0>>

	* Euro (U+20AC) contains a short segment B<<257.0,351.0>-<257.0,344.0>-<257.0,337.5>>

	* Euro (U+20AC) contains a short segment B<<257.0,337.5>-<257.0,331.0>-<258.0,325.0>>

	* Euro (U+20AC) contains a short segment B<<90.0,325.0>-<89.0,330.0>-<89.0,337.5>>

	* Euro (U+20AC) contains a short segment B<<89.0,337.5>-<89.0,345.0>-<89.0,351.0>>

	* trademark (U+2122) contains a short segment L<<398.0,622.0>--<394.0,622.0>>

	* uniFDFD (U+FDFD) contains a short segment B<<1486.0,403.0>-<1486.0,394.0>-<1491.0,388.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<381.0,687.0>--<381.0,687.0>> -> L<<381.0,687.0>--<382.0,687.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<327.0,211.0>-<334.0,179.0>-<336.0,158.0>>/B<<336.0,158.0>-<339.0,179.0>-<345.0,211.0>> = 13.570434385161475

	* W (U+0057): B<<285.5,212.5>-<292.0,176.0>-<295.0,152.0>>/B<<295.0,152.0>-<299.0,185.0>-<307.0,229.0>> = 14.03624346792643

	* W (U+0057): B<<508.0,473.5>-<504.0,498.0>-<502.0,514.0>>/B<<502.0,514.0>-<500.0,498.0>-<496.0,473.5>> = 14.25003269780357

	* W (U+0057): B<<699.5,207.5>-<705.0,176.0>-<708.0,152.0>>/B<<708.0,152.0>-<711.0,177.0>-<717.5,213.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<285.5,212.5>-<292.0,176.0>-<295.0,152.0>>/B<<295.0,152.0>-<299.0,185.0>-<307.0,229.0>> = 14.03624346792643

	* Wacute (U+1E82): B<<508.0,473.5>-<504.0,498.0>-<502.0,514.0>>/B<<502.0,514.0>-<500.0,498.0>-<496.0,473.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<699.5,207.5>-<705.0,176.0>-<708.0,152.0>>/B<<708.0,152.0>-<711.0,177.0>-<717.5,213.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<285.5,212.5>-<292.0,176.0>-<295.0,152.0>>/B<<295.0,152.0>-<299.0,185.0>-<307.0,229.0>> = 14.03624346792643

	* Wcircumflex (U+0174): B<<508.0,473.5>-<504.0,498.0>-<502.0,514.0>>/B<<502.0,514.0>-<500.0,498.0>-<496.0,473.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<699.5,207.5>-<705.0,176.0>-<708.0,152.0>>/B<<708.0,152.0>-<711.0,177.0>-<717.5,213.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<285.5,212.5>-<292.0,176.0>-<295.0,152.0>>/B<<295.0,152.0>-<299.0,185.0>-<307.0,229.0>> = 14.03624346792643

	* Wdieresis (U+1E84): B<<508.0,473.5>-<504.0,498.0>-<502.0,514.0>>/B<<502.0,514.0>-<500.0,498.0>-<496.0,473.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<699.5,207.5>-<705.0,176.0>-<708.0,152.0>>/B<<708.0,152.0>-<711.0,177.0>-<717.5,213.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<285.5,212.5>-<292.0,176.0>-<295.0,152.0>>/B<<295.0,152.0>-<299.0,185.0>-<307.0,229.0>> = 14.03624346792643

	* Wgrave (U+1E80): B<<508.0,473.5>-<504.0,498.0>-<502.0,514.0>>/B<<502.0,514.0>-<500.0,498.0>-<496.0,473.5>> = 14.25003269780357

	* Wgrave (U+1E80): B<<699.5,207.5>-<705.0,176.0>-<708.0,152.0>>/B<<708.0,152.0>-<711.0,177.0>-<717.5,213.0>> = 13.967789761532726

	* uni0667 (U+0667): L<<389.0,12.0>--<240.0,-8.0>>/L<<240.0,-8.0>--<240.0,-8.0>> = 7.64501327167069 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Uogonek (U+0172): L<<678.0,714.0>--<677.0,268.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansThaana-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, old-permic, coptic, malayalam, canadian-aboriginal, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, yezidi, arabic
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: nko, arabic
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: nko, arabic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* ellipsis
	* nine
	* one
	* parenleft
	* parenright
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesinglbase
	* uni0661
	* uni0662
	* uni0663
	* uni0664
	* uni0666
	* uni0667
	* uni0668
	* uni0669
	* uniFDF2 and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thaana Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uniFDF2
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<187.0,95.0>--<187.0,93.0>>

	* at (U+0040) contains a short segment B<<621.0,294.0>-<620.0,278.0>-<620.0,270.0>>

	* at (U+0040) contains a short segment B<<620.0,270.0>-<620.0,262.0>-<620.0,259.0>>

	* M (U+004D) contains a short segment L<<191.0,604.0>--<187.0,604.0>>

	* M (U+004D) contains a short segment L<<455.0,142.0>--<459.0,142.0>>

	* N (U+004E) contains a short segment L<<191.0,575.0>--<187.0,575.0>>

	* N (U+004E) contains a short segment L<<585.0,142.0>--<589.0,142.0>>

	* Q (U+0051) contains a short segment B<<414.0,-9.0>-<409.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<398.0,-10.0>-<393.0,-10.0>>

	* a (U+0061) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* d (U+0064) contains a short segment L<<435.0,72.0>--<430.0,72.0>>

	* m (U+006D) contains a short segment L<<183.0,467.0>--<189.0,467.0>>

	* n (U+006E) contains a short segment L<<183.0,467.0>--<189.0,467.0>>

	* p (U+0070) contains a short segment L<<186.0,467.0>--<191.0,467.0>>

	* r (U+0072) contains a short segment L<<182.0,443.0>--<187.0,443.0>>

	* u (U+0075) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<191.0,575.0>--<187.0,575.0>>

	* Ntilde (U+00D1) contains a short segment L<<585.0,142.0>--<589.0,142.0>>

	* germandbls (U+00DF) contains a short segment B<<411.0,410.0>-<411.0,397.0>-<419.0,386.5>>

	* agrave (U+00E0) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* aacute (U+00E1) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* acircumflex (U+00E2) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* atilde (U+00E3) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* adieresis (U+00E4) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* aring (U+00E5) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* ntilde (U+00F1) contains a short segment L<<183.0,467.0>--<189.0,467.0>>

	* ugrave (U+00F9) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* amacron (U+0101) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* abreve (U+0103) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* aogonek (U+0105) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* dcaron (U+010F) contains a short segment L<<435.0,72.0>--<430.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<434.0,72.0>--<429.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<191.0,575.0>--<187.0,575.0>>

	* Nacute (U+0143) contains a short segment L<<585.0,142.0>--<589.0,142.0>>

	* nacute (U+0144) contains a short segment L<<183.0,467.0>--<189.0,467.0>>

	* uni0145 (U+0145) contains a short segment L<<191.0,575.0>--<187.0,575.0>>

	* uni0145 (U+0145) contains a short segment L<<585.0,142.0>--<589.0,142.0>>

	* uni0146 (U+0146) contains a short segment L<<183.0,467.0>--<189.0,467.0>>

	* Ncaron (U+0147) contains a short segment L<<191.0,575.0>--<187.0,575.0>>

	* Ncaron (U+0147) contains a short segment L<<585.0,142.0>--<589.0,142.0>>

	* ncaron (U+0148) contains a short segment L<<183.0,467.0>--<189.0,467.0>>

	* Eng (U+014A) contains a short segment L<<191.0,575.0>--<187.0,575.0>>

	* Eng (U+014A) contains a short segment L<<585.0,186.0>--<589.0,186.0>>

	* eng (U+014B) contains a short segment L<<184.0,467.0>--<190.0,467.0>>

	* racute (U+0155) contains a short segment L<<182.0,443.0>--<187.0,443.0>>

	* uni0157 (U+0157) contains a short segment L<<182.0,443.0>--<187.0,443.0>>

	* rcaron (U+0159) contains a short segment L<<182.0,443.0>--<187.0,443.0>>

	* umacron (U+016B) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* uring (U+016F) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<544.5,-155.5>-<557.0,-153.0>-<566.0,-151.0>>

	* uogonek (U+0173) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* uni0668 (U+0668) contains a short segment L<<336.0,682.0>--<336.0,681.0>>

	* uni0668 (U+0668) contains a short segment L<<336.0,681.0>--<337.0,682.0>>

	* uni066D (U+066D) contains a short segment L<<101.0,0.0>--<96.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<16.0,279.0>--<18.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<252.0,458.0>--<259.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<494.0,287.0>--<496.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<416.0,3.0>--<411.0,-1.0>>

	* raathaana (U+0783) contains a short segment B<<253.0,273.0>-<252.0,277.0>-<252.0,281.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<254.0,308.0>-<261.0,308.0>-<268.0,308.0>>

	* zaviyanithaana (U+0792) contains a short segment B<<194.0,278.0>-<194.0,281.0>-<194.0,285.0>>

	* taviyanithaana (U+0793) contains a short segment L<<219.0,219.0>--<219.0,219.0>>

	* zaathaana (U+079C) contains a short segment B<<253.0,273.0>-<252.0,277.0>-<252.0,281.0>>

	* Euro (U+20AC) contains a short segment B<<201.0,352.0>-<201.0,344.0>-<201.0,334.0>>

	* Euro (U+20AC) contains a short segment B<<201.0,334.0>-<201.0,324.0>-<202.0,315.0>>

	* Euro (U+20AC) contains a short segment B<<92.0,352.0>-<92.0,362.0>-<92.5,371.5>>

	* Euro (U+20AC) contains a short segment B<<92.5,371.5>-<93.0,381.0>-<93.0,386.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* uniFDFD (U+FDFD) contains a short segment B<<1481.0,390.0>-<1481.0,381.0>-<1486.5,374.5>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178

	* Wacute (U+1E82): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178

	* Wcircumflex (U+0174): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178

	* Wdieresis (U+1E84): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178

	* Wgrave (U+1E80): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 9 | 95 | 1064 | 55 | 882 | 0 |
| 0% | 0% | 5% | 51% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
