# lodestar-sample-project

A minimal Lodestar project, copied from
[`immediately-run/lodestar`'s `fixtures/sample-project`](https://github.com/immediately-run/lodestar/tree/main/fixtures/sample-project)
so that it sits at a repository **root**.

Its `immediately.run.json` declares `"opensWith": { "task": "open-project" }`. Opening
this repository on immediately.run therefore dispatches through the host's
`task.open-project` binding, which points to Lodestar, instead of running any code
from this repository:

https://immediately.run/present/github/immediately-run/lodestar-sample-project/main

Used as the live check for that binding (roadmap R3-735).
