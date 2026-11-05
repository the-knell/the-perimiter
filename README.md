# The Perimeter

**knell** — Paper II of the Session trilogy. Companion to [One Root](https://archive.org/details/knell-one-root).

Timestamp of record (archive.org): https://archive.org/details/knell-the-perimeter

Paper I was the root. This is everything the root touches. A Session client in ordinary default use also contacts Google's Firebase infrastructure, Signal's content proxy, the foundation's bootstrap seed servers — over plain HTTPS, from your real IP — call relays running one static credential shared by every client since 2021, and legacy storage namespaces that accept unauthenticated reads and writes. Each contact is identified, most are persistent, and one of them joins a user's successive accounts on the same device in the operator's own database, whether the user changed identities or not.

## Verify

```
gpg --import knell-public.asc
gpg --verify whitepaper2-FINAL-2026-11-03.md.asc
```

Expect: `Good signature from "knell"`, key 133883AB9F6EDE5B9BA6B82E27BEDAF0CE152F25
Fingerprint: 1338 83AB 9F6E DE5B 9BA6 B82E 27BE DAF0 CE15 2F25
