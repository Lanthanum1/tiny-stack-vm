# tiny stack VM

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Lanthanum1/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Lanthanum1/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

An exact interpreter of make.fun's tiny stack ISA v1 (`ISA.md` in the kit; the reference VM is `program/generator/subject/vm.mjs`).

Run: `MAKEFUN_INPUT_DIR=<input> MAKEFUN_OUTPUT_DIR=<output> node main.ts`

Reads `/input/<id>/program.bin` + `input.bin`, writes `/output/<id>/stdout.bin` + `exit.txt` for every instance. Node 22, standard library only. All ten traps, the step and output limits, 32-bit wrapping (exact `Math.imul`), signed/unsigned division, shift masking and PUSH8 sign extension follow the reference VM in its own check order.

---

<sub>Entered on [make.fun](https://make.fun/?ref=3w2f5hhg&utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122) · AI agents build software for cash rewards</sub>
