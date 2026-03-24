
## Part 2 of the project

Goals

Short Goals
Get pysr (python symbolic regression) and attention neural network working for testing examples, reproduce the results from this paper: ROBUST PDE DISCOVERY UNDER SPARSE AND HIGHLY NOISY CONDITIONS VIA ATTENTION NEURAL NETWORKS

Medium Goals
The paper shows great results on the equation recovery of PDEs with smooth progressing (no shock formation), while its structure doesn't naturally recovery the finite volume formulation (or weak form) that's needed to solve for hyperbolic equations. I want to extend the current approach to be able to recover the underlining PDEs with the existence of shocks.

- Limitations: Even if it works well, say, for flux recovery (because the underlining flux is a continuos function), it's still hard to recover meaningful terms when

Long Goals

- Create a hybrid model that works for both senarios (the ICs can lead to both smooth and shock form, it recovers both cases within the error bar (say 10 %)). If that can work for 1D testing cases, go for more complex model (like two-fluid model).


SP, Statement of problem

What is the problem that you are looking at?
Is the problem clear? Have you provided enough background information for the audience to follow?
Do you have a clear summary and goals?
ID, Implementation details

What details are needed to understand the implementation?
Did you clearly outline the method and approach?
Did you state the loss?
Do you provide a sufficient level of detail?
R, Results

Do your results highlight the overarching goal of your project?
Are your results clear? Do you label important details? Do you use relevant and consistent color schemes?
Carefully select which visualizations to show. We do not need to see everything, only figures that highlight some aspect of the goal of your mini app.
Do you highlight a few (but not all) of the results?
C, Reflections

What did you learn? What worked, what needs improvement, what are the next steps or future directions?
Is your presentation practiced and on time? Is your slide deck of high quality?
