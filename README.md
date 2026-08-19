# ChoCo Atlas

The built site behind **[choco-atlas.eu](https://choco-atlas.eu)** — an atlas of
computational social choice results and their continuous mirrors, generated
end-to-end by an automated pipeline from machine-readable run artifacts.

This repository contains **built site releases only**. Each commit is one build,
stamped in its commit message (and in the site footer) with the exact commit of
the pipeline repository that produced it. The pipeline itself — code, prompts,
harness — is still changing quickly and will be released in full once it
stabilizes; because the build stamps are published first, that release can be
checked retroactively against every build that ever appeared here.

No paper full texts are distributed. Provenance pages quote only the specific
named statements under discussion, and every machine-proved result links its
full provenance: the task as posed, the proof as returned, the adversarial
review as it happened.
