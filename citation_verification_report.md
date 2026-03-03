# Citation Verification Report

## Scope and Rules Applied
- File audited: `references.bib`
- Entries audited: 27
- Title-lock rule enforced: no `title` field was edited.
- Verification order per entry: title search first, then DOI/publisher metadata.
- Source priority: DOI/publisher metadata first; indexing sources used only as secondary confirmation.

## Outcome Summary
- `corrected_non_title`: 9
- `unchanged`: 18
- `flag_no_title_match`: 0
- `manual_review`: 0

## Entry Status (All Keys)

| key | status | fields_changed | primary_source_link | secondary_source_link | notes |
|---|---|---|---|---|---|
| Cox1972 | corrected_non_title | pages | https://doi.org/10.1111/j.2517-6161.1972.tb00899.x | https://academic.oup.com/jrsssb/article/34/2/187/7027194 | Title matched; corrected page range. |
| Tibshirani1997 | unchanged | - | https://doi.org/10.1002/(SICI)1097-0258(19970228)16:4%3C385::AID-SIM380%3E3.0.CO;2-3 | - | Title matched. |
| Simon2011 | unchanged | - | https://doi.org/10.18637/jss.v039.i05 | - | Title matched. |
| Ishwaran2008 | unchanged | - | https://doi.org/10.1214/08-AOAS169 | - | Title matched. |
| Katzman2018 | unchanged | - | https://doi.org/10.1186/s12874-018-0482-1 | - | Title matched. |
| VantVeer2002 | unchanged | - | https://doi.org/10.1038/415530a | - | Title matched. |
| Paik2004 | unchanged | - | https://doi.org/10.1056/NEJMoa041588 | - | Title matched. |
| Bovelstad2007 | unchanged | - | https://doi.org/10.1093/bioinformatics/btm305 | - | Title matched. |
| Bair2006 | unchanged | - | https://doi.org/10.1198/016214505000000628 | - | Title matched. |
| vanWieringen2009 | unchanged | - | https://doi.org/10.1016/j.csda.2008.05.021 | - | Title matched. |
| Weinstein2013 | unchanged | - | https://doi.org/10.1038/ng.2764 | - | Title matched. |
| Tomczak2015 | unchanged | - | https://doi.org/10.5114/wo.2014.47136 | - | Title matched. |
| Liu2018 | unchanged | - | https://doi.org/10.1016/j.cell.2018.02.052 | - | Title matched. |
| VanBelle2011 | unchanged | - | https://doi.org/10.1016/j.artmed.2011.06.006 | - | Title matched. |
| KleinMoeschberger2003 | unchanged | - | https://doi.org/10.1007/b97377 | - | Title matched (book record). |
| AndersenGill1982 | unchanged | - | https://doi.org/10.1214/aos/1176345976 | - | Title matched. |
| McGough2021 | corrected_non_title | author | https://doi.org/10.1002/sim.9136 | https://pubmed.ncbi.nlm.nih.gov/34309104/ | Expanded `and others` to full author list. |
| Brown2022 | corrected_non_title | author | https://doi.org/10.1001/jamaoncol.2021.5153 | https://pubmed.ncbi.nlm.nih.gov/34935962/ | Expanded `and others` to full author list and consortium. |
| FuSimonoff2016 | corrected_non_title | journal, year, volume, number, pages, doi, note | https://doi.org/10.1093/biostatistics/kxw047 | https://arxiv.org/abs/1606.03033 | Title matched; upgraded preprint metadata to peer-reviewed journal version while retaining arXiv info. |
| LaurentVoVan2024 | unchanged | - | https://doi.org/10.5201/ipol.2024.466 | - | Title matched. |
| Seo2025 | corrected_non_title | author | https://doi.org/10.3390/app152212093 | - | Expanded `and others` to complete listed authors. |
| Gray1988 | unchanged | - | https://doi.org/10.1214/aos/1176350951 | - | Title matched. |
| FineGray1999 | unchanged | - | https://doi.org/10.1080/01621459.1999.10474144 | - | Title matched. |
| Binder2009 | corrected_non_title | author | https://doi.org/10.1093/bioinformatics/btp088 | https://pubmed.ncbi.nlm.nih.gov/19237326/ | DOI confirmed; author list expanded to full author set from publisher/PubMed metadata. |
| HouBradicXu2019EJS | corrected_non_title | key, author, pages | https://doi.org/10.1214/19-EJS1562 | https://experts.umn.edu/en/publications/inference-under-fine-gray-competing-risks-model-with-high-dimensi/ | Title matched; corrected first-author attribution, author list, and page range; citation key renamed from `Cui2019EJS`. |
| RAEN2023 | corrected_non_title | author, pages, doi | https://doi.org/10.1002/bimj.202100164 | https://onlinelibrary.wiley.com/doi/10.1002/bimj.202100164 | Title matched; corrected authors, article identifier, and DOI. |
| PSHSAFE2022 | corrected_non_title | journal, doi | https://doi.org/10.1002/sim.9545 | https://onlinelibrary.wiley.com/doi/10.1002/sim.9545 | Title matched; added missing DOI and standardized journal capitalization. |

