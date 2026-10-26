# dinel-shah-reiki
dinel-shah-reiki
# Dinel Shah · Reiki & Holistic Healing

Website for Dinel Shah, certified holistic healer, Reiki practitioner and teacher.
It is a single static page (`index.html`) with no server or database, so it can be
hosted free on GitHub Pages.

Sections: about, what holistic healing is, sessions and classes, events,
testimonials, Calendly booking and a newsletter sign-up.

## Publish it on GitHub Pages

1. In this repo on GitHub, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**,
   choose the **main** branch and the **/ (root)** folder, then click **Save**.
3. After a minute the site is live at `https://dinelshah.github.io/dinel-shah-reiki/`.
   (For a custom domain such as `dinelshah.com`, enter it on the same page.)

Pages on a free account requires a **public** repository.

## Editing the site

Open `index.html` on GitHub, click the pencil icon, make the change and click
**Commit changes**. The live site updates within a minute or two.

- **Calendly link:** near the bottom of the file, set `CALENDLY_URL` to Dinel's link,
  e.g. `"https://calendly.com/dinelshah"`.
- **Newsletter:** create a free account with an email service (Mailchimp, MailerLite
  or Buttondown). Copy the *form action URL* from its embedded sign-up form and paste
  it into `NEWSLETTER_ACTION`. The form sends `EMAIL` and `FNAME`, which Mailchimp
  uses by default. Until this is set, the form tells visitors sign-ups open soon.
- **Events:** each event is an `<article class="event">` block in the
  `Events & workshops` section. Copy one, change the date, title and details, and
  mark it `Past event` once it has happened.
- **Testimonials:** the three quotes in the `Kind words` section are examples.
  Replace them with real client words and remove the `Example` labels.
- **Portrait:** upload a photo (e.g. `dinel.jpg`) to the repo and replace the
  `<div class="portrait">…</div>` placeholder with
  `<img class="portrait" src="dinel.jpg" alt="Dinel Shah" style="object-fit: cover; padding: 0">`.
