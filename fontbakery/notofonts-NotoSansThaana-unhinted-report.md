## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[11] NotoSansThaana-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* exclam
	* parenleft
	* parenright
	* quotedbl
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* period (U+002E): X=119.5,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=133.0,Y=1.5 (should be at baseline 0?)

	* five (U+0035): X=145.5,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=119.5,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=115.5,Y=1.0 (should be at baseline 0?)

	* uni061B (U+061B): X=115.5,Y=1.0 (should be at baseline 0?)

	* uni061F (U+061F): X=170.5,Y=1.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=205.0,Y=2.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=124.0,Y=-2.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=205.0,Y=2.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=203.0,Y=2.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=124.0,Y=-2.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=203.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=203.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=124.0,Y=-2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=203.0,Y=2.0 (should be at baseline 0?)

	* uni066D (U+066D): X=413.0,Y=-1.0 (should be at baseline 0?)

	* uni06D4 (U+06D4): X=87.5,Y=1.0 (should be at baseline 0?)

	* paviyanithaana (U+0795): X=311.0,Y=-1.0 (should be at baseline 0?)

	* tothaana (U+07A0): X=342.0,Y=-2.0 (should be at baseline 0?)

	* tothaana (U+07A0): X=342.0,Y=-2.0 (should be at baseline 0?)

	* ubufilithaana (U+07AA): X=234.5,Y=715.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=466.5,Y=715.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=283.5,Y=715.0 (should be at cap-height 714?)

	* sukunthaana (U+07B0): X=106.5,Y=714.5 (should be at cap-height 714?)

	* quoteright (U+2019): X=61.5,Y=712.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=61.5,Y=712.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=238.5,Y=712.0 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=683.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=663.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1717.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1698.0,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=377.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=266.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1380.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.5,Y=1.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1157.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<164.0,78.0>--<164.0,76.0>>

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

	* zaathaana (U+079C) contains a short segment B<<256.0,270.0>-<255.0,273.0>-<255.0,277.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<321.0,680.0>--<321.0,680.0>> -> L<<321.0,680.0>--<322.0,680.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nine
	* one
	* parenleft
	* parenright
	* quotedbl
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=131.5,Y=1.0 (should be at baseline 0?)

	* four (U+0034): X=346.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=468.0,Y=716.0 (should be at cap-height 714?)

	* five (U+0035): X=141.5,Y=0.5 (should be at baseline 0?)

	* six (U+0036): X=493.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=81.0,Y=-2.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=243.0,Y=1.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=243.0,Y=1.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=240.0,Y=1.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=240.0,Y=1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=240.0,Y=1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=240.0,Y=1.0 (should be at baseline 0?)

	* uni066D (U+066D): X=409.0,Y=-1.0 (should be at baseline 0?)

	* shaviyanithaana (U+0781): X=-52.0,Y=-1.0 (should be at baseline 0?)

	* shaviyanithaana (U+0781): X=-52.0,Y=-1.0 (should be at baseline 0?)

	* noonuthaana (U+0782): X=-52.0,Y=-1.0 (should be at baseline 0?)

	* noonuthaana (U+0782): X=-52.0,Y=-1.0 (should be at baseline 0?)

	* raathaana (U+0783): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* raathaana (U+0783): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* faafuthaana (U+078A): X=-5.0,Y=-1.0 (should be at baseline 0?)

	* faafuthaana (U+078A): X=-5.0,Y=-1.0 (should be at baseline 0?)

	* dhaaluthaana (U+078B): X=-37.0,Y=-1.0 (should be at baseline 0?)

	* dhaaluthaana (U+078B): X=-37.0,Y=-1.0 (should be at baseline 0?)

	* laamuthaana (U+078D): X=4.0,Y=-2.0 (should be at baseline 0?)

	* laamuthaana (U+078D): X=4.0,Y=-2.0 (should be at baseline 0?)

	* yaathaana (U+0794): X=-52.0,Y=-1.0 (should be at baseline 0?)

	* yaathaana (U+0794): X=-52.0,Y=-1.0 (should be at baseline 0?)

	* paviyanithaana (U+0795): X=-5.0,Y=-1.0 (should be at baseline 0?)

	* paviyanithaana (U+0795): X=-5.0,Y=-1.0 (should be at baseline 0?)

	* thaaluthaana (U+079B): X=-36.0,Y=-1.0 (should be at baseline 0?)

	* thaaluthaana (U+079B): X=-36.0,Y=-1.0 (should be at baseline 0?)

	* zaathaana (U+079C): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* zaathaana (U+079C): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* abafilithaana (U+07A6): X=330.0,Y=716.0 (should be at cap-height 714?)

	* aabaafilithaana (U+07A7): X=198.5,Y=714.5 (should be at cap-height 714?)

	* ebefilithaana (U+07AC): X=186.0,Y=714.5 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=236.0,Y=714.5 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=409.0,Y=714.5 (should be at cap-height 714?)

	* quoteleft (U+2018): X=147.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=147.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=354.0,Y=715.0 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=684.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1718.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=378.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=264.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1381.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.0,Y=1.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1158.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1133.5,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<209.0,113.0>--<209.0,109.0>>

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

	* zaathaana (U+079C) contains a short segment B<<250.0,276.0>-<248.0,280.0>-<248.0,286.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<351.0,683.0>--<351.0,683.0>> -> L<<351.0,683.0>--<352.0,683.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* exclam
	* quotedbl
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=130.5,Y=1.0 (should be at baseline 0?)

	* four (U+0034): X=335.0,Y=715.0 (should be at cap-height 714?)

	* four (U+0034): X=476.0,Y=715.0 (should be at cap-height 714?)

	* six (U+0036): X=499.0,Y=715.0 (should be at cap-height 714?)

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

	* uni0668 (U+0668) contains a short segment L<<366.0,685.0>--<366.0,685.0>>

	* uni0668 (U+0668) contains a short segment L<<366.0,685.0>--<367.0,685.0>>

	* uni066D (U+066D) contains a short segment L<<98.0,0.0>--<93.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<13.0,279.0>--<15.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<249.0,458.0>--<256.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<490.0,287.0>--<492.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<412.0,3.0>--<407.0,-1.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<273.0,322.0>-<277.0,322.0>-<282.0,322.0>>

	* uniFDFD (U+FDFD) contains a short segment B<<1484.0,399.0>-<1484.0,390.0>-<1489.5,383.5>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<366.0,685.0>--<366.0,685.0>> -> L<<366.0,685.0>--<367.0,685.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* kaafuthaana (U+0786): L<<230.0,220.0>--<223.0,212.0>>/B<<223.0,212.0>-<248.0,240.0>-<278.5,275.0>> = 0.5743745381882183 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaana-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=158.5,Y=1.5 (should be at baseline 0?)

	* three (U+0033): X=135.5,Y=2.0 (should be at baseline 0?)

	* five (U+0035): X=150.0,Y=2.0 (should be at baseline 0?)

	* six (U+0036): X=465.0,Y=713.0 (should be at cap-height 714?)

	* uni060C (U+060C): X=158.5,Y=1.5 (should be at baseline 0?)

	* uni0663 (U+0663): X=147.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=147.0,Y=2.0 (should be at baseline 0?)

	* uni0664 (U+0664): X=354.0,Y=0.5 (should be at baseline 0?)

	* uni0668 (U+0668): X=487.0,Y=-2.0 (should be at baseline 0?)

	* uni066D (U+066D): X=419.0,Y=-1.0 (should be at baseline 0?)

	* uni066D (U+066D): X=105.0,Y=-1.0 (should be at baseline 0?)

	* shaviyanithaana (U+0781): X=2.5,Y=-0.5 (should be at baseline 0?)

	* noonuthaana (U+0782): X=2.5,Y=-0.5 (should be at baseline 0?)

	* yaathaana (U+0794): X=2.5,Y=-0.5 (should be at baseline 0?)

	* paviyanithaana (U+0795): X=264.0,Y=-1.0 (should be at baseline 0?)

	* ainuthaana (U+07A2): X=194.0,Y=-2.0 (should be at baseline 0?)

	* ainuthaana (U+07A2): X=194.0,Y=-2.0 (should be at baseline 0?)

	* aabaafilithaana (U+07A7): X=316.0,Y=713.0 (should be at cap-height 714?)

	* ubufilithaana (U+07AA): X=185.5,Y=714.5 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=413.5,Y=714.5 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=260.5,Y=714.5 (should be at cap-height 714?)

	* obofilithaana (U+07AE): X=179.0,Y=713.0 (should be at cap-height 714?)

	* obofilithaana (U+07AE): X=279.5,Y=715.0 (should be at cap-height 714?)

	* oaboafilithaana (U+07AF): X=304.0,Y=713.0 (should be at cap-height 714?)

	* sukunthaana (U+07B0): X=156.0,Y=713.0 (should be at cap-height 714?)

	* sukunthaana (U+07B0): X=156.0,Y=713.0 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=680.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=660.5,Y=1.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1716.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1696.5,Y=1.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=376.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=268.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1377.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1156.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<95.0,26.0>--<95.0,25.0>>

	* uni066D (U+066D) contains a short segment L<<105.0,-1.0>--<100.0,3.0>>

	* uni066D (U+066D) contains a short segment L<<20.0,279.0>--<22.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<259.0,458.0>--<266.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<502.0,287.0>--<504.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<424.0,3.0>--<419.0,-1.0>>

	* noonuthaana (U+0782) contains a short segment B<<280.0,311.0>-<280.0,306.0>-<279.0,301.0>>

	* noonuthaana (U+0782) contains a short segment B<<279.0,301.0>-<278.0,296.0>-<276.0,290.0>>

	* noonuthaana (U+0782) contains a short segment B<<-41.0,-87.0>-<-45.0,-83.0>-<-49.5,-77.5>>

	* noonuthaana (U+0782) contains a short segment B<<-49.5,-77.5>-<-54.0,-72.0>-<-58.0,-68.0>>

	* raathaana (U+0783) contains a short segment B<<254.0,259.0>-<254.0,261.0>-<254.0,262.0>>

	* dhaaluthaana (U+078B) contains a short segment B<<416.0,252.0>-<416.0,249.0>-<414.0,243.5>>

	* dhaaluthaana (U+078B) contains a short segment B<<414.0,243.5>-<412.0,238.0>-<410.0,233.0>>

	* thaathaana (U+078C) contains a short segment B<<212.0,33.0>-<212.0,32.0>-<211.5,26.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<218.0,297.0>-<218.0,292.0>-<216.0,288.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<289.0,-47.0>-<290.0,-52.0>-<290.5,-57.5>>

	* gnaviyanithaana (U+078F) contains a short segment B<<290.5,-57.5>-<291.0,-63.0>-<292.0,-70.0>>

	* zaviyanithaana (U+0792) contains a short segment B<<316.0,-49.0>-<317.0,-53.0>-<317.5,-58.5>>

	* taviyanithaana (U+0793) contains a short segment B<<206.0,171.0>-<201.0,171.0>-<197.0,171.0>>

	* taviyanithaana (U+0793) contains a short segment B<<303.0,-48.0>-<304.0,-51.0>-<305.0,-57.0>>

	* yaathaana (U+0794) contains a short segment B<<280.0,311.0>-<280.0,306.0>-<279.0,303.0>>

	* yaathaana (U+0794) contains a short segment B<<-41.0,-87.0>-<-45.0,-83.0>-<-49.5,-77.5>>

	* yaathaana (U+0794) contains a short segment B<<-49.5,-77.5>-<-54.0,-72.0>-<-58.0,-68.0>>

	* javiyanithaana (U+0796) contains a short segment B<<376.0,275.0>-<376.0,272.0>-<374.0,266.5>>

	* javiyanithaana (U+0796) contains a short segment B<<374.0,266.5>-<372.0,261.0>-<370.0,256.0>>

	* javiyanithaana (U+0796) contains a short segment B<<298.0,-49.0>-<299.0,-52.0>-<300.0,-58.0>>

	* chaviyanithaana (U+0797) contains a short segment B<<212.0,33.0>-<212.0,32.0>-<211.5,26.0>>

	* chaviyanithaana (U+0797) contains a short segment B<<211.5,26.0>-<211.0,20.0>-<209.0,15.0>>

	* ttaathaana (U+0798) contains a short segment B<<242.0,33.0>-<242.0,32.0>-<241.5,26.0>>

	* thaaluthaana (U+079B) contains a short segment B<<416.0,252.0>-<416.0,249.0>-<414.0,243.5>>

	* thaaluthaana (U+079B) contains a short segment B<<414.0,243.5>-<412.0,238.0>-<410.0,233.0>>

	* zaathaana (U+079C) contains a short segment B<<254.0,259.0>-<254.0,261.0>-<254.0,262.0>>

	* tothaana (U+07A0) contains a short segment B<<212.0,33.0>-<212.0,32.0>-<211.5,26.0>>

	* zothaana (U+07A1) contains a short segment B<<230.0,33.0>-<230.0,32.0>-<229.5,26.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniFDFD (U+FDFD): L<<479.0,369.0>--<479.0,373.0>> -> L<<479.0,373.0>--<476.0,452.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* lhaviyanithaana (U+0785): B<<245.5,269.5>-<278.0,307.0>-<300.0,333.0>>/B<<300.0,333.0>-<276.0,315.0>-<254.5,306.0>> = 12.89374404488216 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaana-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* exclam
	* period
	* quotedbl
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* six (U+0036): X=510.0,Y=716.0 (should be at cap-height 714?)

	* uni066D (U+066D): X=403.0,Y=-1.0 (should be at baseline 0?)

	* gaafuthaana (U+078E): X=78.5,Y=-0.5 (should be at baseline 0?)

	* gnaviyanithaana (U+078F): X=69.5,Y=-1.0 (should be at baseline 0?)

	* zaviyanithaana (U+0792): X=105.0,Y=-0.5 (should be at baseline 0?)

	* javiyanithaana (U+0796): X=53.5,Y=-0.5 (should be at baseline 0?)

	* qaafuthaana (U+07A4): X=108.5,Y=-0.5 (should be at baseline 0?)

	* obofilithaana (U+07AE): X=396.5,Y=716.0 (should be at cap-height 714?)

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
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<278.0,164.0>--<278.0,159.0>>

	* uni0663 (U+0663) contains a short segment B<<245.0,577.0>-<247.0,573.0>-<255.0,564.0>>

	* uni0667 (U+0667) contains a short segment L<<238.0,-10.0>--<238.0,-10.0>>

	* uni0667 (U+0667) contains a short segment L<<238.0,-10.0>--<237.0,-10.0>>

	* uni0668 (U+0668) contains a short segment L<<396.0,689.0>--<396.0,689.0>>

	* uni0668 (U+0668) contains a short segment L<<396.0,689.0>--<397.0,689.0>>

	* uni066D (U+066D) contains a short segment L<<96.0,0.0>--<90.0,4.0>>

	* uni066D (U+066D) contains a short segment L<<10.0,279.0>--<12.0,287.0>>

	* uni066D (U+066D) contains a short segment L<<246.0,458.0>--<253.0,458.0>>

	* uni066D (U+066D) contains a short segment L<<486.0,287.0>--<488.0,279.0>>

	* uni066D (U+066D) contains a short segment L<<408.0,3.0>--<403.0,-1.0>>

	* noonuthaana (U+0782) contains a short segment B<<378.0,330.0>-<383.0,330.0>-<389.0,330.0>>

	* raathaana (U+0783) contains a short segment B<<261.0,293.0>-<261.0,296.0>-<261.0,300.0>>

	* gnaviyanithaana (U+078F) contains a short segment B<<313.0,327.0>-<321.0,327.0>-<327.0,327.5>>

	* gnaviyanithaana (U+078F) contains a short segment B<<327.0,327.5>-<333.0,328.0>-<337.0,329.0>>

	* zaathaana (U+079C) contains a short segment B<<261.0,293.0>-<261.0,296.0>-<261.0,300.0>>

	* naathaana (U+07B1) contains a short segment B<<190.0,103.0>-<183.0,99.0>-<183.0,96.0>>

	* naathaana (U+07B1) contains a short segment B<<183.0,96.0>-<183.0,93.0>-<191.0,91.0>>

	* uniFDFD (U+FDFD) contains a short segment B<<1386.0,407.0>-<1386.0,397.0>-<1390.5,391.5>>

	* uniFDFD (U+FDFD) contains a short segment B<<1488.0,407.0>-<1488.0,399.0>-<1492.5,392.5>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<396.0,689.0>--<396.0,689.0>> -> L<<396.0,689.0>--<397.0,689.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ainuthaana (U+07A2): B<<299.5,121.0>-<305.0,160.0>-<310.0,209.0>>/L<<310.0,209.0>--<309.0,205.0>> = 8.209901438370684

	* alifuthaana (U+0787): B<<299.5,121.0>-<305.0,160.0>-<310.0,209.0>>/L<<310.0,209.0>--<309.0,205.0>> = 8.209901438370684

	* ghainuthaana (U+07A3): B<<319.5,121.0>-<325.0,160.0>-<330.0,209.0>>/L<<330.0,209.0>--<329.0,205.0>> = 8.209901438370684

	* uni0667 (U+0667): L<<405.0,12.0>--<238.0,-10.0>>/L<<238.0,-10.0>--<238.0,-10.0>> = 7.504732450611929 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* eight
	* five
	* four
	* nine
	* one
	* parenleft
	* parenright
	* seven
	* six
	* three
	* two
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
	* uniFDFD and zero
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=132.5,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=124.5,Y=-1.0 (should be at baseline 0?)

	* period (U+002E): X=202.5,Y=1.5 (should be at baseline 0?)

	* three (U+0033): X=134.0,Y=1.5 (should be at baseline 0?)

	* five (U+0035): X=147.0,Y=1.5 (should be at baseline 0?)

	* nine (U+0039): X=88.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=124.5,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=202.5,Y=1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=120.5,Y=-1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=198.5,Y=1.5 (should be at baseline 0?)

	* uni061B (U+061B): X=120.5,Y=-1.0 (should be at baseline 0?)

	* uni061B (U+061B): X=198.5,Y=1.5 (should be at baseline 0?)

	* uni061F (U+061F): X=390.5,Y=712.0 (should be at cap-height 714?)

	* uni0661 (U+0661): X=186.0,Y=2.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=124.0,Y=-1.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=186.0,Y=2.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=184.0,Y=2.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=124.0,Y=-1.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=184.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=184.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=124.0,Y=-1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=184.0,Y=2.0 (should be at baseline 0?)

	* uni0667 (U+0667): X=248.0,Y=-2.0 (should be at baseline 0?)

	* uni0668 (U+0668): X=76.0,Y=-1.0 (should be at baseline 0?)

	* uni0668 (U+0668): X=76.0,Y=-1.0 (should be at baseline 0?)

	* uni066B (U+066B): X=184.0,Y=1.0 (should be at baseline 0?)

	* uni066D (U+066D): X=415.0,Y=-1.0 (should be at baseline 0?)

	* uni06D4 (U+06D4): X=86.5,Y=-1.0 (should be at baseline 0?)

	* uni06D4 (U+06D4): X=164.5,Y=1.5 (should be at baseline 0?)

	* paviyanithaana (U+0795): X=295.0,Y=-1.0 (should be at baseline 0?)

	* aabaafilithaana (U+07A7): X=254.0,Y=713.0 (should be at cap-height 714?)

	* ubufilithaana (U+07AA): X=98.0,Y=712.0 (should be at cap-height 714?)

	* ubufilithaana (U+07AA): X=223.5,Y=713.0 (should be at cap-height 714?)

	* ubufilithaana (U+07AA): X=98.0,Y=712.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=328.0,Y=712.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=454.0,Y=713.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=328.0,Y=712.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=155.0,Y=712.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=281.0,Y=713.0 (should be at cap-height 714?)

	* ooboofilithaana (U+07AB): X=155.0,Y=712.0 (should be at cap-height 714?)

	* obofilithaana (U+07AE): X=340.0,Y=715.5 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=682.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=662.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1717.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1697.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=377.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=267.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=155.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1379.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1157.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<141.0,61.0>--<141.0,59.0>>

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

	* uniFDFD (U+FDFD) contains a short segment L<<476.0,373.0>--<476.0,373.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<306.0,678.0>--<306.0,678.0>> -> L<<306.0,678.0>--<307.0,678.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaana-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* eight
	* five
	* four
	* nine
	* one
	* seven
	* six
	* three
	* two
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
	* uniFDFD and zero
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* period (U+002E): X=194.0,Y=-0.5 (should be at baseline 0?)

	* three (U+0033): X=135.0,Y=2.0 (should be at baseline 0?)

	* five (U+0035): X=148.0,Y=1.5 (should be at baseline 0?)

	* six (U+0036): X=471.0,Y=713.0 (should be at cap-height 714?)

	* nine (U+0039): X=91.0,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=194.0,Y=-0.5 (should be at baseline 0?)

	* semicolon (U+003B): X=190.0,Y=-0.5 (should be at baseline 0?)

	* uni061B (U+061B): X=190.0,Y=-0.5 (should be at baseline 0?)

	* uni061F (U+061F): X=381.5,Y=713.5 (should be at cap-height 714?)

	* uni0661 (U+0661): X=124.0,Y=-1.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=124.0,Y=-1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=166.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=124.0,Y=-1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=166.0,Y=2.0 (should be at baseline 0?)

	* uni0667 (U+0667): X=249.0,Y=-1.0 (should be at baseline 0?)

	* uni0668 (U+0668): X=61.0,Y=1.0 (should be at baseline 0?)

	* uni0668 (U+0668): X=61.0,Y=1.0 (should be at baseline 0?)

	* uni066A (U+066A): X=69.0,Y=2.0 (should be at baseline 0?)

	* uni066D (U+066D): X=417.0,Y=-1.0 (should be at baseline 0?)

	* uni066D (U+066D): X=104.0,Y=-1.0 (should be at baseline 0?)

	* uni06D4 (U+06D4): X=149.0,Y=-0.5 (should be at baseline 0?)

	* daviyanithaana (U+0791): X=160.0,Y=-0.5 (should be at baseline 0?)

	* paviyanithaana (U+0795): X=280.0,Y=-1.0 (should be at baseline 0?)

	* aabaafilithaana (U+07A7): X=250.0,Y=712.0 (should be at cap-height 714?)

	* obofilithaana (U+07AE): X=179.0,Y=716.0 (should be at cap-height 714?)

	* obofilithaana (U+07AE): X=342.5,Y=713.5 (should be at cap-height 714?)

	* obofilithaana (U+07AE): X=397.0,Y=713.0 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=681.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=661.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1716.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1697.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=376.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=267.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1378.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.0,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1156.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<118.0,43.0>--<118.0,42.0>>

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

	* zothaana (U+07A1) contains a short segment B<<226.0,36.0>-<226.0,33.0>-<225.5,26.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<291.0,676.0>--<291.0,676.0>> -> L<<291.0,676.0>--<291.0,676.0>>

	* uniFDFD (U+FDFD): L<<478.0,371.0>--<478.0,373.0>> -> L<<478.0,373.0>--<475.0,450.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaana-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* exclam
	* nine
	* quotedbl
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=130.0,Y=1.0 (should be at baseline 0?)

	* four (U+0034): X=325.0,Y=715.0 (should be at cap-height 714?)

	* four (U+0034): X=484.0,Y=715.0 (should be at cap-height 714?)

	* six (U+0036): X=505.0,Y=716.0 (should be at cap-height 714?)

	* uni0662 (U+0662): X=278.0,Y=1.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=278.0,Y=1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=278.0,Y=1.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=278.0,Y=1.0 (should be at baseline 0?)

	* uni066D (U+066D): X=405.0,Y=-1.0 (should be at baseline 0?)

	* gaafuthaana (U+078E): X=75.0,Y=1.0 (should be at baseline 0?)

	* qaafuthaana (U+07A4): X=97.0,Y=1.0 (should be at baseline 0?)

	* abafilithaana (U+07A6): X=349.0,Y=713.0 (should be at cap-height 714?)

	* ebefilithaana (U+07AC): X=185.5,Y=714.5 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=218.5,Y=714.5 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=394.5,Y=714.5 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=686.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1719.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=378.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=262.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1383.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.0,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1159.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1135.5,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<255.0,147.0>--<255.0,143.0>>

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

	* uniFDFD (U+FDFD) contains a short segment B<<1486.0,403.0>-<1486.0,394.0>-<1491.0,388.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0668 (U+0668): L<<381.0,687.0>--<381.0,687.0>> -> L<<381.0,687.0>--<382.0,687.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0667 (U+0667): L<<389.0,12.0>--<240.0,-8.0>>/L<<240.0,-8.0>--<240.0,-8.0>> = 7.64501327167069 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansThaana-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command:

