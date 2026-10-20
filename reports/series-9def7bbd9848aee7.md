# Publish advisory CI history

[Trusted main](index.md) · [All series](all.md) · [JSON](recent.jsonl) · [CSV](recent.csv)

Policy hosted-ci-cohort-v1; refresh 2026-10-20T07:38:07Z. Cohort fields and missing values:

| Field | Value |
|---|---|
| workflow&#95;path | .github/workflows/ci-timing-history.yml |
| job&#95;key | publish |
| matrix&#95;identity | non-matrix |
| invocation&#95;path | direct |
| display&#95;name | Publish advisory CI history |
| requested&#95;labels | ubuntu-26.04 |
| event | schedule |
| head&#95;branch | main |
| workflow&#95;blob | 1d0ef5cdf8654b1275554d8923ea8e213a2c814c |
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

**insufficient data**. Baseline: n=0; median/dispersion unavailable; p95 unavailable (requires 20). Candidate: n=4; median 95.5 s; MAD 4.0 s; 2 UTC date buckets; p95 unavailable (requires 20). Change unavailable (percent unavailable below two-second baseline). Observed practical floor 2.0 s; candidate variability allowance 12.0 s.

**Trailing baseline observations:** unavailable.

**Candidate observations:** [job 117818287729](https://github.com/buster14a/buster/actions/runs/39175792741/job/117818287729) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39175792741/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T23:17:15Z; [job 117846351944](https://github.com/buster14a/buster/actions/runs/39185049648/job/117846351944) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39185049648/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-19T01:25:40Z; [job 117929942999](https://github.com/buster14a/buster/actions/runs/39212616586/job/117929942999) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39212616586/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-19T06:56:43Z; [job 118371697446](https://github.com/buster14a/buster/actions/runs/39343634898/job/118371697446) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39343634898/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-19T23:49:01Z.

### Cumulative change from the fixed initial anchor

**noncomparable/workload-or-environment changed**. Baseline: n=10; median 103.5 s; MAD 9.0 s; 2 UTC date buckets; p95 unavailable (requires 20). Candidate: n=4; median 95.5 s; MAD 4.0 s; 2 UTC date buckets; p95 unavailable (requires 20). Change: -8.0 s (-7.7%). Observed practical floor 27.0 s; candidate variability allowance 12.0 s.

Anchor reason: initial observations of this exact policy/cohort. It fills at most twenty points and never slides. Candidate overlap is excluded. Changing an anchor requires a new explicit report/policy and recorded reason; old rows remain.

**Fixed anchor observations:** [job 117357034607](https://github.com/buster14a/buster/actions/runs/39018863894/job/117357034607) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39018863894/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T08:53:36Z; [job 117402869842](https://github.com/buster14a/buster/actions/runs/39034712675/job/117402869842) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39034712675/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T13:03:19Z; [job 117445314503](https://github.com/buster14a/buster/actions/runs/39049495951/job/117445314503) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39049495951/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T16:29:10Z; [job 117476470601](https://github.com/buster14a/buster/actions/runs/39059978982/job/117476470601) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39059978982/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T18:55:33Z; [job 117509660104](https://github.com/buster14a/buster/actions/runs/39071142746/job/117509660104) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39071142746/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-17T21:33:11Z; [job 117555970771](https://github.com/buster14a/buster/actions/runs/39086941131/job/117555970771) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39086941131/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T01:37:06Z; [job 117608417377](https://github.com/buster14a/buster/actions/runs/39104706280/job/117608417377) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39104706280/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T06:40:20Z; [job 117667022126](https://github.com/buster14a/buster/actions/runs/39124512753/job/117667022126) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39124512753/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T11:46:59Z; [job 117750257312](https://github.com/buster14a/buster/actions/runs/39152783398/job/117750257312) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39152783398/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T18:11:02Z; [job 117786384569](https://github.com/buster14a/buster/actions/runs/39164896602/job/117786384569) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39164896602/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) at 2026-10-18T20:50:27Z.

Existing native phase receipts, where supplied, are retained in the JSON/CSV exports as native_phase_records_json. Their native monotonic clock scope, elapsed_ns and observer overhead remain separate from API job wall time; phases are not summed into CPU time. Toolchain log receipts are reported context rather than complete producer authentication.

These are descriptive CI signals, not independent significance tests or paired experiments. At least eight successful physical executions and three UTC date buckets per side are required. No detectable change does not establish equivalence or causality. Outliers remain in the raw rows.

| Started | Outcome / population | Elapsed s | Source evidence |
|---|---|---:|---|
| 2026-10-18T23:17:15Z | success / executed / physical-execution | 88 | [job 117818287729](https://github.com/buster14a/buster/actions/runs/39175792741/job/117818287729) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39175792741/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-19T01:25:40Z | success / executed / physical-execution | 104 | [job 117846351944](https://github.com/buster14a/buster/actions/runs/39185049648/job/117846351944) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39185049648/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-19T06:56:43Z | success / executed / physical-execution | 95 | [job 117929942999](https://github.com/buster14a/buster/actions/runs/39212616586/job/117929942999) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39212616586/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
| 2026-10-19T23:49:01Z | success / executed / physical-execution | 96 | [job 118371697446](https://github.com/buster14a/buster/actions/runs/39343634898/job/118371697446) / [attempt 1](https://github.com/buster14a/buster/actions/runs/39343634898/attempts/1) / [tested dbc869835b0c](https://github.com/buster14a/buster/commit/dbc869835b0c4d66b591e5b420f7ee4d16cb23ed) |
