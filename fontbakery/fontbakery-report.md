## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[12] InstrumentSerif-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Instrument Serif Italic | Instrument Serif |
| Subfamily Name | Regular | Italic |
| Full Name | Instrument Serif Italic | Instrument Serif Italic |
| Poscript Name | InstrumentSerif-Italic | InstrumentSerif-Italic |
| Typographic Family Name | Instrument Serif | N/A |
| Typographic Subfamily Name | Italic | N/A | [code: bad-names]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Instrument Serif Italic' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* ⚠ **WARN** Glyph '.notdef' should contain a drawing, but it is empty. [code: empty]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=251.5,Y=719.0 (should be at cap-height 720?)

	* quotedbl (U+0022): X=390.5,Y=719.0 (should be at cap-height 720?)

	* ampersand (U+0026): X=407.5,Y=719.5 (should be at cap-height 720?)

	* quotesingle (U+0027): X=251.5,Y=719.0 (should be at cap-height 720?)

	* comma (U+002C): X=41.5,Y=1.5 (should be at baseline 0?)

	* five (U+0035): X=45.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=468.0,Y=719.0 (should be at cap-height 720?)

	* semicolon (U+003B): X=41.5,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=302.0,Y=2.0 (should be at baseline 0?)

	* Q (U+0051): X=166.0,Y=1.0 (should be at baseline 0?)

	* grave (U+0060): X=248.0,Y=719.0 (should be at cap-height 720?)

	* a (U+0061): X=326.0,Y=508.5 (should be at x-height 510?)

	* d (U+0064): X=354.0,Y=508.0 (should be at x-height 510?)

	* f (U+0066): X=247.0,Y=722.0 (should be at cap-height 720?)

	* g (U+0067): X=341.0,Y=509.0 (should be at x-height 510?)

	* p (U+0070): X=100.0,Y=2.0 (should be at baseline 0?)

	* q (U+0071): X=326.0,Y=508.5 (should be at x-height 510?)

	* s (U+0073): X=46.5,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=255.5,Y=508.0 (should be at x-height 510?)

	* z (U+007A): X=190.0,Y=1.5 (should be at baseline 0?)

	* germandbls (U+00DF): X=200.0,Y=-0.5 (should be at baseline 0?)

	* agrave (U+00E0): X=289.0,Y=719.0 (should be at cap-height 720?)

	* atilde (U+00E3): X=271.0,Y=718.0 (should be at cap-height 720?)

	* aring (U+00E5): X=240.5,Y=718.5 (should be at cap-height 720?)

	* egrave (U+00E8): X=266.0,Y=719.0 (should be at cap-height 720?)

	* igrave (U+00EC): X=196.0,Y=719.0 (should be at cap-height 720?)

	* ntilde (U+00F1): X=295.0,Y=718.0 (should be at cap-height 720?)

	* ograve (U+00F2): X=259.0,Y=719.0 (should be at cap-height 720?)

	* otilde (U+00F5): X=241.0,Y=718.0 (should be at cap-height 720?)

	* ugrave (U+00F9): X=286.0,Y=719.0 (should be at cap-height 720?)

	* thorn (U+00FE): X=88.0,Y=2.0 (should be at baseline 0?)

	* abreve (U+0103): X=226.0,Y=718.0 (should be at cap-height 720?)

	* abreve (U+0103): X=462.0,Y=718.0 (should be at cap-height 720?)

	* dcaron (U+010F): X=603.5,Y=721.5 (should be at cap-height 720?)

	* Gbreve (U+011E): X=302.0,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=190.0,Y=718.0 (should be at cap-height 720?)

	* gbreve (U+011F): X=426.0,Y=718.0 (should be at cap-height 720?)

	* Gdotaccent (U+0120): X=302.0,Y=2.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=302.0,Y=2.0 (should be at baseline 0?)

	* lcaron (U+013E): X=369.5,Y=721.5 (should be at cap-height 720?)

	* sacute (U+015B): X=46.5,Y=1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=46.5,Y=1.0 (should be at baseline 0?)

	* scaron (U+0161): X=46.5,Y=1.0 (should be at baseline 0?)

	* ubreve (U+016D): X=223.0,Y=718.0 (should be at cap-height 720?)

	* ubreve (U+016D): X=459.0,Y=718.0 (should be at cap-height 720?)

	* uring (U+016F): X=237.5,Y=718.5 (should be at cap-height 720?)

	* zacute (U+017A): X=190.0,Y=1.5 (should be at baseline 0?)

	* zdotaccent (U+017C): X=190.0,Y=1.5 (should be at baseline 0?)

	* zcaron (U+017E): X=190.0,Y=1.5 (should be at baseline 0?)

	* uni0219 (U+0219): X=46.5,Y=1.0 (should be at baseline 0?)

	* breve (U+02D8): X=192.0,Y=718.0 (should be at cap-height 720?)

	* breve (U+02D8): X=428.0,Y=718.0 (should be at cap-height 720?)

	* ring (U+02DA): X=172.5,Y=718.5 (should be at cap-height 720?)

	* tilde (U+02DC): X=257.0,Y=718.0 (should be at cap-height 720?)

	* gravecomb (U+0300): X=248.0,Y=719.0 (should be at cap-height 720?)

	* tildecomb (U+0303): X=257.0,Y=718.0 (should be at cap-height 720?)

	* uni0306 (U+0306): X=192.0,Y=718.0 (should be at cap-height 720?)

	* uni0306 (U+0306): X=428.0,Y=718.0 (should be at cap-height 720?)

	* uni030A (U+030A): X=172.5,Y=718.5 (should be at cap-height 720?)

	* wgrave (U+1E81): X=389.0,Y=719.0 (should be at cap-height 720?)

	* ygrave (U+1EF3): X=260.0,Y=719.0 (should be at cap-height 720?)

	* quoteleft (U+2018): X=230.5,Y=722.0 (should be at cap-height 720?)

	* quotesinglbase (U+201A): X=16.5,Y=2.0 (should be at baseline 0?)

	* quotedblleft (U+201C): X=230.5,Y=722.0 (should be at cap-height 720?)

	* quotedblleft (U+201C): X=380.5,Y=722.0 (should be at cap-height 720?)

	* quotedblbase (U+201E): X=16.5,Y=2.0 (should be at baseline 0?) 

	* And quotedblbase (U+201E): X=166.5,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[8] InstrumentSerif-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* ⚠ **WARN** Glyph '.notdef' should contain a drawing, but it is empty. [code: empty]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=76.5,Y=-1.0 (should be at baseline 0?)

	* C (U+0043): X=366.5,Y=-1.5 (should be at baseline 0?)

	* G (U+0047): X=363.0,Y=-1.5 (should be at baseline 0?)

	* N (U+004E): X=445.5,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=222.0,Y=-1.0 (should be at baseline 0?)

	* d (U+0064): X=303.0,Y=512.0 (should be at x-height 510?)

	* g (U+0067): X=243.0,Y=508.0 (should be at x-height 510?)

	* g (U+0067): X=283.0,Y=508.0 (should be at x-height 510?)

	* g (U+0067): X=294.5,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=121.0,Y=-1.0 (should be at baseline 0?)

	* p (U+0070): X=159.0,Y=2.0 (should be at baseline 0?)

	* s (U+0073): X=213.0,Y=511.5 (should be at x-height 510?)

	* t (U+0074): X=19.0,Y=508.0 (should be at x-height 510?)

	* u (U+0075): X=123.0,Y=2.0 (should be at baseline 0?)

	* v (U+0076): X=181.0,Y=2.0 (should be at baseline 0?)

	* v (U+0076): X=207.0,Y=2.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=366.5,Y=-1.5 (should be at baseline 0?)

	* Ntilde (U+00D1): X=445.5,Y=-2.0 (should be at baseline 0?)

	* atilde (U+00E3): X=137.0,Y=718.0 (should be at cap-height 720?)

	* ntilde (U+00F1): X=172.0,Y=718.0 (should be at cap-height 720?)

	* otilde (U+00F5): X=141.0,Y=718.0 (should be at cap-height 720?)

	* ugrave (U+00F9): X=123.0,Y=2.0 (should be at baseline 0?)

	* uacute (U+00FA): X=123.0,Y=2.0 (should be at baseline 0?)

	* ucircumflex (U+00FB): X=123.0,Y=2.0 (should be at baseline 0?)

	* udieresis (U+00FC): X=123.0,Y=2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=159.0,Y=2.0 (should be at baseline 0?)

	* abreve (U+0103): X=81.0,Y=718.0 (should be at cap-height 720?)

	* abreve (U+0103): X=319.0,Y=718.0 (should be at cap-height 720?)

	* Cacute (U+0106): X=366.5,Y=-1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=366.5,Y=-1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=366.5,Y=-1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=363.0,Y=-1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=294.5,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=121.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=77.0,Y=718.0 (should be at cap-height 720?)

	* gbreve (U+011F): X=315.0,Y=718.0 (should be at cap-height 720?)

	* Gdotaccent (U+0120): X=363.0,Y=-1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=294.5,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=121.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=363.0,Y=-1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=294.5,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=121.0,Y=-1.0 (should be at baseline 0?)

	* Nacute (U+0143): X=445.5,Y=-2.0 (should be at baseline 0?)

	* uni0145 (U+0145): X=445.5,Y=-2.0 (should be at baseline 0?)

	* Ncaron (U+0147): X=445.5,Y=-2.0 (should be at baseline 0?)

	* umacron (U+016B): X=123.0,Y=2.0 (should be at baseline 0?)

	* ubreve (U+016D): X=123.0,Y=2.0 (should be at baseline 0?)

	* ubreve (U+016D): X=97.0,Y=718.0 (should be at cap-height 720?)

	* ubreve (U+016D): X=335.0,Y=718.0 (should be at cap-height 720?)

	* uring (U+016F): X=123.0,Y=2.0 (should be at baseline 0?)

	* uhungarumlaut (U+0171): X=123.0,Y=2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=123.0,Y=2.0 (should be at baseline 0?)

	* breve (U+02D8): X=85.0,Y=718.0 (should be at cap-height 720?)

	* breve (U+02D8): X=323.0,Y=718.0 (should be at cap-height 720?)

	* tilde (U+02DC): X=163.0,Y=718.0 (should be at cap-height 720?)

	* tildecomb (U+0303): X=163.0,Y=718.0 (should be at cap-height 720?)

	* uni0306 (U+0306): X=85.0,Y=718.0 (should be at cap-height 720?)

	* uni0306 (U+0306): X=323.0,Y=718.0 (should be at cap-height 720?)

	* uni1E9E (U+1E9E): X=279.5,Y=-0.5 (should be at baseline 0?) 

	* And Euro (U+20AC): X=383.0,Y=-1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 17 | 221 | 13 | 185 | 0 |
| 0% | 1% | 4% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
