LITTLE PAGES 2.1 — UPDATE PACKAGE

WHAT'S INCLUDED
- index.html: updated single-page Little Pages website.

PRESERVED
- Supabase project URL and public publishable key already present in your 2.0 source.
- Existing email OTP login flow.
- Existing book catalogue, demo cart, and PDF path conventions.
- Existing worksheet cards and sheets/ paths.
- Existing pdfs/ paths.
- GitHub Pages-compatible static hosting.

IMPROVEMENTS
- Added canonical URL and search-friendly page metadata.
- Added live book count and improved book search matching.
- Made worksheet empty state use the hidden attribute so it cannot appear alongside results.
- Added a clear-filters control and accessible live result count.
- Improved footer navigation and added digital-product information.
- Improved mobile layout for worksheet filters.
- Added dynamic copyright year.

HOW TO PUBLISH
1. Download and extract this ZIP.
2. Open your GitHub repository: smartfilemanger/little-pages.
3. Replace the repository-root index.html with this package's index.html.
4. Also upload privacy.html and terms.html to the same repository root as index.html.
5. Do NOT delete or rename the existing pdfs/ or sheets/ folders.
6. Commit the changes to the branch/folder used by GitHub Pages.
7. Wait for GitHub Pages to deploy, then hard-refresh the website (Ctrl+F5).

IMPORTANT
- This package does not include your PDF files. Keep your existing pdfs/ and sheets/ folders in the repository.
- The cart remains a demo. No payment processing or secure paid-file delivery has been added.
- Confirm all paid-book files and prices before accepting orders.
- The Supabase key in a static website must be a publishable/anon key only; never use a service_role or secret key.
- No live deployment was performed from this package.

SEPARATE LEGAL PAGES (2.3)
- Privacy Policy now opens at privacy.html.
- Terms & Conditions now opens at terms.html.
- Both pages include a Back to Home link.
- The homepage footer links point to these separate pages.
- Replace [ADD YOUR SUPPORT EMAIL BEFORE PUBLISHING] in both pages with a monitored support email before publishing.
