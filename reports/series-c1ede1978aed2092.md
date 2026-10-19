# Reconcile trusted retirement requests

[Trusted main](index.md) · [All series](all.md) · [JSON](recent.jsonl) · [CSV](recent.csv)

Policy hosted-ci-cohort-v1; refresh 2026-10-19T20:14:46Z. Cohort fields and missing values:

| Field | Value |
|---|---|
| workflow&#95;path | .github/workflows/native-retirement-automation.yml |
| job&#95;key | reconcile |
| matrix&#95;identity | non-matrix |
| invocation&#95;path | direct |
| display&#95;name | Reconcile trusted retirement requests |
| requested&#95;labels | ubuntu-26.04 |
| event | schedule |
| head&#95;branch | main |
| workflow&#95;blob | 35f0397b6fe481faaace4d97599ca48166992e81 |
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

**insufficient data**. Baseline: n=0; median/dispersion unavailable; p95 unavailable (requires 20). Candidate: n=5; median 67.0 s; MAD 2.0 s; 2 UTC date buckets; p95 unavailable (requires 20). Change unavailable (percent unavailable below two-second baseline). Observed practical floor 2.0 s; candidate variability allowance 6.0 s.

**Trailing baseline observations:** unavailable.

**Candidate observations:** [job 117731503175](https://github.com/buster14a/buster/actions/runs/39146570187/job/117731503175) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39146570187/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T16:46:59Z; [job 117761111600](https://github.com/buster14a/buster/actions/runs/39156635239/job/117761111600) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39156635239/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T18:58:57Z; [job 117819570200](https://github.com/buster14a/buster/actions/runs/39176301399/job/117819570200) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39176301399/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T23:23:20Z; [job 117846271717](https://github.com/buster14a/buster/actions/runs/39185273189/job/117846271717) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39185273189/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-19T01:25:20Z; [job 118094664369](https://github.com/buster14a/buster/actions/runs/39262829773/job/118094664369) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39262829773/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-19T13:45:14Z.

### Cumulative change from the fixed initial anchor

**noncomparable/workload-or-environment changed**. Baseline: n=13; median 69.0 s; MAD 3.0 s; 4 UTC date buckets; p95 unavailable (requires 20). Candidate: n=5; median 67.0 s; MAD 2.0 s; 2 UTC date buckets; p95 unavailable (requires 20). Change: -2.0 s (-2.9%). Observed practical floor 9.0 s; candidate variability allowance 6.0 s.

Anchor reason: initial observations of this exact policy/cohort. It fills at most twenty points and never slides. Candidate overlap is excluded. Changing an anchor requires a new explicit report/policy and recorded reason; old rows remain.

**Fixed anchor observations:** [job 116716708533](https://github.com/buster14a/buster/actions/runs/38820821040/job/116716708533) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38820821040/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-15T23:00:09Z; [job 116757644359](https://github.com/buster14a/buster/actions/runs/38833601591/job/116757644359) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38833601591/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T01:09:45Z; [job 116833392646](https://github.com/buster14a/buster/actions/runs/38857902140/job/116833392646) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38857902140/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T05:50:45Z; [job 116921923785](https://github.com/buster14a/buster/actions/runs/38885437181/job/116921923785) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38885437181/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T10:10:20Z; [job 117130286452](https://github.com/buster14a/buster/actions/runs/38947517845/job/117130286452) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38947517845/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-16T18:27:47Z; [job 117275397474](https://github.com/buster14a/buster/actions/runs/38991734466/job/117275397474) / [attempt 1](https://github.com/buster14a/buster/actions/runs/38991734466/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T01:38:43Z; [job 117413434081](https://github.com/buster14a/buster/actions/runs/39038634074/job/117413434081) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39038634074/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T13:56:37Z; [job 117449438199](https://github.com/buster14a/buster/actions/runs/39051018223/job/117449438199) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39051018223/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T16:48:34Z; [job 117476032146](https://github.com/buster14a/buster/actions/runs/39060073449/job/117476032146) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39060073449/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T18:53:26Z; [job 117503648808](https://github.com/buster14a/buster/actions/runs/39069393689/job/117503648808) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39069393689/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T21:04:35Z; [job 117527361739](https://github.com/buster14a/buster/actions/runs/39077421399/job/117527361739) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39077421399/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T23:01:59Z; [job 117641842488](https://github.com/buster14a/buster/actions/runs/39116015876/job/117641842488) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39116015876/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T09:36:49Z; [job 117688691661](https://github.com/buster14a/buster/actions/runs/39131930171/job/117688691661) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39131930171/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T13:31:40Z.

Existing native phase receipts, where supplied, are retained in the JSON/CSV exports as native_phase_records_json. Their native monotonic clock scope, elapsed_ns and observer overhead remain separate from API job wall time; phases are not summed into CPU time. Toolchain log receipts are reported context rather than complete producer authentication.

These are descriptive CI signals, not independent significance tests or paired experiments. At least eight successful physical executions and three UTC date buckets per side are required. No detectable change does not establish equivalence or causality. Outliers remain in the raw rows.

| Started | Outcome / population | Elapsed s | Source evidence |
|---|---|---:|---|
| 2026-10-18T16:46:59Z | success / executed / physical-execution | 67 | [job 117731503175](https://github.com/buster14a/buster/actions/runs/39146570187/job/117731503175) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39146570187/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-18T18:58:57Z | success / executed / physical-execution | 66 | [job 117761111600](https://github.com/buster14a/buster/actions/runs/39156635239/job/117761111600) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39156635239/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-18T23:23:20Z | success / executed / physical-execution | 82 | [job 117819570200](https://github.com/buster14a/buster/actions/runs/39176301399/job/117819570200) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39176301399/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-19T01:25:20Z | success / executed / physical-execution | 65 | [job 117846271717](https://github.com/buster14a/buster/actions/runs/39185273189/job/117846271717) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39185273189/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-19T13:45:14Z | success / executed / physical-execution | 87 | [job 118094664369](https://github.com/buster14a/buster/actions/runs/39262829773/job/118094664369) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39262829773/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
