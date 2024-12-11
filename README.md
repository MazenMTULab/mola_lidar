[![CI Check clang-format](https://github.com/MOLAorg/mola/actions/workflows/check-clang-format.yml/badge.svg)](https://github.com/MOLAorg/mola/actions/workflows/check-clang-format.yml)
[![CI ROS](https://github.com/MOLAorg/mola/actions/workflows/build-ros.yml/badge.svg)](https://github.com/MOLAorg/mola/actions/workflows/build-ros.yml)
[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](https://docs.mola-slam.org/latest/)

| Distro | Build dev | Release |
| --- | --- | --- |
| ROS 2 Humble (u22.04) | [![Build Status](https://build.ros2.org/job/Hdev__mola__ubuntu_jammy_amd64/badge/icon)](https://build.ros2.org/job/Hdev__mola__ubuntu_jammy_amd64/) | [![Version](https://img.shields.io/ros/v/humble/mola)](https://index.ros.org/search/?term=mola) |
| ROS 2 Jazzy (u24.04) | [![Build Status](https://build.ros2.org/job/Jdev__mola__ubuntu_noble_amd64/badge/icon)](https://build.ros2.org/job/Jdev__mola__ubuntu_noble_amd64/) | [![Version](https://img.shields.io/ros/v/jazzy/mola)](https://index.ros.org/search/?term=mola) |
| ROS 2 Rolling (u24.04) | [![Build Status](https://build.ros2.org/job/Rdev__mola__ubuntu_noble_amd64/badge/icon)](https://build.ros2.org/job/Rdev__mola__ubuntu_noble_amd64/) | [![Version](https://img.shields.io/ros/v/rolling/mola)](https://index.ros.org/search/?term=mola) |

| EOL Distro | Last Release |
| --- | ---
| ROS 2 Iron (u22.04) | [![Version](https://img.shields.io/ros/v/iron/mola)](https://index.ros.org/search/?term=mola) |

# MOLA
A Modular Optimization framework for Localization and mApping (MOLA).
This repository contains the base open-sourced packages for the MOLA project. Other packages exist under the [MOLAorg](https://github.com/MOLAorg/) organization.

Refer to the [official documentation](https://docs.mola-slam.org/latest/) for build instructions, demos, API reference, etc.

![kitti_demo_06](https://github.com/MOLAorg/mola/assets/5497818/76cf07e2-ab20-41a3-abc6-df5c5ba74b97)

## ROSCon Talk introducing MOLA
Video ([Slides](https://docs.google.com/presentation/d/1Zg1saZCxlE49jZ4SxPBLaRh7WUYGmfC0fiKUunJg-dA/edit?usp=drivesdk)):

[![MOLA ROSCon talk](https://img.youtube.com/vi/FkDnbfVyN2M/0.jpg)](https://www.youtube.com/watch?v=FkDnbfVyN2M)


## Individual package build status

Note: Rows within each cell are for ``amd64`` and ``arm64`` architectures.

| Package | ROS 2 Humble <br/> BinBuild |  ROS 2 Jazzy <br/> BinBuild |  ROS 2 Rolling <br/> BinBuild |
| --- | --- | --- | --- |
| kitti_metrics_eval | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__kitti_metrics_eval__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__kitti_metrics_eval__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__kitti_metrics_eval__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__kitti_metrics_eval__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__kitti_metrics_eval__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__kitti_metrics_eval__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__kitti_metrics_eval__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__kitti_metrics_eval__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__kitti_metrics_eval__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__kitti_metrics_eval__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__kitti_metrics_eval__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__kitti_metrics_eval__ubuntu_noble_arm64__binary/) | 
| mola | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola__ubuntu_noble_arm64__binary/) | 
| mola_bridge_ros2 | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_bridge_ros2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_bridge_ros2__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_bridge_ros2__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_bridge_ros2__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_bridge_ros2__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_bridge_ros2__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_bridge_ros2__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_bridge_ros2__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_bridge_ros2__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_bridge_ros2__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_bridge_ros2__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_bridge_ros2__ubuntu_noble_arm64__binary/) | 
| mola_demos | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_demos__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_demos__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_demos__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_demos__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_demos__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_demos__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_demos__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_demos__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_demos__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_demos__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_demos__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_demos__ubuntu_noble_arm64__binary/) | 
| mola_imu_preintegration | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_imu_preintegration__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_imu_preintegration__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_imu_preintegration__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_imu_preintegration__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_imu_preintegration__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_imu_preintegration__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_imu_preintegration__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_imu_preintegration__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_imu_preintegration__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_imu_preintegration__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_imu_preintegration__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_imu_preintegration__ubuntu_noble_arm64__binary/) | 
| mola_input_euroc_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_euroc_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_euroc_dataset__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_euroc_dataset__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_euroc_dataset__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_input_euroc_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_input_euroc_dataset__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_euroc_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_euroc_dataset__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_euroc_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_euroc_dataset__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_euroc_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_euroc_dataset__ubuntu_noble_arm64__binary/) | 
| mola_input_kitti360_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti360_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti360_dataset__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_kitti360_dataset__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_kitti360_dataset__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_input_kitti360_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_input_kitti360_dataset__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_kitti360_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_kitti360_dataset__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti360_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti360_dataset__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_kitti360_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_kitti360_dataset__ubuntu_noble_arm64__binary/) | 
| mola_input_kitti_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_kitti_dataset__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_kitti_dataset__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_kitti_dataset__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_input_kitti_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_input_kitti_dataset__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_kitti_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_kitti_dataset__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_kitti_dataset__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_kitti_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_kitti_dataset__ubuntu_noble_arm64__binary/) | 
| mola_input_mulran_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_mulran_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_mulran_dataset__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_mulran_dataset__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_mulran_dataset__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_input_mulran_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_input_mulran_dataset__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_mulran_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_mulran_dataset__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_mulran_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_mulran_dataset__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_mulran_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_mulran_dataset__ubuntu_noble_arm64__binary/) | 
| mola_input_paris_luco_dataset | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_paris_luco_dataset__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_paris_luco_dataset__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_paris_luco_dataset__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_paris_luco_dataset__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_input_paris_luco_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_input_paris_luco_dataset__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_paris_luco_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_paris_luco_dataset__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_paris_luco_dataset__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_paris_luco_dataset__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_paris_luco_dataset__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_paris_luco_dataset__ubuntu_noble_arm64__binary/) | 
| mola_input_rawlog | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_rawlog__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_rawlog__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_rawlog__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_rawlog__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_input_rawlog__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_input_rawlog__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_rawlog__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_rawlog__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_rawlog__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_rawlog__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_rawlog__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_rawlog__ubuntu_noble_arm64__binary/) | 
| mola_input_rosbag2 | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_input_rosbag2__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_input_rosbag2__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_rosbag2__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_input_rosbag2__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_input_rosbag2__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_input_rosbag2__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_rosbag2__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_input_rosbag2__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_input_rosbag2__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_input_rosbag2__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_rosbag2__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_input_rosbag2__ubuntu_noble_arm64__binary/) | 
| mola_kernel | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_kernel__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_kernel__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_kernel__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_kernel__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_kernel__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_kernel__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_kernel__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_kernel__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_kernel__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_kernel__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_kernel__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_kernel__ubuntu_noble_arm64__binary/) | 
| mola_launcher | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_launcher__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_launcher__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_launcher__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_launcher__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_launcher__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_launcher__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_launcher__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_launcher__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_launcher__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_launcher__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_launcher__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_launcher__ubuntu_noble_arm64__binary/) | 
| mola_metric_maps | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_metric_maps__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_metric_maps__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_metric_maps__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_metric_maps__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_metric_maps__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_metric_maps__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_metric_maps__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_metric_maps__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_metric_maps__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_metric_maps__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_metric_maps__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_metric_maps__ubuntu_noble_arm64__binary/) | 
| mola_msgs | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_msgs__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_msgs__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_msgs__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_msgs__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_msgs__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_msgs__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_msgs__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_msgs__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_msgs__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_msgs__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_msgs__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_msgs__ubuntu_noble_arm64__binary/) | 
| mola_navstate_fg | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_navstate_fg__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_navstate_fg__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_navstate_fg__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_navstate_fg__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_navstate_fg__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_navstate_fg__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_navstate_fg__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_navstate_fg__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_navstate_fg__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_navstate_fg__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_navstate_fg__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_navstate_fg__ubuntu_noble_arm64__binary/) | 
| mola_navstate_fuse | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_navstate_fuse__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_navstate_fuse__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_navstate_fuse__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_navstate_fuse__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_navstate_fuse__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_navstate_fuse__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_navstate_fuse__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_navstate_fuse__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_navstate_fuse__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_navstate_fuse__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_navstate_fuse__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_navstate_fuse__ubuntu_noble_arm64__binary/) | 
| mola_pose_list | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_pose_list__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_pose_list__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_pose_list__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_pose_list__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_pose_list__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_pose_list__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_pose_list__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_pose_list__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_pose_list__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_pose_list__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_pose_list__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_pose_list__ubuntu_noble_arm64__binary/) | 
| mola_relocalization | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_relocalization__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_relocalization__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_relocalization__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_relocalization__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_relocalization__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_relocalization__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_relocalization__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_relocalization__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_relocalization__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_relocalization__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_relocalization__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_relocalization__ubuntu_noble_arm64__binary/) | 
| mola_traj_tools | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_traj_tools__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_traj_tools__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_traj_tools__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_traj_tools__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_traj_tools__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_traj_tools__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_traj_tools__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_traj_tools__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_traj_tools__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_traj_tools__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_traj_tools__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_traj_tools__ubuntu_noble_arm64__binary/) | 
| mola_viz | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_viz__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_viz__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_viz__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_viz__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_viz__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_viz__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_viz__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_viz__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_viz__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_viz__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_viz__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_viz__ubuntu_noble_arm64__binary/) | 
| mola_yaml | [![Build Status](https://build.ros2.org/job/Hbin_uJ64__mola_yaml__ubuntu_jammy_amd64__binary/badge/icon)](https://build.ros2.org/job/Hbin_uJ64__mola_yaml__ubuntu_jammy_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_yaml__ubuntu_jammy_arm64__binary/badge/icon)](https://build.ros2.org/job/Hbin_ujv8_uJv8__mola_yaml__ubuntu_jammy_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Jbin_uN64__mola_yaml__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Jbin_uN64__mola_yaml__ubuntu_noble_amd64__binary/) <br> [![Build Status](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_yaml__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Jbin_unv8_uNv8__mola_yaml__ubuntu_noble_arm64__binary/)  | [![Build Status](https://build.ros2.org/job/Rbin_uN64__mola_yaml__ubuntu_noble_amd64__binary/badge/icon)](https://build.ros2.org/job/Rbin_uN64__mola_yaml__ubuntu_noble_amd64__binary/)<br> [![Build Status](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_yaml__ubuntu_noble_arm64__binary/badge/icon)](https://build.ros2.org/job/Rbin_unv8_uNv8__mola_yaml__ubuntu_noble_arm64__binary/) | 


## Citations

The latest publications on MOLA are ([PDF](https://arxiv.org/abs/2407.20465)).

```bibtex
@misc{blanco2024mola,
      title={A flexible framework for accurate LiDAR odometry, map manipulation, and localization},
      author={José Luis Blanco-Claraco},
      year={2024},
      eprint={2407.20465},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2407.20465},
}
```

MOLA was initially presented in 2019 in ([PDF](http://www.roboticsproceedings.org/rss15/p43.pdf)):

```bibtex
@INPROCEEDINGS{Blanco-Claraco-RSS-19, 
    AUTHOR    = {Jose Luis Blanco-Claraco}, 
    TITLE     = {A Modular Optimization Framework for Localization and Mapping}, 
    BOOKTITLE = {Proceedings of Robotics: Science and Systems}, 
    YEAR      = {2019}, 
    ADDRESS   = {FreiburgimBreisgau, Germany}, 
    MONTH     = {June}, 
    DOI       = {10.15607/RSS.2019.XV.043} 
} 
```

## License
MOLA is released under the GNU GPL v3 license, except noted otherwise in each individual module. Other options available upon request.
Some modules are released under BSD-3. See the [official documentation](https://docs.mola-slam.org/latest/).


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=MOLAorg/mola&type=Date)](https://star-history.com/#MOLAorg/mola&Date)
