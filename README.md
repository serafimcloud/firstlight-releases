# Firstlight releases

The update feed the macOS application polls, and the builds it downloads.

The app asks `https://firstlight.sh/appcast.xml`, which the site rewrites to
`firstlight.xml` here, served by GitHub Pages. Each entry's build hangs off a
release in this repository. Public on purpose: Sparkle downloads without
credentials, so nothing here may be private.
