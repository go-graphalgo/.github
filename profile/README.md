<p align="center"><img src="https://raw.githubusercontent.com/go-graphalgo/brand/main/social/go-graphalgo.png" alt="go-graphalgo" width="720"></p>

# go-graphalgo

🌐 **[Website](https://go-graphalgo.github.io)** · 📚 **[Documentation](https://go-graphalgo.github.io/docs/)** · 🗺️ **[Roadmap](https://github.com/go-scikit/roadmap)**

**Graph algorithms in pure Go (CGO=0): matching, isomorphism, cut extraction and the centralities gonum lacks. Planned, wave 3.**

**Status: planned (wave 3).** This organization holds no library yet: only
its landing, its documentation and its brand. Its scope is graph algorithms. The plan is in
[PLAN.md](https://github.com/go-scikit/roadmap/blob/main/PLAN.md), where it is
item 16 of wave 3 (go-graphalgo: matching, isomorphism, communities, the centralities gonum lacks; gonum/graph already has max flow and betweenness, so they are reused and not rewritten); its progress is in
[STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md).

## Planned packages

The names are working names; none exists as a repository yet.

| Package | Status | What it will provide |
|---------|--------|----------------------|
| §graph§ | planned (wave 3), no repository yet | Graph algorithms that gonum/graph lacks, behind a MATLAB-style graph and digraph facade. |

## Repositories

| Repo | What it is |
|------|------------|
| [**docs**](https://github.com/go-graphalgo/docs) | the documentation site (Hugo + Hextra), served at [/docs/](https://go-graphalgo.github.io/docs/) |
| [**go-graphalgo.github.io**](https://github.com/go-graphalgo/go-graphalgo.github.io) | the landing page (Hugo) |
| [**brand**](https://github.com/go-graphalgo/brand) | logo, icons and social images |

Every package will be pure Go (CGO=0), tested on the architectures the fleet's
CI covers, and validated against the reference tool of its domain.
