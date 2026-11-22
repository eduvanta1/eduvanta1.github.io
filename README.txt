EDUVANTA SCHOLARS — GitHub Pages project

FILES
- index.html              Main website
- keyfree/index.html      24-hour access activation / return page
- assets/                 Upload eduvanta-logo.png here

PUBLISH
1. Upload the contents of this folder to the ROOT of the GitHub repository used by
   https://eduvanta.github.io/
2. Upload your logo as assets/eduvanta-logo.png (exact spelling).
3. In VPLink, set the destination/redirect URL to:
   https://eduvanta.github.io/keyfree
4. Enable pop-ups for eduvanta.github.io if your browser blocks the VPLink tab.

ACCESS FLOW
- Clicking Next Toppers with an active key opens the platform inside the website iframe.
- Without an active key, VPLink opens in a new tab.
- The keyfree page stores a 24-hour expiry and signals the original tab.
- The original tab opens Next Toppers automatically; the return tab also redirects to the site.
- Expiry is checked against the saved timestamp and the countdown is updated every second.

IMPORTANT SECURITY NOTE
This is client-side access gating. It stores an expiry timestamp in the visitor's browser,
but it cannot independently verify that a VPLink ad/task was actually completed. A user
can modify browser storage. Genuine completion verification requires a trusted backend
and a server-issued access token.

PLATFORM
https://eduvibe-nt.pages.dev/

VPLink
https://vplink.in/Emxg

COMMUNITY
https://t.me/EduVantaHQG/1
