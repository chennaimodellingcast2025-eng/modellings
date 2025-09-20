PhotoShare — User + Admin demo (safe simulation)
==================================================

Files:
- index.html : User-facing login page. On submit it stores a simulated capture in localStorage and redirects to admin.html.
- admin.html : Admin view that reads simulated captures from localStorage and displays them. Includes Refresh and Clear buttons.

How it works (safe):
- This is a client-side simulation only. Captures are saved to your browser's localStorage under the key 'photoshare_sim_captures_v1'.
- No network requests are made and nothing leaves your machine.
- To demonstrate publicly, host both files on the same origin (e.g., GitHub Pages) so localStorage works across pages.

Hosting example (GitHub Pages):
1. Create a public GitHub repository and push these files to the repository root.
2. Enable Pages on the repo settings (branch: main, folder: / (root)).
3. Access the user page at https://<your-username>.github.io/<repo>/index.html
   and the admin page at https://<your-username>.github.io/<repo>/admin.html

Important:
- Do NOT use real credentials when demonstrating.
- Inform participants that this is a controlled simulation and obtain instructor approval if required.
