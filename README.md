# tiny-stack-vm

[![make.fun](https://img.shields.io/badge/make.fun-tiny--stack--vm-blue)](https://make.fun)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A faithful interpreter of make.fun's tiny stack ISA v1: 32-bit wrapping
integers, a 256-value stack, branches, calls, 256 words of memory, input
and output, and all ten traps with their exact exit codes — including the
step and output limits. `node main.ts` answers a whole 40-instance set.
