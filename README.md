# OSS Link Auditor consumer demo

This tiny repository proves that
[`Aryalmilan-max/oss-link-auditor`](https://github.com/Aryalmilan-max/oss-link-auditor)
can be consumed as a GitHub Action without installing a package or maintaining
a custom script.

The workflow audits this README and `docs/`, then publishes a source-aware trust
report in the GitHub Actions job summary. It runs manually and on pull requests.

## Try it

1. Open the **Actions** tab.
2. Select **Audit Markdown links**.
3. Choose **Run workflow**.
4. Open the completed run and read the job summary.

The workflow is intentionally minimal. Production repositories should review
the Action source and pin it to a full commit SHA.

