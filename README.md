# learning

A personal study collection — textbooks, reference material, and course repositories
across systems, compilers, machine learning, and software design.

## Layout

| Directory | Contents |
| --- | --- |
| `Artificial Intelligence/` | AI/ML reading (e.g. *Little Book of Deep Learning*) |
| `Compilers/` | Compiler theory & implementation texts (Cooper & Torczon, Appel, dependence-based optimization) |
| `Computer_Arch_and_Org/` | *Computer Architecture: A Quantitative Approach* |
| `cxx/` | C++ language & standard library references (Stroustrup, C++ Primer, templates, C++17) |
| `Design Patterns/` | GoF *Design Patterns* and Pikus's *Hands-On Design Patterns with C++* |
| `LLVM/` | LLVM tooling guides and IR tutorials |
| `mlc/` | Compiler construction with LLVM |
| `Operating Systems/` | OS concepts, the Linux kernel, parallel programming |
| `Python/` | Fluent Python, Architecture Patterns with Python |
| `CSAPP_2016.pdf` | *Computer Systems: A Programmer's Perspective* |

## Course repositories

These subdirectories are course materials with their own setup and READMEs:

- **`cs336-spring2025-lectures/`** & **`spring2024-lectures/`** — Stanford CS336
  "Language Modeling from Scratch" executable lectures. Lectures are Python
  programs (`lecture_*.py`) run via `python execute.py -m lecture_01`. See each
  folder's `README.md` for setup.
- **`cs6120/bril/`** — Bril, the intermediate language used in Cornell CS6120
  "Advanced Compilers." A multi-language toolchain (TypeScript, Rust, Python)
  for an educational compiler IR.

## Notes

- The bulk of this repo is reference PDFs (not version-controlled source); the
  course directories carry the actual code.
- `git-push.sh` force-pushes the whole tree (`git add -A && commit && push --force`).
  It rewrites remote history — use with care.
