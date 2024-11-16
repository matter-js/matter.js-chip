# matter.js-chip container
[matter.js](https://github.com/project-chip/matter.js) uses this Docker image for testing.  It contains chip-tool and tests from [connectedhomeip](https://github.com/project-chip/connectedhomeip).

matter.js tooling pulls automatically as needed.  You can also pull manually:

```sh
docker pull ghcr.io/matter-js/chip:latest
```

The Docker file and related scripts are [here](https://github.com/project-chip/matter.js/tree/main/packages/testing/chip).
