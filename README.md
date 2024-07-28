# Polytope-Training

This is the repository accompanying the paper titled "Certified Robust Invariant Polytope Training in Neural Controlled ODEs" by Akash Harapanahalli and Samuel Coogan.

Clone the repository and its submodule `immrax`, our tool for interval analysis and mixed monotone reachability in JAX:
```shell
git clone --recurse-submodules https://github.com/gtfactslab/Polytope-Training.git
```

Navigate into the `immrax` folder, and follow the steps in its `README.md` to install it and its dependencies into a new `conda` environment.

There are some extra dependencies to install to generate the figures:
```shell
pip install -r requirements.txt
```

We provide three Jupyter notebooks: `examples/examples.ipynb` generates Figures 1 and 2 for Examples 1 and 2 from the paper; `segway/segway.ipynb` trains the robust neural network controller for the segway model and generates Figure 3; `platoon/platoon.ipynb` trains the robust neural network controller for the platoon model and generates Figure 5.
