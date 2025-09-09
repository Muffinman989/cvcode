<!-- markdownlint-disable MD041 -->

The role involved reading white papers implementing state of the art algorithms with a graphics/computer vision solutions often involving ML for PC and mobile platforms.

#### Frame Interpolation

A ML model deisgned to generate a predictive frame given a sequence of previous frames within realtime frame rates.

* Experiment with CNN based U-Net Architectures
* Profile models on Device for realtime proformance
* Vulkan Proof of Concept (POC) for shared NPU memory

##### References

* GitHub: https://liuziwei7.github.io/projects/VoxelFlow

#### 3D Avatar Generation

A realistic 3D avatar capture for mobile devices from single image capture.

* Post processing optimization based solution for mesh deformation based on 2D features and blendshapes.
* Intrinsic camera parameter estimation cost function on reprojection error

##### Patents

* Name: ""
* Role: Co-inventor with 7 other colleagues as part of the 3D Avatar Generation at Samsung
* Status: Pending

##### References

* WebSite: https://deca.is.tue.mpg.de/

#### Blendshape Mapping

The mapping solution between sematically similar blendshapes across meshes with different topological layouts.

* Optimization based methods with different solvers such as Direct Methods (Decomposition) or Quadratic Programming (Active Sets) with different regularizers and constraints. 

* Experimented with Functional Maps for correspondence mapping between two different meshes involving mapping functions such as scalar functions (Geodesics) defined over a manifold (e.g. mesh) with mathematical operations as constraints designed to solve a linear operator that maps the correspondence.

* Python based Maya scripts to support Artist workflows for 3D meshes, Demo videos and Finetuning/Testing the Results.

##### References

* Paper: https://ls7-gv.cs.tu-dortmund.de/publications/2017-faces.pdf

##### Patents

* Name: ""
* Role: Co-inventor with 3 other colleagues as part of the Blendshape Mapping
* Status: Pending

#### Cloth Physics

A cloth based physics simulation for clothing items on avatars for mobile devices.

* Mass spring based solution using Euler intergation with time step sizes, spring lengths and dampening requiring a lot of tunning.

* Experimentation with Block based gradient decent with compute shaders.

##### References

* Paper: http://graphics.berkeley.edu/papers/Liu-FSM-2013-11/Liu-FSM-2013-11.pdf

#### Deep Reinforcement Learning for Animation

An ML based solution to drive a skeleton around in a virtual environment with physics.

* A Reinforcement Learning (RL) based solution training a policy based model with different reward functions and preparing training data.

* Unreal Engine based solution for Rendering environments with UI and environmental interactions using Blueprints and C++ code.

* Google Protocal buffers for network based integration between python based RL solution to Unreal simulation environments.

##### References

* Paper: https://ls7-gv.cs.tu-dortmund.de/publications/2017-faces.pdf

<!-- markdownlint-disable MD041 -->