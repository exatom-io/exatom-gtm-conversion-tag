# Exatom Conversion Tag
Our cookieless conversion tag will measure the success of your forms.

In the Exatom administration interface, you can find your **client code** and **conversion code**, which will be required in the GTM interface.

## Where to install
- Install **only** on the **thank you** or **confirmation** page that users see **after** successfully submitting a form.
  - Example pages:
    - `/thank-you`
    - `/confirmation`
    - Order or signup confirmation pages

## Content Security Policy (CSP)
If you use a **Content Security Policy (CSP)**, make sure you allow:
- `*.exatom.io` as an approved source.
- More information about Content Security Policy: https://support.exatom.io/portal/en/kb/articles/installing-exatom-with-a-content-security-policy

## Consent & privacy
Exatom is cookieless and ISO27001 certified.
Learn more on how we handle your data: https://exatom.io/data-journey/

- In the EU and many other jurisdictions:
  - No consent is required for the Event Tag.
- The tag:
  - Is asynchronous, so it does not block page load.
  - Is loaded separately from your website content.
  - Is designed to have minimal performance impact.
