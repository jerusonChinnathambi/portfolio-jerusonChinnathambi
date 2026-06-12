JERUSON PAUL CHINNATHAMBI - PORTFOLIO v7 (SELF-CONTAINED PAGES)
==============================================================

WHY v7: the page showed up unstyled because index.html was opened by
itself, with no assets/ folder beside it, so the stylesheet 404'd.
FIXED: the CSS and JS are now baked INTO every .html page. Each page
styles itself with no external stylesheet, so it looks right whether you
double-click it loose OR deploy the whole folder.

TO PREVIEW ON YOUR MAC (quick check)
------------------------------------
Unzip this file, then open  site/index.html  by double-clicking.
It will be fully styled and animated on its own.
(The "Full PDF" buttons and the links between project pages only work
when the whole unzipped folder stays together - which it does in the zip.)

FILE STRUCTURE
--------------
index.html                         <- self-contained, styled on its own
projects/
  biryani-heaven.html              <- each also self-contained
  fintech-inclusion.html
  redbull-forecasting.html
  apple-supply-chain.html
assets/
  papers/
    biryani-heaven-analytics-case-study.pdf
    fintech-financial-inclusion-ieee.pdf
    redbull-marketing-ml-analytics.pdf
    apple-arm-chip-operations-logistics.pdf

(There is no longer any site.css / site.js to upload - the styling lives
inside each page.)

TO GO LIVE ON GITHUB PAGES (jerusonchinnathambi.github.io/JerusonPortfolio7/)
----------------------------------------------------------------------------
Upload, keeping this exact structure:
  - index.html  (replace the old one)
  - the /projects/ folder
  - the /assets/papers/ folder WITH all 4 PDFs
All links are relative, so they work under the /JerusonPortfolio7/ subpath.
GitHub Pages is case-sensitive - keep names exactly as shown.
Redeploys in about a minute.
