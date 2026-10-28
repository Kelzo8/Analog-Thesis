# Project Ideas and Plan

## Aim

Determine whether tactile feedback improves learning-based grasp-and-transport when vision and robot-state information are already available.

## Research Question

To what extent does adding tactile feedback to visual and robot-state observations improve task success and robustness during robotic grasp-and-transport?

## Main Task

The robot will grasp an object and transport it to a target region. An episode succeeds if the object reaches the target without being dropped.

Failed grasps, slip events, and dropped objects will be recorded where possible.

## Planned Models

1. Vision-and-robot-state baseline  
2. Tactile-and-robot-state model  
3. Visuo-tactile model  

## Evaluation

The models will be compared using:

- Task success rate
- Robustness to object placement and visual occlusion
- Slip or grasp-failure detection
- Inference time and model size

## Platform

The project will use the Franka-based robotic platform available through the Analog Devices project. Simulation will be used for initial development, with physical-robot trials used for validation.

## Current Ideas

- Compare models with and without tactile input under identical conditions.
- Test performance when the camera view is partially obscured.
- Record and analyse slip and dropped-object failures.
- Measure whether tactile feedback is worth the extra integration and computation.