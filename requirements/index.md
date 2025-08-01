# MESSAi Requirements Documentation

This directory contains requirements documentation for the MESSAi project, gathered using the Claude Requirements Gathering System.

## =� Requirements List

*No requirements documented yet. Use `/requirements-start [description]` to begin.*

## =� Quick Start

1. **Start a new requirement**: `/requirements-start [feature description]`
2. **Check progress**: `/requirements-status`
3. **View current**: `/requirements-current`
4. **List all**: `/requirements-list`
5. **End gathering**: `/requirements-end`

## =� Structure

Each requirement is stored in its own timestamped folder:
```
requirements/
   index.md                     # This file
   .current-requirement         # Tracks active requirement
   YYYY-MM-DD-HHMM-name/       # Individual requirements
       metadata.json           # Status tracking
       00-initial-request.md   # Original request
       01-discovery-questions.md
       02-discovery-answers.md
       03-context-findings.md
       04-detail-questions.md
       05-detail-answers.md
       06-requirements-spec.md # Final specification
```

## <� Recent Requirements

*None yet*

---

Last updated: ${new Date().toISOString()}