## Detailed Before/After for Corrected Entries

### Cox1972
- `pages`
  - before: `187--220`
  - after: `187--202`

### McGough2021
- `author`
  - before: `McGough, Sarah F. and others`
  - after: `McGough, Sarah F. and Incerti, Devin and Lyalina, Svetlana and Copping, Ryan and Narasimhan, Balasubramanian and Tibshirani, Robert`

### Brown2022
- `author`
  - before: `Brown, Samantha and Lavery, Jessica A. and Shen, Ronglai and others`
  - after: `Brown, Samantha and Lavery, Jessica A. and Shen, Ronglai and Martin, Axel S. and Kehl, Kenneth L. and Sweeney, Shawn M. and Lepisto, Eva M. and Rizvi, Hira and McCarthy, Caroline G. and Schultz, Nikolaus and Warner, Jeremy L. and Park, Ben Ho and Bedard, Philippe L. and Riely, Gregory J. and Schrag, Deborah and Panageas, Katherine S. and AACR Project GENIE Consortium`

### FuSimonoff2016
- `journal`
  - before: `arXiv preprint`
  - after: `Biostatistics`
- `year`
  - before: `2016`
  - after: `2017`
- `volume`
  - before: *(missing)*
  - after: `18`
- `number`
  - before: *(missing)*
  - after: `2`
- `pages`
  - before: *(missing)*
  - after: `352--369`
- `doi`
  - before: *(missing)*
  - after: `10.1093/biostatistics/kxw047`
- `note`
  - before: *(missing)*
  - after: `First posted on arXiv in 2016`

### Seo2025
- `author`
  - before: `Seo, B. J. and others`
  - after: `Seo, Bum-Jeun and Lee, Mi-Joon`

### Binder2009
- `author`
  - before: `Binder, Harald and Schumacher, Martin`
  - after: `Binder, Harald and Allignol, Arthur and Schumacher, Martin and Beyersmann, Jan`

### HouBradicXu2019EJS
- `key`
  - before: `Cui2019EJS`
  - after: `HouBradicXu2019EJS`
- `author`
  - before: `Cui, Yining and Ma, Shu and Sun, Jiajia`
  - after: `Hou, Jue and Bradic, Jelena and Xu, Ronghui`
- `pages`
  - before: `3404--3442`
  - after: `4449--4507`

### RAEN2023
- `author`
  - before: `Zhang, Yaqi and Li, Yujing and others`
  - after: `Sun, Han and Wang, Xiaofeng`
- `pages`
  - before: `2200154`
  - after: `e2100164`
- `doi`
  - before: `10.1002/bimj.202200154`
  - after: `10.1002/bimj.202100164`

### PSHSAFE2022
- `journal`
  - before: `Statistics in medicine`
  - after: `Statistics in Medicine`
- `doi`
  - before: *(missing)*
  - after: `10.1002/sim.9545`

## Title-Lock Compliance
- `title` edits applied: 0
- Entries flagged `flag_no_title_match`: 0
