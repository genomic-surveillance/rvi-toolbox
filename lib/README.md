# Lib

Currently, only `lib` added is the `NextflowTool`. This is a library developed by PAM which provide some handy methods to log info.

---
## NextflowTool

A Groovy library of helper functions such as printing path-info logo or printing help messages from JSON schemas

Originally available [here](https://gitlab.internal.sanger.ac.uk/sanger-pathogens/pipelines/nextflowtool/-/tree/main?ref_type=heads)

### Using in your project

The library is currently just some Groovy source files. Therefore the easiest way to manage them is via [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules). To use them with nextflow, make a submodule directory inside your `lib` directory. Groovy classes placed in this directory are automatically imported into your test files' scope, so you can simply reference them as e.g. `NextflowTool`, with no need for an `import` line.

---
