## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[25] NotoSansGurungKhema-Regular.ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check METADATA.pb includes production subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-includes-production-subsets">googlefonts/metadata/includes_production_subsets</a></summary>
    <div>







* 💥 **ERROR** <p>HTTPSConnectionPool(host='fonts.google.com', port=443): Max retries exceeded with url: /metadata/fonts (Caused by ConnectTimeoutError(&lt;urllib3.connection.HTTPSConnection object at 0x7fa2a72e4940&gt;, 'Connection to fonts.google.com timed out. (connect timeout=None)'))</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check if the axes match between the font and the Google Fonts version. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-axes-match">googlefonts/axes_match</a></summary>
    <div>







* 💥 **ERROR** <p>HTTPSConnectionPool(host='fonts.google.com', port=443): Max retries exceeded with url: /metadata/fonts (Caused by ConnectTimeoutError(&lt;urllib3.connection.HTTPSConnection object at 0x7fa2a7145810&gt;, 'Connection to fonts.google.com timed out. (connect timeout=None)'))</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check font follows the Google Fonts CJK vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-cjk-vertical-metrics">googlefonts/cjk_vertical_metrics</a></summary>
    <div>







* 💥 **ERROR** <p>HTTPSConnectionPool(host='fonts.google.com', port=443): Max retries exceeded with url: /metadata/fonts (Caused by ConnectTimeoutError(&lt;urllib3.connection.HTTPSConnection object at 0x7fa2aa0498a0&gt;, 'Connection to fonts.google.com timed out. (connect timeout=None)'))</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-cjk-vertical-metrics-regressions">googlefonts/cjk_vertical_metrics_regressions</a></summary>
    <div>







* 💥 **ERROR** <p>HTTPSConnectionPool(host='fonts.google.com', port=443): Max retries exceeded with url: /metadata/fonts (Caused by ConnectTimeoutError(&lt;urllib3.connection.HTTPSConnection object at 0x7fa2a71479a0&gt;, 'Connection to fonts.google.com timed out. (connect timeout=None)'))</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 💥 **ERROR** <p>HTTPSConnectionPool(host='fonts.google.com', port=443): Max retries exceeded with url: /metadata/fonts (Caused by ConnectTimeoutError(&lt;urllib3.connection.HTTPSConnection object at 0x7fa2a6df8ca0&gt;, 'Connection to fonts.google.com timed out. (connect timeout=None)'))</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 💥 **ERROR** <p>HTTPSConnectionPool(host='fonts.google.com', port=443): Max retries exceeded with url: /metadata/fonts (Caused by ConnectTimeoutError(&lt;urllib3.connection.HTTPSConnection object at 0x7fa2a6df97b0&gt;, 'Connection to fonts.google.com timed out. (connect timeout=None)'))</p>
 [code: error]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap (204) and hhea lineGap (0) must be equal.</p>
 [code: lineGap]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-widths">whitespace_widths</a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 1024 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check family name for GF Guide compliance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-name-compliance">googlefonts/family_name_compliance</a></summary>
    <div>







* 🔥 **FAIL** <p>&quot;NotoSansGurungKhema&quot; is a CamelCased name. To solve this, simply use spaces instead in the font name.</p>
 [code: camelcase]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2025 Adobe Systems Incorporated. All rights reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⚠️ **WARN** <p>Uppercase glyphs are not vertically centered in the em box.</p>
 [code: vertical-metrics-not-centered]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#valid-glyphnames">valid_glyphnames</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
consonantsignmedialha_gurungkhema, consonantsignmedialracomb_gurungkhema, consonantsignmedialva_gurungkhema and consonantsignmedialya_gurungkhema</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansGurungKhema/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, todhri, duployan, canadian-aboriginal, hebrew, malayalam, tai-le, tifinagh, math, coptic, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>gurung-khema</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wacute (U+1E82): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wcircumflex (U+0174): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wdieresis (U+1E84): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* Wgrave (U+1E80): B&lt;&lt;473.5,553.5&gt;-&lt;463.0,596.0&gt;-&lt;461.0,609.0&gt;&gt;/B&lt;&lt;461.0,609.0&gt;-&lt;460.0,596.0&gt;-&lt;450.5,553.5&gt;&gt; = 13.144867617550734

