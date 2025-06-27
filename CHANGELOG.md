## v0.2.0 (2025-06-26)

### Feat

- **stage-0**: switch to manually managed debian image
- **task**: push built images to local registry
- **task**: use local container registry (#8)
- **stage-0**: use clang-20 image as base instead of alpine (#6)

### Fix

- **ci**: fix shellcheck invocation
- **task**: fix broken sources field

### Refactor

- **task**: move STAGES to top-level var
- split container builds into stages

## v0.1.0 (2025-06-24)

### Feat

- initial commit with working build system
