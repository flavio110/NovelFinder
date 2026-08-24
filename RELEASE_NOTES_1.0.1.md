# NovelFinder 1.0.1 Stable

NovelFinder 1.0.1 is the first frozen Stable public runtime release.

## Release validation

- Stable source integrity: **465/465 PASS**
- Public runtime ZIP integrity: **PASS**
- Internal public manifest: **PASS**
- Python source compilation: **PASS**
- Final secret scan: **0 findings**
- Test fixtures: excluded from public runtime
- Credentials / DPAPI store: not included
- Automatic paid-provider spending: disabled
- Automatic metered fallback: disabled
- Automatic production promotion: disabled

## Package

`NovelFinder_1.0.1_STABLE_PUBLIC_RUNTIME.zip`

SHA-256:

`C7B47DDC3515D63BDC012DFA43FD3C91078623AA139FC62332BEA46498BB4FCC`

## Runtime notes

The public runtime contains the frozen production files needed by the application,
while the development test suite remains outside the distributed runtime.

Optional external providers, Hermes, Ollama models and other accelerators are
configured separately and no developer credential is distributed with the ZIP.

Further development continues on **1.0.2-dev**.