* ha_gurungkhema (U+1610A): B&lt;&lt;573.0,850.0&gt;-&lt;636.0,916.0&gt;-&lt;702.0,920.0&gt;&gt;/L&lt;&lt;702.0,920.0&gt;--&lt;354.0,920.0&gt;&gt; = 3.468229258917096

* ja_gurungkhema (U+16108): B&lt;&lt;483.0,762.0&gt;-&lt;483.0,627.0&gt;-&lt;365.0,606.0&gt;&gt;/B&lt;&lt;365.0,606.0&gt;-&lt;473.0,605.0&gt;-&lt;548.0,564.0&gt;&gt; = 10.621558555562682

* ja_gurungkhema (U+16108): L&lt;&lt;752.0,922.0&gt;--&lt;350.0,922.0&gt;&gt;/B&lt;&lt;350.0,922.0&gt;-&lt;483.0,901.0&gt;-&lt;483.0,762.0&gt;&gt; = 8.972626614896399

* jha_gurungkhema (U+16109): B&lt;&lt;483.0,762.0&gt;-&lt;483.0,627.0&gt;-&lt;365.0,606.0&gt;&gt;/B&lt;&lt;365.0,606.0&gt;-&lt;473.0,605.0&gt;-&lt;548.0,564.0&gt;&gt; = 10.621558555562682

* jha_gurungkhema (U+16109): L&lt;&lt;752.0,922.0&gt;--&lt;350.0,922.0&gt;&gt;/B&lt;&lt;350.0,922.0&gt;-&lt;483.0,901.0&gt;-&lt;483.0,762.0&gt;&gt; = 8.972626614896399

* nga_gurungkhema (U+16105): B&lt;&lt;680.0,356.0&gt;-&lt;616.0,420.0&gt;-&lt;561.0,432.0&gt;&gt;/B&lt;&lt;561.0,432.0&gt;-&lt;574.0,432.0&gt;-&lt;559.0,434.0&gt;&gt; = 12.308015817427924

* sa_gurungkhema (U+1611D): B&lt;&lt;281.0,825.0&gt;-&lt;305.0,895.0&gt;-&lt;420.0,922.0&gt;&gt;/L&lt;&lt;420.0,922.0&gt;--&lt;166.0,922.0&gt;&gt; = 13.212746878335233
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* ba_gurungkhema (U+16117): L&lt;&lt;868.0,922.0&gt;--&lt;524.0,920.0&gt;&gt;

* bha_gurungkhema (U+16118): L&lt;&lt;868.0,924.0&gt;--&lt;524.0,922.0&gt;&gt;

* cha_gurungkhema (U+16107): L&lt;&lt;840.0,152.0&gt;--&lt;842.0,922.0&gt;&gt;

* da_gurungkhema (U+16112): L&lt;&lt;913.0,115.0&gt;--&lt;915.0,920.0&gt;&gt;

* ddha_gurungkhema (U+1610E): L&lt;&lt;1042.0,922.0&gt;--&lt;1044.0,-2.0&gt;&gt;

* dha_gurungkhema (U+16113): L&lt;&lt;913.0,115.0&gt;--&lt;915.0,920.0&gt;&gt;

* nine_gurungkhema (U+16139): L&lt;&lt;240.0,1022.0&gt;--&lt;238.0,272.0&gt;&gt;

* nine_gurungkhema (U+16139): L&lt;&lt;506.0,283.0&gt;--&lt;504.0,590.0&gt;&gt;

* pha_gurungkhema (U+16116): L&lt;&lt;1120.0,920.0&gt;--&lt;1118.0,0.0&gt;&gt;

* va_gurungkhema (U+1610F): L&lt;&lt;1108.0,922.0&gt;--&lt;524.0,920.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* a_gurungkhema (U+16100) contains a short segment B&lt;&lt;840.0,573.0&gt;-&lt;842.0,545.0&gt;-&lt;843.0,521.5&gt;&gt;

