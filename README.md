# matlab-docker 

Initial attempt at layering Matlab atop existing Datahub docker stack using previous work by agt (11/2024 idk)

Combines UC San Diego Datahub base images & Mathworks
[Matlab-Dockerfile](https://github.com/mathworks-ref-arch/matlab-dockerfile)

Matlab release & toolboxes can be configured within Dockerfile.

* Includes:
    * Matlab cli 
    * Matlab Web GUI (via [matlab-proxy](https://github.com/mathworks/matlab-proxy))
    * Matlab Jupyter/Python integration (via [jupyter-matlab-proxy](https://github.com/mathworks/jupyter-matlab-proxy))


