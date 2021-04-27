# Overall
- Take an ODE, an initial condition, and be able to solve the ODE and plug in the initial condition to arrive at a solution. 

# Lecture 10
- Define: homogeneous and nonhomogeneous ODE
- The canonical SIR model (e.g. for measles)
    - ODE representation and flow diagram

# Lecture 11
- Rescaling the SIR model (S+I+R=1 for all t)
- SIR equilibria
- What is S when the epidemic peaks?
- What fraction of population needs to be vaccinated to get herd immunity?
- What does herd immunity *mean* in words? 
- Define: basic reproductive number (words and formula for SIR)

# Lecture 12
- Linearization will NOT be on the final. 
- SEIR model
    - What's the difference -vs- SIR model? 
    - Name a disease for which SEIR would be used.
    - Equilibrium = ?

# Lecture 13
- What does a perfect vaccine do? 
- How do we model a perfect vaccine? 
- What is vaccine efficacy VE? How does it differ from vaccine effectiveness?
- What are some factors that *may* affect VE?

# Lecture 14
- Explain the difference between the "all-or-nothing" vaccine model and the "leaky" vaccine model...
    - in words
    - in ODEs
    - in a flow diagram
- Explain the three factors of the "three factor" vaccine model. 
- Understand the tradeoffs between the three factors. For example, if you could pick just one of the three factors to be nearly perfect, which would you choose? Explain. 
- Give real-world examples of (i) vaccination as an "initial condition" and (ii) vaccination under a "continuous rollout."
- SIRS model
    - ODEs
    - Flow diagram
    - Examples of diseases or scenarios in which this is a good model. 
- Ross-MacDonald model
    - be able to explain the different terms in the equation in words. 

# Lecture 15
- Take a two-dimensional linear ODE system and sketch the vector field in the phase plane. 
- Basic growth model for two populations (n1 and n2) with mutation:
    - Setup (Slide 10)
    - Matrix-vector representation (Slide 11)
- What's the plural of matrix?
- Why can we consider a 2-D vector like a point in the x-y plane? 
- Why can we consider a 3-D vector like a point in x-y-z space?
- Define: 
    - Row vector
    - Column vector
- Is a vector always a matrix? Is a matrix always a vector? 
- Rules to know:
    - When can you add two matrices or vectors?
    - When can you multiply a matrix or vector by a scalar? When can you "factor out" a scalar from a matrix or vector? 
    - Graphically what happens when you multiply a vector by a scalar?
    - When can you subtract one matrix or vector from another? 
    - When AND how can you multiply a row vector and a column vector?
    - Note: for column vectors x and y,  y^T * x produces a scalar. (Slide 20)
- What is the transpose of a vector or matrix?
- What happens to the dimensions when you take a transpose? 
- Which elements are unchanged by taking the transpose?
- How to: matrix-vector multiplication. MUST SHOW WORK.

# Lecture 16
- How to: matrix-matrix multiplicadtion. MUST SHOW WORK.
- Does matrix multiplication commute?
    - general rule: matrix multiplication does NOT commute. 
    - particular examples of when it DOES commute: (i) everything commutes with the identity. (ii) inverse matrices commute with each other. 
- Algebra vs Linear Algebra
    - Associative law of multiplication
    - Left & right distributive laws
    - Commutative law for scalars
- What is (ABCD)^T ?
- Define: zero matrix
- Define: Identity matrix
- Define: Diagonal matrix
- Thought process: matrix = machine. Explain in words what this means. 
- Define & calculate: trace
- Define & calculate: determinant (2x2 matrix only)

# Lecture 17
- How to: rewrite a system of equations (linear system) as a matrix-vector system. 
- How to: solve a linear system using linear algebra
    - Take an inverse of the matrix, and then multiply both sides by it. MUST SHOW WORK. 
- Define: the inverse matrix.
    - Define in math.
    - Explain in words.
    - Calculate (2x2)
- Generic 2x2 inverse (yellow box, Slide 8)

# Lecture 18
- Equivalent statements:
    - A is invertible
    - A^{-1} exists
    - For an arbitrary vector b, Ax=b has a unique solution x.
    - If Ax=0 then x=0
    - Det(A)≠0
- Equivalent statements:
    - A is NOT invertible
    - A^{-1} does NOT exist
    - For an arbitrary vector b, Ax=b DOES NOT have a unique solution x.
    - There exists some NON-ZERO vector x such that Ax=0.
    - Det(A)=0
- Define: Eigenvector
- Define: Eigenvalue
- Explain: what is an eigenvector, and why do we call it a "characteristic direction"? How does an eigenVALUE relate to this?
- How to: find the eigenvalues of a 2x2 matrix from scratch. MUST SHOW WORK. (Slide 11)
- How to: find the eigenvector associated with an eigenvalue. MUST SHOW WORK. (Slide 13)

# Lecture 19
- How do eigenvalues and eigenvectors relate to the solution of a 2D linear system of ODEs?
- How can this help us understand the *long term* behavior of a solution as t -> infinity? 
- How to: solve a 2D linear system of ODEs (Slide 5)
- Equivalent expressions: multiple ODEs and a matrix-vector ODE (Slide 6)
- Define: nullcline
- Rule: what is the equilibrium of a LINEAR system, and what is required of the matrix M? 
- Rule: what is the equilibrium of an AFFINE system, and what is required of the matrix M? 
- Rule: how does the stability of an equilibrium relate to the eigenvalues of M? (real eigenvalues)

# Lecture 20
- Define: triangular and diagonal matrices
- Trick: eigenvalues of triangular or diagonal matrices. 
- When do we get complex eigenvalues?
- Euler's equation is NOT on the test, but it IS awesome.
- What *happens* in a system with complex eigenvalues?
- Rule: how does the stability of an equilibrium relate to the eigenvalues of M? (complex eigenvalues) 

# Lecture 21
- Define: [class-structured populations] transition matrix aka projection matrix.
- Define: vital statistics
- What is the general solution of a DISCRETE TIME linear system? (Slide 10)
- What is the long-term growth rate of a population, in terms of its transition matrix? 
- What is the long-term class structure of a population, in terms of its transition matrix?
- What does "class structure" mean, in the note above?
- What are the needed conditions for the Perron Frobenius Theorem to hold? What does the PF theorem guarantee for us?
- What are "reproductive values" and how are they related to the transition matrix? 

# Lecture 22
- Home mortgages NOT on the final. 
- Understand the concept of how to take the solution of an ODE and solve for t, to find the amount of time it takes before some condition is met. 
    - Example 1: When was the water poured into the french press?
    - Example 2: How old is the woolly mammoth?
- Understand how to use multiple data points of information to pin down the values of constants.
    - Example 1: We used the temperature at time 0 and the temperature at time 10 to find the value of k in the cooling French Press. 
    - Example 2: We used the information about the half life (mass at time=0 vs mass at time=halflife) to find the value of the radioactive decay constant









