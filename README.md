# Hi, I'm Jack.

I build reliable systems for data and AI workloads. I am a
[TiDB maintainer](https://github.com/pingcap/community/blob/master/teams/tidb/membership.json)
and reviewer/approver with
[250+ merged pull requests](https://github.com/pingcap/tidb/pulls?q=is%3Apr+author%3Ajackysp+is%3Amerged)
in the TiDB repository.

My distributed-systems work spans transaction correctness, GC safety,
initial data distribution, observability, performance, and compatibility.
I am now applying those engineering principles to AI infrastructure by
building [agentd](https://github.com/minifish-org/agentd), a durable
single-host runtime for personal agents.

## Selected systems work

- **Reliable agent runtimes** — built and released
  [agentd v0.1.0-alpha.1](https://github.com/minifish-org/agentd/releases/tag/v0.1.0-alpha.1)
  with scoped execution, explicit capability boundaries, inspectable traces,
  and transactional delivery. Its independent
  [Telegram adapter](https://github.com/minifish-org/agentd-telegram-adapter)
  keeps transport concerns outside the core runtime.
- **Transaction correctness** — implemented and hardened
  [Read Committed for pessimistic transactions](https://github.com/pingcap/tidb/pull/14087)
  across timestamp ownership, subqueries, executor fast paths, and lock semantics.
- **Distributed GC safety** — published
  [per-server transaction watermarks](https://github.com/pingcap/tidb/pull/12133)
  and incorporated their
  [global minimum into GC safe-point calculation](https://github.com/pingcap/tidb/pull/12223).
- **Scalability and operations** — evolved
  [DDL-time region split/scatter](https://github.com/pingcap/tidb/pull/10980)
  into [configurable v8.4 defaults](https://github.com/pingcap/tidb/pull/55717).

## Current focus

- Reliable agent runtimes and durable execution
- Capability boundaries, state ownership, and observable failures
- Inference serving, scheduling, and resource management

I write about systems and engineering at [blog.minifish.org](https://blog.minifish.org/).
