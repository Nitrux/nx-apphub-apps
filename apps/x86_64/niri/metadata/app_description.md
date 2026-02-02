# quickshell

## Summary

A scrollable-tiling Wayland compositor.

## Description

Windows are arranged in columns on an infinite strip going to the right. Opening a new window never causes existing windows to resize.

Every monitor has its own separate window strip. Windows can never "overflow" onto an adjacent monitor.

Workspaces are dynamic and arranged vertically. Every monitor has an independent set of workspaces, and there's always one empty workspace present all the way down.

The workspace arrangement is preserved across disconnecting and connecting monitors where it makes sense. When a monitor disconnects, its workspaces will move to another monitor, but upon reconnection they will move back to the original monitor.

## Category

AppHub.System

## Homepage

[https://github.com/YaLTeR/niri](https://github.com/YaLTeR/niri)

## License

Not specified in metadata
