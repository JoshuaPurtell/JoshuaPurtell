Read [Here](https://www.pnas.org/content/108/48/19193)

By [[David Rand]], [[Samuel Arbesman]], and [[Nicholas Christakis]]

### Terminology

### Summary

In this experiment, agents are assigned to nodes in an [[Erdos Renyi Graph]] $G(n,\frac{n(n-1)}{10})$, which is rewired with rate $r$. When an edge is subject to rewiring, one of the nodal agents is allowed to unilaterally decide to either create the edge (if it does not exist), destroy the edge (if it does), or do nothing; $rn$ edges are subject to rewiring every time step. Agents can choose costly cooperation or costless defection.

In static graphs, high mutation rate can impede the ability of cooperative clusters to persist in a cooperate/defect regime. Inducing network fluidity by allowing agents to use decision histories to form and break ties on a dyadic basis allows for cooperative clusters to persist in time despite mutation pressures; agents punish defection by breaking ties and reward cooperation by preferentially initiating ties with cooperators.

- Cooperation persisted when $r=.3$, but decayed when $r=.1$ or $r=0$ were reconsidered.
- Increasing number of allowed updates changes equilibrium behave but does not necessarily lead to significant churn; the incentive structure is internalized by agents and equilibrium is stable.

### Related