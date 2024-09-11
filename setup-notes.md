# Setup Notes

### Talos

[ISO Download](https://factory.talos.dev/?arch=amd64&cmdline-set=true&extensions=-&extensions=siderolabs%2Fi915-ucode&extensions=siderolabs%2Fintel-ucode&extensions=siderolabs%2Fiscsi-tools&extensions=siderolabs%2Frealtek-firmware&extensions=siderolabs%2Futil-linux-tools&platform=metal&target=metal&version=1.7.6)

Your image schematic ID is: `e570def3e711fa4d3fec3f1351e814d9d8cbc0a597f3d02f161bb34650ad82f7`

```yaml
customization:
    systemExtensions:
        officialExtensions:
            - siderolabs/i915-ucode
            - siderolabs/intel-ucode
            - siderolabs/iscsi-tools
            - siderolabs/realtek-firmware
            - siderolabs/util-linux-tools
```
