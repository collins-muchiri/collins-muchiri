# Portfolio reproducibility standard

Applies to every repository under this account. A repository that fails any line is labelled
prototype in its README until it passes.

1. No committed binary model artifacts. Models are produced by a pinned, deterministic training
   entry point and are gitignored.
2. A pinned environment file naming the Python or Node version and exact dependency versions.
3. One documented command that takes a clean clone to a running or evaluated state.
4. Every dataset carries source, licence and retrieval date, or is labelled synthetic with its
   generator named.
5. Every model carries a model card stating intended use, out-of-scope use and known failure modes.
6. Every outcome claim carries its measurement method, or the label prototype, unmeasured.
7. Every repository handling personal data carries a DPIA summary and a retention schedule.
8. No em or en dashes in user-facing documentation, matching the account holder's publication style.
