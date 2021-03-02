# Lecture 1
- Define Variable.
- Define Dynamics.
- Define Parameter.

# Lecture 2
- What is the difference between a deterministic model and a stochastic model? Which type have we considered in class?
- Otto & Day's 7 Steps:
    1. Formulate the Question.
    2. Determine the basics. 
        -Variables: constraints, interaction rules? 
        - Discrete or continuous time? 
        - Parameters: fundamental and reasonable constraints.
    3. Qualitatively describe the biological system
        - Life cycle. 
        - Flow diagrams. 
        - Event tables. 
    4. Quantitatively describe the biological system
    5. Analyze the equations.
        - Solve (analytical)
        - Simulate (numerical)
        - Analyze
    6. Checks & Balances: check against known examples. 
    7. Relate your results back to the question. 
        - Did the model answer the question? 
        - Were your results intuitive? Counterintuitive?
        - Can you tell a story to summarize the model and insights? 
        - What experiments might you conduct, based on your findings?
- Three Models:
    1. Number of branches on a tree. 
    2. Number of mice in the yard.
    3. Basic SIR model. 
- Define time scale.
- Recursion equation vs Difference equation vs. Differential equation. 
- Sketch a solution of a differential equation from the differential equation and an initial condition.
- Know how to write down the various model diagram types from a narrative. 
- Know how to write a recursion, difference, or differential equation from a model diagram. 

# Lecture 3
- Leibniz vs prime vs dot notation. 
- Define: order (of a differential equation).
- Classify: linear or nonlinear 
- Show/verify that a function is a solution to a differential, difference, or recursion equation.

# Lecture 4
- Exponential and logistic growth models
    - What are their common assumptions?
    - what are their different assumptions?
- Derive and explain the exponential growth (birth+death) model.
    - Recursion equation form
    - Difference equation form
    - Differential equation form
    - Growth rate R(n)
- Derive and explain the logistic growth model.
    - How is it based on the exponential growth model? Hint: R(n) isn't a constant.
    - Define: Intrinsic rate of growth.
    - Recursion equation form
    - Difference equation form
    - Differential equation form
- Vector Fields
    - Take a differential equation and draw a vector field.
    - Trace a solution through the vector field. 
    - (Loads of examples in Zill!)


# Lecture 5
- Separation of variables
    - Exponential growth
    - Logistic growth
    - General solving method. 
- Define & check for separability. 

# Lecture 6
- Haploid model of natural selection
    - In words, how does this model generally work? (Hint: two birth/death processes)
    - Derivation: how did we go from counts (n) to fractions (p,q)?
    - Equation (discrete): P(t+1) = ...?
    - What is the relative reproduction rate (relative fitness)? 
    - Equation (continuous): dp/dt = ... ?
- What are the similarities and differences between the haploid model ODE and the logistic growth ODE? 

# Lecture 7
- Define equilibrium
    - Recursion equation
    - Difference equation 
    - Differential equation
- Find equilibrium solution(s)
- Explain local stability, global stability, and instability in words / meaning / implications in a biological system. 
- Lotka Volterra Competition
    - Relationship with Logistic Growth? 
    - Characteristics of competitive, parasitic, mutualistic or commensal. Relationship between equations and concepts. 

# Lecture 8
- Consumer-Resource Models
    - General form.
    - Storytelling/explanation of general form. What do the terms mean? 
    - Equilibria
    - Predator/Prey
    - Constant Immigration

# Lecture 9
- Equations to interpretation: Interpreting an equation in words, translating the math.
- Integrating factor method