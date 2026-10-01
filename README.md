# DatasetDoctor Releases

Public release and update-feed repository for DatasetDoctor.

- Website: https://kostas-kmp.github.io/datasetdoctor-releases/
- Current release: https://github.com/kostas-kmp/datasetdoctor-releases/releases/tag/v1.8.7
- Update feed: https://kostas-kmp.github.io/datasetdoctor-releases/latest.json

DatasetDoctor is a local-first forensic auditing and repair system for supervised tabular machine-learning datasets and experimental design.

The application source code is not published in this repository. This repository contains only public release metadata, documentation, and downloadable release artifacts.

## Updating the feed

For a new release, upload and verify the installer first. Then generate a new `latest.json` with the exact installer URL and SHA-256. Replace the public `latest.json` only after the installer is confirmed accessible. Publishing `latest.json` is the final step that makes the update visible to installed DatasetDoctor clients.
