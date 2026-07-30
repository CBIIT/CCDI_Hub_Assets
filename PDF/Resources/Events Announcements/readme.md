# CCDI Events Announcements PDFs

This folder stores PDF files referenced on the CCDI Events Announcements page:  
https://ccdi.cancer.gov/ccdi-events-announcements

## Folder purpose

- Serve as the GitHub-backed location for CCDI Events Announcements PDFs previously hosted via CloudFront.
- Provide stable, GitHub Pages URLs for use in CCDI markdown content.
- Preserve all PDF titles and metadata as provided by NCI ODS, with no modifications.


## Source of PDFs

- All PDFs in this folder are supplied by ODS or other NCI content owners.
- The CCDI Hub team does **not**:
  - Edit PDF content.
  - Change PDF filenames, titles, or embedded metadata.
  - Regenerate or re-export PDFs.

We simply receive the finalized PDF, upload it to GitHub, and reference it from markdown on ccdi.cancer.gov. 

## URL format

PDFs in this folder are served via GitHub Pages with the prefix:

https://cbiit.github.io/CCDI_Hub_Assets/PDF/Resources/EventsAnnouncements/

To link to a PDF from CCDI markdown:

1. Confirm the file has been uploaded to this folder.
2. Construct the URL as:  
   `https://cbiit.github.io/CCDI_Hub_Assets/PDF/Resources/EventsAnnouncements/<original-file-name>.pdf`
3. Use that URL in the relevant markdown file for the CCDI Events Announcements page or related content.

## Maintenance guidelines

- When a new event announcement PDF is provided:
  - Upload the file to this folder using the **original filename**.
  - Add or update links in the associated markdown file(s) to point to the GitHub Pages URL.
- If a corrected PDF is provided:
  - Replace the existing file with the new version, keeping the same filename, or
  - Upload the new file as provided and update the markdown link accordingly, following ODS instructions. 

## Contact

For questions about CCDI event announcements content or PDF availability, contact the CCDI Hub/ODS content management team through the standard CCDI support channels:  
NCIChildhoodCancerDataInitiative@mail.nih.gov 
