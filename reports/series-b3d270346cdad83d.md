# watch-merge-group

[Trusted main](index.md) · [All series](all.md) · [JSON](recent.jsonl) · [CSV](recent.csv)

Policy hosted-ci-cohort-v1; refresh 2026-10-19T23:46:52Z. Cohort fields and missing values:

| Field | Value |
|---|---|
| workflow&#95;path | .github/workflows/ci-merge-group-watch.yml |
| job&#95;key | watch-merge-group |
| matrix&#95;identity | non-matrix |
| invocation&#95;path | direct |
| display&#95;name | watch-merge-group |
| requested&#95;labels | ubuntu-26.04 |
| event | schedule |
| head&#95;branch | main |
| workflow&#95;blob | 079df8228d8ce6d829f095027a3303fb98cfe406 |
| cpu&#95;normalized | AMD EPYC 7763 64-Core Processor |
| os | Ubuntu 26.04.1 LTS |
| os&#95;version | 26.04 |
| kernel | 7.0.0-1017-azure |
| machine&#95;arch | x86&#95;64 |
| process&#95;arch | x86&#95;64 |
| effective&#95;cpu | 4 |
| cpu&#95;quota | unavailable |
| memory&#95;limit | unavailable |
| runner&#95;image | ubuntu26 |
| runner&#95;image&#95;version | 20261012.163.1 |
| execution&#95;context | VM indicated by CPU hypervisor feature; underlying physical host unknown |
| toolchain&#95;identity | unavailable |
| cache&#95;state | unavailable |
| workload&#95;identity | unavailable |
| worker&#95;budget | unavailable |
| execution&#95;kind | executed |

Context qualification: incomplete-producer-context. Unknown critical context prevents change signals; raw points remain selectable. Workflow/blob, CPU/resources, image, cache, toolchain and workload changes create distinct boundaries. The tested SHA labels a point, rather than defining a separate cohort.

### Trailing comparison

**insufficient data**. Baseline: n=0; median/dispersion unavailable; p95 unavailable (requires 20). Candidate: n=4; median 35.5 s; MAD 1.5 s; 2 UTC date buckets; p95 unavailable (requires 20). Change unavailable (percent unavailable below two-second baseline). Observed practical floor 2.0 s; candidate variability allowance 4.5 s.

**Trailing baseline observations:** unavailable.

**Candidate observations:** [job 117741741703](https://github.com/buster14a/buster/actions/runs/39150083701/job/117741741703) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39150083701/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T17:32:49Z; [job 117824965233](https://github.com/buster14a/buster/actions/runs/39178130934/job/117824965233) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39178130934/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T23:49:55Z; [job 117863118816](https://github.com/buster14a/buster/actions/runs/39190859927/job/117863118816) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39190859927/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-19T02:37:43Z; [job 117953645932](https://github.com/buster14a/buster/actions/runs/39220259740/job/117953645932) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39220259740/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-19T08:05:13Z.

### Cumulative change from the fixed initial anchor

**noncomparable/workload-or-environment changed**. Baseline: n=13; median 38.0 s; MAD 4.0 s; 4 UTC date buckets; p95 unavailable (requires 20). Candidate: n=4; median 35.5 s; MAD 1.5 s; 2 UTC date buckets; p95 unavailable (requires 20). Change: -2.5 s (-6.6%). Observed practical floor 12.0 s; candidate variability allowance 4.5 s.

Anchor reason: initial observations of this exact policy/cohort. It fills at most twenty points and never slides. Candidate overlap is excluded. Changing an anchor requires a new explicit report/policy and recorded reason; old rows remain.

**Fixed anchor observations:** [job 116736134597](https://github.com/buster14a/buster/actions/runs/38826832307/job/116736134597) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38826832307/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-15T23:59:22Z; [job 116810782138](https://github.com/buster14a/buster/actions/runs/38850617153/job/116810782138) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38850617153/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T04:26:21Z; [job 116900172787](https://github.com/buster14a/buster/actions/runs/38878783539/job/116900172787) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38878783539/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T09:11:51Z; [job 117009988600](https://github.com/buster14a/buster/actions/runs/38912028437/job/117009988600) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38912028437/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T13:58:33Z; [job 117118483460](https://github.com/buster14a/buster/actions/runs/38944024530/job/117118483460) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38944024530/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T18:00:35Z; [job 117244944229](https://github.com/buster14a/buster/actions/runs/38982059617/job/117244944229) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38982059617/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T23:33:28Z; [job 117274015684](https://github.com/buster14a/buster/actions/runs/38991285593/job/117274015684) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38991285593/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T01:32:15Z; [job 117327163537](https://github.com/buster14a/buster/actions/runs/39008967586/job/117327163537) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39008967586/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T06:11:10Z; [job 117414065290](https://github.com/buster14a/buster/actions/runs/39038852808/job/117414065290) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39038852808/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T13:59:53Z; [job 117453360233](https://github.com/buster14a/buster/actions/runs/39052367540/job/117453360233) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39052367540/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T17:07:27Z; [job 117531651322](https://github.com/buster14a/buster/actions/runs/39078901433/job/117531651322) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39078901433/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T23:24:29Z; [job 117553078367](https://github.com/buster14a/buster/actions/runs/39086165543/job/117553078367) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39086165543/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T01:21:09Z; [job 117659921831](https://github.com/buster14a/buster/actions/runs/39122211333/job/117659921831) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39122211333/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T11:11:09Z.

Existing native phase receipts, where supplied, are retained in the JSON/CSV exports as native_phase_records_json. Their native monotonic clock scope, elapsed_ns and observer overhead remain separate from API job wall time; phases are not summed into CPU time. Toolchain log receipts are reported context rather than complete producer authentication.

These are descriptive CI signals, not independent significance tests or paired experiments. At least eight successful physical executions and three UTC date buckets per side are required. No detectable change does not establish equivalence or causality. Outliers remain in the raw rows.

| Started | Outcome / population | Elapsed s | Source evidence |
|---|---|---:|---|
| 2026-10-18T17:32:49Z | success / executed / physical-execution | 35 | [job 117741741703](https://github.com/buster14a/buster/actions/runs/39150083701/job/117741741703) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39150083701/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-18T23:49:55Z | success / executed / physical-execution | 38 | [job 117824965233](https://github.com/buster14a/buster/actions/runs/39178130934/job/117824965233) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39178130934/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-19T02:37:43Z | success / executed / physical-execution | 31 | [job 117863118816](https://github.com/buster14a/buster/actions/runs/39190859927/job/117863118816) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39190859927/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-19T08:05:13Z | success / executed / physical-execution | 36 | [job 117953645932](https://github.com/buster14a/buster/actions/runs/39220259740/job/117953645932) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39220259740/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
