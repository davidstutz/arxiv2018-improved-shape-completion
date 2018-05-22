# Learning 3D Shape Completion under Weak Supervision

The code is spread over the following repositories, which are included
as sub-repositories. Use `git clone --recursive` for cloning the
subrepositories.

* [davidstutz/aml-improved-shape-completion](https://github.com/davidstutz/aml-improved-shape-completion),
  Torch and C++ implementation of the proposed approach and baselines as well
  as the created benchmarks.
* [davidstutz/mesh-evaluation](https://github.com/davidstutz/mesh-evaluation),
  C++ implementation of mesh-to-mesh / mesh-to-point distance
  used for evaluation.
* [davidstutz/bpy-visualization-utils](https://github.com/davidstutz/bpy-visualization-utils),
  Python and Blender (`bpy`) utilities for visualization as shown below.
* [davidstutz/mesh-fusion](https://github.com/davidstutz/mesh-fusion),
  Python implementation of TSDF fusion used to obtain watertight and simplified
  meshes for our benchmarks.
* [davidstutz/mesh-voxelization](https://github.com/davidstutz/mesh-voxelization),
  C++ implementation of mesh voxelization for computing occupancy grids
  and signed distance functions from watertight meshes.
