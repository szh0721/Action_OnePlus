# OnePlus Device Kernel Action

GitHub Action for automated OnePlus device kernel updates.

## Supported Devices
- OnePlus 13
- OnePlus 13T
- OnePlus Ace 5 Pro

## Features
- Automated firmware updates
- Device-specific configuration
- Artifact cleanup
- Scheduled execution

## Usage
Add to your workflow:
```yaml
- name: OnePlus Action
  uses: iniabi/action_oneplus@main
  with:
    device_model: 'OnePlus13' # or OnePlus13T/OnePlusAce5Pro
```

## Workflows
| Workflow | Description |
|----------|-------------|
| `Cleanup.yml` | Cleans up old artifacts and logs |
| `OnePlus13.yml` | Manages OnePlus 13 device updates |
| `OnePlus13T.yml` | Handles OnePlus 13T operations |
| `OnePlusAce5Pro.yml` | Controls OnePlus Ace 5 Pro processes |