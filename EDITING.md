# How to edit the website

The whole website is one page: `index.html`. Colours and layout are in `styles.css`.

## Change some words

1. Sign in at github.com and open the repository **venkatasuryam.github.io**.
2. Click **index.html**, then the **pencil icon** (Edit this file).
3. Press Ctrl + F (Cmd + F on a Mac) to find the sentence you want to change.
4. Change only the words between the tags. For example, in
   `<p>Please enquire about the consultation fee before booking.</p>`
   change the text, but keep `<p>` and `</p>` exactly as they are.
5. Click **Commit changes…**, add a short note (for example "Updated availability"), and click **Commit changes** again.
6. Wait 1–5 minutes and refresh https://venkatasuryam.github.io/ to see the change.

Tip: special characters like `&` must be written as `&amp;` in index.html.

## Common edits — search for these words

| To change | Search index.html for |
| --- | --- |
| Booking hours text | `Monday to Saturday, 10 am` |
| Consultation fee / UPI ID | `₹500` and `9247395624@ibl` (also update the UPI QR: ask a helper, as the QR image is generated) |
| Note under contact details | `To book, follow the three steps` |
| A service | the service title, e.g. `Financial concerns` |
| Phone number | `919515746132` (appears in the WhatsApp and call links — change every place) |
| Email | `venkatasuryam1965@gmail.com` |
| Frequently asked questions | `<details>` |

## Telugu version

The site has a full Telugu copy: `te/index.html` (home) and `te/privacy.html`, at https://venkatasuryam.github.io/te/. The English / తెలుగు buttons at the very top of every page switch between them.

- When you change words on the English page, make the same change in `te/index.html` so both stay the same.
- Prices, UPI ID, phone number and hours appear in both files — change them in both.
- The Google Form and booking calendar are in English; the Telugu page tells visitors they may answer in Telugu.

## Undo a mistake

Open **index.html**, click **History**, open the last good version, and copy its text back in — or ask a helper to revert the commit.

## Keep safe

- This repository is public. Never upload birth details, client notes or other private information.
- Keep two-factor authentication turned on for the GitHub account.
- The brochures' QR codes point to https://venkatasuryam.github.io/ — keep the repository name unchanged so they keep working.

## How bookings work

1. Visitors pay ₹500 by UPI to 9247395624@ibl (button and QR code on the website).
2. They fill the Google Form "Consultation Form (website bookings)" in Google Drive, including the UPI reference (UTR). You get an email for each new form.
3. The form's thank-you message shows the Google Calendar booking page "First consultation – WhatsApp call" (Mon–Sat, 10–12 and 4–6, 30 minutes, max 4 a day, at least 24 hours ahead). Bookings appear in Google Calendar on your phone.
4. Before each call, match the UTR in the form/booking with the payment in your UPI app.

Hours and limits are changed in Google Calendar → Booking pages → First consultation → Edit.
