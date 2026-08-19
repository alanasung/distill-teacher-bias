<p align="center">
  <h1 align="center">When Distillation Makes Monitors Prefer Their Teacher</h1>
  <p align="center"><strong>Test whether distilled monitors systematically favor their teacher model's attributions under self-monitoring.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **When Distillation Makes Monitors Prefer Their Teacher**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Test whether distilled monitors systematically favor their teacher model's attributions under self-monitoring.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
