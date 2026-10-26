# apollocap.com (static holding page)

Static, no build step. Deploy as-is to GitHub Pages (same pattern as abcvirtualoffices.com):
`CNAME` = www.apollocap.com, `.nojekyll`, `404.html`. Content is taken only from the
original Hot Weazel-hosted page (backup: ApolloCap.com.zip).

DNS to keep at GoDaddy: Google Workspace MX records, `mail` CNAME -> ghs.google.com,
both google-site-verification TXT records.
