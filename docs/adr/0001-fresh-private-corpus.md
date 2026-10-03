# Fresh private corpus and public engine

Status: accepted by operator's rebuild instruction.

Begin with fresh authenticated retrieval into an empty private data root. Existing
authentication mechanisms may be used without exposing credential material.
Historical archives, research, dispositions, and wiki pages are not inputs.

The public code repository contains no personal corpus. All examples and tests
are synthetic. Runtime rejects corpus roots inside a Git checkout. Deployments
use separate code and data directories with restrictive data permissions.

Durable SQLite state and content-addressed captures support safe resumption.
Research and review cannot write canonical output. A deterministic publisher
validates proposals, journals publication, reads back targets, and commits receipts.

Tradeoff: fresh collection can only retrieve what X currently makes accessible.
Coverage must report that boundary honestly and never claim recovery of unavailable
historical selections without evidence.