* a_gurungkhema (U+16100) contains a short segment B&lt;&lt;843.0,521.5&gt;-&lt;844.0,498.0&gt;-&lt;844.0,479.0&gt;&gt;

* nga_gurungkhema (U+16105) contains a short segment B&lt;&lt;827.0,588.0&gt;-&lt;828.0,598.0&gt;-&lt;828.5,605.0&gt;&gt;

* nga_gurungkhema (U+16105) contains a short segment B&lt;&lt;828.5,605.0&gt;-&lt;829.0,612.0&gt;-&lt;829.0,616.0&gt;&gt;

* nga_gurungkhema (U+16105) contains a short segment B&lt;&lt;856.0,362.0&gt;-&lt;841.0,353.0&gt;-&lt;827.0,348.0&gt;&gt;

* ca_gurungkhema (U+16106) contains a short segment B&lt;&lt;631.0,455.0&gt;-&lt;627.0,443.0&gt;-&lt;622.0,427.0&gt;&gt;

* ca_gurungkhema (U+16106) contains a short segment B&lt;&lt;622.0,427.0&gt;-&lt;617.0,411.0&gt;-&lt;612.0,391.0&gt;&gt;

* cha_gurungkhema (U+16107) contains a short segment B&lt;&lt;429.5,436.5&gt;-&lt;456.0,422.0&gt;-&lt;481.0,408.0&gt;&gt;

* cha_gurungkhema (U+16107) contains a short segment B&lt;&lt;631.0,455.0&gt;-&lt;627.0,443.0&gt;-&lt;622.0,427.0&gt;&gt;

* cha_gurungkhema (U+16107) contains a short segment B&lt;&lt;622.0,427.0&gt;-&lt;617.0,411.0&gt;-&lt;612.0,391.0&gt;&gt;

* tta_gurungkhema (U+1610B) contains a short segment B&lt;&lt;791.0,412.0&gt;-&lt;816.0,412.0&gt;-&lt;829.0,408.0&gt;&gt;

* ttha_gurungkhema (U+1610C) contains a short segment B&lt;&lt;147.0,543.0&gt;-&lt;143.0,516.0&gt;-&lt;143.0,498.0&gt;&gt;

* ttha_gurungkhema (U+1610C) contains a short segment B&lt;&lt;748.0,408.0&gt;-&lt;764.0,412.0&gt;-&lt;791.0,412.0&gt;&gt;

* ttha_gurungkhema (U+1610C) contains a short segment B&lt;&lt;791.0,412.0&gt;-&lt;817.0,412.0&gt;-&lt;829.0,408.0&gt;&gt;

* ddha_gurungkhema (U+1610E) contains a short segment B&lt;&lt;600.0,252.0&gt;-&lt;587.0,252.0&gt;-&lt;567.5,250.5&gt;&gt;

* ddha_gurungkhema (U+1610E) contains a short segment B&lt;&lt;476.5,243.5&gt;-&lt;457.0,242.0&gt;-&lt;444.0,242.0&gt;&gt;

* da_gurungkhema (U+16112) contains a short segment B&lt;&lt;299.0,385.0&gt;-&lt;303.0,385.0&gt;-&lt;311.0,385.5&gt;&gt;

* da_gurungkhema (U+16112) contains a short segment B&lt;&lt;311.0,385.5&gt;-&lt;319.0,386.0&gt;-&lt;330.0,387.0&gt;&gt;

* dha_gurungkhema (U+16113) contains a short segment B&lt;&lt;299.0,385.0&gt;-&lt;303.0,385.0&gt;-&lt;311.0,385.5&gt;&gt;

* dha_gurungkhema (U+16113) contains a short segment B&lt;&lt;311.0,385.5&gt;-&lt;319.0,386.0&gt;-&lt;330.0,387.0&gt;&gt;

* dha_gurungkhema (U+16113) contains a short segment B&lt;&lt;330.0,387.0&gt;-&lt;353.0,389.0&gt;-&lt;377.0,387.0&gt;&gt;

* pa_gurungkhema (U+16115) contains a short segment B&lt;&lt;785.5,362.0&gt;-&lt;786.0,369.0&gt;-&lt;786.0,370.0&gt;&gt;

