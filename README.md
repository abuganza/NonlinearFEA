# Nonlinear Finite Element Analysis

Repository for nonlinear finite element analysis course, taught by Prof. Adrian Buganza Tepole 

This repository mainly contains the Jupyter notebooks used in the class.

## Module 1: Math fundamentals 

### Nonlinearities in solid mechanics 

* [Jupyter notebook](JupyterNotebooks/Nonlinearities_in_solid_mechanics.ipynb): code associated to *Video: Nonlinearities in solid mechanics*, as well as other examples not solved in the Video. The example from *Video: Hyperelastic example* is also solved in this notebook. Note that this notebook as some gaps for you to try to fill in. There are prompts in the notebooks to guide you along these examples on nonlinearities due to large displacements, nonlinear strains, and hyperelastic materials.  

* [Jupyter notebook (solution)](JupyterNotebooks/Nonlinearities_in_solid_mechanics_solution.ipynb): same code as the previous one but will all gaps filled in. 

### Solution of nonlinear equations

* [Jupyter notebook](JupyterNotebooks/Solution_of_nonlinear_equations_with_Newton-Raphson.ipynb): code associated to *Video: Solution of nonlinear equations using Newton Raphson*, as well as other examples not solved in the Video. There are prompts in the notebooks to guide you solve equations of one variable as well as systems of nonlinear equations with the Newton-Raphson algorithm.  

* [Jupyter notebook (solution)](JupyterNotebooks/Solution_of_nonlinear_equations_with_Newton-Raphson_solution.ipynb): same code as the previous one but will all gaps filled in. 

### Vector and tensor calculus 

* [Jupyter notebook](JupyterNotebooks/Vector_and_Tensor_Algebra.ipynb): code associated to *Video:  Vector basics*, *Video:  Second order tensors*, *Video:  Fourth order tensors*, as well as other examples not solved in the Videos. There are prompts in the notebooks to guide you to do coordinate transformations for vectors and tensors, computing dot products, cross products, invariants, and storing and applying four order tensors.  

* [Jupyter notebook (solution)](JupyterNotebooks/Vector_and_Tensor_Algebra_solution.ipynb): same code as the previous one but will all gaps filled in. 

### Motion and deformation gradient 

* [Jupyter notebook](JupyterNotebooks/Motion_and_Deformation_Gradient.ipynb): code associated to *Vide: Motion and deformation gradient*, as well as other examples not solved in the Video. This notebook will ask you to plot deforming grids and contours of length and area changes.  

* [Jupyter notebook (solution)](JupyterNotebooks/Motion_and_Deformation_Gradient_solution.ipynb): same code as the previous one but will all gaps filled in. 

### Velocities and accelerations  

* [Jupyter notebook](JupyterNotebooks/Velocities_Accelerations_Gradients.ipynb): code associated to *Video: Velocities, accelerations, gradients*, as well as other examples not solved in the Video. This notebook will ask you to plot particle trajectories, the corresponding velocity and acceleration vectors along the trajectory, and use that to generate the velocity and acceleration vectors in terms of material or spatial coordinates.   

* [Jupyter notebook (solution)](JupyterNotebooks/Velocities_Accelerations_Gradients_solution.ipynb): same code as the previous one but will all gaps filled in. 

### Hyperelasticity  

* [Jupyter notebook](JupyterNotebooks/Hyperelasticity.ipynb): code associated to *Video: Hyperelasticity*, as well as other examples not solved in the Video. This notebook will review the neo-Hookean material and emphasize the difference between compressible (coupled) material models, nearly incompressible (uncoupled) materials, and perfectly incompressible models. The code will show how to plot stress-stretch curve for uniaxial tension and ask you to do the same for a Mooney-Rivlin  material model.   

* [Jupyter notebook (solution)](JupyterNotebooks/Hyperelasticity_solution.ipynb): same code as the previous one but will all gaps filled in. 

### Finite elements in 1D  

* [Jupyter notebook](JupyterNotebooks/Finite_element_discretization_1D.ipynb): code associated to *Video: Finite element discretization in 1D*, as well as other examples not solved in the Video. This notebook will review the concept of shape functions to interpolate functions inside an element given nodal values. The code shows an example with linear elements and asks for the solution of an example with quadratic shape functions.   

* [Jupyter notebook (solution)](JupyterNotebooks/Finite_element_discretization_1D_solution.ipynb): same code as the previous one but with the quadratic shape functions.

### Isoparametric map, Gauss quadrature 

* [Jupyter notebook](JupyterNotebooks/Isoparametric_map_1D.ipynb): code associated to *Video: Isoparametric map, Gauss quadrature*, as well as other examples not solved in the Video. This notebook will review the concept of mapping the element physical coordinate x to the parametric domain xi. In this way, shape functions can be put directly in terms of xi and used to interpolate both the geometry and any function over either the x coordinates or the xi coordinates. The first example is based on linear elements and the first activity is with quadratic shape functions. The second part of the notebook introduces the Gauss integration or quadrature to approximate integrals, which will become important to integrate the weak form.   

* [Jupyter notebook (solution)](JupyterNotebooks/Isoparametric_map_1D_solution.ipynb): same code as the previous one but with the quadratic shape functions over the parametric domain, and a second example of Gauss quadrature.

### Linear triangular elements 

* [Jupyter notebook](JupyterNotebooks/Discretization_2D_linear_triangles_solution.ipynb): code associated to *Video: Triangular elements*, it covers the shape functions in terms of (x,y) coordinates as well as in terms of barycentric coordinates for the isoparametric map. The notebook shows how the shape functions can be used to evaluate the function inside of an element given only nodal values.    

### Quadrilateral elements 

* [Jupyter notebook](JupyterNotebooks/Discretization_2D_Q4element_solution.ipynb): code associated to *Video: Quadrilateral elements*, it covers the shape functions in terms of the parametric coordinates (xi,eta) for the linear quadrilateral elements. It shows how to use the shape functions in terms of (xi,eta) and its derivatives to interpolate the geometry and bi-linear functions out of nodal values. 
