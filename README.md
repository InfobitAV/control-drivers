# Infobit Control Drivers

Control drivers and plugins that let third-party control platforms operate Infobit AV
products. Currently this repository contains plugins for use with Q-SYS systems, in
[`q-sys/`](q-sys/). Other platforms may be added here in future.

## Status labels

Every driver carries one of these labels. A label describes testing done, not a guarantee.

| Label | Meaning |
|---|---|
| Untested | Built from Infobit's own protocol specification for the device. Not yet run against real hardware. |
| Community tested | An integrator submitted a test report, and Infobit staff reviewed it. A community report never moves a driver past this label — it is not the same as Infobit's own hardware test. |
| Infobit verified | Infobit tested the driver on real hardware itself. |

## Reporting a test

If you have run a driver against real hardware, please open a test report using the
**Test report** issue template:

https://github.com/InfobitAV/control-drivers/issues/new/choose

Bug reports use the separate **Bug report** template on the same page.

## Support and warranty

This software is provided as-is. See [LICENSE](LICENSE) for the full terms, including
section 6 (no warranty) and section 7 (limitation of liability).

## Trademarks

Infobit product and company names are trademarks of Infobit.

Q-SYS is a trademark of QSC, LLC.

This project is not affiliated with, endorsed by, or certified by QSC.
