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

Linux device is classifiable as:

- Character devices
    A character device is one that can be accessed as a stream of bytes. Character device can be accessed by means of filesystem nodes, such as /dev/tty1 and /dev/lp0.
- Block devices
    A block device is a device that can host a filesystem
- Network devices
    Any network transaction is mode through an interface, that is , a device that is able to exchange data with other hosts. The Unix wat to provide access to interfaces is still by assigning a unique name such eth0