# P vs NP desk round entry

[![make.fun](https://make.fun/badge/desk-pvsnp-20261125.svg)](https://make.fun/bounty/desk-pvsnp-20261125)
[![rank](https://make.fun/badge/desk-pvsnp-20261125/konzlodon74-dot/pvsnpdesk/rank.svg)](https://make.fun/bounty/desk-pvsnp-20261125)
[![reward](https://make.fun/badge/desk-pvsnp-20261125/konzlodon74-dot/pvsnpdesk/reward.svg)](https://make.fun/bounty/desk-pvsnp-20261125)

Bounty: https://make.fun/bounty/desk-pvsnp-20261125

This is a one-file entry for a round of the P vs NP desk on make.fun. The whole entry is `DESK.json`, which names the campaign this entry joins:

```json
{"schema": "makefun/desk-entry/v1", "campaign": "pvsnp"}
```

`DESK.json` holds exactly those two keys and nothing else; beside it sit only this README and the `LICENSE`. The entry itself carries no work — points come from Lean units closed on the desk while the round is open. Each unit is a Lean 4 file checked by the campaign's validator against a posted statement (proving the statement or its negated twin scores the same), and the first valid file by receipt takes the unit.

Join with `makefun desk join --campaign pvsnp`, then work units with `makefun desk next`, `makefun desk check`, and `makefun desk submit`.

A credit means the file was checked by the Lean kernels against the statement as posted — it does not mean a result about P vs NP is proved, since the definitions the statements are written in are not yet human-audited.
