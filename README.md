This README file is updated via the Renovate regexManager defined in this
repositories configuration and intents to demonstrates that the
github-release-attachments data source is not functional as of Renovate v35.

---

The following regex is broken on Renovate v35. On Renovate v34,
when setting the datasource to datasource=github-releases, it works.

```
# renovate: datasource=github-release-attachments depName=cilium/hubble digestVersion=v0.11.2
hubble_sha256[amd64]="fa2b5a1468f17957899063ad2ff1b51c68aae955a2b5d09390174a7b36a80bdb"
```