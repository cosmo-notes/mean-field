# Mean-field approximations and compartmental models

Mean-field approximations are the simplest way to reduce complicated properties of complex systems to simple quantities as they simply average all possible scenarios and track an expected quantity. As we will see, in most systems, mean-field approximations imply having to ignore key features of a system (heterogeneity of its parts, spatial distribution of the system) and taking unrealistic but convenient mathematical limits (infinite population size, infinite interaction rate). The resulting system is usually a highly idealized system of equations that simply follows the average (or 'mean') state of a continuous object (like a field) rather than a system of discrete parts. Hence, we are dealing with a 'mean field' or a 'mean-field model'.

Compartmental models are a useful conceptual tool to introduce along with mean-field approximations as they provide a recipe for how to build simple models and are incredibly powerful when paired with mean-field approximations. Compartmental models are simply a way of drawing maps of a system using boxes and arrows. They ask modelers to decide what parts of the system matter and what states matter for these parts. This process therefore assigns parts to compartments (boxes). Finally, we draw the transitions (arrows) between compartments to capture important mechanisms between the different parts of the system. In general, an experience modeler can directly go from a schematic of a compartmental model to a mathematical mean-field system of equations by only making a few additional assumptions.

Here are some references that might be of interest in combination with this notebook:
- **_Chaos and Dynamical Systems_** {cite}`feldman2019chaos`. This is an introduction to dynamical systems and chaos theory meant for a more general audience than textbooks aimed at physicists and mathematicians.
- **_Nonlinear Dynamics and Chaos: With Applications to Physics, Biology, Chemistry, and Engineering_** {cite}`strogatz`. The classic textbook on systems of differential equations, nonlinear dynamics, and their interdisciplinary applications.

Our main goal here is to provide a tutorial on (1) the model building steps involved in compartmental models, (2) translation of a compartmental model to a mean-field system, and (3) mathematical and computational analysis of mean-field systems of equations. As applications, we will cover classic models from the study of complex systems: species interactions and disease modeling.

## Table of content
```{tableofcontents}
```

## References
```{bibliography}
```