* pha_gurungkhema (U+16116) contains a short segment B&lt;&lt;787.5,362.0&gt;-&lt;788.0,369.0&gt;-&lt;788.0,370.0&gt;&gt;

* ra_gurungkhema (U+1611B) contains a short segment B&lt;&lt;504.0,459.0&gt;-&lt;497.0,460.0&gt;-&lt;481.0,460.0&gt;&gt;

* consonantsignmedialya_gurungkhema (U+1612A) contains a short segment L&lt;&lt;0.0,1020.0&gt;--&lt;4.0,1026.0&gt;&gt;

* consonantsignmedialva_gurungkhema (U+1612B) contains a short segment L&lt;&lt;-2.0,1020.0&gt;--&lt;2.0,1026.0&gt;&gt;

* two_gurungkhema (U+16132) contains a short segment B&lt;&lt;102.0,541.0&gt;-&lt;102.0,549.0&gt;-&lt;102.5,561.0&gt;&gt;

* three_gurungkhema (U+16133) contains a short segment B&lt;&lt;710.5,561.0&gt;-&lt;711.0,549.0&gt;-&lt;711.0,541.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;177.0,626.0&gt;--&lt;173.0,626.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;450.0,129.0&gt;--&lt;454.0,129.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;416.0,-9.0&gt;-&lt;410.0,-9.0&gt;-&lt;403.5,-9.5&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;403.5,-9.5&gt;-&lt;397.0,-10.0&gt;-&lt;391.0,-10.0&gt;&gt;

* Uogonek (U+0172) contains a short segment B&lt;&lt;539.5,-158.5&gt;-&lt;551.0,-156.0&gt;-&lt;559.0,-155.0&gt;&gt;

* a (U+0061) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aacute (U+00E1) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* abreve (U+0103) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* acircumflex (U+00E2) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* adieresis (U+00E4) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* agrave (U+00E0) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* amacron (U+0101) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aogonek (U+0105) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aring (U+00E5) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;613.0,293.0&gt;-&lt;612.0,275.0&gt;-&lt;612.0,267.5&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;612.0,267.5&gt;-&lt;612.0,260.0&gt;-&lt;612.0,257.0&gt;&gt;

* atilde (U+00E3) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* d (U+0064) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcaron (U+010F) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcroat (U+0111) contains a short segment L&lt;&lt;445.0,72.0&gt;--&lt;441.0,72.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;184.0,390.0&gt;-&lt;183.0,380.0&gt;-&lt;183.0,371.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,371.0&gt;-&lt;183.0,362.0&gt;-&lt;183.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,352.0&gt;-&lt;183.0,343.0&gt;-&lt;183.0,332.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,332.5&gt;-&lt;183.0,322.0&gt;-&lt;184.0,311.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;95.0,311.0&gt;-&lt;94.0,323.0&gt;-&lt;94.0,331.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,331.0&gt;-&lt;94.0,339.0&gt;-&lt;94.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,352.0&gt;-&lt;94.0,363.0&gt;-&lt;94.5,373.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.5,373.5&gt;-&lt;95.0,384.0&gt;-&lt;95.0,390.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* n (U+006E) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* nacute (U+0144) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ncaron (U+0148) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* uni0146 (U+0146) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ntilde (U+00F1) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* p (U+0070) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;173.0,463.0&gt;&gt;

* r (U+0072) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* racute (U+0155) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* rcaron (U+0159) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;386.0,633.0&gt;--&lt;382.0,633.0&gt;&gt;

* two (U+0032) contains a short segment L&lt;&lt;159.0,84.0&gt;--&lt;159.0,80.0&gt;&gt;

* u (U+0075) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uacute (U+00FA) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ucircumflex (U+00FB) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* udieresis (U+00FC) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ugrave (U+00F9) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uhungarumlaut (U+0171) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* umacron (U+016B) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uring (U+016F) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '????' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-use-typo-metrics">googlefonts/use_typo_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansGurungKhema/googlefonts/ttf/NotoSansGurungKhema-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 6 | 0 | 7 | 13 | 102 | 6 | 102 | 0 | 
| 3% | 0% | 3% | 6% | 43% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
