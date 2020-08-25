# shyL

- [x] Paradigm
  - [x] OOP?
  - [x] Functional?
  - [x] What about both?
  - [x] This could be acheived by using OOP and FP versions of the
      language on the same underlying VM.

- Syntax
  - [x] Lisp-like syntax.
  - [x] Ruby-like syntax.
  - [x] Switchable?
  - [x] Pipeline operator.
  - [ ] Header files.
  - [x] Preprocessor for macros? (soon)
  - [x] Guards.
  - [x] Pattern matching.
  - [x] Functions, different arities. Matching.

- Concurrency
  - [x] Concurrency primitives.
  - [ ] What about support for building things like Erlang's `gen_server`?
  - [ ] Optional actor model.

- VM
  - [ ] Register-based (maybe stack-based) virtual machine.
  - [ ] Written in Rust.
  - [ ] The VM can be statically linked to run in a container.
  - [ ] Hot code reloads/upgrades.
  - [x] REPL.
  - [ ] Embed documentation in the REPL.
  - [x] Full Unicode support (UTF-8).
  - [ ] Lint checker.
  - [x] AST easy to utilise.
  - [x] Language Server Protocol. (via Perl 5 module)
  - [x] Documentation should be especially important.

- Performance
  - [x] Garbage collection system.
  - [ ] Fast startup.
  - [x] Good for general tasks, heavy computing, and distributed
    computing.

- Language
  - [x] Language should have a fairly extensive standard library, to cover
    most use-cases.
  - [ ] Do NOT encourage practices a la Node.JS + NPM (example: `is-odd`),
    etc.
  - [x] Distributed with build tooling.
