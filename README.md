# Tempus — website

The two pages the App Store requires to exist and be reachable: a privacy policy
and a support page. Plain HTML, one stylesheet, no build step.

**These are published from a separate public repository**, because GitHub Pages
on a private repo needs a paid plan and the app's source stays private:

    BentoEno/tempus-site   →   https://bentoeno.github.io/tempus-site/

Copy this folder's contents to the root of that repo and enable Pages (Settings
→ Pages → Deploy from branch → main → / (root)).

The resulting URLs are the ones in `Tempus/Links.swift` and the ones typed into
App Store Connect. **All three must say the same thing** — a privacy policy URL
that 404s is a rejection on its own.

    https://bentoeno.github.io/tempus-site/privacy/
    https://bentoeno.github.io/tempus-site/support/
