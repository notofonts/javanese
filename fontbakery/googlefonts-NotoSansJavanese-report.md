## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansJavanese/googlefonts/ttf', 'fonts/NotoSansJavanese/googlefonts/variable-ttf'] [code: single-directory]
</div></details><br></div></details><details><summary><b>[6] NotoSansJavanese-Bold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- cakra.ns
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

	* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=192.5,Y=749.0 (should be at cap-height 750?)

	* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=295.0,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=288.5,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=481.0,Y=536.5 (should be at x-height 536?)

	* m (U+006D): X=627.5,Y=537.0 (should be at x-height 536?) 

	* And 72 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[6] NotoSansJavanese-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/javanese.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansJavanese/googlefonts/ttf/NotoSansJavanese-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/javanese.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">◌ꦿꦸ</span> (googlefonts/noto-fonts#1473)</li>


<pre>Expected: cakra=0+238|uni25CC=0+594|u.ns=0@-66,0+0</pre>



<pre>Got     : cakra=0+238|uni25CC=0+594|u.ns=0@1,0+0</pre>



<pre>                                           ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 832 3036" transform="matrix(1 0 0 -1 0 0)">
<path d="M299.0,-181.0Q69.0,-181.0 69.0,118.0Q69.0,404.0 281.0,750.0L341.0,717.0Q158.0,381.0 158.0,135.0Q158.0,67.0 172.5,15.5Q187.0,-36.0 220.0,-64.5Q253.0,-93.0 310.0,-93.0Q367.0,-93.0 431.0,-57.0L467.0,-125.0Q385.0,-181.0 299.0,-181.0Z"  transform="translate(0, 1416)"/>
<path d="M297.0,540.0Q308.0,540.0 315.5,532.5Q323.0,525.0 323.0,514.0Q323.0,504.0 315.5,496.0Q308.0,488.0 297.0,488.0Q287.0,488.0 279.0,496.0Q271.0,504.0 271.0,514.0Q271.0,525.0 279.0,532.5Q287.0,540.0 297.0,540.0ZM213.0,522.0Q224.0,522.0 231.5,514.5Q239.0,507.0 239.0,496.0Q239.0,486.0 231.5,478.0Q224.0,470.0 213.0,470.0Q203.0,470.0 195.0,478.0Q187.0,486.0 187.0,496.0Q187.0,507.0 195.0,514.5Q203.0,522.0 213.0,522.0ZM381.0,522.0Q392.0,522.0 399.5,514.5Q407.0,507.0 407.0,496.0Q407.0,486.0 399.5,478.0Q392.0,470.0 381.0,470.0Q371.0,470.0 363.0,478.0Q355.0,486.0 355.0,496.0Q355.0,507.0 363.0,514.5Q371.0,522.0 381.0,522.0ZM113.0,449.0Q113.0,460.0 121.0,467.5Q129.0,475.0 139.0,475.0Q150.0,475.0 157.5,467.5Q165.0,460.0 165.0,449.0Q165.0,439.0 157.5,431.0Q150.0,423.0 139.0,423.0Q129.0,423.0 121.0,431.0Q113.0,439.0 113.0,449.0ZM429.0,449.0Q429.0,460.0 437.0,467.5Q445.0,475.0 455.0,475.0Q466.0,475.0 473.5,467.5Q481.0,460.0 481.0,449.0Q481.0,439.0 473.5,431.0Q466.0,423.0 455.0,423.0Q445.0,423.0 437.0,431.0Q429.0,439.0 429.0,449.0ZM66.0,375.0Q66.0,386.0 74.0,393.5Q82.0,401.0 92.0,401.0Q103.0,401.0 110.5,393.5Q118.0,386.0 118.0,375.0Q118.0,365.0 110.5,357.0Q103.0,349.0 92.0,349.0Q82.0,349.0 74.0,357.0Q66.0,365.0 66.0,375.0ZM476.0,375.0Q476.0,386.0 484.0,393.5Q492.0,401.0 502.0,401.0Q513.0,401.0 520.5,393.5Q528.0,386.0 528.0,375.0Q528.0,365.0 520.5,357.0Q513.0,349.0 502.0,349.0Q492.0,349.0 484.0,357.0Q476.0,365.0 476.0,375.0ZM48.0,291.0Q48.0,302.0 56.0,309.5Q64.0,317.0 74.0,317.0Q85.0,317.0 92.5,309.5Q100.0,302.0 100.0,291.0Q100.0,281.0 92.5,273.0Q85.0,265.0 74.0,265.0Q64.0,265.0 56.0,273.0Q48.0,281.0 48.0,291.0ZM494.0,291.0Q494.0,302.0 502.0,309.5Q510.0,317.0 520.0,317.0Q531.0,317.0 538.5,309.5Q546.0,302.0 546.0,291.0Q546.0,281.0 538.5,273.0Q531.0,265.0 520.0,265.0Q510.0,265.0 502.0,273.0Q494.0,281.0 494.0,291.0ZM66.0,207.0Q66.0,218.0 74.0,225.5Q82.0,233.0 92.0,233.0Q103.0,233.0 110.5,225.5Q118.0,218.0 118.0,207.0Q118.0,197.0 110.5,189.0Q103.0,181.0 92.0,181.0Q82.0,181.0 74.0,189.0Q66.0,197.0 66.0,207.0ZM476.0,207.0Q476.0,218.0 484.0,225.5Q492.0,233.0 502.0,233.0Q513.0,233.0 520.5,225.5Q528.0,218.0 528.0,207.0Q528.0,197.0 520.5,189.0Q513.0,181.0 502.0,181.0Q492.0,181.0 484.0,189.0Q476.0,197.0 476.0,207.0ZM113.0,133.0Q113.0,144.0 121.0,151.5Q129.0,159.0 139.0,159.0Q150.0,159.0 157.5,151.5Q165.0,144.0 165.0,133.0Q165.0,123.0 157.5,115.0Q150.0,107.0 139.0,107.0Q129.0,107.0 121.0,115.0Q113.0,123.0 113.0,133.0ZM429.0,133.0Q429.0,144.0 437.0,151.5Q445.0,159.0 455.0,159.0Q466.0,159.0 473.5,151.5Q481.0,144.0 481.0,133.0Q481.0,123.0 473.5,115.0Q466.0,107.0 455.0,107.0Q445.0,107.0 437.0,115.0Q429.0,123.0 429.0,133.0ZM213.0,112.0Q224.0,112.0 231.5,104.5Q239.0,97.0 239.0,86.0Q239.0,76.0 231.5,68.0Q224.0,60.0 213.0,60.0Q203.0,60.0 195.0,68.0Q187.0,76.0 187.0,86.0Q187.0,97.0 195.0,104.5Q203.0,112.0 213.0,112.0ZM381.0,112.0Q392.0,112.0 399.5,104.5Q407.0,97.0 407.0,86.0Q407.0,76.0 399.5,68.0Q392.0,60.0 381.0,60.0Q371.0,60.0 363.0,68.0Q355.0,76.0 355.0,86.0Q355.0,97.0 363.0,104.5Q371.0,112.0 381.0,112.0ZM297.0,94.0Q308.0,94.0 315.5,86.5Q323.0,79.0 323.0,68.0Q323.0,58.0 315.5,50.0Q308.0,42.0 297.0,42.0Q287.0,42.0 279.0,50.0Q271.0,58.0 271.0,68.0Q271.0,79.0 279.0,86.5Q287.0,94.0 297.0,94.0Z"  transform="translate(238, 1416)"/>
<path d="M-14.0,-829.0Q-136.0,-829.0 -136.0,-667.0L-136.0,16.0L-49.0,16.0L-49.0,-692.0Q-49.0,-746.0 -15.0,-746.0Q20.0,-746.0 20.0,-692.0L20.0,-97.0L107.0,-97.0L107.0,-667.0Q107.0,-829.0 -14.0,-829.0Z"  transform="translate(833, 1416)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 832 3036" transform="matrix(1 0 0 -1 0 0)">
<path d="M299.0,-181.0Q69.0,-181.0 69.0,118.0Q69.0,404.0 281.0,750.0L341.0,717.0Q158.0,381.0 158.0,135.0Q158.0,67.0 172.5,15.5Q187.0,-36.0 220.0,-64.5Q253.0,-93.0 310.0,-93.0Q367.0,-93.0 431.0,-57.0L467.0,-125.0Q385.0,-181.0 299.0,-181.0Z"  transform="translate(0, 1416)"/>
<path d="M297.0,540.0Q308.0,540.0 315.5,532.5Q323.0,525.0 323.0,514.0Q323.0,504.0 315.5,496.0Q308.0,488.0 297.0,488.0Q287.0,488.0 279.0,496.0Q271.0,504.0 271.0,514.0Q271.0,525.0 279.0,532.5Q287.0,540.0 297.0,540.0ZM213.0,522.0Q224.0,522.0 231.5,514.5Q239.0,507.0 239.0,496.0Q239.0,486.0 231.5,478.0Q224.0,470.0 213.0,470.0Q203.0,470.0 195.0,478.0Q187.0,486.0 187.0,496.0Q187.0,507.0 195.0,514.5Q203.0,522.0 213.0,522.0ZM381.0,522.0Q392.0,522.0 399.5,514.5Q407.0,507.0 407.0,496.0Q407.0,486.0 399.5,478.0Q392.0,470.0 381.0,470.0Q371.0,470.0 363.0,478.0Q355.0,486.0 355.0,496.0Q355.0,507.0 363.0,514.5Q371.0,522.0 381.0,522.0ZM113.0,449.0Q113.0,460.0 121.0,467.5Q129.0,475.0 139.0,475.0Q150.0,475.0 157.5,467.5Q165.0,460.0 165.0,449.0Q165.0,439.0 157.5,431.0Q150.0,423.0 139.0,423.0Q129.0,423.0 121.0,431.0Q113.0,439.0 113.0,449.0ZM429.0,449.0Q429.0,460.0 437.0,467.5Q445.0,475.0 455.0,475.0Q466.0,475.0 473.5,467.5Q481.0,460.0 481.0,449.0Q481.0,439.0 473.5,431.0Q466.0,423.0 455.0,423.0Q445.0,423.0 437.0,431.0Q429.0,439.0 429.0,449.0ZM66.0,375.0Q66.0,386.0 74.0,393.5Q82.0,401.0 92.0,401.0Q103.0,401.0 110.5,393.5Q118.0,386.0 118.0,375.0Q118.0,365.0 110.5,357.0Q103.0,349.0 92.0,349.0Q82.0,349.0 74.0,357.0Q66.0,365.0 66.0,375.0ZM476.0,375.0Q476.0,386.0 484.0,393.5Q492.0,401.0 502.0,401.0Q513.0,401.0 520.5,393.5Q528.0,386.0 528.0,375.0Q528.0,365.0 520.5,357.0Q513.0,349.0 502.0,349.0Q492.0,349.0 484.0,357.0Q476.0,365.0 476.0,375.0ZM48.0,291.0Q48.0,302.0 56.0,309.5Q64.0,317.0 74.0,317.0Q85.0,317.0 92.5,309.5Q100.0,302.0 100.0,291.0Q100.0,281.0 92.5,273.0Q85.0,265.0 74.0,265.0Q64.0,265.0 56.0,273.0Q48.0,281.0 48.0,291.0ZM494.0,291.0Q494.0,302.0 502.0,309.5Q510.0,317.0 520.0,317.0Q531.0,317.0 538.5,309.5Q546.0,302.0 546.0,291.0Q546.0,281.0 538.5,273.0Q531.0,265.0 520.0,265.0Q510.0,265.0 502.0,273.0Q494.0,281.0 494.0,291.0ZM66.0,207.0Q66.0,218.0 74.0,225.5Q82.0,233.0 92.0,233.0Q103.0,233.0 110.5,225.5Q118.0,218.0 118.0,207.0Q118.0,197.0 110.5,189.0Q103.0,181.0 92.0,181.0Q82.0,181.0 74.0,189.0Q66.0,197.0 66.0,207.0ZM476.0,207.0Q476.0,218.0 484.0,225.5Q492.0,233.0 502.0,233.0Q513.0,233.0 520.5,225.5Q528.0,218.0 528.0,207.0Q528.0,197.0 520.5,189.0Q513.0,181.0 502.0,181.0Q492.0,181.0 484.0,189.0Q476.0,197.0 476.0,207.0ZM113.0,133.0Q113.0,144.0 121.0,151.5Q129.0,159.0 139.0,159.0Q150.0,159.0 157.5,151.5Q165.0,144.0 165.0,133.0Q165.0,123.0 157.5,115.0Q150.0,107.0 139.0,107.0Q129.0,107.0 121.0,115.0Q113.0,123.0 113.0,133.0ZM429.0,133.0Q429.0,144.0 437.0,151.5Q445.0,159.0 455.0,159.0Q466.0,159.0 473.5,151.5Q481.0,144.0 481.0,133.0Q481.0,123.0 473.5,115.0Q466.0,107.0 455.0,107.0Q445.0,107.0 437.0,115.0Q429.0,123.0 429.0,133.0ZM213.0,112.0Q224.0,112.0 231.5,104.5Q239.0,97.0 239.0,86.0Q239.0,76.0 231.5,68.0Q224.0,60.0 213.0,60.0Q203.0,60.0 195.0,68.0Q187.0,76.0 187.0,86.0Q187.0,97.0 195.0,104.5Q203.0,112.0 213.0,112.0ZM381.0,112.0Q392.0,112.0 399.5,104.5Q407.0,97.0 407.0,86.0Q407.0,76.0 399.5,68.0Q392.0,60.0 381.0,60.0Q371.0,60.0 363.0,68.0Q355.0,76.0 355.0,86.0Q355.0,97.0 363.0,104.5Q371.0,112.0 381.0,112.0ZM297.0,94.0Q308.0,94.0 315.5,86.5Q323.0,79.0 323.0,68.0Q323.0,58.0 315.5,50.0Q308.0,42.0 297.0,42.0Q287.0,42.0 279.0,50.0Q271.0,58.0 271.0,68.0Q271.0,79.0 279.0,86.5Q287.0,94.0 297.0,94.0Z"  transform="translate(238, 1416)"/>
<path d="M-14.0,-829.0Q-136.0,-829.0 -136.0,-667.0L-136.0,16.0L-49.0,16.0L-49.0,-692.0Q-49.0,-746.0 -15.0,-746.0Q20.0,-746.0 20.0,-692.0L20.0,-97.0L107.0,-97.0L107.0,-667.0Q107.0,-829.0 -14.0,-829.0Z"  transform="translate(766, 1416)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- cakra.ns
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

	* G (U+0047): X=537.0,Y=-1.0 (should be at baseline 0?) 

	* And 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[7] NotoSansJavanese[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- cakra.ns
 [code: unreachable-glyphs]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 2 | 15 | 317 | 20 | 294 | 0 |
| 0% | 0% | 2% | 49% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
