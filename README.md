# retirementready-website

Public website for RetirementReady.me.

## Kit early-access confirmation

The public waitlist uses Kit form UID `6d9b7eb27b`.

In Kit, configure the form's post-confirmation redirect / "After confirming redirect to" value as:

`https://retirementready.me/?early_access=confirmed`

The website consumes that parameter to show the one-time "You're on the list!" confirmation
overlay, removes the parameter from the browser URL, and remembers the visitor as already joined
so the waitlist prompt does not continue to appear on that browser.
