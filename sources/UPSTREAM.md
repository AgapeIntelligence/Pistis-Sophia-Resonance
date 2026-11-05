# Upstream Coptic source

Source repository: https://github.com/CopticScriptorium/corpora
Corpus directory: https://github.com/CopticScriptorium/corpora/tree/master/pistis-sophia

The source currently exposes ANNIS, CONLLU, PAULA, TEI and TT subdirectories. This is a **source pointer**, not a completed clone.

## Import gate
Before vendoring the corpus, verify the upstream revision, license and attribution requirements. Preserve the source commit SHA and unchanged files under `upstream/`. Do not imply that an English translation or reconstructed phonetics is part of the upstream material unless confirmed.

## Proposed local import command

```bash
git clone https://github.com/CopticScriptorium/corpora.git
cd corpora
git rev-parse HEAD
```

Research project: AgapeIntelligence/Pistis-Sophia-Resonance.
