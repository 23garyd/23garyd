## Gary Ding

Dartmouth '27 — B.A. Environmental Earth Sciences modified with Computer Science.
ORISE Research Fellow, USDA Forest Service. Google Summer of Code contributor in 2022
(OpenCV) and 2026 (dora-rs).

---

### Agents over robots

**[Agentic DORA](https://github.com/dora-rs/gsoc2026-dora-agentic-robot)** — Google Summer of Code 2026, dora-rs

An LLM agent layer over the DORA dataflow runtime that drives a UR5e with a Robotiq
gripper through multi-step pick-and-place from a plain-language goal. Collision-aware
RRT-Connect planning with forward kinematics and self-collision masking, obstacles
registered into the scene at runtime, and automatic replanning when the planner fails
rather than halting the dataflow. Delivered as 13 weekly PRs across the summer, ~200 unit
tests, a full documentation set and a rendered demo —
[the merge that brought all of it into main](https://github.com/dora-rs/gsoc2026-dora-agentic-robot/pull/48).

**[isaacSim-go2-humble](https://github.com/23garyd/isaacSim-go2-humble)** — Isaac Sim 4.5
and Isaac Lab brought up on RTX-50-series hardware under Ubuntu 22.04, bridged to ROS 2
Humble Nav2 for a Unitree Go2 quadruped.

**[tracer-mini-ros2](https://github.com/23garyd/tracer-mini-ros2)** ·
**[d1-ultra-ros2](https://github.com/23garyd/d1-ultra-ros2)** — C++ ROS 2 navigation
stacks: online FAST-LIO localization, rolling-costmap Nav2, AMCL tuning, and a mission
wrapper implementing a versioned robot-interface contract.

**[python-ironoak](https://github.com/23garyd/python-ironoak)** ·
**[java-ironoak](https://github.com/23garyd/java-ironoak)** — Google Summer of Code 2022
with OpenCV: Python and Java computer-vision libraries for FRC teams on OAK-D stereo
cameras and the DepthAI runtime.

### Agents over maps

**[nksk-fuelbreak-tool](https://github.com/23garyd/nksk-fuelbreak-tool)** —
**[open the live tool](https://23garyd.github.io/nksk-fuelbreak-tool/)**

A planning tool for land managers on leeward Hawai'i Island: 280 candidate road segments,
198 km of corridor, 20 native species. Choose a planting palette, move the cost and drought
sliders, get back a budget-constrained implementation plan. It runs entirely in the browser,
and the whole scenario — palette, sliders, corridors, plan — is encoded in the URL hash, so
a plan is a link you can send to someone. Built during an ORISE fellowship with the USDA
Forest Service, Institute for Pacific Islands Forestry.

**[NKSK-greenbreaks](https://github.com/23garyd/NKSK-greenbreaks)** — the Python pipeline
underneath it (GeoPandas, Rasterio, Shapely, PyProj). Per-segment drought probabilities
derived from 2000–2023 Hawai'i Climate Data Portal rainfall instead of one district-wide
constant, native species suitability from NRCS climatic–elevation envelopes and climatic
water deficit, and three-year implementation-plus-maintenance cost models. First author on
a manuscript in preparation.

---

### Stack

**Languages** Python · C++ (ROS 2) · C# / .NET · Java · JavaScript · Bash

**Robotics** ROS 2 · Nav2 · DORA · Isaac Sim & Isaac Lab · MuJoCo · robosuite · RRT-Connect · RoboDK · ArduPilot

**Perception & learning** OpenCV · DepthAI · PyTorch · imitation learning · diffusion policy · LLM tool-calling & agent orchestration · RAG

**Geospatial** QGIS · ArcGIS Pro add-in development · GeoPandas · Rasterio · Shapely · PyProj · GDAL · OSM/Overpass · TIGER · ACS

---

Bay Area, CA and Hanover, NH ·
[LinkedIn](https://www.linkedin.com/in/gary-ding-6ba10a201) ·
[ORCID 0009-0008-6805-6461](https://orcid.org/0009-0008-6805-6461)
