# Typeform Listener

Pushes a dataLayer event each time someone submits an embedded Typeform, inline or popup, with the form ID and response ID. Your forms keep working exactly as they do today.

## Setup

Follow the [setup guide](https://converly.io/gtm-templates/typeform).

Fire this tag on All Pages so it is listening wherever a Typeform is embedded. Then trigger your conversion tags on the custom event typeform_form_submitted.

## Event

The listener sends typeform_form_submitted. Use CE - Typeform Submitted as the custom event trigger.

## Script

The template loads https://gtm-templates.converly.io/typeform-listener.js.

## Notes

Sends one typeform_form_submitted event per submitted Typeform response, with the form ID and response ID. It reads no answers or other personal data and doesn't change how your forms work. Full setup guide at https://converly.io/gtm-templates/typeform

## License

Apache License 2.0.
