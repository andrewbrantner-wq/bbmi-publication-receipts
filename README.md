# bbmi-publication-receipts

Public BBMI publication verification metadata.

This repository holds verification metadata only: hashes, timestamps, verification status and publication identifiers. It contains no model inputs, projections, private paths, credentials or executable workflows.

## Current contents

`tests/retrieval-test.json` is a **retrieval test only**. It checks that the metadata can be read publicly without credentials. It is marked `test_only` and `not_certified`, certifies no production data, and authorizes no exhibit or social post. Its ID uses the `retrieval-test-ncaaf-` namespace, which the production receipt reader rejects.

No production receipt (`current.json`, `latest.json`) has been published yet.
