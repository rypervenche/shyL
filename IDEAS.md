- Paradigm
  - OOP?
  - Functional?
  - What about both?
  - This could be acheived by using OOP and FP versions of the
      language on the same underlying VM.

- Syntax
  - Lisp-like syntax.
  - Ruby-like syntax.
  - Switchable?
  - Pipeline operator.
  - Header files.
  - Preprocessor for macros?
  - Guards.
  - Pattern matching.
  - Functions, different arities. Matching.

- Concurrency
  - Concurrency primitives.
  - What about support for building things like Erlang's `gen_server`?
  - Optional actor model.

- VM
  - Register-based (maybe stack-based, but I like the register-based
      approach better) virtual machine.
  - Written in Rust.
  - The VM can be statically linked to run in a container.
  - Hot code reloads/upgrades.
  - REPL.
  - Embed documentation in the REPL.
  - Full Unicode support (UTF-8).
  - Lint checker.
  - AST easy to utilise.
  - Language Server Protocol.
  - Documentation should be especially important.

- Performance
  - Garbage collection system.
  - Fast startup.
  - Good for general tasks, heavy computing, and distributed
    computing.

- Language
  - Language should have a fairly extensive standard library, to cover
    most use-cases.
  - Do NOT encourage practices a la Node.JS + NPM (example: `is-odd`),
    etc.
  - Distributed with build tooling.
