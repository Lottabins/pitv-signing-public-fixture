# Harmless PiTV signing boundary fixture

This public repository contains only a synthetic, non-release signing fixture.
It contains no PiTV application source, package, credentials or release tuple.

The manual workflow signs a small JSON document containing its public repository,
source commit and run identity. Its purpose is to verify a genuine public Sigstore
tuple positively, then confirm that adding the private-policy `--no-public-good`
flag rejects that same tuple. It does not publish or qualify a PiTV release.

Execution requires separate exact-source approval and a protected, secret-free
environment. Publication of these files alone does not authorize a dispatch.
After the single approved run, qualification and repository Actions are disabled.
