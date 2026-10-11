# ai-incident-card-landing

Static landing site for the **[AI Incident Card spec](https://github.com/mizcausevic-dev/ai-incident-card-spec)** — part of the [Kinetic Gain Protocol Suite](https://suite.kineticgain.com).

Live at **[incidents.kineticgain.com](https://incidents.kineticgain.com)**.

Hand-written HTML + CSS, no build step. Merging to `main` does not deploy: the GitHub Actions FTPS upload requires `workflow_dispatch` and is unverified. For a release, use a reviewed local Hostinger SSH/SFTP route with pinned host key, exact backups and hashes, hosted checks, and restore proof.

## License
Apache-2.0. Underlying spec is MIT-licensed.
