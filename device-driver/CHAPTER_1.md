# An Introduction to Device Device
## The Role of the Device Device
> The role of a device driver is providing *mechanism*, not **policy**

- Mechanism: what capabilities are to be provided
- Policy: how thos capabilities can be used

## Splitting the Kernel
- Process management
- Memory management
- Filesystems
- Device control
- Networking

## Loadable Module
> Each piece of code that can be added to the kernel at runtime is called a **module**
![A split view of the kernel](http://www.makelinux.net/ldd3/images/0596005903/figs/ldr3_0101.gif "A split view of the kernel")