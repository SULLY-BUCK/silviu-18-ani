# Invitation page

This workspace contains a single static HTML invitation page in `invitatie.html`.

For a full publish-and-share guide, see `SHARE_GUIDE.md`.

## How to publish

1. Upload the project to GitHub Pages, Netlify, or Vercel.
2. Make sure the published file path is `/invitatie.html`.
3. Send personalized links in this format:
   - `https://YOUR-DOMAIN/invitatie.html?name=Ioana`
   - `https://YOUR-DOMAIN/invitatie.html?name=Marian&gender=f`
   - `https://YOUR-DOMAIN/invitatie.html?name=Ioana&message=Textul%20personalizat%20pentru%20mesajul%20tău`
   - `https://YOUR-DOMAIN/invitatie.html?name=Familia%20mea&family=1` (link separat pentru familie, iubita și rude apropiate)

## Notes

- No separate server is needed for each guest.
- The page uses the `name` parameter to personalize the message and heading.
- You can also pass `gender` and `message` (or `note`) to override the note text for a specific guest.
- Add `family=1` (or `group=family`) for the dedicated family version of the invitation.
