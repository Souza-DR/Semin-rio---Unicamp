# Stochastic Optimization Methods

This repository contains a LaTeX presentation on stochastic optimization methods, with a special focus on applications for computationally intensive problems such as Full Waveform Inversion (FWI).

## Description

The presentation addresses the computational dilemma between deterministic and stochastic methods, exploring how to combine the best of both worlds for large-scale optimization problems. The content evolves from the basics of Stochastic Gradient Descent (SGD) to advanced variants like Adam, providing visualizations and practical comparisons.

## Content

- **Motivation and Context**
  - Computational cost in problems like FWI
  - The dilemma between deterministic and stochastic methods

- **SGD Fundamentals**
  - Problem formulation
  - Mini-batch concepts
  - Behavior and convergence analysis

- **Advanced Variants**
  - SGD with Momentum
  - Nesterov Accelerated Gradient (NAG)
  - Adaptive Gradient (Adagrad) and its limitations
  - Root Mean Square Propagation (RMSProp)
  - Adaptive Moment Estimation (Adam)
  - Other important variants

- **Comparison and Practical Recommendations**
  - Comparative analysis of methods
  - Guidelines for choosing the appropriate method

## How to Use

### Requirements

To compile the presentation, you will need:
- A LaTeX distribution (like TeX Live or MiKTeX)
- Beamer, TikZ, and other packages specified in the preamble

### Compilation

```bash
pdflatex presentation.tex
```

To generate animations correctly, you may need to compile multiple times or use specific tools like `animate`.

## File Structure

- `presentation.tex` - Main presentation file
- `/figures` - Directory containing images and graphics used in the slides
- `/optimization-on-loss-surface-contours` - Files for loss surface contour animations
- `/optimization-on-saddle-point` - Files for saddle point animations

## Contributions

Contributions are welcome! Feel free to open issues or send pull requests with improvements, corrections, or additions to the material.

## Authors

- **Supervision**: Paulo J. S. Silva
- **Post-doc**: Danilo R. Souza
- **Institution**: University of Campinas (UNICAMP)

## License

This material is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## References

- Robbins, H., & Monro, S. (1951). A stochastic approximation method. The annals of mathematical statistics, 400-407.
- Kingma, D. P., & Ba, J. (2015). Adam: A method for stochastic optimization. ICLR.
- Duchi, J., Hazan, E., & Singer, Y. (2011). Adaptive subgradient methods for online learning and stochastic optimization. JMLR.
- Richardson, A. (2018). Seismic Full-Waveform Inversion Using Deep Learning Tools and Techniques. arXiv preprint.
- van Herwaarden et al. (2020). Stochastic amplitude versus offset inversion with mini-batches. Geophysics.
- Friedlander, M. P., & Schmidt, M. (2012). Hybrid Deterministic-Stochastic Methods for Data Fitting. SIAM Journal on Scientific Computing, 34(3), A1380-A1405. doi:10.1137/110830629
- Ruder, S. (2017). An overview of gradient descent optimization algorithms. arXiv preprint arXiv:1609.04747.
- Qian, N. (1999). On the momentum term in gradient descent learning algorithms. Neural networks, 12(1), 145-151.
- Nesterov, Y. (1983). A method for unconstrained convex minimization problem with the rate of convergence O(1/k^2). Doklady AN USSR, 269, 543-547.
- Zeiler, M. D. (2012). ADADELTA: An adaptive learning rate method. arXiv preprint arXiv:1212.5701.
- Loshchilov, I., & Hutter, F. (2019). Decoupled weight decay regularization. ICLR.
- Reddi, S. J., Kale, S., & Kumar, S. (2018). On the convergence of Adam and beyond. ICLR.
- Dozat, T. (2016). Incorporating Nesterov momentum into Adam. ICLR Workshop.
