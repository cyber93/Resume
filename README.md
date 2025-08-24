[Overleaf_Customised_CurVe_CV]
 * Download simpleicons: https://ctan.org/pkg/simpleicons
 * Extract and Update the default font map
   - cd simpleicons/map
   - sudo updmap-sys --enable Map=simpleicons.map

 * Changed the default bibliography tool from bibtex to biber.
   [TeXstudio]
     - Options > Configure TeXstudio > Build > Default Bibliography Tool > (BibTex -> Biber)
   [Texmaker]
     - Options > Configure Texmaker > Commands >Bib(la)tex > (bibtex %.aux -> biber %)
