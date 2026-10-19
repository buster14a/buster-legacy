# Hosted CI timing history

Operational Actions observations; advisory. Compiler performance acceptance and the qualified 9700X dashboard are separate.

Collected at 2026-10-19T20:14:46Z. Policy hosted-ci-cohort-v1. 146 active observations, 4787 unknown hardware, 0 API/ingestion gaps, 0 incomplete runs, 116 aliases, 3184 unresolved cost intervals.

Observed hosted runner-seconds: 765476; observed unsuccessful-job runner-seconds: 98393 (262 jobs). These exclude unknown-hosting and missing intervals; they are neither billed minutes nor process CPU time. Dependency/deployment waits and required-CI critical-path attribution remain unavailable.

Reporting bounds: 30 observation-date shards / 32768 rows / 96 rendered series; 6946 rows outside the rendered series bound remain in exports. Raw history is retained separately from these bounded derived reports.

Bounded view omitted 0 older shards and 8016 older loaded rows; their raw records remain on the data branch.

[JSON export](recent.jsonl) · [CSV export](recent.csv) · [Collector policy](https://github.com/buster14a/buster/blob/main/docs/ci-timing-history.md)

Default view: trusted main push observations only. [All events, PRs and queues](all.md). The coverage totals and exports above include all selected events; the selector below filters main. Native report filters select job, OS, CPU, branch, revision and UTC date range.

| Job / matrix | OS / actual CPU | Event / branch | Successful samples | Missing context | History |
|---|---|---|---:|---:|---|
| Reconcile trusted retirement requests /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-0901cea64b4b1428.md) |
| Rebind unit &#40;macos-26&#41; /  | unknown OS / unknown CPU | push / main | 0 | 9 | [series](series-2739fd069892a158.md) |
| Rebind unit &#40;ubuntu-26.04&#41; /  | unknown OS / unknown CPU | push / main | 0 | 9 | [series](series-51c0dbb885831a80.md) |
| Reconstruct candidate closure ephemerally /  | unknown OS / unknown CPU | push / main | 0 | 9 | [series](series-b887354780260cb7.md) |
| GPU Linux consumers /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-4da7be43363bb291.md) |
| GPU Metal consumer /  | unknown OS / unknown CPU | push / main | 0 | 25 | [series](series-5055dc4fc114973a.md) |
| Native retirement merge admission /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-df5872d2617cf392.md) |
| Workflow lint /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-9b14cdb0ee39831d.md) |
| Main CI reuse decision /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-e6c46684015a34aa.md) |
| github.event&#95;name == 'merge&#95;group' &#38;&#38; 'Workflow lint' &#124;&#124; 'Queue lint preflight &#40;inactive&#41;' /  | unknown OS / unknown CPU | push / main | 0 | 22 | [series](series-a9b57d195a9e6398.md) |
| Clang analyzer shards /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-c7538b8ceded1339.md) |
| Linux AArch64 portability /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-28158a1153aa0110.md) |
| macOS AArch64 release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-82f414a369b4e994.md) |
| Linux AArch64 release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-976b578905c3fa3a.md) |
| Windows AArch64 release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-1f532a321e856b6d.md) |
| macOS AArch64 sanitized-release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-68b6e3e7c53d5340.md) |
| macOS AArch64 portability /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-1085ea746f43e17a.md) |
| Windows x86-64 release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-041d2eabafe8417b.md) |
| Linux AArch64 sanitized-release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-ac8a4f9c958ae4ba.md) |
| Windows AArch64 checks /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-5359c7916d60ebb1.md) |
| Linux x86-64 portability /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-35fac8646b51558d.md) |
| Windows x86-64 sanitized-release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-1545e2eef5ff832f.md) |
| Linux x86-64 sanitized-release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-3c7844aa31983dab.md) |
| Windows x86-64 portability /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-4562382efb503e41.md) |
| Linux x86-64 release /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-07310f68e4feb15f.md) |
| ${{ matrix.name }}${{ &#40;&#40;&#40;github.event&#95;name == 'pull&#95;request'&#41; &#38;&#38; github.event.pull&#95;request.draft &#38;&#38; &#40;github.run&#95;attempt == '1'&#41; &#38;&#38; startsWith&#40;matrix.runner, 'macos-'&#41; &#38;&#38; ' &#40;deferred for draft PR&#41;'&#41; &#124;&#124; ''&#41; }} /  | unknown OS / unknown CPU | push / main | 0 | 41 | [series](series-a2e01e6c19ba3f4d.md) |
| UEFI firmware boot /  | unknown OS / unknown CPU | push / main | 0 | 22 | [series](series-869cab7418f8fa44.md) |
| CI complete /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-d13355b70de081b2.md) |
| foundation /  | unknown OS / unknown CPU | push / main | 0 | 8 | [series](series-334e24637d69c450.md) |
| Exact merge-tree preflight /  | unknown OS / unknown CPU | push / main | 0 | 10 | [series](series-4a0cb53cd5e4105c.md) |

## Largest observed main time changes

Ordered by absolute median seconds per physical execution; candidate frequency is shown separately. These descriptive differences include improvements and slowdowns. Missing context is not a qualified signal, and no required-CI critical-path impact is inferred.

| Series | Median change s | Change % | Candidate executions | State |
|---|---:|---:|---:|---|

Last selected execution completed: 2026-10-19T19:47:44Z; collection lag 1622 s. Pending runs: 1; reverse-sweep cursor 2026-10-08T11:00:03Z. The cursor measures discovery progress, not evidence of complete historical coverage.
