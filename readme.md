# LightNVM: An open platform for open firmware SSDs

LightNVM implements the internal logic of SSDs within the host system.

This includes logic such as translation tables for logical to physical
address translation, garbage collection and wear-leveling.

It is designed to be used either standalone or with a LightNVM
compatible device and firmware. If used standalone, NVM memory can be simulated
by passing timings to the dm target table. If used with a LightNVM
compatible device, the device will be queried upon initialized for the
relevant values.

Please see [here](https://github.com/MatiasBjorling/lightnvm/wiki/LightNVM-Setup) for 
a guide on how to get started.
