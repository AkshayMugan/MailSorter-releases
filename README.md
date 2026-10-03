# MailSorter downloads

Download the newest `MailSorter-Setup-x.y.z.exe` from **Releases** on the right.

## Getting started with MailSorter

MailSorter runs on your own Windows PC. It sorts your Gmail, lists your bills with amounts and due dates,
files adverts away, gives you a summary every evening, and forwards your proof-of-payment (POP) emails to
whoever you choose. Your mail never leaves your PC except for the forwards you set up.

1. **Install:** download the latest `MailSorter-Setup-x.y.z.exe` from the releases page and run it.
   Windows may warn that the publisher is unknown — click **More info → Run anyway**.
2. **Sign in:** the first time MailSorter opens, the **Welcome** screen has a big **Sign in with Google** button — click it
   and choose your Google account. You can sign in again, switch to another Google account or sign out any time
   in **Settings → Account**. (Switching to a different Gmail address keeps your settings but clears the old
   account's mail history, bills and summaries on this PC, and MailSorter starts the trial (dry-run mode,
   step 5) again for the new account.)
   - Google will say **"Google hasn't verified this app"**. MailSorter is a small private app shared by
     the person who gave it to you, so this is expected: click **Advanced → Go to MailSorter (unsafe) → tick the boxes → Continue**.
     The "unsafe" wording is just Google's standard label for apps it hasn't reviewed; your mail stays on your PC.
   - MailSorter can read your mail, add labels and send the POP forwards you set up. It never deletes mail.
     You can remove its access any time at https://myaccount.google.com/permissions.
3. **Smart features (optional, recommended):** on Setup, install **Ollama** (a free AI helper that runs on your PC) and click **Download model**
   (about 3 GB, once). Without it MailSorter still works, but summaries are just subject lines.
4. **Tell it about your bills:** **Settings → Accounts & POP recipients** — add each account (e.g. your
   municipality), the address its bills come from, its account number, and who should receive your
   POPs. Then **Settings → Approved senders** (so their PDFs may be opened) and
   **Settings → Banks** (where your POP emails come from).
   - POPs are forwarded automatically only for accounts where you tick **Forward proofs of payment
     automatically**. For the others, the dashboard shows the matching POP and you click **Forward**.
   - Your "always copy" list is only added for accounts where you tick **Also copy my always-copy list**.
5. **Try it safely:** MailSorter starts in **dry-run mode** — it shows what it *would* do without moving
   mail or forwarding anything. When you're happy, turn dry-run off in **Settings → General**.
   Proofs of payment that arrived during the trial are not sent automatically afterwards: the dashboard
   lists them with a **Forward now** button.
