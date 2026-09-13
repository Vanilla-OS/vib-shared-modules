# Vib Shared Modules

A repository containing user submitted vib modules, intended to be used inside vib recipes

A module may contain extra information on how to use it

# Usage
a module can simply be included like this:
```
modules:
	- gh:Vanilla-OS/vib-shared-modules:main:<module directory>/<filename>.yml
```

# Submitting new modules

Make a pull request adding your module in its own directory, also add your username and the directory to the CODEOWNERS file

View extra information in the wiki page of this repo

## Note on security

All added modules and their plugins are reviewed by @axtloss before being merged or updated, this ONLY includes the module definitions, there are no guarantees that any software plugins fetch or add are safe.

## Use of Generative AI

Maintainers may use generative AI tools as assistants while working on vib-shared-modules. Non-trivial assisted commits disclose the tool, model, and scope of the work.

AI tools may assist with code comments, documentation, repetitive code, and issue triage. Maintainers make project decisions and review every assisted change before it is merged.

Use these trailers for non-trivial assisted commits:

```plain
Assisted-by: <tool>:<model-version>
AI-Scope: <what the tool generated and the prompt or a short prompt summary>
```

Single-line completions, renames, and formatting changes do not need trailers.

Coding agents must also follow [AGENTS.md](AGENTS.md) before changing files,
creating commits, or opening pull requests.
