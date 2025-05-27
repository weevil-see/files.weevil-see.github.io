# About (WORK IN PROGRESS)
This directory contains scans of the "Coleopterorum Catalogus" which where manually curated by Lutz Behne (25.4.1956 – 25.8.2024). When he scanned Literature, he took great care that every character in scientific names is correctly recognized, and if necessary he corrected them. Thus, he ensured that his files are reliably searchable for scientific names.\
**This is very important for everyone who, like Lutz Behne and me, is using a local search engine to access literature. When we search for a scientific name, the relevant files can only be found if they contain the name exactly as we search for it!**

In short:
- He replaced slavic characters with simplified forms
- He replaced umlauts depending on the origin of names: from German to oe, ae, ue; for non-German names to o, a, u.
  - Schönherri -> schoenherri; Nordenskiöldi -> nordenskioldi  
- Historically, eponyms and patronyms (names honoring a person or place) were capitalized, but modern species names are always lowercase. This was not corrected consistently, though search functions usually ignore capitalization.

There are two directories, which differ only in how the files are organized:
- **./Junk_Concatenated** (some Subfamilies are spread in several parts, those are concatenated into a single file here. Files are named after taxon only)
- **./Junk_Catalog** (files are numbered after the original "pars" number)

The following is a translation of the original "readme" by Lutz Behne, a file which is named "Junk_Curculionoidea_Datierung_Kataloge.pdf" and was last modified 2006/03/27.

# Coleopterorum Catalogus
## (Curculionoidea, Vol. 27-30)

### Overview
In two directories, every catalog from this series (including supplements) have been stored as searchable PDF documents. "Searchable" means that the extracted [recognized using OCR] text was proofread and embedded into the pdf file. All authors, taxa and distribution information have been consistently corrected and standardized.\
Slavic special characters ("ç ć č ě ł š ţ ž" etc.) where replaced with simplified forms (“c e l s t z” etc) in author names and sources. Western european special characters where retained.\
Genus characters (♂♀) where replaced with $ and §, as the program did not embed them during export to pdf. Nowadays, with modern software, "embedding of system fonts" is possible during export.\
Ligatures in the text (Œ, œ, Æ, æ) were replaced with "oe" or "ae".\
Of particular importance is the **standardization of Latin taxon spelling**, which, in accordance with current nomenclature rules (ICZN), no longer permits umlauts (ö, ä, ü). These have been converted to “oe, ae, ue” in German taxa, and to “o, a, u” in non-German taxa—for example: Schönherri, Mülleri became schoenherri and muelleri; Nordenkiöldi became nordenskioldi.\
Taxa printed as nouns (e.g., eponyms or locality names) have in some cases been retained, though this has no impact on text searches—as long as the “match case” option is disabled.\
Searches for multiple terms at once (phrase searching) are currently not possible, since the original text may contain spaces, tabs, margins, indentations, or line breaks between search terms. To preserve the original appearance as closely as possible (and to keep the text exportable to Word), such control characters have largely been left intact.\
**Searching for literature sources is not recommended**, as the number of search results is often limited by the program. Unfortunately, there appear to have been no consistent guidelines for journal title abbreviations or geographic references. In general, full titles of the cited works were not included. Some French authors published nearly everything in French, including country names. In certain cases, source citations are inaccurate or unchecked, and are still frequently misquoted today. Journal issue numbers and years often do not match the original publications.\
In journals with proceedings, usually only the main journal is cited—containing the major papers but not the attached proceedings or member communications (which are often paginated with Roman numerals). Co-authorships are often incorrectly cited as well, e.g., “Boheman in:”. Thus, the citations are not always complete.\
The date of journals can be mistaken, since year of publication per volume and issue can deviate from the front matter. The same applies to monographs or separate works that were published in parts over time.

A disambiguated and corrected version of the citations exists in the literature databases of the DEI [=[Senckenberg Deutsches Entomologisches Institut, Müncheberg](https://www.senckenberg.de/en/institutes/senckenberg-german-entomological-institute/)] which also include the catalogs from the “Index Literaturae Entomologicae, Series I.” However, creating a full searchable database of the complete text was not the goal here.

In this directory, you will find compiled files of all parts for each subfamily (e.g., Brachyderinae I, II, III and Index) grouped together into a single file, despite different parts, authors, and years.
