# PunchList — legal

Hosts the privacy policy, terms of use and support page for the **PunchList**
iOS app, at <https://williamscott701.github.io/punchlist-legal/>.

- [Privacy Policy](https://williamscott701.github.io/punchlist-legal/privacy.html)
- [Terms of Use](https://williamscott701.github.io/punchlist-legal/terms.html)
- [Support](https://williamscott701.github.io/punchlist-legal/support.html)

## Do not edit these pages by hand

The HTML here is generated. The source of truth is the Markdown bundled inside
the app, so the wording a user reads offline and the wording published here
cannot drift apart:

    PunchList/Resources/PrivacyPolicy.md
    PunchList/Resources/TermsOfUse.md

To publish a change, edit the Markdown in the app repository and run:

    ./scripts/publish-legal.sh

from there. It regenerates this site and pushes it.