```
# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools
```
 [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure UnicodeRange bits are properly set. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/unicode_range_bits">com.google.fonts/check/unicode_range_bits</a>)</summary><div>


* ⚠ **WARN** UnicodeRange bit 0 "Basic Latin" should be 1 because cmap has 21 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 1 "Latin-1 Supplement" should be 1 because cmap has 1 of the 128 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 13 "Arabic" should be 1 because cmap has 18 of the 304 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 31 "General Punctuation" should be 1 because cmap has 9 of the 240 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 45 "Geometric Shapes" should be 1 because cmap has 1 of the 96 codepoints in this range. [code: bad-range-bit]
* ⚠ **WARN** UnicodeRange bit 63 "Arabic Presentation Forms-A" should be 1 because cmap has 3 of the 688 codepoints in this range. [code: bad-range-bit]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure the manufacturer is a known Noto manufacturer and the URL is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Noto Fonts>.html#com.google.fonts/check/name/noto_manufacturer">com.google.fonts/check/name/noto_manufacturer</a>)</summary><div>


* ⚠ **WARN** The font's manufacturer name 'Google Inc.' was not a known Noto font manufacturer [code: unknown-manufacturer]
* ⚠ **WARN** The font contained no designer URL [code: no-designer-urls]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+066D ARABIC FIVE POINTED STAR: try adding arabic
 * U+06D4 ARABIC FULL STOP: try adding one of: hanifi-rohingya, arabic, yezidi
 * U+FD3E ORNATE LEFT PARENTHESIS: try adding one of: arabic, nko
 * U+FD3F ORNATE RIGHT PARENTHESIS: try adding one of: arabic, nko

Or you can add the above codepoints to one of the subsets supported by the font: `thaana` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* colon
	* nine
	* one
	* parenleft
	* parenright
	* quotedbl
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=132.5,Y=1.5 (should be at baseline 0?)

	* four (U+0034): X=356.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=459.0,Y=716.0 (should be at cap-height 714?)

	* five (U+0035): X=143.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=84.0,Y=-1.0 (should be at baseline 0?)

	* uni061F (U+061F): X=164.5,Y=2.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=224.0,Y=2.0 (should be at baseline 0?)

	* uni0661 (U+0661): X=224.0,Y=2.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=222.0,Y=2.0 (should be at baseline 0?)

	* uni0662 (U+0662): X=222.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=222.0,Y=2.0 (should be at baseline 0?)

	* uni0663 (U+0663): X=222.0,Y=2.0 (should be at baseline 0?)

	* uni066D (U+066D): X=411.0,Y=-1.0 (should be at baseline 0?)

	* raathaana (U+0783): X=141.5,Y=-2.0 (should be at baseline 0?)

	* zaathaana (U+079C): X=141.5,Y=-2.0 (should be at baseline 0?)

	* abafilithaana (U+07A6): X=318.0,Y=713.0 (should be at cap-height 714?)

	* ebefilithaana (U+07AC): X=187.0,Y=715.5 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=239.0,Y=715.5 (should be at cap-height 714?)

	* eybeyfilithaana (U+07AD): X=418.0,Y=715.5 (should be at cap-height 714?)

	* uniFDFD (U+FDFD): X=684.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=664.0,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1717.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1698.5,Y=0.5 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=377.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=265.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1381.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1259.5,Y=1.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1157.0,Y=-2.0 (should be at baseline 0?)

	* uniFDFD (U+FDFD): X=1133.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<187.0,95.0>--<187.0,93.0>>

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

	* uniFDFD (U+FDFD) contains a short segment B<<1481.0,390.0>-<1481.0,381.0>-<1486.5,374.5>> [code: found-short-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 18 | 91 | 1073 | 46 | 940 | 0 |
| 0% | 1% | 4% | 49% | 2% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
