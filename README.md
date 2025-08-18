# Awesome Autoware [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Autoware resources and libraries.

Autoware is the world's leading open-source project for autonomous driving. Autoware is built on Robot Operating System (ROS) and enables commercial deployment.

## Table of Content

- [Awesome Autoware ](#awesome-autoware-)
  - [Table of Content](#table-of-content)
  - [Official Resources](#official-resources)
  - [Media](#media)
  - [Working Groups](#working-groups)
  - [Projects](#projects)
  - [Tools](#tools)
  - [Simulator](#simulator)
  - [Zenoh](#zenoh)
  - [Vehicles](#vehicles)
  - [Videos](#videos)
  - [Datasets](#datasets)
  - [Papers](#papers)
  - [Obsolete](#obsolete)
  - [Contributing](#contributing)

## Official Resources

- [Autoware Website](https://autoware.org/)
- [Autoware GitHub Organization](https://github.com/autowarefoundation)
- [Autoware Documentation](https://autowarefoundation.github.io/autoware-documentation/main/): The documentation for the installation, tutorial, etc.
- [Autoware Universe Documentation](https://autowarefoundation.github.io/autoware_universe/main/index.html): The documentation for different components, like sensing, perception, etc.
- [Autoware Discussion](https://github.com/orgs/autowarefoundation/discussions)
- [Discord](https://discord.gg/Q94UsPvReQ)

## Media

- [Autoware Blog](https://autoware.org/awf-blog/)
- [Autoware Foundation LinkedIn](https://www.linkedin.com/company/the-autoware-foundation)
- [Autoware Foundation YouTube](https://www.youtube.com/@autowarefoundation)

## Working Groups

- [Autoware Working Group](https://autoware.org/join-a-work-group/)
- [Meeting Minutes](https://github.com/orgs/autowarefoundation/discussions/categories/working-group-meetings)
- [Working Group Wiki](https://github.com/autowarefoundation/autoware-projects/wiki#working-groups)
- [Working Group Calendar](https://calendar.google.com/calendar/u/0/embed?src=autoware.org_6lol0ho5ft0217h8c60pi1fm30@group.calendar.google.com&ctz=America/Anchorage): Google calendar lists all the working group meetings. You can download [iCal format](https://calendar.google.com/calendar/ical/autoware.org_6lol0ho5ft0217h8c60pi1fm30%40group.calendar.google.com/public/basic.ics).

## Projects

- [Open AD Kit](https://autowarefoundation.github.io/openadkit/): Bring software-defined best practices to the Autoware project and to enhance the Autoware ecosystem and capabilities by partnering with other organizations.
- [Reference Design Guideline for Low Speed Autonomy (LSA) Vehicles](https://autowarefoundation.github.io/LSA-reference-design-docs/main/): A guideline to design and deploy a TRL-6 low speed autonomy vehicle based on Autoware.
- Privately-owned Vehicles (PoV):
  - [Autonomous Highway Pilot](https://github.com/autowarefoundation/autoware.privately-owned-vehicles): Build an open-source highway autonomy system that can power safe, SAE Level-4, autonomous driving around the world.
  - [Reference Design Guideline for Privately-owned Vehicles (PoV)](https://autowarefoundation.github.io/autoware.pov-reference-design-docs/main/): A guideline to design and deploy a PoV vehicle based on Autoware.

## Tools

Useful tools specifically designed for Autoware.

- [Scenario simulator v2](https://tier4.github.io/scenario_simulator_v2-docs/): A scenario testing framework for Autoware.
- [Vector Map Builder](https://tools.tier4.jp/feature/vector_map_builder_ll2/): A tool for quickly creating a vector map for Autoware that is compatible to Lanelet2 Format.
- [CARET](https://github.com/tier4/caret): CARET (Chain-Aware ROS Evaluation Tool) is one of performance analysis tool dedicated with ROS 2 applications.

## Simulator

Simulator list that supports Autoware.

- [AWSIM](https://tier4.github.io/AWSIM/): A Simulator for Autoware developed by TierIV.
- [CARLA](https://carla.org/): A famous open-source simulator for the autonomous driving research.
  - [carla_autoware_bridge](https://github.com/autowarefoundation/autoware_universe/tree/main/simulator/autoware_carla_interface): Autoware ROS package to enables communication between Autoware and CARLA simulator for autonomous driving simulation.
  - [zenoh_carla_bridge](https://autoware-carla-launch.readthedocs.io/en/latest/): The project is mainly for controlling multiple vehicles in Carla via Zenoh.

## Zenoh

Zenoh is a network protocol that is designed for robotics, automotive, and IoT. Here are some projects that integrate Zenoh into Autoware.

- [autoware_rmw_zenoh](https://github.com/evshary/autoware_rmw_zenoh) - Tutorial for running Autoware with [rmw_zenoh](http://github.com/ros2/rmw_zenoh).
- [zenoh_autoware_fms](https://github.com/evshary/zenoh_autoware_fms) - Project to showcase an Autoware fleet management system with Zenoh.
- [zenoh_autoware_v2x](https://github.com/evshary/zenoh_autoware_v2x) - Project to showcase an Autoware V2X scenario with Zenoh.

## Vehicles

The list of vehicles that use Autoware.

- [AutoSDV](https://github.com/NEWSLabNTU/AutoSDV): A small-scale autonomous vehicle, equipped with practical, industry-standard sensors and running Autoware.

## Videos

- [Self-Driving Cars with ROS and Autoware](https://www.youtube.com/playlist?list=PL8EeqqtDev54yyF5-o2jUEOhAm2GSZm6e)
- [A Tale of Two Open-Source Ecosystems: AutoDRIVE and Autoware | Autoware Tutorial | IEEE IV2025](https://youtu.be/MDpC3oAN9gI?si=iWdujfwmkT9WM-fE)

## Datasets

- [TuSimple](https://www.kaggle.com/datasets/manideep1108/tusimple)
- [CurveLanes](https://www.kaggle.com/datasets/bnyadmohammed/curvelanes)

## Papers

- [ROS 2 Agnocast: Supporting Unsized Message Types for True Zero-Copy Publish/Subscribe IPC](https://arxiv.org/abs/2506.16882)
- [TUM Teleoperation: Open Source Software for Remote Driving and Assistance of Automated Vehicles](https://arxiv.org/abs/2506.13933)
- [Open-Source Autonomous Driving Software Platforms: Comparison of Autoware and Apollo](https://arxiv.org/abs/2501.18942)

## Obsolete

- [Autoware.AI](https://github.com/autowarefoundation/autoware_ai): The autonomous driving framework based on ROS 1.
- [Autoware.Auto](https://autowarefoundation.gitlab.io/autoware.auto/AutowareAuto/): The autonomous driving framework based on ROS 2, which is replaced by Autoware.core/Autoware.universe.

## Contributing

Always happy to accept contributions. Feel free to open pull request to add any awesome resource related to Autoware!
