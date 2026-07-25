# Local Regularization Publication

## Goal

Publish Eric Hou's paper, *Local Regularization Does Not Characterize Multiclass PAC Learnability*, on the research page and make its PDF available from the deployed site.

## Design

Add a Machine Learning section to `research.html`, between Mathematics and Scientific Computing. It will contain one publication paragraph matching the existing typography and structure: bold title, muted authorship/date, a concise abstract-derived summary, and a relative link to the PDF.

Copy the supplied PDF into `assets/` with a descriptive, URL-safe filename and link to that local asset. No stylesheet or navigation changes are required.

## Validation

Confirm the source PDF is present at the linked asset path, inspect the rendered research page for the publication text and working link, then deploy the unchanged static-site layout through the existing Vercel project and verify the production URL returns the updated page.
