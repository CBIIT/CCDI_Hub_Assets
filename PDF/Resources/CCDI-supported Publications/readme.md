# CCDI Publications PDFs

This folder stores PDF files used by the CCDI-Supported Publications page and linked from https://github.com/CBIIT/CCDI_Hub_Static_Contents/blob/dev/publicationsData.md.

## Purpose

The CCDI-Supported Publications page includes cards for conference abstracts, journal publications, white papers, and preprints.[1] Conference abstract cards have historically linked users to external conference sites, but those sites may later be deprecated, archived, or removed, which can result in broken links and lost access to abstract content.

To support long-term access, abstract PDFs and other publication PDFs can be stored in this CCDI-supported Publications folder and linked from the Publications page markdown content rather than relying solely on external conference websites for Conference Abstract cards. 

## Source-of-truth workflow 

PDFs placed in this folder are provided as finalized files by the appropriate content owners. The CCDI Hub team does not edit PDF content, change PDF filenames, titles, or embedded metadata, or regenerate or re-export PDFs.

The workflow is straightforward:

1. Receive the finalized PDF.
2. Upload the file to the CCDI-supported Publications folder in GitHub.
3. Point to the hosted file from `publicationsData.md` and surface it on the CCDI Publications page.

## Hosting and link usage

Publication PDFs in this folder are intended to be hosted in GitHub and referenced from the CCDI static content repository, including `publicationsData.md`. The rendered user-facing publications page is available at [ccdi.cancer.gov/publications](https://ccdi.cancer.gov/publications).

When a PDF is uploaded to the CCDI-supported Publications folder in the assets repository, the markdown entry should point to the corresponding hosted file URL so the Publications page can direct users to a CCDI-managed copy instead of an external site when appropriate.

## Maintenance guidelines

- Preserve the original PDF exactly as received.
- Do not rename the file unless a content owner specifically provides a replacement filename.
- Update the relevant markdown entry in `publicationsData.md` to point to the hosted PDF.

This approach supports more reliable access to CCDI-related publication materials over time.
