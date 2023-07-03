# superdup

`superdup` ("**super**vised de**dup**lication") is a package built around the [dedupe](https://github.com/dedupeio/dedupe) record linkage library. The goal of this package is to leverage the speed and ease of using `dedupe`, while improving linkage quality in scenarios where the user has:
* Ground truth person identifiers for a subset of records, and/or
* Hard constraints to enforce about what types of links are permitted

