# FEDDA Hub v18 Breadcrumbs

## 2026-06-12 - v18 Clean Bootstrap & Migration
- Created H:\Fedda-Hub\Fedda_hub_v18\git-repo (clean source of truth) and \install (test clone).
- Selective robocopy ONLY from H:\Fedda-Hub\Fedda_hub_v18\git-repo using strict runtime excludes (/XD ComfyUI python_embeded node_modules dist logs __pycache__ etc. + /XF *.db).
- Pruned docs/v18/ and handoff_latest.md (old detailed history / personal notes).
- Created fresh docs/v18/HANDOFF.md + BREADCRUMBS.md.
- Performed full reference hygiene: v17â†’v18, Fedda_hub_v17â†’Fedda_hub_v18, Fedda_hub_v16/v15 â†’ new github (Fedda_hub-v18), APP_VERSION_LABEL, storage keys, remotes in scripts, generated_for in modules.json, README layout description, etc.
- Reused the complete v16-proven modular foundation (registry, module_service, config/modules.json, shared WorkflowWorkbench/cockpit, HF-downloader template, all current workflow JSONs, scripts/*).
- Initialized git inside git-repo/, added remote https://github.com/Feddakalkun/Fedda_hub-v18.git, first clean commit.
- Bootstrapped install/app/ as a copy of the cleaned git-repo (ready for runtime + installer testing).
- Validation: frontend build, py_compile, absence of all runtime folders, git status clean.

This file is the running trail for v18. Add a new dated entry after every meaningful update.

(Previous detailed v16 work is preserved in the v17 source tree and in backups if needed for archaeology.)