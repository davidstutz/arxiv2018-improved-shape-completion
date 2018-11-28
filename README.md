# Learning 3D Shape Completion under Weak Supervision

This repository contains paper and code corresponding to:

D. Stutz, A. Geiger. **Learning 3D Shape Completion under Weak Supervision.** International Journal of Computer Vision (2018). [[ArXiv](http://arxiv.org/abs/1805.07290) | [Springer Link](https://link.springer.com/article/10.1007/s11263-018-1126-y)]

Please cite as:

    @article{Stutz2018ARXIV,
        author    = {David Stutz and Andreas Geiger},
        title     = {Learning 3D Shape Completion under Weak Supervision},
        journal   = {International Journal of Computer Vision},
        year      = {2018},
    }

This work is based on our earlier CVPR'18 paper

D. Stutz, A. Geiger. **Learning 3D Shape Completion from Laser Scan Data with Weak Supervision.** IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018.

Also check the [project page](http://davidstutz.de/projects/improved-shape-completion/)
and the repository for our CVPR publication:
[davidstutz/cvpr2018-shape-completion](https://github.com/davidstutz/cvpr2018-shape-completion)

Here, you can find:

* `paper/`: the LaTeX source of the paper, as available on ArXiv.
* `code/`:
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

![AML.](screenshot.png?raw=true "AML.")

## License

Licenses for source code and data corresponding to:

D. Stutz, A. Geiger. **Learning 3D Shape Completion under Weak Supervision.** International Journal of Computer Vision (2018).

Note that the source code and/or data is based on other projects for which separate licenses apply. See the corresponding subrepositories for details.

### Source Code

Copyright (c) 2018 David Stutz, Max-Planck-Gesellschaft

**Please read carefully the following terms and conditions and any accompanying documentation before you download and/or use this software and associated documentation files (the "Software").**

The authors hereby grant you a non-exclusive, non-transferable, free of charge right to copy, modify, merge, publish, distribute, and sublicense the Software for the sole purpose of performing non-commercial scientific research, non-commercial education, or non-commercial artistic projects.

Any other use, in particular any use for commercial purposes, is prohibited. This includes, without limitation, incorporation in a commercial product, use in a commercial service, or production of other artefacts for commercial purposes.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

You understand and agree that the authors are under no obligation to provide either maintenance services, update services, notices of latent defects, or corrections of defects with regard to the Software. The authors nevertheless reserve the right to update, modify, or discontinue the Software at any time.

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. You agree to cite the corresponding papers (see above) in documents and papers that report on research using the Software.

### Data

Copyright (c) 2018 David Stutz, Max-Planck-Gesellschaft

**Please read carefully the following terms and conditions and any accompanying documentation before you download and/or use the data (the "Dataset").**

The authors grant you a non-exclusive, non-transferable, free of charge right: To download the Dataset and use it on computers owned, leased or otherwise controlled by you and/or your organisation; To use the Dataset for the sole purpose of performing non-commercial scientific research, non-commercial education, or non-commercial artistic projects.

Any other use, in particular any use for commercial purposes, is prohibited. This includes, without limitation, incorporation in a commercial product, use in a commercial service, or production of other artefacts for commercial purposes.

Without prior written approval from the authors, the Dataset, in whole or in part, shall not be further distributed, published, copied, or disseminated in any way or form whatsoever, whether for profit or not. This includes further distributing, copying or disseminating to a different facility or organizational unit in the requesting university, organization, or company.

THE DATASET IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATASET OR THE USE OR OTHER DEALINGS IN THE DATASET.

You understand and agree that the authors are under no obligation to provide either maintenance services, update services, notices of latent defects, or corrections of defects with regard to the Dataset. The authors nevertheless reserve the right to update, modify, or discontinue the Dataset at any time.

You agree to cite the corresponding papers (see above) in documents and papers that report on research using the Dataset.
