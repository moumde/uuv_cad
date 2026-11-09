# UUV CAD Models

This repository contains the CAD design files for the UCR-v1 underwater robot prototype. It covers the robot structure, electronics enclosures, thruster and suction assemblies, wheels, buoyancy blocks, tether reel, and demonstration components.

## Files

- `机器人/UCR-v1.SLDASM` — main robot assembly.
- `机器人/` — robot parts and subassemblies, organized by module.
- `缆盘/` — tether reel assembly and parts.
- `工作展示模型.SLDASM` and `岸上组件.SLDASM` — demonstration and onshore assemblies.
- `.STEP` and `.DWG` files — auxiliary exchange and drawing files.

The original filenames and folder structure are preserved. When opening an assembly in SOLIDWORKS, keep its referenced parts in the same relative locations.

## Related software

- [UUV ROS control](https://github.com/moumde/uuv_ros)
- [STM32 driver](https://github.com/moumde/uuv_driver)

The mechanical design files are stored with Git LFS.
