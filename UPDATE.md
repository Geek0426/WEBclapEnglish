# Updating from 1.0.0 to 1.1.0

## What's new

- The calendar uses bold dates for days with claps, red dots for new messages, and blue dots for days with messages / replies. Existing read status is preserved.
- Select a year and month to jump directly to older records.
- Added Message history, ordered by received time with the newest first. The number of messages per page adapts to message length. Click a received date to open that day's records.
- The design settings now display the public URL for each clap page and replies page.
- Updated the Japanese and English interfaces and guides.

## Update steps

1. **Download and back up the entire installed app folder first.** `Setting` contains the admin password, email settings, thank-you content and images, received messages, replies, and read status. Keep the backup private.
2. Save any work in the admin area and close it. Update during a quiet period if possible.
3. Download and extract `WEBclap-sai-1.1.0-en.zip`.
4. From the extracted `webclap-sai` folder, upload **only `public`, `src`, and `vendor`** to the matching folders in your existing installation, overwriting their files. Include hidden files. Wait for all three folders to finish uploading before using the admin area.
5. **Keep your installed `Setting` folder intact.** Do not upload the empty `Setting` folder from the package. Do not delete, replace, or reset the installed one.
6. Open the same admin URL as before. If the old interface remains, refresh with `Ctrl+F5`.
7. Check that your clap counts, past messages, replies, and thank-you content remain. Check Month to display, Message history, and the public URLs in the design settings.

You do not need to register the admin password again or reconfigure your time zone or email notifications. Existing read status is preserved. Viewing Message history alone does not mark messages as read. Clicking a received date opens that day and marks it as read.

For a new installation, follow the installation section in **Guide.html**. This procedure does not support direct migration from other Web Clap products or overwriting an entire live installation folder with the distribution folder.
