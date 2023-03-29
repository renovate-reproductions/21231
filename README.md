This README file is updated via the Renovate regexManager defined in this
repositories configuration and intents to demonstrates that the
github-release-attachments data source is not functional as of Renovate v35.

---

The following regex is broken on Renovate v35. On Renovate v34,
when setting the datasource to datasource=github-releases, it works.

```
# renovate: datasource=github-release-attachments depName=cilium/hubble digestVersion=v0.11.3
hubble_sha256[amd64]="cf1c699bd604cc5cb72219a36658b75ed6c112725c1a905f23f3b143b3bc4224"
```