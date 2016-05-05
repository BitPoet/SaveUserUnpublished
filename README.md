# SaveUserUnpublished
Allow saving users in unpublished state in ProcessWire

### Caveats

Only tested with ProcessWire 3.0.16

### Description

Adds a "Save + Keep Unpublished" button to the edit page for users and a checkbox to unpublish already published users.

### Status

Proof-of-concept

### Internals

Uses a bit of hook trickery to circumvent InputfieldPassword setting itself to "required" if it is invoked for an unpublished page.
