# percio-version

Percio's forced-update manifest. The iOS app reads `version.json` on launch; builds older than `min_version` show an update screen.

Release order: ship the new build to the App Store first, then raise `min_version` here.
