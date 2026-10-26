# Send the sponsorship design inside an email

The campaign is sent as an HTML email body, not as a link to the webpage. Use `index-email.html` as the email-safe version of the same design in the root `index.html`. It uses table layout, mobile rules, and public absolute URLs for its images and dossier so they can load in mail apps.

## Recommended test with Thunderbird (embedded images)

The most reliable method is the prepared `TUCN-Australia-test-embedded.eml` file in this folder. It contains the logo and both photos inside the message, so Gmail and phone mail apps do not need to fetch them from the website.

1. Double-click `TUCN-Australia-test-embedded.eml` to open it in Thunderbird.
2. Choose **Message → Edit as New Message** (or **Edit as New**).
3. Replace the **To** address with your own address for the test and keep the subject.
4. Send it. Check the received message in Gmail on desktop and on your phone.

After the test looks correct, use the same file for a sponsor: open it as new, change the recipient and subject, add a personal greeting, and send. The three images are already embedded in the message.

## Alternative: paste the HTML source

1. Open `index-email.html` in a text editor and copy all of its source.
2. In Thunderbird, choose **Write** and address the message to yourself.
3. Add a subject such as `TEST — Australia sponsorship | TUCN Racing Team`.
4. In the message window, choose **Insert → HTML…** (the wording may be **Insert HTML**), paste the source into the dialog, and select **Insert**.
5. Send the test to yourself. This method can be simplified by Thunderbird or Gmail, so use the embedded `.eml` method above when the exact design matters.

The body of the sent message contains the designed campaign. The page link and dossier link remain available inside it as supporting links.

## Before sending to sponsors

- Check the layout and both links in a received test email on desktop and mobile.
- Send one message per sponsor, with a personal greeting and a relevant subject.
- Do not attach the 25.8 MB dossier; the email contains a link to the hosted PDF.

## Public URLs used by the email

- Campaign page: `https://tucnracingteam.github.io/australia-sponsorship-request/`
- Team photo: `https://tucnracingteam.github.io/australia-sponsorship-request/assets/iesc-2026-team.jpg`
- Workshop photo: `https://tucnracingteam.github.io/australia-sponsorship-request/assets/iesc-2026-workshop.jpg`
- Dossier: `https://tucnracingteam.github.io/australia-sponsorship-request/Australia%20Sponsorship%20Request/Mapa%20Sponsorizare.pdf`
- Contact: `utcn.src@gmail.com`
