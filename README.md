# ramp-chestnut1-workspace

Proof of concept for RAMP workspace storage (Chestnut Ramp 1, customer key `chestnut-ramp1`).

**This repository is public and holds synthetic data only.** Every record, id, name and price in it
was generated for the POC. No real customer data, Salesforce credentials, org identifiers or
proprietary code may ever be added.

- `main`: this README.
- `ramp-project-main`: the checked-in RAMP workspace. `ramp-manifest.json` lists every file with its
  SHA-256; `workspace/` holds the files. Each commit is one approved RAMP check-in.

Check-ins are made by RAMP after a named approval of the exact manifest; they are never force-pushed.
