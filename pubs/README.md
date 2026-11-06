# Hosted publication PDFs

Drop publication PDFs here (e.g. `transport-stress-2025.pdf`), commit, and push —
Netlify redeploys automatically.

Then in `publications.html`, find the matching "HOSTED PDF SLOT" comment and replace
the `<span class="pub-slot">…</span>` with:

    <a class="pub-btn" href="/pubs/FILENAME.pdf" target="_blank">Read the PDF</a>

Only host PDFs Gigi's has the right to distribute: the journal articles and abstracts
are open access (fine to host); the Wiley textbook and Clinician's Brief article are
not — link only.
