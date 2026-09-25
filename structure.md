SOPPG/
├── DeployedPrompts/       # exact prompts deployed (when separately retained)
├── logs/
│   ├── plog0001/           # process and deployment conversation records/reports
│   └── plog0002/
├── manifests/             # per-run receipts, run index, and template
├── README.md
├── structure.md
└── ...

Each run gets a directory under `logs/` with role-based filenames. Final
deployed prompts remain flat in `DeployedPrompts/`, one file per run. Manifests
link these files by repository-relative path and provenance; they do not replace
or duplicate the source records.

