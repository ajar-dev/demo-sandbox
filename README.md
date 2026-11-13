# demo-autorelease

A minimal demo project: one small Python script (`greet.py`).

Releases are automated: pushing a tag that matches `v*` runs `.github/workflows/release.yml`.

This repository exists only to test a permissions-analysis tool. The workflow publishes nothing, calls no external service, and `DEMO_PUBLISH_TOKEN` holds an obviously fake value.

Run it with `python3 greet.py [name]`.
