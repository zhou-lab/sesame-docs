# sesame documentation

Rendered documentation for [sesame](https://github.com/zhou-lab/sesame) — SEnsible Step-wise Analysis of DNA MEthylation BeadChips.

Published at <https://zhou-lab.github.io/sesame-docs/>.

| Version | Notes |
| --- | --- |
| `dev/` | Development version, tracks the `master` branch of the package |
| `v1.18/` | Release snapshot |
| `v1.16/` | Release snapshot |
| `v1.14/` | Release snapshot |

Each directory holds self-contained HTML rendered from R Markdown via `build.sh`.

## History

These files previously lived in the `sesame/` directory of
[zhou-lab.github.io](https://github.com/zhou-lab/zhou-lab.github.io) and were
extracted to this repository on 2026-07-16. Because the docs are self-contained
HTML (~6 MB per page) that were rewritten in full on every rebuild, they had
grown to ~95% of the lab site repository's git history. They were moved here and
purged from that repository's history.

The pre-split history is not carried over — it was the thing being removed. It is
preserved in the lab site backups made at the time of the split.

**URLs changed in the move.** Pages previously served from
`zhou-lab.github.io/sesame/<version>/` are now at
`zhou-lab.github.io/sesame-docs/<version>/`.
