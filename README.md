# clean (CDT fixture)

Cross-domain transfer fixture for mdssc-automation (`CDT_CLEAN_BRANCH`). This branch must scan
clean under a Strict blocked-file policy: no malware, no secrets, no vulnerable packages, so a
Low Side scan does not block and the transfer completes end to end. It holds more than one file
so a per-file outcome and a per-scan outcome can be told apart.

Do not add anything that scans dirty here; use `main` or `cdt_blocked` for that.
