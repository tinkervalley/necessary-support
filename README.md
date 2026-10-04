# Necessary Support

Static GitHub Pages site for Necessary, including the public landing page, support information, and privacy policy.

## Public URLs

- Home: `https://tinkervalley.github.io/necessary-support/`
- Support: `https://tinkervalley.github.io/necessary-support/support/`
- Apple Pay setup: `https://tinkervalley.github.io/necessary-support/apple-pay/`
- Privacy: `https://tinkervalley.github.io/necessary-support/privacy/`

GitHub Pages should deploy from the `main` branch and repository root.

## Keeping the policy current

The public policy should stay aligned with `ios/Necessary/PrivacyPolicyView.swift` in the `tinkervalley/necessary` repository. Review both copies whenever Necessary changes its collected data, household sharing, service providers, notifications, Shortcuts integration, local storage, retention, or account deletion behavior.

Support email: `support@tinkervalley.ca`.

## Updating the Apple Pay shortcut

The signed public download lives at `apple-pay/downloads/Necessary Apple Pay.shortcut`. Remove personal Wallet card identifiers before sharing, sign it for anyone, and keep the setup instructions and update date in sync. Test the download on an iPhone before replacing it. Existing installations do not update automatically.

The setup walkthrough and screenshots in `apple-pay/media/` were captured in the iOS 27 iPhone simulator. The video shows installation and activation, not an actual Apple Pay payment. Keep these assets and their captions current when setup steps change.
