# Mufid Portfolio — HTML-first prototype

- `index.html`: single-file public portfolio prototype; HTML is the main structure, with inline CSS and JavaScript for presentation and interactions.
- `assets/images/mufid-kuala-lumpur.jpg`: first uploaded photo selected for hero.
- `assets/images/mufid-upi-bandung.jpg`: second uploaded photo for About.

## Run locally
1. Extract the ZIP and open the folder in VS Code.
2. Run with the Live Server extension or another static local server.
3. Open `index.html` in the browser.

## Scope and limitations
- This is a static prototype. Supabase is not connected yet.
- The admin section is a specification preview only; it is not a login page and accepts no password.
- The contact form opens a `mailto:` draft; it does not save messages in a database.
- Projects are seed content in HTML. The next phase should connect project/article content to Supabase and implement a separate protected admin interface, CRUD, draft/published preview, uploads, RLS policies, and tests.
- Never put passwords or Supabase service-role keys in HTML/JavaScript. Create the admin account through Supabase Auth, disable public sign-up, and use a new strong password rather than any temporary code previously shared in chat.
- Verify HKI titles, project statuses, contributions, dates, and public document permissions before final publication.


## Readable formatting in VS Code
- `index.html` has been indented and split into lines for easier study.
- To format again, open `index.html` and use **Shift + Alt + F** on Windows.
- If VS Code asks for a formatter, select **HTML Language Features**.
- Optional: install the Prettier extension for consistent formatting across HTML, CSS, and JavaScript.
- Turn on **View → Word Wrap** (shortcut **Alt + Z**) to wrap long lines visually without changing the source.
