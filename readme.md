# Convert Word docx files to more readable preprint pdfs

## Purpose

Preprints are distributed with increasing freuquency. This freedom to distribute preprints results in a variety of presentation formats. Most psychology journals requires submissions in APA format, requiring authors to write their master document in this format. However, this format is not particularly attractive or readable. To increase readability and consistency across documents while minimising burden on researchers, this R markdown script will convert a correctly APA formatted document in to a more readable pdf preprint.

This is a proof of concept - tables and figures are not yet accomodated. Please feel free to fork and add such functionality!      

## Usage

1. Remove all tables and figures from your .docx manuscript. These aren't yet accomodated.
2. If the document used a reference manager, convert these fields to text. E.g., in Zotero click the "Remove codes" button.
3. This script requires your document to have title and authors as the first and second lines in the document, the headings "abstract", "methods", "results", "discussion", and "references". The abstract must be followed by a line starting with "Keywords", immediately followed by the introduction section.
4. Rename your .docx to "manuscript.docx" and place in the same folder as this R markdown file.
5. Open the .Rmd in RStudio and click the "Knit" button. "preprint.pdf" will be created in the same folder.

## License

[GPLv3+](https://tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3)): You may copy, distribute and modify the software as long as you track changes/dates in source files. Any modifications to or software including (via compiler) GPL-licensed code must also be made available under the GPL along with build & install instructions.