# Online Technical Appendix to ‘Capital-Funded Public Provision and the Private-Consumption Gap in a Two-Class Dynamic Game’
Carlos Galindo Escajeda
2026-07-01

This appendix accompanies “Capital-Funded Public Provision and the
Private-Consumption Gap in a Two-Class Dynamic Game.” Section, equation,
assumption and result numbers refer to the main text unless prefixed by
an appendix letter.

Appendix A proves the state reduction asserted in Section 2 and
establishes the differentiability the envelope method requires. Appendix
B derives the four envelope conditions (6), (8), (10) and (11) and signs
the marginal values they turn on. Appendix C states the computational
procedure. Appendix D reports the parameter sweeps summarised in
Computation 1. Appendix E reports the state-contingent rule censuses
summarised in Computation 2. Appendix F reports the form-robustness
comparisons. Appendix G is the replication statement.

# Appendix A. The state reduction

Section 2 asserts $V_j = N_W^{1-\sigma_j}v_j$, at each class’s own
curvature and, under (O), in the two ratios $(x,z)$ alone. The result
usually cited for it concerns *differential* games, and this game is a
map: Section 2 fixes time as discrete and Section 7 turns on that choice
entirely, so a theorem about flows is the wrong instrument even where
the algebra would rhyme. Within the constant-share class of Definition 1
nothing needs importing. The reduction follows from Assumptions 1–3,
with admissibility as Assumption 5 defines it.

## A.1 The primitive map

Fix a constant share profile $(\tau,\phi,i)\in[0,\bar\tau]\times[0,1]^2$
and write the four state-free constants it determines,
$$\kappa_W \equiv (1-\alpha)+(1-\phi)\tau\alpha, \quad \kappa_C \equiv (1-i)(1-\tau)\alpha, \quad
  \kappa_K \equiv i(1-\tau)\alpha, \quad \kappa_G \equiv \phi\tau\alpha .$$
Assumptions 1–2 written out are a map $\mathcal{T}$ on the open positive
orthant $\mathbb{X}=\mathbb{R}^4_{++}$, carrying $S=(K,N_W,N_C,G)$ to
$S'$:
$$Y = AK^{\alpha}N_W^{1-\alpha}, \qquad C_W = \kappa_W Y, \qquad C_C = \kappa_C Y,$$
$$K' = (1-\delta)K + \kappa_K Y, \qquad G' = (1-\delta_G)G + \kappa_G Y,$$
$$N_W' = B\Big[\big(C_W/N_W\big)^{\theta}\big(G/N_W\big)^{1-\theta}\Big]^{\gamma} N_W, \qquad
  N_C' = B\big(C_C/N_C\big)^{\gamma} N_C .$$

$\mathcal{T}$ maps $\mathbb{X}$ into itself except at three corners, and
they divide by the *kind* of law rather than by the variable. A stock
law carries an undepreciated remainder, so it can only reach zero if the
inflow vanishes **and** depreciation is total: $\kappa_K=0$ with
$\delta=1$, or $\kappa_G=0$ with $\delta_G=1$. A population law carries
no such remainder — the previous population is multiplied, not added to
— so a single failure suffices, and $\kappa_C=0$, which is $i=1$, sends
$C_C$ and with it $g_C$ and $N_C'$ to zero in one step. The worker has
no counterpart: $\kappa_W\ge 1-\alpha>0$ whatever the instruments do,
which is what borrowing-constrained consumption out of the wage bill
buys. All three corners are disposed of by Assumption 5 rather than by
any restriction imposed here, because $\sigma>1$ makes a vanishing
population a payoff of $-\infty$ and the affected class always has a
feasible interior deviation. The one remaining case is $\theta=1$ with
$G$ extinguished, and there $G$ is inert by construction — it is the
no-social-wage corner of Section 4, where the reduction holds on the
smaller orthant.

**Lemma A.1 (the primitive map is homogeneous of degree one).** *For
every $S\in\mathbb{X}$ and every $\lambda>0$,
$\mathcal{T}(\lambda S) = \lambda\,\mathcal{T}(S)$.*

*Proof.* Output first:
$A(\lambda K)^{\alpha}(\lambda N_W)^{1-\alpha} = \lambda^{\alpha+(1-\alpha)}Y
= \lambda Y$ — the exponents sum to one, which is constant returns and
nothing more. Because $\kappa_W,\kappa_C,\kappa_K,\kappa_G$ are
constants free of the state, all four income flows $C_W$, $C_C$,
$\kappa_K Y$ and $\kappa_G Y$ inherit degree one. Each stock law is then
a sum of a degree-one carry-over and a degree-one flow,
$$K'(\lambda S) = (1-\delta)\lambda K + \kappa_K \lambda Y = \lambda K'(S),$$
and identically for $G'$.

The two reproduction laws go through the growth *factors*, and this is
the only substantive step. Both arguments of the worker’s composite are
ratios of degree-one quantities,
$$c_W(\lambda S) = \frac{\lambda C_W}{\lambda N_W} = c_W(S), \qquad
  \frac{\lambda G}{\lambda N_W} = z(S),$$ so $g_W$ is homogeneous of
degree **zero**, and $N_W'(\lambda S) = g_W(S)\cdot\lambda N_W =
\lambda N_W'(S)$. Likewise
$c_C(\lambda S) = \lambda C_C/(\lambda N_C) = c_C(S)$, so $g_C$ is
degree zero and $N_C'$ degree one. $\blacksquare$

A stock law is degree one for the cheap reason that it adds degree-one
terms. A population law is degree one only because the factor
multiplying the population does not see the scale, and that is what a
*level* object destroys; the two failures at the end of this appendix
are exactly this step failing. Note also that $\phi$ enters only through
$\kappa_W$ and $\kappa_G$: it is a share like the other two, so it is
degree zero, and the fiscal split adds an instrument without adding a
level.

**Lemma A.2 (the iterates, by induction on $t$).** *Fix a profile at
none of the three corners above, so that $\mathcal{T}$ maps $\mathbb{X}$
into itself: $\kappa_C>0$, and $\kappa_K>0$ or $\delta<1$, and
$\kappa_G>0$ or $\delta_G<1$. Let $S_t(\cdot)$ denote the $t$-fold
composition of $\mathcal{T}$, with $S_0(S)=S$. Then
$S_t(\lambda S) = \lambda\,S_t(S)$ for every integer $t\ge0$, every
$S\in\mathbb{X}$ and every $\lambda>0$.*

The hypothesis restricts the profile and the two depreciation rates and
never the state, so Proposition A.1(i)’s cone argument is untouched by
it. It also costs nothing: Assumption 5 disposes of all three corners
for the reason given above Lemma A.1, so every profile the reduction is
applied to carries it. Without it the induction has nothing to apply
Lemma A.1 to — at $\kappa_C=0$, which is $i=1$, $N_C'$ vanishes in one
step and $S_2$ does not exist.

*Proof.* At $t=0$ the claim is the identity $\lambda S = \lambda S$.
Suppose it holds at $t$. Then
$$S_{t+1}(\lambda S) \;=\; \mathcal{T}\big(S_t(\lambda S)\big)
  \;=\; \mathcal{T}\big(\lambda\,S_t(S)\big)
  \;=\; \lambda\,\mathcal{T}\big(S_t(S)\big)
  \;=\; \lambda\,S_{t+1}(S),$$ the second equality by the induction
hypothesis and the third by Lemma A.1. $\blacksquare$

The induction step composes *the same* map at every date, and that is
what Definition 1’s constant shares buy. The action sets are what let
them: $[0,\bar\tau]\times[0,1]^2$ does not scale with the state, so the
profile available at $\lambda S$ is the profile available at $S$ and
$\mathcal{T}$ is date-invariant. Two harmless extensions follow at once.
A time-varying but state-independent share path $(\tau_t,\phi_t,i_t)$
changes nothing, the induction then composing maps $\mathcal{T}_t$ each
degree one by Lemma A.1. And a rule that reads the *reduced* state is
degree zero by construction, a function of $(x,\nu,z)$ being unchanged
when the levels scale, so the same induction covers the share-valued
Markov policies of the grid computation. What it does not cover is a
rule that reads the levels.

**Proposition A.1 (the reduction).** *Let Assumptions 1–3 hold and fix a
constant share profile that is admissible in the sense of Assumption 5
at some $S\in\mathbb{X}$. Then:*

*(i) **The admissible set is a cone.** The set of states at which the
profile satisfies Assumption 5 contains $S$ if and only if it contains
$\lambda S$, for every $\lambda>0$.*

*(ii) **Each value function is homogeneous of degree $1-\sigma_j$ in the
levels, at its own exponent.**
$V_j(\lambda S) = \lambda^{1-\sigma_j}V_j(S)$ for $j\in\{W,C\}$. The
reduction is therefore a **per-player** property and requires no common
curvature: what it requires of class $j$’s felicity is that it be
homogeneous of *some\* degree in the levels, which a power is and
$\ln(1+K)$ is not.\*

*(iii) **Hence the reduction.** With
$(x,\nu,z)=(K/N_W,\ N_C/N_W,\ G/N_W)$,*
$$V_j(K,N_W,N_C,G) \;=\; N_W^{1-\sigma_j}\,v_j(x,\nu,z), \qquad
  v_j(x,\nu,z) \;\equiv\; V_j(x,1,\nu,z),$$ *and under (O) the
capitalist’s $v_C$ carries no $\nu$, so both classes reduce to $(x,z)$.*

*Proof.* For (i), Assumption 5 states admissibility as a condition on
the growth factors *along the realised path*, and by Lemma A.2 the path
from $\lambda S$ is the path from $S$ scaled by $\lambda$ at every date.
The factors themselves are ratios of successive populations, so
$g_{j,t}(\lambda S) = \lambda N_{j,t+1}(S)/\lambda N_{j,t}(S) = g_{j,t}(S)$
for every $t$: the two paths present Assumption 5 with the *same*
sequence of numbers, and it cannot separate them. The condition is
therefore a property of the profile and the ray through $S$, never of
the point chosen along it — which is what makes properness a statement
about shares.

For (ii), write $W_{j,t}(S)$ for the argument of class $j$’s felicity
along the path from $S$: $W_{W,t}=N_{W,t}$ for the worker and
$W_{C,t}=P_t=C_{C,t}^{1-\omega}K_t^{\omega}$ for the capitalist. Both
are homogeneous of degree **one** in the state. For the worker that is
immediate. For the capitalist, $C_C=(1-i)(1-\tau)\alpha Y$ is degree one
because $Y$ is, and $K$ is degree one, so their geometric mean at
weights summing to one is degree one — which is the whole of what (O)’s
Cobb–Douglas form is needed for here, and the reason an *additive* mix
of $C_C^{1-\sigma_C}$ and $K^{1-\sigma_C}$ would do as well while a mix
at different exponents would not.

Class $j$’s payoff is then
$V_j(S) = (1-\sigma_j)^{-1}\sum_{t\ge0}\beta^t
W_{j,t}(S)^{1-\sigma_j}$. The integrand is homogeneous of degree
$1-\sigma_j$ exactly, since $(\lambda W)^{1-\sigma_j} =
\lambda^{1-\sigma_j}W^{1-\sigma_j}$. Combining that with Lemma A.2,
$$\beta^t W_{j,t}(\lambda S)^{1-\sigma_j} \;=\; \beta^t\big(\lambda W_{j,t}(S)\big)^{1-\sigma_j}
  \;=\; \lambda^{1-\sigma_j}\,\beta^t W_{j,t}(S)^{1-\sigma_j}$$ term by
term: every term of the series at $\lambda S$ is the corresponding term
at $S$ times one and the same positive constant $\lambda^{1-\sigma_j}$.
Every partial sum therefore carries that same factor, which settles
convergence in both directions at once and gives a second and
independent route to (i). The series at $S$ converges by hypothesis,
since the profile is admissible there; the partial sums at $\lambda S$
are $\lambda^{1-\sigma_j}$ times partial sums that converge, so the
series at $\lambda S$ converges too, and its limit is
$\lambda^{1-\sigma_j}V_j(S)$. Setting $\lambda = 1/N_W$ gives (iii),
since $S = N_W\cdot(x,1,\nu,z)$. Nothing in this argument compares the
two classes’ exponents, which is why they need not agree; and nothing in
it uses the *form* of $W_{j,t}$ beyond its degree, which is why the
felicity must be a power but the aggregate inside it need not be
Cobb–Douglas. For the capitalist, $\nu$ does not appear in $W_{C,t}$ at
any date, so $v_C$ is a function of $(x,z)$ alone. $\blacksquare$

Reading $\mathcal{T}$ in the ratios reproduces $(\star)$ of Section 2:
with $y \equiv Y/N_W =
Ax^{\alpha}$,
$$x' = \frac{K'}{N_W'} = \frac{(1-\delta)x + \kappa_K y}{g_W}, \qquad
  z' = \frac{G'}{N_W'} = \frac{(1-\delta_G)z + \kappa_G y}{g_W}, \qquad
  \nu' = \frac{N_C'}{N_W'} = \nu\,\frac{g_C}{g_W}.$$ Dividing the
primitive Bellman equation
$V_j(S) = W_j^{1-\sigma_j}/(1-\sigma_j) + \beta V_j(\mathcal{T}S)$
through by $N_W^{1-\sigma_j}$ and substituting (iii),
$$v_W(x,z) = \frac{1}{1-\sigma_W} + \beta\,g_W^{1-\sigma_W}\,v_W(x',z'), \qquad
  v_C(x,z) = \frac{\big[(1-i)(1-\tau)\alpha Ax^{\alpha}\big]^{(1-\omega)(1-\sigma_C)}
             x^{\omega(1-\sigma_C)}}{1-\sigma_C}
             + \beta\,g_W^{1-\sigma_C}\,v_C(x',z').$$ The
period-to-period factor is $g_W^{1-\sigma_j}$ in *both* recursions — the
worker’s growth factor in the capitalist’s problem too, because the
normalisation is by $N_W$ on both sides. These are the $\tilde\beta_W$
and $\tilde\beta_C$ that Appendix B carries through every envelope. Two
features of the capitalist’s recursion are worth marking. Its flow term
is a function of $x$ alone, so his felicity is state-dependent where the
worker’s is a constant — that is the flow term $\zeta\varphi$ in B.4.
And his own reproduction factor $g_C$ has disappeared from his problem
entirely, which is what Assumption 5’s capitalist clause records. On the
realised path his condition is $\beta g_P^{1-\sigma_C}<1$ with
$g_P=P_{t+1}/P_t$; **at a rest point** $P$ grows at $g_W$ and this
reduces to $\beta g_W^{1-\sigma_C}<1$, which coincides with the dynastic
condition only because $g_W=g_C$ there and not by construction. Off a
rest point the reduction is unavailable and the two factors separate
materially, so the general form is the one Assumption 5 states and the
one the computation of Appendix C.2 measures.

**Corollary A.1 (the worker’s block is autonomous, and under (O) so is
the capitalist’s).** $N_C$ enters neither $Y$, $K'$, $G'$ nor $N_W'$, so
the subsystem $(K,N_W,G)$ is closed under $\mathcal{T}$ and $N_{W,t}$ is
a function of $(K_0,N_{W,0},G_0)$ alone. Hence $V_W$ carries no $N_C$
and $v_W$ no $\nu$. Under (O) the same is now true of the capitalist,
for a second and independent reason: $N_C$ does not enter his felicity
either, so $V_C(K,G,N_W)$ and $v_C(x,z)$. Appendix B.1 writes both
against the same three states, which is what lets one elasticity table
serve both classes. The dependence is one-way, not a decoupling: $N_C'$
still reads $K$ through output, so $\nu$ remains a state of the economy
and Theorem 1, which is a statement about the stationary class ratio and
not about anyone’s payoff, is untouched. It holds under any rule that
does not itself read $\nu$, which includes every policy under which
anything below is *derived* — the constant shares of Definition 1, and
the $z$- and $\tau$-anchored families of Appendix E, none of which reads
the class ratio. The one object in this paper that does read it is the
damped best-response field of C.3, whose policies are functions of all
three state ratios; that computation corroborates and derives nothing,
and no envelope in Appendix B is taken under it.

## A.2 Two ways the reduction fails

- *A public argument of the wrong degree.* Let the public argument of
  the worker’s composite be homogeneous of degree $d$ in the state, in
  place of $z=G/N_W$. Since $c_W$ is degree zero, $g_W$ is homogeneous
  of degree $\gamma(1-\theta)d$ and $N_W'$ of degree
  $1+\gamma(1-\theta)d$. Under Assumption 2’s $\gamma>0$, with the
  public input active ($\theta<1$) — precisely the case this paper is
  about — that degree is one if and only if $d=0$. What the reduction
  needs is therefore the *degree* and not the particular ratio, which is
  why $G/K$ serves exactly as well as $G/N_W$, and why no rescaling of
  either rescues a specification of any other degree.

  Congestion is the instance that prices this. Write
  $z_\psi \equiv G/N_W^{\psi}$, $\psi\in\mathbb{R}$, with $\psi=1$ this
  paper’s specification, $\psi=0$ an aggregate stock the workforce
  shares without congestion, $\psi\in(0,1)$ partial congestion, and
  $\psi>1$ congestion more than proportional to headcount. Its degree is
  $d=1-\psi$, so $N_W'$ is homogeneous of degree
  $1+\gamma(1-\theta)(1-\psi)$ and the admissible set is the single
  point $\psi=1$. Nothing in the scaling bounds $\psi$, so no departure
  from proportional congestion is admissible in either direction: the
  aggregate stock, at degree $1+\gamma(1-\theta)$, is one point of the
  failure and not the shape of it, and share-valuedness is a knife-edge
  rather than an approximation that a little non-rivalry would perturb.
  At every $\psi\neq1$ Lemma A.1 fails at its only substantive step, and
  Lemma A.2 has nothing to iterate. What fails is this reduction, and
  A.3 states what that does and does not settle.

- *A lump-sum transfer.* Add a level $T$ to worker income. Then
  $C_W = \kappa_W Y + T$ is degree one only if $T$ scales with the
  state, that is only if the transfer was a share after all. Adding $G$
  does not soften this.

The two are the composite’s two arguments, and each fails the same way:
the first puts the public argument at a non-zero degree, the second the
private one.

## A.3 What the reduction establishes, and what it does not

Four limits, none cosmetic.

- It is a statement about the homogeneity of a value function under a
  *fixed* degree-zero policy. It says nothing about existence,
  uniqueness or characterisation of a feedback equilibrium, and
  certifies no Markov-perfect object.
- It does **not** show that restricting attention to share-valued
  policies is *without loss*. Only one direction is proved: *given* a
  degree-zero rule, the value function is degree $1-\sigma$. A rule
  reading the levels is not excluded here — it is outside what this
  argument covers, and outside Definition 1. Nothing in the paper is
  entitled to the converse.
- Homogeneity is not differentiability. Appendix A.4 supplies that
  separately, on a neighbourhood of a rest point, and needs Theorem
  2(iii) to do it.
- It is neither a proof nor a use of Long and Shimomura (1998). Their
  result concerns *differential* games — best replies within the
  linear-homogeneous Markov class, in continuous time. The reference
  stands as the lineage in which the homogeneity idea belongs; no step
  above rests on it, and the paper’s discrete-time commitments are the
  reason it must not.

## A.4 Differentiability, and why it is not an extra assumption

Every step in Appendix B differentiates a value function with respect to
a state, so it needs $V_W$ and $V_C$ to be differentiable there — a
regularity condition Assumptions 1–5 do not state. Within the
constant-share class of Definition 1 it need not be assumed, because the
value functions are not primitives but explicit sums. Under fixed shares
$(\star)$ is real-analytic on the open positive orthant, so each
$W_{j,t}$ of Proposition A.1(ii) is a real-analytic function of the
initial state and
$V_j = (1-\sigma_j)^{-1}\sum_t \beta^t W_{j,t}^{1-\sigma_j}$ is a series
of real-analytic terms. Differentiating it termwise is legitimate where
the differentiated series converges locally uniformly, and it does on a
neighbourhood of an interior rest point. Under constant shares $\ln g_W$
is affine in $(\ln x,\ln z)$ with the *constant* coefficients $p$ and
$q$ of Proposition 1, so
$$\frac{\partial \ln N_{W,t}}{\partial \ln S} \;=\; \sum_{s<t} (p,q)\cdot
  \frac{\partial(\ln x_s,\ln z_s)}{\partial \ln S},$$ a sum of
state-Jacobian products, and those products are bounded near an interior
rest point by this paper’s own Theorem 2(iii). That theorem puts the
whole spectrum of the reduced Jacobian strictly inside the unit disc, at
every interior rest point and everywhere in the admissible parameter
space. For any matrix and any $\epsilon>0$ there is an induced norm
within $\epsilon$ of its spectral radius, so there is a norm and a
neighbourhood of the rest point on which
$\|\mathrm{D}\mathcal{F}\| \le \rho^\ast+\epsilon<1$; the products are
then bounded by $(\rho^\ast+\epsilon)^{t}$, the elasticities above are
bounded *uniformly in $t$*, and the differentiated series is dominated
by a geometric series with ratio $\tilde\beta<1$. Differentiability
follows, and with it every envelope step. A perturbation of the levels
splits into a scale part, to which $\ln N_{W,t}$ responds with
elasticity one because the whole system is degree-one, and a ratio part,
which is the block Theorem 2(iii) governs.

The capitalist’s side needs no separate argument under (O), and it needs
one state fewer than it did before. His felicity is
$P_t=C_{C,t}^{1-\omega}K_t^{\omega}$; writing $K=xN_W$ and substituting
$Y=AK^{\alpha}N_W^{1-\alpha}$,
$$\ln P_t \;=\; (1-\omega)\ln\big[(1-i)(1-\tau)\alpha A\big] \;+\; \zeta\,\ln x_t \;+\; \ln N_{W,t},
\qquad \zeta=(1-\omega)\alpha+\omega,$$ the coefficient on $\ln N_{W,t}$
being $(1-\omega)(1-\alpha)+\zeta=1$. So his payoff is built from the
*same* two objects the worker’s argument has just bounded — the $(x,z)$
block Theorem 2(iii) governs, and the degree-one scale part — with no
$\nu$ and no $N_C$ at any date. The domination is the worker’s with
$\tilde\beta_C=\beta g^{1-\sigma_C}$ in its place, since $P$ grows at
$g$ at a rest point and properness is then $\beta g^{1-\sigma_C}<1$.
That licenses differentiating $V_C$ in the three states Corollary A.1
leaves it, which is what Lemma B.2 rests on and exactly the $3\times3$
system B.2 tabulates. Under the dynastic objective the licence had to be
wider — there $\ln g_C=\text{const}+\gamma(\alpha\ln x-\ln\nu)$ carried
$\nu$, $\ln N_{C,t}$ was a fourth sum of state-Jacobian products with
$(\gamma\alpha,-\gamma)$ in place of $(p,q)$, and the fourth state was
needed; Assumption 3 is what removed it, and nothing below uses it.

Three limits travel with that, and none is cosmetic. The argument is
**local** — a neighbourhood of a rest point, not a region: the far-field
unit root of Section 7 makes the spectral radius approach one as the
stocks grow, and *no* norm makes this map a uniform contraction, so
nothing here licenses the envelope method globally and no larger region
is claimed. It rests on **pointwise spectral radius at a rest point plus
continuity**, not on a common Lyapunov function. And it is confined to
**constant shares**: it says nothing about the differentiability of a
Markov feedback value function, which this paper does not use and does
not certify. Independently of the argument, both classes’ envelope
ratios are also differenced straight off the value functions numerically
and agree to about $10^{-9}$, which is corroboration that the derivative
exists and that these are its values (Appendix C.4).

# Appendix B. The envelope conditions derived

Section 6 states four conditions — (6), (8), (10) and (11) — as envelope
steps. This appendix derives them from the Bellman equation and the
reduction of Appendix A, so that Propositions 3–5 rest on the page, and
signs the marginal values both conditions turn on: Lemma B.1 for the
worker, Lemma B.2 for the capitalist.

## B.1 Value shares, and the scaling that makes them constant

By Proposition A.1(ii) each value function is homogeneous of degree
$1-\sigma_j$ in the levels, at **its own** exponent. Under (O) both are
functions of the same three states, $V_W(K,G,N_W)$ and $V_C(K,G,N_W)$:
the worker’s carries no $N_C$ because his own path is independent of the
class ratio, which is Corollary A.1, and the capitalist’s carries none
because $N_C$ has left his payoff. Write
$$a_S \;\equiv\; S\,\frac{\partial V}{\partial S}$$ for the marginal
value of a state times that state, one per state per class. Two
consequences carry everything below. Euler’s theorem gives
$\sum_S a_S = (1-\sigma_j)V_j$. And along a balanced path every state
grows by $g$, so each $a_S$ — a degree-one state times a
degree-$(-\sigma_j)$ derivative — is itself homogeneous of degree
$1-\sigma_j$ and satisfies $a_S' = g^{1-\sigma_j}a_S$. Discounting
therefore attaches the *same* factor to every continuation marginal
value of a given class,
$$\beta\,a_S' \;=\; \tilde\beta_j\,a_S, \qquad \tilde\beta_j \;=\; \beta g^{1-\sigma_j},$$
which is why $\tilde\beta_j$ rather than $\beta$ appears in every
condition, and why properness is what makes the recursions solvable at
all rather than a hygiene condition imposed on them from outside. The
class index is not decoration: the reduction of Appendix A is a
*per-player* homogeneity property, so nothing anywhere requires
$\sigma_W=\sigma_C$, and every wedge built from $\tilde\beta_j$ —
$\Omega$, $J$, $D_x$ — is class-indexed with it. Unsubscripted symbols
below are the worker’s.

Combining the two with the Bellman equation at a rest point closes the
worker’s Euler sum:
$$a_K + a_G + a_{N_W} \;=\; (1-\sigma_W)V_W \;=\; \frac{N_W^{1-\sigma_W}}{1-\tilde\beta} \;>\; 0
\tag{B.1}$$ under $\tilde\beta<1$. The same computation gives the
capitalist’s, and it is where the change of objective first shows: his
flow payoff is $P^{1-\sigma_C}/(1-\sigma_C)$ rather than
$N_C^{1-\sigma}/(1-\sigma)$, so
$$a_K + a_G + a_{N_W} \;=\; (1-\sigma_C)V_C \;=\; \frac{\varphi}{1-\tilde\beta_C} \;>\;0,
\qquad \varphi \;\equiv\; P^{1-\sigma_C}, \tag{B.1$_C$}$$ under
$\tilde\beta_C<1$. The two sums run over the *same three states*, which
is what makes the capitalist’s envelopes assemble from the same
elasticity table as the worker’s — and (B.1$_C$) is used once, in B.8,
as an independent second route to $\rho$.

## B.2 The transition elasticities at a rest point

Every envelope is assembled from the elasticities of the four laws of
motion, evaluated where $K'=gK$, $G'=gG$ and the two rest-point
identities
$$i(1-\tau)\alpha Y \;=\; (g-1+\delta)K, \qquad \phi\tau\alpha Y \;=\; (g-1+\delta_G)G \tag{B.2}$$
hold. With $p=\alpha\theta\gamma$ and $q=(1-\theta)\gamma$ as in
Proposition 1:

|  | $\ln K'$ | $\ln G'$ | $\ln N_W'$ | $\ln N_C'$ |
|----|----|----|----|----|
| $\ln K$ | $\dfrac{(1-\delta)+\alpha(g-1+\delta)}{g}$ | $\dfrac{\alpha(g-1+\delta_G)}{g}$ | $p$ | $\gamma\alpha$ |
| $\ln G$ | $0$ | $\dfrac{1-\delta_G}{g}$ | $q$ | $0$ |
| $\ln N_W$ | $\dfrac{(1-\alpha)(g-1+\delta)}{g}$ | $\dfrac{(1-\alpha)(g-1+\delta_G)}{g}$ | $1-p-q$ | $\gamma(1-\alpha)$ |
| $\ln N_C$ | $0$ | $0$ | $0$ | $1-\gamma$ |

Two rows carry the paper’s asymmetry. The $\ln G$ row is zero in both
the capital column and the capitalist’s reproduction column: public
infrastructure is an input to the worker’s reproduction and to nothing
else. And the $\ln N_C$ row and column are used by **neither** envelope
below. The row is scalar, so the class ratio never feeds back into the
block that determines it; the column is needed only by an objective that
values $N_C$, and under (O) neither class does. What the table therefore
supplies is a single $3\times3$ system in $(\ln K,\ln G,\ln N_W)$, read
once for each class at that class’s own discount factor. Under the
dynastic objective the capitalist’s envelopes ran over the full
$4\times4$ table and the $\ln N_C$ row’s single entry was what closed
them; that closure is what Assumption 3 has removed, and what B.4’s flow
term replaces.

## B.3 The stock envelope, and what $\Omega$ is

Differentiating with respect to $G$ and multiplying by $G$, the $\ln G$
row leaves two terms — and the same two for *either* class, the
capitalist’s stock envelope being the worker’s verbatim:
$$a_G \;=\; \tilde\beta\Big[\tfrac{1-\delta_G}{g}\,a_G \;+\; q\,a_{N_W}\Big]
\quad\Longrightarrow\quad
a_G \;=\; \frac{\gamma(1-\theta)\,g}{g-1+\delta_G}\;\Omega\;a_{N_W}, \tag{B.3}$$
with $\Omega$ exactly as in (6). This is what $\Omega$ is — one period’s
discount factor, times the share of next period’s stock that one
period’s investment buys, times the geometric sum of that stock’s
discounted survival thereafter:
$$\Omega \;=\; \tilde\beta\;\cdot\;\frac{g-1+\delta_G}{g}\;\cdot\;
   \sum_{t\ge0}\Big(\frac{\tilde\beta(1-\delta_G)}{g}\Big)^{t}, \tag{B.3$'$}$$
an identity rather than a reading. The sum converges exactly when
$\tilde\beta(1-\delta_G)<g$ — Proposition 3(i)’s condition, met as a
convergence requirement before it is met as a sign. The decomposition
also reads off the comparative static: raising $\delta_G$ raises the
middle factor and lowers the sum, and
$\partial\Omega/\partial\delta_G>0$ says the first wins — exactly under
properness, which is where Proposition 3(i) puts it. That is the
mechanism Section 6 states as perishability buying delivery.

## B.4 The capital envelope — equation (11)

The $\ln K$ row gives three continuation terms for either class, and for
the capitalist one flow term besides, because $K$ now enters his
felicity directly with elasticity $\zeta=\alpha+\omega(1-\alpha)$:
$$a_K \;=\; \zeta\,\varphi \;+\; \tilde\beta_C\Big[\tfrac{(1-\delta)+\alpha(g-1+\delta)}{g}\,a_K
   \;+\; \tfrac{\alpha(g-1+\delta_G)}{g}\,a_G \;+\; p\,a_{N_W}\Big].$$
Collecting the $a_K$ terms leaves the coefficient
$\big(g-\tilde\beta_C(1-\delta)-\tilde\beta_C\alpha(g-1+\delta)\big)/g = D_{x,C}/g$
— which is where $D_{x,C}$ comes from, and why $D_{x,C}\neq0$ is what
Proposition 4’s analogue needs for $a_K$ to be defined at all.
Substituting (B.3) and using $p=\alpha\theta\gamma$,
$q=(1-\theta)\gamma$,
$$a_K D_{x,C} \;=\; \tilde\beta_C\alpha\gamma g\,a_{N_W}\big(\theta+(1-\theta)\Omega_C\big)
   \;+\; g\,\zeta\,\varphi,$$ which is (11). The worker’s own capital
envelope is the same display with $\varphi$ deleted and the class index
dropped, since $K$ does not enter *his* felicity: his payoff is
$N_W^{1-\sigma_W}/(1-\sigma_W)$ and carries no stock. Setting
$\varphi=0$ therefore returns the worker’s envelope identically,
$$\frac{a_K}{a_{N_W}} \;=\; \frac{\tilde\beta\alpha\gamma g\big[\theta+(1-\theta)\Omega\big]}{D_x},
\tag{B.4}$$ the ratio quoted above (8). The derivation also says why $J$
is $\Omega$’s twin (Proposition 4(i)): at $\alpha=0$ capital stops
feeding back into its own accumulation through output, $D_x$ collapses
to $g-\tilde\beta(1-\delta)$, and $J=\tilde\beta(g-1+\delta)/D_x$ is
then the same survival sum as (B.3$'$) with $\delta$ in place of
$\delta_G$.

## B.5 The split — equation (6), and its sign

The split reaches two objects: it adds $\tau\alpha Y$ to $G'$ and lowers
$\ln N_W'$ through the consumption share,
$\partial\ln g_W/\partial\phi = -\gamma\theta\tau\alpha/\kappa_W(\phi)$.
So $$\frac{\partial V_W}{\partial\phi}
 \;=\; \tilde\beta\Big[\frac{a_G\,\tau\alpha Y}{gG} \;-\; \frac{\gamma\theta\tau\alpha}{\kappa_W(\phi)}\,a_{N_W}\Big]
 \;=\; \tilde\beta\Big[\frac{a_G\,(g-1+\delta_G)}{g\,\phi} \;-\; \frac{\gamma\theta\tau\alpha}{\kappa_W(\phi)}\,a_{N_W}\Big],$$
the second equality by (B.2) — which is where the $1/\phi$ comes from.
Substituting (B.3),
$$\frac{\partial V_W}{\partial\phi} \;=\; \tilde\beta\,\gamma\,a_{N_W}\;\Psi(\phi), \tag{B.5}$$
with $\Psi$ exactly as in (6). Equation (6) is a claim about a *sign*,
so it needs one more step.

**Lemma B.1 (the worker’s marginal values are positive).** *Let
Assumptions 1–4 hold with $\theta\in(0,1)$, let the profile be
admissible at a constant-share rest point — so that (B.1) and the
elasticities of B.2 are available — and let the worker’s problem be
proper, $\tilde\beta<1$ (Assumption 5). Then $a_{N_W}>0$, $a_G>0$ and
$a_K>0$, and consequently
$\operatorname{sign}\big(\partial V_W/\partial\phi\big) = \operatorname{sign}\Psi(\phi)$.*

*Proof.* By Proposition 3(i), properness puts $\Omega$ in $(0,1)$; by
the sign step of Proposition 4(iii) — the decomposition
$D_x = (g-1+\delta)(1-\tilde\beta\alpha)+(1-\delta)(1-\tilde\beta)$,
which uses Assumptions 1 and 4 with properness and no envelope condition
— it makes $D_x>0$. Only that step is used here, so the order of
derivation is $D_x>0$, then this lemma, then (8) in B.6, then the closed
form (9) that Proposition 4(iii) reads off (8). The coefficients in
(B.3) and (B.4) are therefore strictly positive, so
$a_G=\mathsf{q}_G a_{N_W}$ and $a_K=\mathsf{q}_K a_{N_W}$ with
$\mathsf{q}_G,\mathsf{q}_K>0$. Then (B.1) reads
$(1+\mathsf{q}_K+\mathsf{q}_G)\,a_{N_W} = N_W^{1-\sigma}/(1-\tilde\beta)$,
whose right-hand side is strictly positive and whose bracket is strictly
positive, so $a_{N_W}>0$; the other two follow from their positive
coefficients. The sign claim is then (B.5), since
$\tilde\beta,\gamma>0$. $\blacksquare$

The properness hypothesis is not decorative there: at $\tilde\beta=2$
the wedge is negative — the counterexample of Proposition 3(i) — and
$\mathsf{q}_G$ flips sign with it, so the argument fails exactly where
Assumption 5 fails.

## B.6 The tax — equation (8)

The tax reaches three objects, one more than the split: it withdraws
$i\alpha Y$ from $K'$, adds $\phi\alpha Y$ to $G'$, and raises
$\kappa_W$ by $(1-\phi)\alpha$. Using (B.2) on the first two,
$$\frac{\partial V_W}{\partial\tau}
 \;=\; \tilde\beta\Big[-\frac{a_K(g-1+\delta)}{g(1-\tau)} \;+\; \frac{a_G(g-1+\delta_G)}{g\,\tau}
       \;+\; \frac{\gamma\theta(1-\phi)\alpha}{\kappa_W(\phi)}\,a_{N_W}\Big].$$
Substituting (B.3) and (B.4), the first term becomes
$J\alpha\gamma\big[\theta+(1-\theta)\Omega\big]a_{N_W}/(1-\tau)$ and the
second $\gamma(1-\theta)\Omega\,a_{N_W}/\tau$. Setting the derivative to
zero and dividing through by $\tilde\beta\gamma\alpha\,a_{N_W}$ —
strictly positive by Lemma B.1 — gives (8) exactly.

## B.7 The reinvestment rate — equations (10) and (12)

Under (O) the $\ln N_C$ row of B.2 is not used at all: $N_C$ is neither
a state of the capitalist’s problem nor an argument of his payoff, so
the row that gave the dynastic model its own-dynasty marginal value has
no subject. What replaces it is a *flow* term, and it enters the capital
envelope rather than an envelope of its own.

The reinvestment rate reaches $K'$ by $(1-\tau)\alpha Y$ and reaches his
date-$t$ felicity through his own consumption,
$\partial\ln P/\partial i = -(1-\omega)/(1-i)$. It reaches nothing else
— the infrastructure law does not contain it, and the worker’s
reproduction runs on $c_W$ and $G/N_W$. So, using (B.2) on the first
channel,
$$\frac{\partial V_C}{\partial i} \;=\; \tilde\beta_C\,\frac{a_K(g-1+\delta)}{g\,i} \;-\;
   \frac{(1-\omega)\,\varphi}{1-i}, \tag{B.6}$$ whose zero is (10). This
is also the pair $(\mathrm{Ben},\mathrm{Cost})$ of Proposition 5, which
is therefore reading the two terms of one envelope rather than imposing
a decomposition on it — and it is where Proposition 5(i) comes from: at
$\omega=1$ the second term is identically zero and the equation has no
root.

Substituting (11) and writing $\rho=a_{N_W}/\varphi$,
$$\frac{i}{1-i} \;=\; \frac{\tilde\beta_C(g-1+\delta)}{D_{x,C}}\cdot\frac{1}{1-\omega}
   \Big[\zeta \;+\; \tilde\beta_C\alpha\gamma\big(\theta+(1-\theta)\Omega_C\big)\rho\Big]
   \;=\; \Lambda_C,$$ which is (12). The lone $\zeta$ in the bracket is
the $g\zeta\varphi$ of (11) — capital’s direct claim on his felicity —
divided through by $g\varphi$, which is why the worker’s conditions have
no counterpart to it. At $\omega=0$, $\zeta=\alpha$ factors out and the
bracket becomes
$\alpha\big[1+\tilde\beta_C\gamma(\theta+(1-\theta)\Omega_C)\rho\big]$,
which is the dynastic paper’s own bracket with
$r=\tilde\beta_C\gamma\rho$: the same expression, reached from a
different payoff. That coincidence is not decorative — it is what lets
Theorem 6’s proof transplant verbatim at $\omega=0$. Above it the
bracket is $\mathcal{Q}=(1-\omega)+J\zeta$ rather than $1+\alpha J$, and
Theorem 6 carries that substitution through rather than stopping at it.

## B.8 The third envelope, and the sign of $\rho$

Equation (12) is a claim about a *level*, and it carries $\rho$, so it
needs the one envelope the body does not use: the capitalist’s valuation
of the *workforce*. Under (O) his flow payoff carries $N_W$, through
output, with elasticity $(1-\omega)(1-\alpha)$, so the $\ln N_W$ row of
B.2 gives an inhomogeneous condition:
$$a_{N_W} \;=\; (1-\omega)(1-\alpha)\,\varphi \;+\;
   \tilde\beta_C\Big[\tfrac{(1-\alpha)(g-1+\delta)}{g}\,a_K
   \;+\; \tfrac{(1-\alpha)(g-1+\delta_G)}{g}\,a_G \;+\; (1-p-q)\,a_{N_W}\Big].$$
Under the dynastic objective this row was homogeneous and closed against
$a_{N_C}$; here the own-dynasty entry $\gamma(1-\alpha)$ is gone and a
flow term stands in its place. Substituting (B.3) and (11) — which
express $a_G$ and $a_K$ in terms of $a_{N_W}$ and $\varphi$ — collapses
it to a scalar equation in $\rho=a_{N_W}/\varphi$:
$$\mathcal{M}_C\,\rho \;=\; (1-\alpha)\big[(1-\omega) \;+\; J_C\,\zeta\big], \qquad
  \mathcal{M}_C \;=\; 1-\tilde\beta_C(1-p-q) \;-\; \tilde\beta_C(1-\alpha)\gamma\Big[\alpha J_C\big(\theta+(1-\theta)\Omega_C\big)
  + (1-\theta)\Omega_C\Big]. \tag{B.7}$$

The point to notice is that $\mathcal{M}_C$ is the dynastic paper’s
$\mathcal{M}$ **identically**, under class-indexing. The change of
objective moves the right-hand side of (B.7) and leaves its left alone,
because $\mathcal{M}$ was never built from the capitalist’s payoff: it
is what is left of the $\ln N_W$ row once that row’s own feedback
through capital and infrastructure is netted out, and both of those
channels are technology. That is why Lemma B.2 survives the change of
objective as a re-derivation rather than dying with $r$, and why its
proof below is the dynastic one with subscripts.

All three continuation entries of the row are positive —
$p+q=\gamma(\alpha\theta+1-\theta)<\gamma<1$ leaves the own-term
positive, and more workers produce more output, which feeds both stocks.
The flow entry is positive for $\omega<1$ and zero at $\omega=1$. So the
economics offers no route by which a worker could be worth negatively to
a capitalist, and the sign question is arithmetic: an undiscounted
future is exactly what would net $\mathcal{M}_C$ to zero.

**Lemma B.2 (the capitalist’s marginal values are positive, and so is
$\rho$).** *Let Assumptions 1–4 hold with $\theta\in(0,1)$ and
$\omega\in[0,1)$, and let the profile be admissible at a constant-share
rest point, so that Assumption 5’s capitalist clause reads
$\tilde\beta_C<1$. Then $a_{N_W}>0$, $a_G>0$ and $a_K>0$ for the
capitalist, hence $\rho>0$ and $\Lambda_C>0$, and Proposition 5’s zero
$i^\ast=\Lambda_C/(1+\Lambda_C)$ is interior without further
hypothesis.*

*Proof.* $\varphi=P^{1-\sigma_C}>0$ because $P>0$. For $\mathcal{M}_C$,
two identities. First, $D_{x,C}-(1-\alpha)\tilde\beta_C(g-1+\delta)
= g(1-\tilde\beta_C)$ — immediate from
$D_{x,C}=(g-1+\delta)(1-\tilde\beta_C\alpha)+(1-\delta)(1-\tilde\beta_C)$
of Proposition 4(iii) — so, writing $\eta_C=g(1-\tilde\beta_C)/D_{x,C}$,
$$(1-\alpha)J_C \;=\; 1-\eta_C \;\in\;(0,1) \quad\text{exactly under properness.} \tag{B.7$'$}$$
Second, substituting (B.7$'$) and $p+q=\gamma(\alpha\theta+1-\theta)$
into (B.7) and collecting, the two subtracted terms recombine with the
own-row term and leave
$$\mathcal{M}_C \;=\; (1-\tilde\beta_C) \;+\; \tilde\beta_C\gamma\Big[(1-\theta)\big(1-\Omega_C\big)
   \;+\; \alpha\,\eta_C\,\big(\theta+(1-\theta)\Omega_C\big)\Big]. \tag{B.7$''$}$$
Under properness $\Omega_C\in(0,1)$ by Proposition 3(i) and $D_{x,C}>0$
by Proposition 4(iii), so $\eta_C>0$ and all three terms of (B.7$''$)
are strictly positive: $\mathcal{M}_C>1-\tilde\beta_C>0$. Hence
$a_{N_W}$ is a strictly positive multiple of $\varphi$, so $\rho>0$;
$a_G$ and $a_K$ then follow from (B.3) and (11), whose coefficients are
positive by the same two facts, the flow term $g\zeta\varphi$ of (11)
being positive outright. Finally
$\Lambda_C=\big[J_C/(1-\omega)\big]\big[\zeta+\tilde\beta_C\alpha\gamma(\theta+(1-\theta)\Omega_C)\rho\big]$
is a product and sum of positives — $\zeta\ge\alpha>0$ and $1-\omega>0$
— and Proposition 5(ii) gives $i^\ast\in(0,1)$. $\blacksquare$

The right-hand side of (B.7) is where $\omega$ enters, and it is worth
reading the two limits. At $\omega=0$ it is $(1-\alpha)(1+\alpha J_C)$,
which is the dynastic paper’s own numerator; at $\omega\to1$ it tends to
$(1-\alpha)J_C$, which is still strictly positive, so $\rho$ does not
vanish at the degenerate weight. What vanishes there is not the
capitalist’s valuation of the workforce but the *cost* in his own
condition, which is Proposition 5(i) and lives in (B.6) rather than
here. The two failures are in different equations, and keeping them
apart is what stops the degeneracy being mistaken for a breakdown of the
envelope.

Properness is load-bearing here in the same way it is in Lemma B.1, and
(B.7$''$) says where: both bracket terms vanish as $\tilde\beta_C\to1$,
at which point $\Omega_C\to1$ and $\eta_C\to0$ together, and
$\mathcal{M}_C$ approaches zero from above. At $\tilde\beta_C=2$ — the
counterexample of Proposition 3(i) — the same expression is negative and
$\rho$ turns with it. The sign is therefore a consequence of discounting
and not of the parameter cells: $\rho$ is measured between $3.3$ and
$6.2$ across the $\gamma$ sweep of Section 6, and those numbers
corroborate a proved sign rather than stand in for one.

## B.9 What this derivation does not buy

It is a *one-shot* condition evaluated at a fixed balanced-growth
factor: $\phi$ and $\tau$ also move $g$, and hence $\Omega$, and this
derivation neither signs that channel nor closes the step from the sign
of a one-shot marginal value to the direction of travel of the
constant-share best response. Lemmas B.1 and B.2 sign the marginal
values, which is the *first* half of that step and not the second. Both
are supplied from outside this appendix, by Theorem 4 of Section 8.4,
and by a route that does not pass through here: the linearised laws are
summed directly, and $\Omega$ and $J$ appear as the resolvents of the
two stock laws rather than as envelope ratios. That the two routes
return the same $\Lambda_C$ is a check on this appendix as much as a
result about the bridge, since a shared error would have to survive
both.

There is a second such check, internal to this appendix and available
only under (O). Euler’s theorem gives (B.1$_C$),
$a_K+a_G+a_{N_W}=\varphi/(1-\tilde\beta_C)$, which is an equation in
$\rho$ built from the Bellman sum rather than from the $\ln N_W$ row. It
is not the equation (B.7) solves, and it returns the same $\rho$
identically in every primitive. Under the dynastic objective this
cross-check was unavailable in the same form, because the capitalist’s
Euler sum ran over four states and closed against $a_{N_C}$.

What that agreement certifies is narrower than the two routes look.
Every column of the $3\times3$ block of B.2 sums to one, and so do the
flow elasticities, $\zeta+(1-\omega)(1-\alpha)=1$; both restate
degree-one homogeneity, of the laws of motion and of $P$ respectively.
Summing the three envelope rows therefore returns
$(1-\tilde\beta_C)\sum_S a_S=\varphi$, which is (B.1$_C$). The Euler sum
is $1/(1-\tilde\beta_C)$ times the sum of the rows, so putting it in
place of the $\ln N_W$ row is an elementary row operation and the two
routes cannot disagree, whatever the individual entries are. The check
tests those four sums. It catches anything that breaks one of them and
nothing that does not: transposing the two entries between the $\ln K$
and $\ln N_W$ rows of the capital column leaves every column sum at one,
passes the check, and moves $\rho$ by nearly sixty per cent. The
agreement is worth having for what it is, which is not a check on the
stock or capital envelope’s own coefficients.

What remains genuinely outside is curvature, which C.8 treats. Both
lemmas are also statements about a constant-share rest point, where the
two dynasties share one growth factor; neither says anything about a
Markov feedback rule, and no Markov-perfect object is certified anywhere
in this paper.

## B.10 The stationary tax odds, and the affine form of the growth channel

Proposition 6$'''$ of Section 8.1 turns on one elimination and one
substitution, both of them algebra over the objects this appendix has
already built. They are recorded here because the proposition’s economic
content — that the correction to the growth channel is the tax’s
distance from its growth-maximising level times the rate at which the
odds on that tax move with growth — depends on there being no
differentiation anywhere in the step.

**The two margins, each a single subtraction.** The identities behind
the wedges’ logarithmic derivatives are
$D_x+\tilde\beta\big[\alpha(g-1+\delta)+1-\delta\big]=g$ for the private
column and $D_G+(1-\delta_G)\tilde\beta=g$ for the public one, the
second being $D_G$’s definition with $g-1+\delta_G$ restored. Under them
the margins of Proposition 5$'''$(ii),
$$M_J=(\sigma-1)(g-1+\delta)-(1-\delta)(1-\tilde\beta),
\qquad
M_\Omega=(\sigma-1)(g-1+\delta_G)-(1-\delta_G)(1-\tilde\beta),$$ each
collapse to one subtraction,
$$M_J=(\sigma-\tilde\beta\alpha)(g-1+\delta)-D_x,
\qquad
M_\Omega=\sigma(g-1+\delta_G)-D_G .$$ Both reduce to
$M_J=\sigma(g-1+\delta)-g+\tilde\beta(1-\delta)$ and
$M_\Omega=\sigma(g-1+\delta_G)-g+\tilde\beta(1-\delta_G)$ on
substituting the two identities, so the pairs agree identically in
$(g,\tilde\beta,\alpha,\delta,\delta_G,\sigma)$. The second form is the
useful one here: it puts each margin over a denominator that already
appears in the bracket.

**The elimination.** By (6) the public wedge is
$\Omega=\tilde\beta(g-1+\delta_G)/D_G$ with
$D_G=g-\tilde\beta(1-\delta_G)$, so
$\Omega D_G=\tilde\beta(g-1+\delta_G)$; and $W=\theta+(1-\theta)\Omega$
gives
$$W D_G \;=\; \theta D_G \;+\; (1-\theta)\,\tilde\beta\,(g-1+\delta_G).$$
Adding $\theta M_\Omega=\theta\sigma(g-1+\delta_G)-\theta D_G$ to both
sides cancels $\theta D_G$ on the right and leaves
$$W D_G \;+\; \theta M_\Omega \;=\; \big[\theta\sigma+(1-\theta)\tilde\beta\big]\,(g-1+\delta_G),$$
so that, dividing by $W D_G(g-1+\delta_G)>0$ — positive because
Proposition 3(i) puts $\Omega$ in $(0,1)$ under properness, which forces
$D_G=\tilde\beta(g-1+\delta_G)/\Omega>0$ and hence
$W=\theta+(1-\theta)\Omega\in(\theta,1)$, while $g-1+\delta_G>0$ on
Proposition 6(ii)’s domain —
$$\frac{\theta\sigma+(1-\theta)\tilde\beta}{W D_G}
\;=\; \frac{1}{g-1+\delta_G} \;+\; \frac{\theta}{W}\,
      \frac{M_\Omega}{(g-1+\delta_G)\,D_G} .$$ That is the whole of
Proposition 6$'''$(i). The first term of Section 8.1’s two-term bracket
carries the public pole with coefficient one, and everything left of it
is the public wedge’s own margin divided by the same pole; the bracket’s
second term is $-M_J/[(g-1+\delta)D_x]$ already. What the bracket is,
therefore, is the public pole less
$$\mathcal{O}\;=\;\frac{M_J}{(g-1+\delta)D_x}-\frac{\theta}{W}\,\frac{M_\Omega}{(g-1+\delta_G)D_G}
\;=\;-(\ln J)'+\frac{\theta}{W}(\ln\Omega)' ,$$ the second equality
being the two margin displays of Section 8.1. Nothing above
differentiates anything: the displayed elimination is an identity
between coefficients of the envelope this appendix has already derived,
and the two logarithmic derivatives it re-expresses are themselves
closed forms.

**The odds, and where the weight comes from.** The third form in
Proposition 6$'''$(i) needs no comparison with anything. At $\phi=1$ the
stationary tax (9) is
$\tau^\ast=(1-\theta)\Omega/\big[(1-\theta)\Omega+J\alpha W\big]$, so
its *odds* are a ratio of the two terms of that denominator,
$$\frac{\tau^\ast}{1-\tau^\ast} \;=\; \frac{(1-\theta)\,\Omega}{J\,\alpha\,W},$$
whence
$\big(\ln[\tau^\ast/(1-\tau^\ast)]\big)'=(\ln\Omega)'-(\ln J)'-(\ln W)'$
with $\alpha$ and $1-\theta$ constant. Now $W=\theta+(1-\theta)\Omega$
gives $W'=(1-\theta)\Omega'$, so
$$(\ln\Omega)'-(\ln W)' \;=\; \Omega'\Big[\frac{1}{\Omega}-\frac{1-\theta}{W}\Big]
\;=\; \Omega'\,\frac{W-(1-\theta)\Omega}{\Omega W} \;=\; \frac{\theta}{W}\,(\ln\Omega)' ,$$
because $W-(1-\theta)\Omega=\theta$ identically. That is $\mathcal{O}$.

Two things are worth reading off it rather than left implicit. The
weight $\theta/W$ is an **elasticity**: differentiating the odds in
$\Omega$ alone, which enters both directly and through $W$, gives
$\partial\ln[\tau^\ast/(1-\tau^\ast)]/\partial\ln\Omega=\theta/W$
exactly. And $\theta$ appears there as the part of $W$ that carries no
$\Omega$ — so the public stock moves the tax odds only to the extent
that the workforce weight does *not* already move with it. Both
statements require $\tilde\beta=\beta g^{1-\sigma}$ to be differentiated
with $g$, not held fixed: freezing it falsifies $(\ln\Omega)'$,
$(\ln J)'$ and the odds identity alike.

**The depreciation wedge.** The falling-side comparison of Section 8.1
needs one further identity. Write
$\widehat D=D_x(1+\alpha J)=g-\tilde\beta(1-\delta)$, which is the
denominator $\mathcal{B}$ carries at $\omega=0$ and is affine in
$\tilde\beta$. Then, using $D_G=g-\tilde\beta(1-\delta_G)$ and the
displayed form of $W D_G$, $$W D_G-\theta\widehat D
\;=\;(1-\theta)\tilde\beta(g-1+\delta_G)+\theta\tilde\beta(1-\delta)-\theta\tilde\beta(1-\delta_G)
\;=\;\tilde\beta\,\mathcal{D},
\qquad
\mathcal{D}=(1-\theta)(g-1+\delta_G)+\theta(\delta_G-\delta).$$ Placing
the two terms of Section 8.1’s falling-side comparison over the common
denominator $W\widehat D D_G(g-1+\delta_G)$ gives a numerator
$\sigma(g-1+\delta_G)\big[W D_G-\theta\widehat D\big]+\theta\widehat D D_G$,
and substituting the identity turns it into the display in the text. Two
readings follow. First, $\widehat D$, $D_G$, $W$ and $g-1+\delta_G$ are
positive at every admissible point, so the sign of the comparison is the
numerator’s alone, and only its first term can be negative. Second,
$\mathcal{D}$ is where the two depreciation rates enter and the only
place they do: it carries no $\gamma$, no $\alpha$, no $\sigma$ and no
$\tilde\beta$, which is why the sufficient condition it delivers is a
statement about depreciation and the workforce weight rather than about
preferences.

**What this does not buy.** Everything above is an identity, and
identities do not sign anything. The affine reduction is a change of
coordinates: it moves the open question on the interior branch from a
correlation between two moving quantities to the sign of a single number
at one endpoint, and it does not settle that sign. $(\ddagger)$ signs
$M_J$ and $M_\Omega$ separately, which is enough to bound
$|\mathcal{O}|$ on the falling side but not to sign
$\mathcal{X}+\gamma\alpha\mathcal{O}/(1-\alpha)$ in general. The census
reported in Section 8.1 visits $243{,}756$ admissible points and settles
no point outside them.

# Appendix C. Computational procedure

## C.1 The constant-share computation

Constant-share best responses are obtained by exact discounted-payoff
maximisation over a discrete share grid, from stated initial states. The
worker’s reply is the arg max of his own discounted payoff over the
product grid in $(\tau,\phi)$ at the capitalist’s current share; the
capitalist’s is the arg max over the grid in $i$; the two alternate to a
fixed point. Payoffs are computed by simulating the reduced path
$(\star)$ under the candidate shares and discounting, truncated at
$T=800$ periods, where $\beta^{800}\approx10^{-14}$. Grids are $0.01$ in
$\tau$ on $[0,\bar\tau]$ and in $\phi$ on $[0,1]$, and $0.005$ in $i$ on
$[0,1]$. Profiles failing either properness condition on the path tail
are masked out before the arg max. **No first-order condition is solved
anywhere in the procedure**; the closed forms of Section 6 are compared
against the grid result, never used to produce it. The strategy class is
the no-feedback subclass of the linear-homogeneous policies — the class
Definition 1 restricts to, and within which Appendix A’s reduction
holds.

## C.2 The two-sided admissibility mask

A single balanced-growth factor exists only because equalisation makes
$g_W=g_C$. This model breaks that lock off the stationary set, so
admissibility is the pair $\beta g_W^{1-\sigma}<1$ **and**
$\beta g_C^{1-\sigma}<1$ on the computed path, with a stated position on
one-sided candidates: for $\sigma>1$ an improper side is a payoff of
$-\infty$, so *whenever the affected class has a feasible unilateral
deviation restoring properness* that deviation dominates, and such
candidates are reported inadmissible-improper, never as equilibria. The
qualifier does logical work: without it the step from an improper side
to inadmissibility is incomplete. Whether profiles admitting no
unilateral restoration arise in this model is not established here, and
the question is moot for what follows, because at an interior stationary
point $g_W=g_C$ and the two conditions coincide. The mask can bite only
on non-stationary or extinction paths, and in the computed equilibria it
never does. The $\phi=0$ corner it excludes is genuinely catastrophic:
with $\theta<1$ the composite makes the public input essential.

On a path that oscillates the tail-minimum test is *stronger* than the
model requires. Properness asks that the discounted dynastic sum
converge; on a settling path that is $\min g > \beta^{1/(\sigma-1)}$
along the tail, which is Proposition 6(iii)’s floor, but on an
oscillating one it is not. The period-two payoff is
$$\frac{1+\beta g_a^{1-\sigma}}{(1-\sigma)\big[1-\beta^{2}(g_ag_b)^{1-\sigma}\big]},$$
so the sum converges exactly when $g_ag_b > \beta^{2/(\sigma-1)}$ — the
*product* of the growth factors over the cycle against the square of
that same floor, not its minimum. At $\sigma=2$, which is the base cell
and every cell of E.3’s census, the payoff is
$-(1+\beta/g_a)/\bigl(1-\beta^2/(g_ag_b)\bigr)$ and the condition is
$\beta^2<g_ag_b$; the star sweep of D.1 also carries
$\sigma\in\{1.5,3\}$, where the floor is $0.9216$ and $0.98$ rather than
$0.96$, so the general form is the one to apply. For constant shares the
distinction is empty, the two coinciding in the limit, so Section 6’s
equilibrium is untouched by it, as is the split’s half of Appendix E,
whose exclusions happen at a *rest point* — the $\phi=0$ corner with
$g_W = 1-\delta_G < \beta$ — where the two conditions again agree. It
reaches neither Theorem 2 nor Lemma 1, which are spectral and algebraic
statements about rest points containing no payoff, no discount factor
and no admissibility test. For oscillating rules the distinction is not
empty, and every count in Appendix E.3 is reported under the exact
geometric-mean criterion.

## C.3 Why not value-function iteration

The Bellman modulus $\beta g^{1-\sigma}$ exceeds one off the stationary
set, so a grid value-function iteration is unreliable there. The
reduction of Appendix A and share-valued Markov policies are what make
the problem computable exactly. A damped best-response protocol on the
three-state grid is run as corroboration only: its fields approach the
same corner as instrument-grid resolution rises, on the visited region
one-shot deviation gains are of order $0.1$ per cent, and the strict
global one-per-cent audit fails only at nodes where the value
approximation is documented unreliable — the improper region, where the
Bellman modulus exceeds one, and grid-boundary shells. That computation
therefore *corroborates* the constant-share equilibrium as a path-local
$\varepsilon$-equilibrium rather than independently certifying a global
feedback equilibrium.

## C.4 Envelope checks against the value function

Both classes’ envelope ratios are differenced straight off the value
functions — central differences in the state ratios, using none of the
envelope algebra — and agree to about $10^{-9}$ wherever the horizon is
long relative to the cell’s tail modulus, the residual at the
slow-growth cells tracking $\mu^{T}$ as the truncation implies. One
caution was earned there: these wedges must be read only at the growth
factor of the *same* policy, since reading them at a neighbouring
policy’s recorded $g$ costs four orders of magnitude because $\Omega$ is
sensitive to $g$. The class-ratio term drops out exactly for both
classes now — for the worker because his own path is independent of it,
which is Corollary A.1, and for the capitalist because under (O) it is
not in his problem.

Beyond that differencing there are two further checks, and what each
buys is worth separating. The first is internal to Appendix B: the Euler
sum (B.1$_C$) and the third envelope (B.7) are written as different
equations in $\rho$ and return the same $\rho$ identically. B.9 sets out
what that certifies — the unit column sums of B.2’s table and
$\zeta+(1-\omega)(1-\alpha)=1$, and nothing finer, the two routes being
row-equivalent once those hold. The second is across sections: Theorem
4’s Step 4 obtains $\Lambda$ by summing linearised growth responses
along the path, where B.7 obtains it by inverting a system of marginal
values at the rest point, and those agree identically too. Neither was
available in this form under the dynastic objective, where both members
of each pair ran through the class-ratio block.

Two discrimination controls establish that agreement with a condition is
not vacuous. Recomputing the tax from a capital envelope missing the
factor $\alpha$ on the reproduction term misses the solver by at least
$0.114$ at every corner cell, against a worst $0.005$ for the correct
one. Replacing (11) with the worker’s envelope — deleting exactly the
direct flow term $g\zeta\varphi$ — misses the computed reinvestment rate
by $0.068$ to $0.091$ across four cells, against $0.004$ to $0.033$ for
the correct envelope on the same four. Under the dynastic objective the
analogous deletion was invisible at two of twelve cells, because there
the deleted term was the capitalist’s own dynasty and it is a small
correction wherever he values the workforce many times over. The change
of objective replaced that term but not the condition under which it
hides, and the condition is worth stating because the obvious argument
for its absence does not work. What the control sees is the deleted
term’s share of $a_KD_x$,
$$\frac{\zeta}{\zeta+\alpha\,r\big[\theta+(1-\theta)\Omega_C\big]},$$
and $\zeta\ge\alpha$ bounds only its numerator. As $\tilde\beta_C\to1^-$
both bracket terms of (B.7$''$) vanish — $\Omega_C\to1$ and $\eta_C\to0$
together, which is what B.8 already records — so $\mathcal{M}_C\to0$
from above while the numerator of $\rho$ tends to
$(1-\alpha)(1-\omega)+\zeta>0$. Hence $r$ grows without bound with
properness never violated, and the share follows it to zero. At
Computation 1’s three equilibria the share runs from $0.34$ to $0.38$,
which is why the deletion is plain there. At a proper profile with
$\tilde\beta_C=0.9997$ it is $0.013$, and deleting the term moves
$i^\ast$ by less than the correct envelope’s own worst residual. So the
control bites where it is run, and where it would not is the
near-singular region C.6 describes.

## C.5 Numerical guards, disclosed

Both computational kernels floor consumption and the public-stock ratio
away from zero before taking logarithms or powers, and the
constant-share kernel additionally clips the class ratio to a wide
bracket. The two kernels use different floors, $10^{-300}$ and
$10^{-12}$. No guard binds anywhere on the paths reported here, and that
is measured rather than assumed: re-simulating all nine solves over the
full horizon, the smallest quantity reached on any path is
$c_C = 0.266$, a factor $2.7\times10^{11}$ clear of the tightest floor,
and $\nu$ stays within $[0.040, 0.300]$, ten orders of magnitude inside
its clip bracket. No result therefore depends on the choice of guard;
the guards are material only at the degenerate corners, where the
reported verdict is inadmissibility rather than a payoff comparison.

Payoffs are finite-horizon path sums ($T=800$) rather than closed-form
infinite sums. No analytic tail-remainder bound is computed, and the
recorded tail moduli — $0.950$ to $0.964$ across the nine base solves —
are what make the truncation immaterial at the reported precision.
Across the sweep cells the modulus is wider, $0.934$ to $0.995$, and at
the top of that range $T=800$ leaves about one and eight tenths of a per
cent of the discounted mass unaccounted —
$0.995^{800}=1.81\times10^{-2}$. That is precisely the size of the
residual disagreement in the envelope checks of C.4, which tracks the
same $\mu^{T}$, and it is concentrated in the slow-growth cells. It is
**larger** than one policy atom, not smaller: the atoms are $0.01$ in
$\tau$ and $\phi$ and $0.005$ in $i$. The closed-form policy results of
Section 6 rest on those cells, and this is the guard that bounds what
they cost.

## C.6 Near-singularity at the slow-growth cells

At the most durable cells $D_x$ is small. Across the sweep it runs from
$0.034$ at the slow end of C.5’s tail-modulus range to $0.135$ at the
fast end, the base cell’s own three equilibria falling between at
$0.085$ to $0.108$; that makes $J$ and $a_K/\varphi$ sensitive enough to
$g$ that an unmasked iteration can leave the admissible set entirely. At
the point such an iteration settles on from a neutral start, $D_x$ is
**negative**, both sides are improper and $\Omega>1$, which is exactly
what the equivalence of Proposition 3(i) requires of an improper
problem: the mask rejects the point rather than a comparison out-scoring
it. The stationary conditions themselves hold at those cells to within
one policy atom. The same near-singularity inflates $r$, which is what
disarms the second discrimination control of C.4 — there at those two
cells, and here wherever $\tilde\beta_C$ runs close enough to one, by
the share argument C.4 states.

## C.7 On what is and is not claimed unique

Uniqueness is asserted for the **stationary split** only, by the single
crossing at fixed transition factor. The tax and the reinvestment rate
are unique *given* the growth factor, each inverting a monotone map —
the tax at every split, not only at the corner, by Proposition 7(i). The
**joint** fixed point in $(\tau,\phi,i,g)$ is proved to *exist* by
Theorem 3 and is **not** proved unique; Brouwer’s theorem returns a
fixed point and says nothing about how many there are, and the numerical
solve reaching the same point from five starts spread across the box is
evidence about those starts. Nothing in the paper rests on joint
uniqueness.

## C.8 On the corner being a maximum rather than a stationary point

For $\sigma>1$,
$V_W = -(\sigma-1)^{-1}\sum_t\beta^t\exp\!\big(-(\sigma-1)\ln N_W(t)\big)$,
and $u\mapsto e^{-(\sigma-1)u}$ is convex and decreasing; so if
$\ln N_W(t)$ is concave in $\phi$ for every $t$, $V_W$ is concave in
$\phi$. That hypothesis is **not proved**. The accumulation equations
are sums, which propagate concavity but not log-concavity, while
reproduction is a product whose Cobb–Douglas exponents sum to
$1+\gamma\theta>1$, which propagates log-concavity but not concavity, so
the natural induction closes on neither. It is checked instead: over the
twelve decidable sweep cells, from both the common start and each cell’s
own balanced-growth point, no period of four hundred exhibits a
non-concave $\ln N_W(t)$, and $V_W$ is concave in $\phi$ in all
twenty-four cases. The reported corners are therefore maxima on the
evidence available, not proved to be so. Proposition 3 does not close
this gap and does not claim to: it settles the stationary split *at a
fixed transition factor*, where the single crossing gives uniqueness,
and making the split self-consistent moves $g$ and hence $\Omega$. Nor
is the gap load-bearing for the reported corners, which are arg maxima
over the admissible atoms of the split grid rather than solutions of a
first-order condition, and so are already global on those atoms.

This is what separates a stationary profile from an equilibrium of
Definition 1; Section 8.4 closes the other step, and closes this one for
the fiscal split. Theorem 3 constructs a profile at which every margin
is zero or at the boundary it points to, and Theorem 4 shows that those
margins are the true payoff derivatives rather than proxies for them, so
the profile is a genuine critical point. What turns a critical point
into a best reply is exactly the curvature hypothesis of this
subsection. Corollary 2 narrows what has to be shown — the question is
no longer concavity of an infinite discounted sum but single-crossing of
$\phi\mapsto\Psi(\phi;\Omega(g))$ — and Theorem 5 then settles it for
the split without a side condition, so the twenty-four checked cases
below now corroborate a proved statement in that instrument instead of
carrying it. Theorem 6 does the same for the reinvestment rate, on the
same region and by the same construction. For the tax they still carry
it, and that is where the evidence remains cell-deep and nothing wider.
The induction above closes on neither concavity nor log-concavity, and
that is unchanged; what has changed is that it is no longer the only
route, and for two of the three instruments it is no longer needed.

The observation this subsection opens with — that
$u\mapsto e^{-(\sigma-1)u}$ is convex and decreasing, so concavity of
$\ln N_W(t)$ in the deviating share at every $t$ makes $V_W$ concave —
is now Theorem 7 of the paper, stated for either class, any start, and
any convex set of shares — which is what lets Section 8.7 read it over
the worker’s two-instrument box rather than over a single share — and
used there for what this subsection could not supply: the transfer of
Theorem 4’s translation off the induced rest point to a start held
fixed. The hypothesis is still not proved in general. It is now known to
be false, and known where: Proposition 13(iii) reduces its tail to one
inequality in $\mathcal{P}$ and $\mathcal{H}$, and Computation 9
exhibits an admissible profile that breaks it. It is also now known to
be *provable* somewhere, and the somewhere is informative: at
$\delta=\delta_G=1$ Proposition 16 proves it jointly in the worker’s
pair, and the reason the proof stops there is the same survival term
that (32) reports. So the induction below fails for a nameable reason
rather than for want of an argument — restore the survival terms and the
object it needs affine in the log-state becomes convex in it. What this
subsection adds and the paper does not repeat is the reason the natural
induction fails on both sides at once, which is the accounting above and
is unchanged by any of it.

## C.9 The date-wise curvature computation

Computation 9 runs on the constant-share kernel of C.1 with the
admissibility mask of C.2 and no other apparatus. For each cell the
incumbent split is located first — by bisecting the diagonal derivative
to $10^{-9}$ where it crosses on a $0.03$ grid, and taken at the corner
where it does not — and the declared start is then the rest point that
split induces, so that the object differentiated is the one Definition 1
grades and not the diagonal. The split is swept on a $61$-point grid
over the proper interval, the path simulated for $800$ periods, and
$\ell_u$ second-differenced in $\phi$.

The ten are ten *profiles* over eight cells, and they are not the sweep
cells of D.1: $\theta\in\{0.80,0.85,0.90,0.95\}$ at $\delta_G=0.05$ with
$(\tau,i)=(0.34,0.41)$, the same $\delta_G$ with
$\theta\in\{0.85,0.90\}$ at $(\tau,i)=(0.45,0.50)$, and four profiles at
which the split rests at its corner — $\theta\in\{0.30,0.60\}$ at
$\delta_G=0.05$ and $\theta\in\{0.60,0.80\}$ at $\delta_G=0.20$, all at
$(0.34,0.41)$ — with $\alpha$, $\beta$, $\gamma$, $\sigma$, $\delta$,
$A$ and $B$ at D.1’s base values throughout. Two cells therefore appear
twice at different $(\tau,i)$, and $\theta\in\{0.30,0.85,0.90,0.95\}$
appear in no arm of D.1’s star. The split reported at each is the root
of the diagonal derivative at that fixed pair, which is not Computation
1’s equilibrium $\phi^\ast$. Four cells are common to both sets —
$\theta\in\{0.60,0.80\}$ crossed with $\delta_G\in\{0.05,0.20\}$ — and
at three of them both sets sit at the corner, so the comparison is
informative at one only: $\theta=0.80$ at $\delta_G=0.05$, where it is
$0.858$ here against $\phi^\ast=0.94$ there.

Three guards are worth naming because each was needed. Step size: the
reported curvatures agree to seven significant figures across $h$ from
$5\times10^{-4}$ to $10^{-2}$, which is what distinguishes a curvature
from a rounding artefact on a converged path, where the second
difference divides trailing digits by $h^{2}$. Horizon: the path is
constant to $2.6\times10^{-11}$ over dates $400$ to $799$, so the tail
is the rest-point value, and the counterexample’s late-date curvature
was confirmed a second time from the rest point alone, with no
transition path and no long sum — the two routes agree to seven figures.
Admissibility: every reported cell is gated on Assumption 4 and on
properness at the rest point, which matters because at several parameter
vectors the solver returns $g$ at exactly $1-\delta$, the limit as
capital diverges rather than an interior rest point; the
counterexample’s rest point was checked instead to be stable to six
decimals across simulation horizons from $10^{3}$ to $1.2\times10^{5}$.

Computation 10 runs on the same kernel and is checked the same way, with
one difference in what the guards had to catch. Its residuals are
truncation rather than disagreement, and the paper says so on evidence:
halving the differencing step quarters the chain-rule residual, a
Richardson ratio of $4.00$ at eight of nine cells, and the wedge
identity’s error falls from $3.2\times10^{-2}$ to $6.7\times10^{-10}$ as
the horizon runs $800\to3200\to12800$ at the slowest cell, where
$\tilde\beta=0.9959$ puts the sum near its radius of convergence.
Because that horizon sensitivity is real, splits are admitted only where
the relative truncation tail $T(1-\tilde\beta)\tilde\beta^{T}$ falls
below $10^{-6}$, which excludes $135$ of $432$ splits and empties two
cells entirely; the counts are reported in Computation 10 rather than
absorbed, because a gate that removes a cell prints a pass
indistinguishable from a vacuum.

Computation 11 runs on the same kernel again, at the same ten profiles
and the same starts, and differs only in that the stencil is
two-dimensional and is run twice — once in $(\tau,\phi)$ and once in
$(\tau,\varpi)$ — so that the coordinate system is the only thing that
varies between the two verdicts. The guard that matters here is not the
step size but the *tolerance*, and it had to be rewritten once. Testing
joint negative semidefiniteness by asking for a strictly positive
determinant is the wrong test at date zero, because Proposition
15(ii)–(iii) proves the determinant there is identically zero: a finite
difference then returns zero plus truncation, and a determinant gate
reads that as a failure. The verdict is therefore taken on the larger
eigenvalue measured against the matrix norm, and the residual is
confirmed to be $O(h^{2})$ by tripling the step. The $11\times11$ grid
over $T$ is reported separately from the per-cell Hessians for the same
reason the sweeps elsewhere are: signing a Hessian at one point is not
concavity on a set, and the grid is what speaks to the set — still by
sampling, and still able only to refute.

That grid is a sub-box of $T$ and its endpoints are what a replication
needs: $\tau$ takes eleven equally spaced values on $[0.20,0.60]$ and
$\phi$ eleven on $[0.10,0.97]$, with $\varpi=\phi\tau$, so it reaches
neither $\bar\tau$ nor the diagonal face $\varpi=\tau$. The three cells
are $\theta=0.85$ and $\theta=0.90$ at $(\tau,i)=(0.34,0.41)$ and
$\theta=0.85$ at $(0.45,0.50)$, all at $\delta_G=0.05$. The two criteria
are *not* evaluated on that grid: the intervals Computation 11 reports
for $(\ast\ast)$ and $(\ast)$ are one value per cell at the rest point,
across all ten profiles above, which is the set they range over.

The tail criterion is swept separately and much more widely, because
unlike the elasticity of Computation 10 it is closed-form at a rest
point and costs a bisection per cell. Two of the four primitives
Computation 10 could not vary need no sweeping at all: $\mathcal{H}$,
$\mathcal{P}$, $\mathcal{G}'$ and $\mathcal{G}''$ contain neither
$\beta$ nor $\sigma$, so both criteria are independent of them except
through the admissibility gate — a derivation, and the reason the sweep
is run over the other six primitives and the three shares instead. The
sweep carries a positive control, without which a clean result would be
indistinguishable from a test that cannot fire: the machinery is
required to flag the Computation 9 profile, and does, at $(\ast)=2.806$
and $(\ast\ast)=3.353$. Its one positive finding is a refutation and is
reported as the headline of that computation, because the complementary
count — the cells at which the criteria hold — establishes nothing at
all.

Computation 12 runs on the same kernel a third time and does two
unrelated jobs, which is why its controls are separate. The first is the
capitalist’s rate on an interval rather than at a point: the $41$-point
grid spans $[0.10,0.90]$, and under (O) all $41$ points are admissible
at each cell, so no mask is applied and nothing is discarded. Under the
replaced dynastic objective between $28$ and $41$ survived, the improper
remainder being discarded rather than counted; Computation 12 gives the
reason the range widens, and the difference matters because Theorem 7
asks for a **convex** set of rates. Its positive control is Computation
9’s own counterexample, at which the machinery must find $\ln N_{W,t}$
turning convex, and returns $t=1190$ — the same date by a route sharing
none of that computation’s code. The second job is a control on
Proposition 16, and the direction of the control is the point: the
closed form must reproduce a path built from the primitive laws *on* the
full-depreciation face and must fail to reproduce it *off* the face,
which it does by at least $9.4\times10^{-2}$ at four interior
depreciation rates. One reconciliation is worth stating, since the two
look as though they collide. D.1 reports no proper solution at
$\delta_G\in\{0.5,1.0\}$; those cells hold $\delta=0.08$ and $B=1$,
while the full-depreciation cells here set $\delta=\delta_G=1$ and lift
$B$, which Assumption 2 leaves free and which properness constrains once
both stocks are rebuilt from nothing each period. Eleven of eighteen are
admissible on that setting and seven are not. Neither result bears on
the other, and neither is evidence about the cells the paper reports.

# Appendix D. Parameter sweeps

## D.1 The corner sweep

The base parameterization is
$\alpha=0.33,\ \beta=0.96,\ \gamma=0.5,\ \sigma=2,\ \delta=0.08,\
\delta_G=0.05,\ \theta=0.6,\ \bar\tau=0.8$, with $A=B=1$.

The sweep behind Computation 1 is a star design around that base, over
$\theta\in\{0.40,0.60,0.70,0.80\}$, $\gamma\in\{0.30,0.50,0.70\}$,
$\sigma\in\{1.5,2,3\}$ and $\delta_G\in\{0.05,0.20,0.50,1.00\}$, solved
from a common start. It has five arms, not four: one per primitive,
perturbed one at a time from the base, and then the $\delta_G$ range a
second time at $\theta=0.80$ rather than at the base $\theta=0.60$ — a
second stock arm at the $\theta$ value where the corner flips, which is
what the two margins of the next paragraph are measured on. Four arms
alone would run eleven rows over eleven distinct cells, the base solved
once; the fifth is why the counts below are larger. It runs fifteen rows
over **fourteen distinct cells** — $\theta=0.80$ at $\delta_G=0.05$ lies
in two arms of the star and is solved twice, with identical results both
times — of which ten distinct cells admit a proper solution and nine of
those ten return $\phi^\ast=1$. The exception is
$\theta=0.80,\ \delta_G=0.05$, where the split is interior at
$\phi^\ast=0.94$ (with $\tau^\ast=0.34$, $i^\ast=0.515$). Four cells,
the perishable end of the stock range at $\delta_G\in\{0.50,1.00\}$
crossed with $\theta\in\{0.60,0.80\}$, yielded no proper solution at the
initialisations tried, which is absence rather than a proof of
non-existence.

Two margins move the corner and $\gamma$ is not one of them. Raising
$\theta$ at $\delta_G=0.05$ flips it. So does *lowering* $\delta_G$ at
$\theta=0.80$: the same cell is interior at $\delta_G=0.05$ and returns
to the corner at $\delta_G=0.20$, where $\phi^\ast=1$ at
$\tau^\ast=0.34,\ i^\ast=0.66$. By contrast every swept value of
$\gamma$ and of $\sigma$ leaves the corner in place, and eight further
values of $\gamma$ spanning $[0.30,0.70]$ at $\theta=0.8$ move
$\tau^\ast$ by at most one atom, so the corner is $\gamma$-inert on
everything tested.

**Two sweeps stand behind this appendix, and the difference is disclosed
rather than smoothed over.** The design above is the one re-run under
(O). An earlier sweep, run before the capitalist’s objective changed,
used a different grid — a full
$\theta\in\{0.3,0.6,0.8\}\times\delta_G\in\{0.05,0.2,0.5,1.0\}$ block
plus three one-off cells, fifteen distinct cells in all, of which twelve
admitted a proper solution and eleven returned the corner. Its verdicts
agree with the present sweep wherever the two grids meet, and its
interior cell is the same one at the same value. It is that earlier
grid, and not the one above, that the twelve-cell counts in C.8 and in
D.3–D.4 below refer to; those checks have not been re-run on the present
cell set, which is a fact a replicator needs and is recorded here rather
than left to inference. The earlier sweep also carries $\theta=0.3$,
which the present one drops, and lacks $\theta\in\{0.40,0.70\}$ and
$\sigma=1.5$, which the present one adds.

Re-solved cell by cell as *self-consistent stationary* equilibria — each
cell’s start required to be the balanced-growth point of the equilibrium
computed from it, every instrument free, and checked from a second,
distant seed — the earlier table is unchanged: no cell flips, and none
is seed-dependent, and at the interior cell the self-consistent split is
$0.84$ against the common start’s $0.94$. That run is on the earlier
grid and under the earlier objective; under (O) the self-consistent
fixed point was recomputed at the base cell only (Computation 3). What
the start moves is not the cell verdicts but the tax level and the
location of the $\theta$ boundary, and it moves them less than a partial
comparison suggests, because the tax adjusts.

## D.2 The $\theta$ boundary and start dependence

With all three instruments free, the equilibrium corner survives initial
stocks $z_0 \in \{0.2,\,1,\,5\}$ at $\theta = 0.60$, $0.70$ and $0.74$
alike; only at $\theta=0.78$ does the high-stock start return an
interior $\phi^\ast=0.83$. The worker meets a larger inherited stock by
taxing less — at $\theta=0.70$, $\tau^\ast$ falls from $0.48$ to $0.35$
as $z_0$ rises from $1$ to $5$ — and the lighter tax is what sustains
the corner. Computed instead as a self-consistent stationary equilibrium
the corner holds for $\theta \lesssim 0.76$ rather than
$\theta \lesssim 0.79$; at $\theta=0.76$ the iteration alternates
between $\phi=0.99$ and $\phi=1$, which is the boundary itself at this
resolution. The base cell sits well inside every one of these regions:
at $\theta=0.6$ the corner survives all five starts tried and the
self-consistent stationary equilibrium
$(\tau^\ast,\phi^\ast,i^\ast) = (0.50,1,0.41)$.

## D.3 Closed forms against the grid

Solving the split, the tax and the growth factor *simultaneously* from a
neutral start — so that $g$ is an output rather than an input — all
twelve decidable cells land within one atom of the grid best responses,
the worst discrepancy being $0.005$ in each of $\tau$ and $\phi$. Adding
the capitalist’s condition and solving $(\tau,\phi,i,g)$ jointly from
two declared generic starts, three cells needing the second, reproduces
the grid best responses at all twelve, worst discrepancy $0.005$. The
stationary split (7), solved as a fixed point from three starts without
reference to the computed equilibrium, reproduces the split at all
twelve decidable cells; at the interior cell it returns $0.84004$
against the grid best response’s $0.84$ on a $0.01$ grid.

Two links were measured here before either was proved, and both are
still reported cell by cell, because the measurements retain their value
as a check on the algebra that later replaced them. That $\Omega$ varies
with $\phi$ is a third channel Proposition 3 holds fixed:
$\mathrm{d}\ln \Omega/\mathrm{d}\phi$ is negative at every cell and
across the swept split range, so that channel *reinforces* the crossing,
with a slack of $1.17$ against the bound it must clear and the same
value at three grid resolutions. That sign is not structural and the
boundary is nearby: $\partial \Omega/\partial g$ changes sign at
$\delta_G=(2g-\beta-g^{2})/(2g-\beta)$, which at $\sigma=2$ runs from
$0.0376$ to $0.0387$ across the growth factors the reported cells occupy
— and from $0.0358$ to $0.0400$ across the wider tail-modulus range of
C.5 — and takes the value $(1-\beta)/(2-\beta)\approx0.038$ at $g=1$; so
at that $\sigma$ a public stock more durable than any swept here makes
the third channel work against the crossing. The restriction to
$\sigma=2$ is doing work and not decoration: at $\sigma=1.5$ the
boundary is above $0.070$, so the star’s own $\sigma$ arm, which holds
$\delta_G$ at the base $0.05$, already sits below it. Corollary 2 turned
that threshold into a sufficient condition for single-crossing; Theorem
5 has since removed the need for it, showing that the channel can work
against the crossing without ever overturning it, because the same
durability that strengthens the channel weakens the growth response it
acts through. The threshold survives as the exact sign boundary of
$\Omega'(g)$ and no longer as a hypothesis of anything. On the
reinvestment side the endogenous-$g$ drift is likewise negative at every
cell, worst ratio $-0.0084$ against the bound $1/i+1/(1-i)$ it would
have to overcome.

That the sign of the one-shot marginal value gives the direction of
travel of the constant-share best response agrees at $156$ of $156$
points for the split and at $165$ of $168$ for the reinvestment rate,
the three exceptions lying $0.3$–$0.4$ of a grid atom from the crossing,
where the best response is to stay and the required move is below what
the $0.005$ grid resolves. Theorem 4 has since proved the coincidence at
a start equal to the induced rest point, so what these counts now
corroborate is a proved identity — and the three exceptions are grid
resolution rather than evidence against it, which is what the proof
independently implies. The counts remain reported for these cells only.

## D.4 The benchmark separated from the rule

Distinct splits sharing a value of $\Phi$ give the same *simulated*
balanced growth: worst relative disagreement $9\times10^{-16}$ over
fifteen pairs, five of them with both splits admissible. At
$\theta=0.8,\ \tau=0.7$, both $\phi=0.624$ and $\phi=0.954$ give
$g^\ast=0.98222$, checked against the simulated three-state fixed point
rather than against (4) itself. At every cell of the sweep the
growth-maximising split $\phi_g>1$, so the balanced-growth comparison
predicts the corner at every one of them, including at
$\theta=0.8,\ \delta_G=0.05$ where the worker chooses $0.84$. Holding
$\theta=0.8$ and $\tau=0.35$, $\phi_g=1.360$ at every
$\delta_G\in\{0.05,0.20,0.50,1.00\}$ while the worker’s best response
moves from $0.768$ to the corner. The split that maximises the payoff
*at each split’s own* balanced-growth point is the corner in all twelve
cells, including the cell where the worker chooses $0.84$, because that
comparison hands the stock over already built; the gap between the two
is the transition cost.

## D.5 The $\gamma$ asymmetry, measured

Holding the base cell and sweeping $\gamma$ across $[0.30,0.70]$ —
re-solving the *whole* equilibrium at each $\gamma$ rather than
perturbing one instrument around a fixed point, with every cell screened
against the properness mask before entering the comparison and none
rejected — $\tau^\ast$ moves three tenths of one of its own $0.01$ atoms
while $i^\ast$ moves five of its own $0.005$ atoms; $r$ moves $22$ per
cent where $\Omega$ moves $0.004$ and $J$ moves $0.012$. Freezing $r$ at
its mid-sweep value while $\Omega$, $J$ and $g$ are left free leaves
$i^\ast$ moving eight tenths of an atom **in the opposite direction**,
so the movement runs through $r$. The split stays at its corner
$\phi^\ast=1$ throughout, so the corner’s own $\gamma$-inertia is
untouched by this result; what moves is the accumulation margin alone.

# Appendix E. State-contingent rules

Theorem 2’s Jacobian holds the shares fixed. Under a Markov rule the
policy response enters the linearisation and the bound is not weakened
but false. This appendix reports what a named power rule family buys in
each instrument, at each of the three constant-share equilibria, and
what it costs. Nothing here certifies a Markov-perfect object; every
number prices a named family on a printed grid against a fixed or
best-replying opponent.

The three equilibria priced here are Computation 2’s, which G.1$'$
records as not re-run under (O):
$(\tau^\ast,\phi^\ast,i^\ast) = (0.51,1,0.410)$, $(0.60,1,0.395)$ and
$(0.72,1,0.350)$. Two are the profiles Computation 1 now reports; the
second differs from its present counterpart by one grid atom in each of
$\tau$ and $i$. Where a subsection below quotes an equilibrium tax or
rate — E.2’s and E.8’s $0.51$, $0.60$ and $0.72$, E.5’s and E.7’s
$0.395$ — it is quoting one of these.

## E.1 The split: admissible but unreachable

At the illustrative cell a feedback $\phi(z)$ carries an eigenvalue out
of the unit disc at an elasticity of $2.3$. That cheap crossing is a
**fold** — a real root at $+1$, which duplicates or destroys rest points
monotonically and is not an oscillation. The genuine oscillation is the
flip, and it is dear: an elasticity of $-21.75$ at the illustrative
cell, and between $-11$ and $-13$ at the three computed equilibria.
Across the scanned range the feedback spectrum never leaves the reals,
so a Neimark–Sacker is not narrowly missed; it never becomes a
candidate.

At the equilibrium the question sharpens, because the split sits at the
corner $\phi^\ast=1$, where a power rule $\phi_a(z/z^\ast)^k$ is a share
only on a band of log-width $\ln(1/\phi_a)/|k|$, which closes as
$\phi_a\to1$. There *neither* direction is admissible unclipped: the
pro-cyclical rule leaves the unit interval above the rest point, the
counter-cyclical one below it. Clipped, which is the only admissible
form, the two are separated by which side of $z^\ast$ the economy is on.
Each of the three equilibria is computed from a start below its own
$z^\ast$, and the reduced spectrum there is real and positive ($0.93$
and $0.66$ at $\tau^\ast=0.51$), so the approach is monotone and never
overshoots. Along those paths a counter-cyclical rule is therefore never
triggered, and the flip is unreachable rather than merely expensive.

Priced over sixteen hundred rules at each of the three equilibria
against exact discounted dynastic payoffs under the two-sided mask, no
state-contingent $\phi$ beats the flat equilibrium rule, and the
direction that *acts* from a given start is invariably the one that
loses. It is already costly at the crossing itself, before any escape
has occurred; how costly is not a quotable number, running from under
three to nearly $270$ per cent of the worker’s discounted payoff across
the three cells, which begin at very different distances from their rest
points. What does not vary is where the rule goes. Steepened, it drives
$\phi$ to zero, the stock to about a quarter of $z^\ast$ ($0.233$ to
$0.251$) and the growth factor to exactly $1-\delta_G$ — the last
algebraically, since $z(g-1+\delta_G)=0$ with $z>0$ admits nothing else.
That destination is improper whenever $\beta(1-\delta_G)^{1-\sigma}>1$,
which at $\sigma=2$ is just $\delta_G>1-\beta$ and holds here. So the
fold, followed far enough, does not find a new equilibrium: it walks
into the $\phi=0$ corner Section 6 already excludes as
inadmissible-improper. A calibration with $\delta_G<1-\beta$ would not
carry that guarantee. One rule family, a fixed opponent and three cells
do not show that no state-contingent deviation is profitable, and a mild
counter-cyclical rule is worth a little from a start above $z^\ast$, at
a slope an order of magnitude too shallow to destabilise anything.

## E.2 The tax: the asymmetry is a fact about the rest point

The worker also sets the tax, and the split’s argument does not
transfer. The split sits at the top of its range, so a rule anchored on
it is not a share on one side and is clipped on the other; the tax is
interior — $0.51$, $0.60$ and $0.72$ against a bound of $0.8$ — so a
rule anchored on it is admissible on a band of positive width in *both*
directions. The tax is also a cleaner object: at the corner the worker’s
consumption share is $(1-\alpha)$, which carries no $\tau$, so
$\partial\ln
g_W/\partial\ln\tau$ vanishes at $\phi=1$ and a state-contingent tax
leaves the reproduction rate untouched, making it a pure portfolio rule
between the two stocks.

As a destabiliser it is *weaker* in the stock and stronger in capital.
At the corner the split keeps a direct grip on reproduction worth
$\gamma\theta\tau\alpha/(1-\alpha)$, while the tax reaches the stock
only through the inflow, whose share of next period’s stock is
$(g-1+\delta_G)/g$ — small precisely when the stock is durable. The flip
the split buys at $-11$ to $-13$ costs the tax $-31$ to $-47$: the
durability that makes delivery slow in Proposition 3 also insulates the
state against the tax. Made contingent on *capital* instead, the tax
folds at an elasticity below one in modulus — $-0.75$, $-0.55$, $-0.40$,
the cheapest crossing anywhere in this paper — because taxing less when
capital is abundant feeds capital directly.

The thresholds differ by instrument; the *asymmetry between them* does
not. Every threshold is a ratio: the distance from the rest point to the
relevant Jury boundary over how hard the rule pulls on that boundary.
The distances are $0.020$–$0.025$ for the fold against $3.19$–$3.23$ for
the flip, a ratio of $126$ to $159$ that is the same for all three rules
because it belongs to the rest point and not to them; the ratio of each
rule’s own two pulls is only $3$ to $21$, and varies across the three by
a factor of seven, nowhere near enough to reverse it. Cheap fold and
dear flip is therefore a fact about where this chassis puts its rest
point in Jury’s triangle, not about which of these three rules is made
state-contingent. The reinvestment rate is not among them and is not
covered.

## E.3 The orbit, and its census

At the second of the three equilibria a counter-cyclical rule anchored
at the equilibrium policy itself — $\tau^\ast$ at the equilibrium state,
elasticity $-39$ in the stock and $-2$ in capital — is clipped in a
tenth of one per cent of twelve thousand periods and not at all on the
orbit itself, keeps both problems proper, and settles on a period-two
orbit. The stock alternates between $2.7379$ and $2.7328$ indefinitely,
the class ratio sits $1.6$ per cent either side of its mean, lag-one
autocorrelation is $-1$ to six figures in both $z$ and $\nu$, and the
worker is better off by one per cent of discounted payoff than under the
constant rule. Nothing in the split’s sixteen hundred rules came near
it.

Under the exact geometric-mean criterion of C.2 the admissible
flip-crossing set at the second equilibrium is three thousand five
hundred and fifty-four of the seven thousand one hundred and eighty-nine
rules swept, and eighty-one of those run as genuine unclipped period-two
orbits, the best worth $1.06$ per cent. Such orbits exist at all three
equilibria — three hundred and forty-six, eighty-one and seven — and pay
against the flat rule at two of them, by $1.06$ and $0.80$ per cent. At
the first, nothing in the enlarged family is worth more than two and a
half basis points from a start thirteen per cent from its own rest
point, cycles included. The criterion change adds cycles to the
admissible set without changing what is chosen from it: on the same
grid, at every cell, the best rule is the same stable rule and worth the
same.

On the orbit the two reproduction indices stop equalising period by
period: $\ln(g_W/g_C)$ alternates by $\pm0.032$ where at a rest point it
vanishes to $3\times10^{-11}$, and the private gap runs between $1.82$
and $2.07$ around the $1.94$ of the equilibrium it orbits. But it
*oscillates* rather than travelling — the mean is the stationary value —
so the exit is real and narrow. Nothing here shows a cycle carrying the
wedge anywhere a rest point could not already reach. The mean is the
stationary value by identity rather than by coincidence:
$\sum\ln(g_W/g_C)$ over the two phases is $-2\times10^{-16}$ against a
per-phase gap of $0.032$.

The two-class content of the oscillation is in whose consumption it
moves, not in whose problem it renders improper. A steep
stock-contingent rule swings the *capitalist’s* consumption — the tax
enters his share and, at the corner, not the worker’s at all — so on the
low phase his growth factor dips far below the worker’s, and a test on
the minimum excludes his side of the problem and never the worker’s. A
test on the cycle average cannot, since by the identity above the two
averages are equal.

The tax fold has *two* destinations where the split’s has one, because
the tax ceiling lies above the equilibrium tax where the split’s bound
lies at it. Downward it reaches the same zero-inflow corner and the same
growth factor $1-\delta_G$, since it is the product $\phi\tau$ that
feeds the stock and either factor kills it; upward it walks to the
constant-share rest point at the tax ceiling, which is admissible and is
a point of the very class Section 6 already sweeps. Neither is an
escape.

## E.4 Nobody chooses the cycle

Across every grid and both starts the rule maximising the worker’s
payoff is stable, or — off the equilibrium path — a fold; it is never
the oscillation, and at the cells where a cycle pays, a stable rule in
the same family is worth roughly twice as much. Nor is the cycle what
the profitable rule is paid for. The payoff crosses the bifurcation
smoothly because the flip is **supercritical**: on the stable side there
is no orbit at all, amplitude at machine precision, and past the
crossing the amplitude grows from $10^{-3}$ to $10^{-2}$ as the square
root of the distance travelled, to within eight per cent. An orbit born
at zero cannot make a payoff jump. What earns the one per cent is the
rule’s shape over a long transition — leaning hard on the tax while the
stock is low — with the orbit arriving at the end of it as a by-product.
Nor is the orbit worth staying on once reached: priced from a state on
the cycle itself, where there is no transition left to collect, the
whole difference between cycling for ever and reverting to the flat rule
is two hundredths of one per cent, and its sign depends on which phase
one asks at. Allowed to choose when to stop, the worker leaves at the
high phase, and that dominates staying at both phases. Steeper is either
worse or inadmissible.

## E.5 The reply extinguishes it

Everything above holds the capitalist at his equilibrium reinvestment
rate, which is what a unilateral deviation test requires. But a
state-contingent rule is a commitment, and a commitment invites a reply.
Asked for his best constant reinvestment rate against the announced
cyclical rule, the capitalist answers $0.205$ against the equilibrium’s
$0.395$ — an interior optimum, and the same answer under either
admissibility test. At that rate the rule no longer oscillates at all:
the orbit’s amplitude falls from $9\times10^{-4}$ to machine precision,
and evaluated at that rate’s own rest point the rule’s leading
eigenvalue is real and positive — a fold — so re-anchoring it there does
not recover the cycle either. The worker’s one per cent becomes a loss
of thirty. The best of the eighty-one genuine cycles draws the same
reply and suffers the same reversal. Most of that loss is not the
oscillation but the accumulation it provokes him into withdrawing: under
the flat rule at the same reinvestment rate the worker would be worse
off by thirty-seven and a half per cent. But provoking it is the rule’s
own doing.

The same happens at the other two equilibria, each with its own reply
and anchor: the capitalist cuts from $0.41$ to $0.26$ at the first and
from $0.35$ to $0.14$ at the third, the orbit dies at both, and the
worker ends thirty-six and twenty-eight per cent below the equilibrium
he left. Each reply is interior and each is the same under either
admissibility test. The three are not quite the same statement: at the
second and third this reverses a gain, while at the first it deepens a
loss, that cell’s best cycle being unprofitable against a fixed opponent
to begin with.

Freed into the same feedback family with the level free, the
capitalist’s best reply to the worker’s cycle improves on his best
constant reply — by $0.4$, $6.6$ and $4.7$ per cent at the three cells —
and still extinguishes the orbit at every one, at machine precision and
with no clipping, leaving the worker twenty-seven to thirty-eight per
cent below the equilibrium. The confinement to a constant reply was a
scope line, not a load-bearing assumption.

## E.6 Which player owns which term

The decomposition identifies the owner. Across $i \in [0.10, 0.70]$ the
flip *margin* moves by $4.9$ per cent while the flip *threshold* moves
from $-91.5$ to $-25.0$: across that range the margin moves with the
rest point and the grip with the capitalist. The worker’s power to
destabilise the class structure is something the other class’s
accumulation grants him — and it is also what feeds him, since his own
stationary growth factor rises monotonically in that accumulation, from
$0.973$ to $1.028$ across the same range. At the rate his deviation
provokes it is $0.988$: below replacement. A counter-cyclical tax steep
enough to oscillate buys the oscillation by squeezing the flow its own
reproduction runs on. That is the funding structure of a social wage
asserting itself: the tax that pays for the worker’s reproduction is
levied on capital income, so the size of what it pays for turns on an
accumulation decision the other class makes.

Measured in the *capital* direction — where the third equilibrium’s
genuine cycles live — the same decomposition tells the same story at all
three cells. The $\tau(x)$ flip threshold falls monotonically in the
reinvestment rate, from $+33.80$ to $+17.70$ at the first equilibrium,
$+23.60$ to $+12.25$ at the second and $+14.45$ to $+7.55$ at the third,
across the same range of $i$, while the flip margin moves five per cent
or less; and at each equilibrium’s reply the best cycle’s re-anchored
leading modulus sits below one — $0.79$, $0.57$, $0.73$ — so the reply
un-crosses capital-contingent cycles exactly as it un-crosses
stock-contingent ones. One reading discipline travels with those
numbers: for a rule contingent on both stocks the on-axis threshold is
indicative only — at the first equilibrium it alone would say the cycle
survives the reply — and the re-anchored modulus of the rule itself is
what decides.

## E.7 Commitment, and joint improvement

Run on the *stable* member of the same family the computation goes the
other way. A rule that taxes capital more lightly when capital is
abundant raises the return to accumulating: the capitalist’s reply is
$0.500$ rather than $0.395$, the worker gains eleven per cent against
the equilibrium instead of the under-two he collects against a fixed
opponent, and the capitalist gains one and a half. So the constant-share
equilibrium is not Pareto-efficient in the enlarged class once the
worker can commit. Three limits go with that. The worker’s own best
commitment is *not* one of the improving rules: it costs the capitalist
four per cent, only eight of three hundred and sixty-four rules improve
both sides, and the exact-priced computation of E.8 only widens the
wedge. Commitment therefore makes a joint improvement available without
making it anyone’s choice. The follower is confined to a constant rate
in that first sweep, and the tax level is held at $\tau^\ast$. And none
of it is a Markov perfect equilibrium.

The capitalist’s side mirrors that, and the improvement there is larger.
His own commitment family holds fifty-four jointly improving rules at
the first equilibrium and nine at the second, none at the third, all
counted against a worker held fixed. Put to the worker’s best reply,
forty of the fifty-four and seven of the nine survive as joint
improvements, and every survivor rests: no clipping, a class ratio
constant to four decimals, an amplitude at machine zero. The best is
worth twenty-three per cent to the capitalist and three and a half to
the worker, and it earns that by changing what the worker wants — he
answers by cutting his tax from a half to under two-fifths. His own best
rule against a fixed worker is again not among them: the reply turns its
three hundredths of a per cent into a loss of twenty-six. On his side
the joint improvement is a region rather than a knife-edge — the eight
grid neighbours of that rule are jointly improving too, and the joint
gain survives the follower being given a five times finer instrument.
Two things are not established. Where his optimum against a *replying*
worker lies: these rules were selected against a fixed one, so
twenty-three per cent is a floor under his leader value and locates
nothing. And how *common* joint improvement is in his family: the
fifty-four were counted against a fixed worker, so they are not the
with-reply census that the worker’s
eight-of-three-hundred-and-sixty-four is, and the two proportions are
not comparable.

Handed the mirror family — reinvestment as a power rule in the two
stocks, $i=\mathrm{clip}(i^\ast(x/\bar x)^{m_x}(z/\bar z)^{m_z})$,
anchored at each cell’s own rate and put through the same admissibility
and genuineness tests, on grids extended until every reported maximum is
interior — the capitalist declines the oscillation more decisively than
the worker does. His payoff-maximising rule is stable at every cell, a
small-sloped rule worth $+0.03$, $+0.34$ and $+1.52$ per cent against
the flat rate. Where the worker’s family contains genuine profitable
cycles at two of three equilibria, the census of his returns none that
pays: seven hundred to a little over a thousand genuine orbits per cell
pass the filter, and the best of them *loses*, by $0.4$, $10.5$ and
$8.0$ per cent. That is a census on printed grids and not a proof that
his family holds none. His commitment *to his fixed-worker optimum*
fares no better than the worker’s did: against that rule the worker’s
constant-class reply is a higher tax at every cell — $0.58$, $0.63$ and
$0.76$ against $0.51$, $0.60$ and $0.72$ — and at the first equilibrium
also a withdrawal of the split from the corner to $0.79$; the reply
turns his $+0.03$, $+0.34$ and $+1.52$ per cent into $-25.9$, $-9.6$ and
$-17.8$. At the first the reply leaves the worker *above* the
equilibrium he left; at the other two it leaves both classes below it.
Commitment to a rule optimised against a passive opponent is punished on
whichever side announces it. That is where the parallel ends: his family
priced *at* the reply settles on a stable joint improvement at every
cell, so the punishment is a fact about fixed-opponent optima, not about
his commitment as such.

## E.8 The leader problem, closed

Freeing the tax level alone — a constant tax chosen anticipating the
constant reply — is worth almost nothing: six tenths of a per cent at
the first equilibrium, four hundredths at the second, three tenths at
the third, on a Stackelberg top as flat as the Nash tax’s own. Nor does
it move one way. The leader sets the tax below the equilibrium’s at the
first two cells and above it at the third, in each case in whichever
direction provokes accumulation, since the reply to the chosen level
sits above the equilibrium rate at all three cells and the reply’s
direction in the tax is not monotone. The mechanism is an envelope: at
the corner split the tax never enters the worker’s own consumption, so
at an interior Nash tax his own first-order margin is already zero and
the leader’s entire gradient is the reply channel.

Freed jointly with both slopes, commitment becomes an extraction device.
The exact-priced optima are worth $+34.3$, $+17.3$ and $+15.1$ per cent
to the worker against $-2169$, $-26$ and $-17$ to the capitalist —
nowhere near a joint improvement — and the level’s own contribution is
seventeen points at the first equilibrium and a point or less at the
other two. At the first the rule is coercive: a pro-cyclical tax steep
enough that every reinvestment rate from five to ninety-five per cent is
improper for *both* dynasties, so the follower’s finite-payoff replies
sit at the top of his strategy space; the worker takes a third above the
equilibrium and the capitalist’s dynasty passes through twenty-eight per
cent of its status-quo size before resuming proper growth. At the second
and third the optimum is interior and stable: at the third the announced
$0.550$ levies two-thirds at its own rest, the tax never approaches its
ceiling, the class ratio is constant and the re-anchored modulus is
$0.75$. The leader’s optimum therefore **rests at each of the three
equilibria priced here**, and what he never chooses at any of them is a
genuine oscillation — a handful of genuine cycles enter the first two
equilibria’s shortlists, and none is the arg max at any of the three.
Outside this beam-priced search nothing is claimed.

Closing that search needed a correction to the method, and the
correction is worth stating because it bears on how much any shortlist
result is worth. Exact-pricing the top $N$ rules by their mask value is
a **beam search**: it keeps the best few nodes by a heuristic and
carries no optimality guarantee. What the claim needs is the pruning
rule of branch and bound — discard a rule only when a bound on its value
cannot beat the best rule already priced — and that requires the bound
to be a genuine one. The mask is not. It is *equal* to the exact gain
whenever the follower’s reply does not move, but when his reply does
move the worker’s payoff can go either way, because it is not monotone
in the follower’s reinvestment rate. Most such corrections are downward
and large — the mask overstates by up to twenty points on clipped paths,
which is why a mask-ranked shortlist fills with clip-riders whose prices
then collapse and a correctly priced stable rule sits below the cut —
but one rule at the second equilibrium corrects *upward* by a quarter of
a point, which is enough to disqualify the mask as a bound.

The search is therefore closed the standard way instead, with a quantity
that is a bound: the worker’s best payoff over those replies the
follower prefers at least as much as the one the mask picks, with every
rule whose bound could beat the incumbent then priced exactly. All three
grids close under it. At the first two equilibria the bound prunes every
rule on the grid; at the third the sixty-three that survive are priced
and none beats. The bound is checked, not assumed, against every rule
whose exact value was already known — a hundred and sixty of them,
including the one that broke the mask. What this buys beyond the third
equilibrium’s own figure is that the first two, which were safe only
because their optima happened to sit above every mask value on their
grids, are now closed searches rather than lucky ones. At the third the
earlier shortlist left $13.8$ points between the best exact gain and the
highest mask value on the grid, and the result was hiding in that
window.

Two reporting conventions follow. With slopes this steep the announced
level is not the outcome: the tax the optimum actually levies at its own
rest differs from the anchor parameter by up to forty points — at the
first equilibrium an announced quarter becomes two-thirds — so both
numbers are reported wherever either is. And every headline is priced at
the follower’s exact-criterion reply rather than at his mask reply,
because at the third cell the mask reply was $0.715$ where the exact
reply is $0.35$, and re-pricing at the reply the follower actually
prefers cost that headline nearly fourteen points. Put to the
capitalist’s best *feedback* reply, his own family with the level free,
the leader’s gains become $+34.3$, $+12.2$ and $+13.3$ per cent: the
follower claims back twelve to fifteen per cent of his own payoff and
reverses nothing. The leader is not re-optimised against the feedback
follower; $\phi$ is held at the corner; the family is the named power
family on printed grids; and none of this is a Markov perfect
equilibrium.

## E.9 Credibility, and one comparison running the other way

A commitment result invites the objection that a rule its author would
want to abandon once the other player has moved is not a credible
commitment. It does not bite here, because the two resolutions agree.
*With* commitment, the reply guts the cycle. *Without* it — the
simultaneous configuration, each player facing the other’s equilibrium
share — the payoff-maximising rule in the enlarged family is stable at
every cell. The oscillation is declined under either reading of the game
and in either class’s family; what depends on the reading is only the
size of the margin by which it is declined.

One check runs the other way. The worker’s own tax response to an
inherited stock, measured at these equilibria, is $-0.12$ to $-0.17$: a
larger stock is met with a lighter tax. That is the flip’s direction at
a hundredth of its slope, and the opposite sign to the fold’s. It is
indicative rather than decisive, because it is the best *constant* tax
given a start, not the elasticity of a feedback rule along a path. Nor
is any of this in tension with the feedback computation of C.3: that
policy sits at the corner across most of the grid, and where it is
interior enough for an elasticity to be defined its measured
$|\mathrm{d}\ln\phi/\mathrm{d}\ln z|$ is of order one, an order of
magnitude short of what a flip would need — again indicative rather than
decisive, since the imposed rule moves one instrument and the computed
policy moves three.

# Appendix F. Form robustness

## F.1 The fiscal asymmetry does not need Cobb–Douglas

Carrying an *arbitrary* composite $h$ with $g_W=B\,h^{\gamma}$ and
writing $s_c,s_z$ for its logarithmic shares: $\gamma$ factors out of
the split bracket and out of its root, so the stationary split is
$\gamma$-free for any $h$, and the Cobb–Douglas shares return (7)
identically. Meanwhile $\gamma$ survives in $\mathcal{M}$ additively for
the same arbitrary $h$: the $\ln N_W$ row contributes
$1-\tilde\beta\big(1-\gamma(s_c\alpha+s_z)\big)$ and the two feedback
groups of (B.7) carry $\gamma$ as a factor besides, so $\mathcal{M}$ is
affine in $\gamma$ about the $\gamma$-free intercept $1-\tilde\beta$. So
$r$ — and hence (12) — cannot shed it. Both a CES composite and a
subsistence floor $(c_W-\bar c)$ are instantiated and both keep $\gamma$
a common factor on the worker’s side, with the CES shares
state-dependent and Cobb–Douglas recovered as the $\rho\to0$ limit. What
the Cobb–Douglas form buys is the closed form, not the asymmetry.

## F.2 The invariance survives the outer map, not only the composite

Writing $g_W=F(h)$ for an arbitrary increasing $F$: the split’s marginal
value is $\varepsilon_F$ times a bracket containing no $F$, so the sign
— and hence the crossing — is invariant to the entire outer map, which
needs no assumption that the composite’s shares are constant. A
saturating map $F=h^{\gamma}/(1+h^{\gamma})$ is instantiated: its
elasticity is state-dependent *and* carries $\gamma$, and the root is
unchanged. The boundary is separability, not isoelasticity — with
$\gamma$ attached to consumption alone the root retains it, and
returning it to both arguments cancels it again. Two scope notes: the
invariance is at a given balanced-growth point and given the composite’s
shares, the indirect channel through $g$ being the one Proposition 3
treats separately; and at full saturation $\varepsilon_F\to0$ the
asymmetry degenerates because no reproduction elasticity is left to
carry it.

## F.3 Reproduction against production

The placement comparison is minimal and is not a re-solution of an
alternative equilibrium. The two split roots share a *shape*, so the
split alone identifies only the ratio of channel elasticities. What
separates the placements is that the reproduction map’s ratio factors
into a share the fiscal rule sees and an outer scale it cannot, while a
production placement’s output elasticity does not factor and the fiscal
rule does see it.

## F.4 The stability exclusion does not need Cobb–Douglas either

Re-running the spectrum over a CES composite under a saturating outer
map, at states drawn anywhere in the orthant rather than only at rest
points, leaves Theorem 2’s exclusion standing. The argument uses only
that the output elasticity is below one, that $a,c\in(0,1)$, and that
the reproduction map’s elasticities sum to less than one. Relaxing
$\gamma$ above one makes a Jury margin go negative, with the critical
value bisected at $\gamma\approx2.22$ for this paper’s own shares.

# Appendix G. Replication

## G.1 What is proved and what is computed

**The weight $\omega$ of Assumption 3, first, because it scopes several
statements below.** Every result in the paper is proved for all
$\omega\in[0,1)$, with no exception. Theorem 6 was the last one to carry
a restriction to $\omega=0$ and no longer does; what its proof needs
above the baseline weight is one substitution,
$\mathcal{Q}=(1-\omega)+J\zeta$ for $1+\alpha J$, together with the
weight $\tilde\upsilon$ that $\varepsilon_\Lambda$ actually carries.
Proposition 5(i) is the statement *about* the excluded endpoint and is
proved by two independent routes — the envelope of (B.6), whose cost
term vanishes identically there, and Proposition 14’s order-preserving
argument, which reaches the capitalist precisely once his own
consumption leaves his payoff. The results that are objective-free
altogether, holding whatever either class maximises, are Lemma 1,
Proposition 2 and Theorem 1: the first names no Assumption at all, and
the other two turn on the stationarity identity and the reproduction
technology rather than on any payoff. The state reduction of Proposition
A.1 is objective-free in a weaker and more useful sense — it needs each
class’s felicity to be homogeneous of *some* degree in the levels, which
a power is and a specification such as $\ln(1+K)$ is not, and it needs
no common curvature across classes. The body takes $\sigma_W=\sigma_C$
for readability and Appendix B keeps the indices.

Propositions 1, 2, 3(i) and 5, Lemma 1 and Theorems 1–2 follow from
Assumptions 1–4, with three additions carried in the results’ own
hypotheses and nowhere left to inference: Theorem 2(ii) adds $i\in(0,1)$
and $\phi\tau>0$; Theorems 1 and 2 and Proposition 3 require
$\theta\in(0,1)$, which is stricter than Assumption 2’s
$\theta\in(0,1]$; and Proposition 5 fixes $a_K>0$ and $\varphi>0$, its
part (ii) adding a constant-share rest point with $D_x\neq0$, which is
what makes $J$ and hence $\Lambda$ defined; Lemma 1$'$ needs less still
— its level-set statement holds for an arbitrary reproduction map at any
interior stationary class ratio, and its bound on the index gap adds
only that the map be non-decreasing, without which no bound follows.
Lemma 1$''$ weakens a *different* hypothesis, and the two are not
comparable: it keeps Lemma 1’s strictly increasing $F$, and instead lets
the worker’s index be an arbitrary $h(c_W,z)$, non-decreasing in private
consumption and strictly increasing in the public stock. No
differentiability, no concavity, no continuity and no functional form
enters, and neither $\gamma$ nor $B$ appears in the statement or the
proof; the displacement is an order property of the stationarity locus,
and Theorem 1 is its Cobb–Douglas case. So the three trade along
different axes: Lemma 1$'$ weakens the reproduction map and buys a
*capped* index gap in place of equality, while Lemma 1$''$ keeps the map
and weakens the index, and buys a *strict* displacement. Proposition
1$'$ sits outside the constant-share class the rest of the paper works
in, and its hypotheses say so: Assumptions 1–2 with $\theta\in(0,1)$, a
fixed $\tau>0$ and $i$, and a split that is a *differentiable* Markov
rule in $z$ alone — differentiability being what makes the elasticity it
characterises an object at all, so the characterisation is within that
class and not within all measurable rules. Its parts (i)–(ii) are proved
there outright. Its part (iii) carries one scope clause that is easy to
lose and is stated in the result itself: the bound on the suppressed
log-growth variation is uniform on any parameter set with
$\alpha\le\bar\alpha<1$ and $\tau\le\bar\tau$, and is **not** uniform on
the open set $\alpha\in(0,1)$, where it grows like $\ln[1/(1-\alpha)]$.
Proposition 2(iii)’s durable half asks less than its own statement
declares in the same way: it divides the public stock’s law of motion by
$N_{W,t+1}$ and carries both reproduction factors as symbols, so
$g_C=g_W=1-\delta_G$ holds for arbitrary maps and for both classes at
once, Assumption 2 entering only the full-depreciation half, where what
is asked of it is not its form but that the composite vanish when the
public input does. Appendix A, which proves the state reduction rather
than importing it, uses Assumptions 1–3 together with admissibility as
Assumption 5 defines it; that is the assumption set of Proposition A.1
and of Corollary A.1, whose second clause turns on the form (O) that
Assumption 3 already fixes and adds nothing above it. Its Lemmas A.1 and
A.2 — the homogeneity of the primitive map and of its iterates — need
less still, turning on constant returns and constant shares alone.
Proposition 4 needs Assumptions 1–4 with $\theta\in(0,1)$ and
$D_x\neq0$, so that $J$ is defined, its parts (i)–(ii) being algebraic
identities that need nothing further. Propositions 3(ii)–(iii), 4(iii),
Corollary 1 and Lemmas B.1 and B.2 add the properness condition
$\tilde\beta<1$ of Assumption 5 — for Lemma B.2 it is the capitalist’s
own clause $\tilde\beta_C<1$ — which is what puts the transition wedge
in $(0,1)$ and is stated in their hypotheses. Proposition 6 needs
Assumptions 1–4 with $\theta\in(0,1)$ and constant shares with $i>0$,
$\phi\tau>0$ and $\tau<1$ — the hypotheses other results cite as
*Proposition 6’s own*, and without the first two of which
$g(\tau,\phi,i)$ is not defined — and nothing else, its part (iii) being
an equivalence rather than a hypothesis; Proposition 7 adds properness,
as Proposition 3 does. Theorem 3 needs Assumptions 1–4 with
$\theta\in(0,1)$ and $\bar\tau<1$, together with condition (E), which is
an explicit inequality in the primitives and is carried in its
hypotheses, not assumed silently: the theorem is unconditional given
(E), and (E) is verified at the reported cells by Computation 3 and
fails at others. Proposition 8, which characterises that condition
rather than assuming it, needs Assumptions 1–4 with $\theta\in(0,1)$ and
$\bar\tau<1$ and nothing further. Its reduction of $A$ and $B$ to the
single index $S$, and its lower bound on $\Phi$, are analytic; the
thresholds Section 8 reads off it — the floor $B>0.4972$ and the
interval in $\bar\tau$ — are located by minimisation and bisection on
$\Phi$ at those cells and are computations. Proposition 9 is an identity
and needs Assumptions 1–4 with properness. Theorem 4 needs Assumptions
1–4 with $\theta\in(0,1)$, admissibility at an interior rest point, and
the local stability of Theorem 2(iii), which is what licenses the
termwise differentiation of Appendix A.4, and it is stated at a start
equal to the induced rest point and at no other; from a transitional
start the linearised coefficients move with $t$ and the summation does
not close. Corollary 2’s criterion is proved, and its sufficient
condition $\Omega'(g)\le0$ is superseded: Theorem 5 proves the split’s
single-crossing on the whole proper region with no condition on
$\Omega'$ at all, so nothing in the paper now depends on where that sign
holds. Theorem 5 needs Assumptions 1–4 with properness and Proposition
6’s hypotheses — $i>0$, $\tau\in(0,1)$, $\phi\in(0,1]$ — and no more; in
particular it does not rest on Theorem 4, which supplies the separate
step from the scalar map to the deviator’s true payoff. It covers the
split and no other instrument.

The primed extensions of Theorem 2 and of Propositions 5 and 6 carry
their own hypotheses and are listed here because the paragraphs above do
not reach them. Theorem 2$'$ takes Assumptions 1–4 with the shares
fixed, $i\in(0,1)$, $\phi\tau>0$ and $\theta\in(0,1]$ — one endpoint
wider than Theorem 2, because its part (i) is an identity at the rest
point rather than a spectral statement, and the $\theta=1$ case is what
recovers Proposition 2(ii). Its part (i) is analytic and exact, and the
cancellation of $x^\ast$ from it is algebraic, not a limit. Its part
(ii) is a partial derivative in $i$ holding $\tau$, $\phi$ and the
primitives fixed: like Proposition 5$'$ it is a statement about its own
closed form, (N$'''$), and not a comparative static in the primitives.
Its part (iii) is signed analytically at $\theta=1$ and, at $\theta<1$,
refutes constancy of sign by exhibiting admissible witnesses of both
signs — a refutation, which a sample can deliver, and not a cover. **The
two quantifiers are kept apart in the statement itself because they are
different propositions.** What is refuted is uniformity of sign
**within** a cell: the witnesses share their entire primitive vector and
differ only in $i$. What is **not** claimed, and is undischarged, is
that every $\theta<1$ cell contains a sign change; no such claim is made
anywhere in the paper. Its one further universal — that the growth
factor is driven to $1-\min(\delta,\delta_G)$ as $i\to0$ at every
reproduction scale — is carried by an argument on $H$ and not by the
sweep that prompted it, $B$ entering $H$ only as a finite additive
constant. **Its part (iv) carries a weaker hypothesis than the rest of
the theorem and is listed separately for that reason: it does not use
Assumption 2’s outer map.** The corner closed form follows from
Assumption 1’s budget and Lemma 1’s hypothesis — a common strictly
increasing map, arbitrary otherwise — through Proposition 2(i)’s (N), so
no reproduction primitive enters the resulting expression and the
invariance is a statement about Lemma 1 rather than about the
Cobb–Douglas composite. Assumption 2 is not dispensed with entirely and
the statement does not claim otherwise: $\theta$ is defined there, so
naming the corner needs it. What the corner does not need is the form of
the outer map. Reading the result off (N$'''$) instead is the same
statement on a stronger hypothesis, and both routes are given. Part (iv)
is analytic throughout except for one witness: the three instrument
signs follow from $\kappa_W\ge1-\alpha>0$; the reversal of the split’s
sign between $\theta=1$ and $\theta<1$ pairs a proved value at the
corner with a single computed value at the reported cell, holding $\phi$
and every primitive fixed so that $\theta$ is the only difference. The
tax is left **undischarged** there by name — a five-point grid found no
sign change, which refutes nothing and establishes nothing. Proposition
5$'$ needs Assumptions 1–4 with $\omega<1$ at a constant-share rest
point where $J$ and $\Omega$ are defined; it is a comparative static in
$\rho$ holding $(J,\Omega,\zeta,\omega)$ fixed, which makes it a
statement about (12) rather than about a rest point’s response to a
primitive. Proposition 5$''$ adds admissibility in Assumption 5’s sense,
$\tilde\beta<1$ — which is what signs the two objects its proof uses —
and holds $g$ fixed. Proposition 5$'''$ takes that assumption set at
$\omega\in[0,1)$ and names properness in its hypotheses rather than
leaving it to its proof, because it is load-bearing three times over;
its part (i) is at $\omega=0$ alone and buys a closed form, its part
(iii) holds at every weight and buys the sign, and where they overlap
the sign is the same. Proposition 6$'$ needs Assumptions 1–5 with
$\theta\in(0,1)$ and $\omega<1$, at the corner $\phi=1$ with $i$
interior, together with one point-hypothesis no other result in the
paper carries: that $g$ be a point at which the constrained tax
$\min\{\tau^\ast,\bar\tau\}$ is differentiable, which excludes the
switch and nothing else. Proposition 6$''$ inherits all of that and adds
tax interiority, which is why its part (iv) is a statement about the
interior branch alone; the ceiling branch is Proposition 6$'$(iv)’s
corollary, and under $(\ddagger)$ the two together cover every fixed
point. Its parts (iv) and (v) are proved on an interval rather than at a
fixed point, and the interval’s endpoints are stated with them. The
reduction of the ceiling margin that §8.1 runs on that interval — the
two-term bracket and the sharpening that replaces $(\ddagger)$ by
$\Omega'\le0$ — is proved at every $\omega\in[0,1)$, by the same
substitution $\mathcal{Q}=(1-\omega)+J\zeta$ for $1+\alpha J$ that
Theorem 6 uses, together with
$\mathcal{N}_\omega=\zeta\mathcal{M}+\alpha\tilde\beta\gamma(1-\alpha)\big[\theta+(1-\theta)\Omega\big]\mathcal{Q}$
in place of Proposition 5$'''$(i)’s $\alpha N$. The interval subdivision
that closes $63$ of the $216$ cells on that reduction is a computation,
not a step in it, and is run at $\omega=0$. Proposition 6$'''$ stands on
Proposition 6$''$’s hypotheses exactly, tax interiority included, and
adds none of its own: its parts (i)–(ii) are identities in $g$,
$\tilde\beta$ and the primitives, and its parts (iii)–(iv) draw on the
$\Omega$ half of $(\ddagger)$ alone, through $\mathcal{B}\ge0$ and
nowhere else. It holds at every $\omega\in[0,1)$, since $\mathcal{B}$
enters it exactly as it enters $\Phi'$ and no other object in it carries
the weight; the sufficient condition on the falling side that follows it
is stated at $\omega=0$, and says so. The lattice of $243{,}756$ points
measuring how far its three lines reach past the two standing conditions
is likewise a measurement of the result and not a step in it.
Proposition 6$''''$ adds nothing to those hypotheses either: its part
(i) is a regrouping, and its parts (ii)–(iv) use both halves of
$(\ddagger)$ — the public half through $\mathcal{B}\ge0$ as before, the
capital half to sign $M_J$ — together with $(\sharp)$, which is a
restriction on $\alpha$, $\theta$ and $\sigma$ and on nothing else. It
holds at every $\omega\in[0,1)$: the weight enters only through
$\mathcal{B}$, and the bound used there is the smaller of that term’s
two endpoint values in $\omega$. Its part (iii) is the one place in §8.1
where a hypothesis is *removed* rather than added: it drops
$\mathcal{U}\ge0$ from **both** of Proposition 6$''$’s conclusions, so
on the band the interval subdivision those parts need is not part of the
argument at all. Its part (v) weakens $(\sharp)$ to one of its two
halves at each point, selected by the sign of $\mathcal{O}$, and adds no
hypothesis to do it; the two witnesses exhibiting points in the
difference measure that inclusion and are not steps in it. None of the
seven is cited by any of Theorems 1–6: they extend Propositions 5 and 6,
and only §§7–8 use them.

Propositions 10 and 11 are identities exhibiting criteria rather than
bounds, on Assumptions 1–4 with $\theta\in(0,1)$ and properness,
Proposition 11’s parts (iii)–(iv) adding Proposition 6’s own hypotheses
because they differentiate the growth factor; Proposition 10’s
inequality is proved by Theorem 6 at every weight and Proposition 11’s
is not proved at any. Theorem 6 needs Assumptions 1–4 with properness
and Proposition 10’s hypotheses, and covers the rate and no other
instrument. It carries no restriction on $\omega$. The weight enters its
proof in three places and nowhere else — the workforce relation
$r\mathcal{M}=\tilde\beta(1-\alpha)\gamma\mathcal{Q}$ of (B.7), the
level of $\Lambda$, and the weight
$\tilde\upsilon=\alpha\Upsilon/(\zeta+\alpha\Upsilon)$ inside
$\varepsilon_\Lambda$, which equals $\upsilon$ at $\omega=0$ and is
strictly smaller above it. $\mathcal{M}$ itself is $\omega$-free, which
is what makes the extension a substitution rather than a re-derivation,
and the residual becomes $(\mathcal{Q}+\omega)$ where the baseline has
$1+\alpha J$ — strictly larger, which is why the inequality slackens.
Independently of the proof, (28) is verified at $61{,}440$ proper cells
at each of $\omega=0.25$ and $\omega=0.50$, with the minimum of $N$
rising in $\omega$; that is a computation, establishes nothing beyond
the cells it visits, and is now corroboration rather than the only
evidence above zero. Step 5’s use of $\varepsilon_\Omega\le\mu$ needs no
hypothesis beyond properness: (22)’s closed form is an identity in $g$
rather than a consequence of standing at a zero of the split margin, and
$\mu-\varepsilon_\Omega=\sigma g^{\sigma}/\big(g^{\sigma}-\beta(1-\delta_G)\big)$,
whose denominator is positive under exactly Proposition 3(i)’s
condition. The theorem is therefore free of the split’s first-order
condition, which it never had any business carrying. Proposition 12
needs Assumptions 1–4 with $\theta\in(0,1)$ and properness, and adds
$\delta\neq\delta_G$ and one further primitive inequality per pole,
without which that pole cannot be approached from inside the proper
region; it fixes each loop gain’s limit and says nothing about the
direction of approach. Theorem 7 needs Assumptions 1–3 and properness
for convergence and nothing else — it is a convexity argument and uses
no differentiability at all — but it is conditional, and Computation 9
refutes its hypothesis as a universal. Proposition 13’s parts (i), (ii),
(iv) and (v) need Assumptions 1–4 with $\theta\in(0,1]$ and $\tau>0$ —
without which the split moves neither the consumption share nor the
public inflow and part (i)’s strictness fails — part (iii) adding
properness and Proposition 6’s hypotheses; part (v) is a proved negative
**about the $(\tau,\phi)$ parameterisation only**, and Proposition 15
exhibits coordinates in which the same date is concave. Proposition 14
and Corollary 3 need Assumptions 1–3 with $\theta\in(0,1)$, a fixed
start and properness along the path, and their derivative statements
carry in addition a uniform-in-$u$ bound on the per-date share
elasticities — which A.4 does *not* supply, since A.4 differentiates in
the state and its domination is local. Corollary 3’s sufficient
condition is not proved. Lemma 2 is a standard fact about logarithms of
positive affine functions and carries no model content. Proposition 15
needs Assumptions 1–3 with $\theta\in(0,1)$ and a fixed start with
$x_0,z_0>0$ and a rate $i>0$, its part (i) using admissibility
(Assumption 5) to discard the collapsed edge and its parts (iv)–(v)
adding Proposition 6’s hypotheses; it proves no concavity of the payoff,
establishing instead that Proposition 13(v)’s obstruction is
coordinate-dependent, that the two free dates survive jointly, and that
the tail criterion generalises to $(\ast\ast)$ — which **implies**
$(\ast)$, so the joint route is strictly the harder one. Proposition
15$'$ takes Proposition 15’s hypotheses and adds Assumption 4, which
enters through its Step 1 alone, where $(\mathrm{A})$ is what puts
$\mu_K,\mu\ge1$ and so signs $\mathcal{G}''$; nothing else in it uses
$\gamma$, the level of $g$, or how $\mu_K$ and $\mu$ were reached, which
is why its condition reads only $(\alpha,\theta,\tau,\phi)$. Both of its
clauses are proved: the sufficient condition $\Phi\le\Phi_c$ for
$(\ast\ast)$, and the sharpness clause that above every exterior point
there are admissible $(\gamma,\delta,\delta_G,\beta,\sigma,i,A,B)$ at
which $(\ast\ast)$ fails — so no larger parameter-free region in those
coordinates, of any shape, certifies the criterion. That second clause
is what sends the residue into the other coordinates rather than leaving
it as slack in the bound. Corollary 4 needs Theorem 4’s hypotheses with
$\theta\in(0,1)$, evaluated from the rest point the profile induces, and
is conditional in addition on joint concavity of $\ln N_{W,t}$ on $T$,
which is proved nowhere. What Computation 11 supplies is narrower than
the hypothesis in two ways worth stating here rather than leaving to
inference: it checks the per-date Hessian at the ten profiles of C.9 and
the Hessian of $\widetilde V_W$ on an $11\times11$ grid at three of
them, and those cells are Computation 11’s own, not the cells at which
Computation 1 reports its equilibria; and the grid is a sub-box of $T$,
so it samples the set the hypothesis quantifies over and can refute it
but never establish it. Proposition 16 and Corollary 5 need Assumptions
1–3 and 5 with $\theta\in(0,1)$, $x_0,z_0>0$, $i>0$ and
$\delta=\delta_G=1$; they discharge that hypothesis outright on that
face and on no wider set, Computation 1’s cells not lying on it. Part
(iv) of Proposition 13 proves the vacuity of $(\ast)$ there and *not*
its date-wise clause, which does not follow from $\mathcal{G}''=0$ and
is Proposition 16’s.

Everything else — the equilibrium levels, every sweep verdict, every
priced deviation and every count — is computational. These establish
what holds at the cells computed and nothing beyond them.

What is not proved in the body is labelled wherever it appears:
quasi-concavity of the discounted payoff in the deviating share, which
is what turns a zero of a margin into a best reply. Theorem 5
establishes it for the fiscal split and Theorem 6 for the reinvestment
rate, both on the proper region and without a side condition. It is not
established for the tax, where the same construction yields an
inequality that has to be checked rather than one that holds by
construction, because the tax enters the capitalist’s investable base
$1-\tau$ and reaches both stock flows where the other two instruments
reach one apiece; for that instrument the evidence is the cells of C.8
and nothing wider. And for the worker it remains a joint condition in
the pair rather than two separate ones, which no single-instrument
result reaches. That condition is now *reached* — Section 8.7 writes his
instruments as the three coefficients they act through, in which they
are affine on a convex triangle, so Theorem 7 applies to the pair and
Corollary 4 closes his clause conditionally — but it is not *proved* in
general, its hypothesis being the joint form of the one the split
already needed. It is proved on one face. At $\delta=\delta_G=1$ the
stock numerators become monomials in the state, the date-wise recursion
collapses under a rank-one matrix, and Proposition 16 exhibits the
coefficients and signs them, so Corollary 5 closes the worker’s clause
with nothing assumed. The face is a corner of Assumption 1’s
depreciation rectangle, not a neighbourhood of the computed cells, and
the obstruction to widening it is structural: restore the survival terms
and the logarithm the argument needs affine becomes a log-sum-exp, which
is convex. The step that used to stand beside it — the move from the
sign of a one-shot marginal value to the direction of travel of the
constant-share best response — is Theorem 4 and is no longer measured.

## G.1$'$ Which computations were re-run under the present objective, and which were not

The capitalist’s objective changed after the computational work of this
paper was first done, and not every Computation was re-run. Which were
is a fact a replicator needs and is set out here rather than left to
inference.

**Re-run under (O), from the primitive laws:** Computation 1, including
the corner sweep, the $\gamma$-asymmetry and the envelope-deletion
control; Computation 3, including the self-consistent fixed point and
the wedges at it; Computation 8, on a grid of $61{,}440$ proper cells;
and Computation 12, whose subject changed from $\ln N_{C,t}$ to
$\ln P_t$ and which is therefore a new measurement rather than a
repetition. Proposition 10’s loop-gain sweep was re-run with it.

**Two of those re-runs changed more than the objective, and a replicator
needs both facts.** The corner sweep was re-run on a *different grid* —
the star design of D.1, which adds $\theta\in\{0.40,0.70\}$ and
$\sigma=1.5$ and drops $\theta=0.3$ — so its counts are not comparable
term by term with the earlier ones, and the twelve-cell counts that
survive in C.8 and D.3–D.4 belong to the earlier grid. And Computation 3
was re-run **at the base cell only**, at $\omega=0$ and $\omega=0.5$;
the cell-by-cell self-consistent version behind D.3 was not repeated.
Neither gap changes a verdict anywhere in the paper, both being
agreements rather than results, but neither is evidence under (O)
either.

**Not re-run:** Computations 2, 4, 5, 6, 7, 10 and 11, and the worker
half of Computation 9. All but one have a **worker-side or
technological** subject — the Jacobian of $(\star)$ and its
bifurcations, the split’s loop gain, the tax margin, the fixed-start
factorisation, the pair in product coordinates — and by Corollary A.1
the worker’s block never saw the capitalist’s payoff. The exception is
Computation 6, whose first grid prices the *rate* criterion and so is
not worker-side — its second grid, the tax bracket of Proposition 11(i),
is. It stands on two grounds of its own instead. It enumerates the
region its criteria range over rather than sampling from a solved
equilibrium, so no equilibrium profile enters it as an input; and the
inequality that grid corroborates is Proposition 10’s, which Theorem 6
now proves at every weight, so what the grid was evidence *for* no
longer rests on it. What the change of objective can move in the others
is not their subject but the *cell* at which they are evaluated, since
there the equilibrium profile is an input. At $\omega=0$ that profile
moves at one of the three starts, and there by one grid atom in each of
$\tau$ and $i$ (Computation 1), so the reported values are expected to
be stable to the precision at which they are quoted; **that expectation
is not a measurement, and it is not offered as one.** At $\omega>0$ the
profile moves materially and these computations should be regarded as
unverified there, with one exception: Computation 11’s stencil was
re-run at the self-consistent profiles at $\omega=0$ **and** at
$\omega=0.50$, and Section 8.7 reports both.

**One computation lost half its subject.** Computation 9’s capitalist
clause measured the curvature of $\ln N_{C,t}$ in the rate. Under (O)
that object is not what his clause needs, and the figures are withdrawn
rather than relabelled; Computation 12 supplies the replacement, on an
interval of rates rather than at a point, which is what Theorem 7
actually asks for and what Computation 9 never provided even before the
change.

## G.2 Symbolic certification

The closed-form algebra — the elasticities of Proposition 1, the wedge
forms of Theorem 1, the crossings of Propositions 3 and 5, the explicit
solutions (7), (9) and (12), and the Jacobian, determinant and three
Jury margins of Theorem 2 — is certified symbolically on a declared
bounded domain. Most checks are symbolic identities, for which a
numerical evaluation would add nothing. Those carrying an independent
numerical cross-check are the interior rest point and the reported
derivative $\partial x'/\partial z$ of Proposition 1, the unique root of
$H$ in Theorem 2(ii), and the three Jury margins of Theorem 2(iii) over
two hundred thousand random draws from the declared domain. Each
margin’s sign is reported, not only its magnitude. The envelope
derivations of Appendix B are certified separately and cross-checked
against an independent arrangement, so that a shared error would have to
survive two routes.

The existence results carry their own certificate. It verifies the
separation identity of Proposition 6 and the equality of $\mathcal{H}'$
with Theorem 2(ii)’s $H'$; the three divergences of $\mathcal{P}$ at the
lower faces, on a domain where every complement is carried as a positive
symbol so that no sign is taken on inspection; the four uniform bounds
on the wedges that properness delivers, each as an identity with a
manifestly signed remainder rather than as an inequality asserted; the
collapse of (B.7) to (B.7$''$), re-derived rather than restated; the
three signed terms and the two limits of Proposition 7(i), together with
its monotonicity in the split and the recovery of (9) at the corner;
and, at the reported cells, condition (E) and the fixed point. The fixed
point is then checked by an independent route that uses none of the
closed forms above: the rest point is rebuilt from the primitive laws
and $(\star)$ is stepped forward once, which leaves the state and both
growth factors unmoved to machine precision. Four controls are run to
establish that the checks can fail — the wedge bound fails on the
improper band, and (E) fails once the reproduction scale or the
instrument ceiling is small enough.

Step 1 of the theorem’s proof asserts three regularity properties, and
those are probed rather than taken on the page. $\Gamma_\star$ is
evaluated at a thousand points of the instrument box, faces and corners
included: at all thousand it is defined and lands in the box, off its
three lower faces. It lands *strictly* inside in the rate alone — the
upper truncations at $\bar\tau$ and at $\phi=1$ are attainable, and the
second is attained at this paper’s own corner fixed point — and that the
map sends the box into itself at all is Step 1’s argument from those
truncations, not a reading off the grid. The truncation is checked to be
*identically* $g_\star$ near each lower face rather than merely so in
the limit. And the largest discrete slope along three fine slices, one
per instrument, is under four, which is what continuity with no jump
looks like on a grid. The probe earned its place: it caught the one
point where the implementation and the stated map disagreed, at
$\tau=0$, where (7) diverges and the convention $\phi^\dagger=+\infty$
is what makes the second coordinate continuous.

Section 8.4 carries a certificate of its own, and its structure is the
same: prove by substitution, then check against a route sharing no step.
The two resolvent identities of Proposition 9 are verified as rational
identities; the solution of the linearised system is verified by
substituting it back into the system rather than by asking a solver to
find it; the master identity (20) is verified with the three direct
log-impacts left as free symbols, so that it holds for any instrument
and not only the three used; and the capitalist’s $\Lambda$ obtained
from the class-ratio sum is compared against (12) built from (B.7),
which is where the third envelope of B.8 is independently confirmed. The
numerical route simulates $(\star)$ and differences the discounted
payoff, writing down no marginal value, no wedge and no first-order
condition; across four cells and three instruments it agrees with
(17)–(18) to a worst relative discrepancy of $6\times10^{-8}$.

Six controls establish that these checks can fail, and one of them did
before it was understood. The identity is asserted only under
properness, and at $\delta_G=0.50$ with $B=1.0$ the profile has
$\tilde\beta=1.023$: there the discounted sums diverge while the closed
form returns a finite number, which is Assumption 5 failing rather than
the theorem. On an unmasked grid in $\phi$ the split’s margin appears to
change sign twice at $\theta=0.80$; the second crossing is $\Omega$
passing through its pole at $\tilde\beta=1$, and it disappears once the
improper points are removed. Proposition 3(i)’s catalogue of the
improper side is doing work in both places rather than sitting as a
caveat.

Theorem 5 carries a third certificate. Its symbolic part clears
$g^{\sigma-1}$ from (6), derives
$\varepsilon_\Omega=\mu(1-\sigma\Omega/\tilde\beta)$ and confirms that
the resulting sign expression is the one already in the text; it
rebuilds Corollary 2’s display by differentiating the composed map from
scratch; and it verifies (23) as an exact identity on a common
denominator, then checks each summand of the numerator separately, so
that the single place properness is load-bearing is visible as one line
rather than buried in a simplification. The numerical part shares no
step with any of that: it obtains $g$ by bisection on
$\mathcal{H}(g)=\mathcal{P}$, builds $\Psi$ from it, counts sign changes
on a masked grid, and takes a central finite difference of the composed
map at the crossing. Three controls fire. A profile with $\tilde\beta>1$
but Assumption 4 intact drives the numerator of (23) negative and the
loop gain to $1.05$, so properness is shown to be load-bearing rather
than decorative. At $\delta_G=0.02$ the assertion $\Omega'(g)\le0$ is
checked and found false, so the two statements are not being conflated.
And the improper cell of Computation 4 is re-checked and excluded. An
earlier version of the first control did not fire: it paired
$\Omega=1.4$ with $\tilde\beta=0.9$, a combination Proposition 3(i)
forbids, and it tested one summand of the numerator rather than the
numerator. Both defects are recorded in the script.

Section 8.7 carries a fourth certificate, and its division of labour is
the sharpest of the four because the symbolic and numerical parts answer
different questions. The symbolic part *establishes*: the
reparameterisation identity of (35); Proposition 13(v)’s determinant,
reproduced exactly and then signed for every $\alpha\le\frac12$ and
every $\phi\le1$ by writing $\alpha=1/(2+n)$ and $\phi=1/(1+w)$ with $n$
and $w$ nonnegative, so that the two endpoints the paper actually uses —
the half share and its own corner — are inside the signed region rather
than beside it, with a control confirming that the strictness is lost at
one corner only, $\tau=1$ with $\phi=0$ and $\alpha=\tfrac12$, which
$\bar\tau<1$ excludes; the rank-one negative semidefiniteness of the
same object in $(\tau,\varpi)$; Lemma 2, verified for a generic affine
$L$ and then instantiated at $\ell_0$, $\ell_1$ and $\mathcal{P}$, in
each case by checking that every $L_k$ is affine and positive, that
every weight is nonnegative, and — for strictness — that the gradients
span, which is a rank test rather than a determinant expansion; the
closed form (38); $\mathcal{G}'>0$ and $\mathcal{G}''\le0$ in their
manifest forms; the two-variable chain rule for $\nabla^{2}\ln g$, all
three entries; the matrix determinant lemma that turns joint concavity
into $(\ast\ast)$; the reduction of $(\ast\ast)$ to $(\ast)$ in the
split direction, with the cross-multiplication shown sign-safe rather
than assumed so; and the identity
$p^{\top}\!A^{-1}p-p_2^{2}/A_{22}=(A_{22}p_1-A_{12}p_2)^{2}/(A_{22}\det A)$
that makes the joint criterion the harder one. Signs are resolved by
writing each bounded primitive as a rational function of strictly
positive free symbols, so that a sign query either resolves mechanically
or returns nothing; two controls confirm that a genuinely indeterminate
sign — including $\alpha$ against $\frac12$, which the model leaves open
— does return nothing, since a sign test that always answers proves
nothing.

The numerical part *refutes or fails to refute*, and its own control is
what makes it readable. The same nine-point stencil is run in both
coordinate systems at the same points: in $(\tau,\phi)$ it returns a
largest eigenvalue between $0.70$ and $0.94$ of the matrix norm — the
saddle Proposition 13(v) predicts — and in $(\tau,\varpi)$ at most
$1.8\times10^{-7}$. Without that control the second number would be an
assertion about arithmetic rather than about the model. The residual is
then identified rather than excused: it falls at $u=0$, the one date
where Proposition 15(ii)–(iii) proves the determinant is exactly zero,
and tripling the differencing step multiplies it by $8.97$ to $9.04$,
which is $O(h^{2})$ truncation and not a violation. Two of the paper’s
own quoted figures were re-derived from an independent closed form in
the course of this and one of them moved: the value
$+6.766177\times10^{-3}$ reproduces at $\phi=0.6894$ to nine figures and
not at the $\phi=0.689$ an earlier draft printed, which is a
transcription of the cell rather than of the number.

Proposition 16 carries a fifth certificate, and it is the one whose
symbolic half is closed over *dates* rather than over a list of them.
The induction is proved at symbolic $t$: the closed form (39)–(40) is
substituted into recursion (30), the substitution
$\chi^{t-1}\mapsto\chi^{t}$ is applied, and the two sides are shown
equal — so no finite number of dates is being mistaken for all of them.
That check is where the script’s first run failed, and the failure was
the finding: the identity holds only because the geometric partial sum
$\Sigma_t$ and $\chi^{t-1}$ are tied by $\Sigma_t(1-\chi)=1-\chi^{t-1}$,
and carrying them as independent symbols breaks it. Both versions are
kept as controls, the second alongside a deliberately perturbed closed
form, so the step test is one that demonstrably fails. The signs are
then reduced to the single inequality $1-\alpha+m\chi^{k}>0$ and
resolved on the declared domain, with a control confirming that the sign
of $m-\alpha$ itself — which the model leaves open, and on which the
whole difficulty turns — does *not* resolve.

Its numerical half is a control on the algebra rather than evidence for
it. The closed form is compared against a path built from the primitive
laws at eighteen full-depreciation cells and agrees to a worst relative
$1.1\times10^{-14}$ over two hundred dates; run off that face, at
$\delta=\delta_G\in\{0.99,0.90,0.50,0.08\}$, the same comparison misses
by at least $9.4\times10^{-2}$, which is what makes the first number a
verification. The nonnegativity of (40) is swept as an implementation
check and not as evidence, Proposition 16 having proved it, and the
sweep is paired with a positive control in which $m$ is pushed above one
and a coefficient duly goes negative. The capitalist’s interval sweep of
Computation 12 carries its own positive control: pointed at Computation
9’s counterexample it is required to return $t=1190$ as the first convex
date of $\ln N_{W,t}$, and does, which is that computation’s headline
figure reproduced by a route that shares none of its code.

The claim that Theorem 3’s fixed point is the same object the grid
computation reaches is checked separately and directly, because the two
procedures share no step: the grid maximises exact discounted path
payoffs over the share grid and writes down no marginal value, while
$\Gamma$ evaluates three marginal values and simulates no path. Compared
at the self-consistent equilibrium — the object Theorem 3 delivers, not
the declared starts of Computation 1 — they agree to seven hundredths of
a grid atom in the tax and the reinvestment rate, exactly at the corner
in the split, and to $4\times10^{-5}$ in the growth factor.

## G.3 Code and data

All numerical results are produced by a single replication package,
available from the author. It contains the constant-share kernel, the
feedback corroboration kernel, the sweep drivers, the state-contingent
rule pricers of Appendix E, the robustness comparisons of Appendix F,
the date-wise curvature audit of C.9 with its refutation hunt and its
closed-form cross-check, the joint-coordinate certificate behind Section
8.7 — symbolic and numerical in one script, with its controls — the
certificate behind Proposition 15$'$, which proves the $\rho$ bound as a
polynomial identity on abstract symbols and then evaluates the condition
over the admissible grid, reporting both the cells it certifies and the
fact that no cell violating $(\ast\ast)$ lies inside the region, the
direct verification of Definition 1’s two clauses at the self-consistent
profiles by global comparison of the discounted payoffs over the whole
instrument set rather than through a curvature criterion, with its
horizon and start controls, the full-depreciation certificate behind
Proposition 16 and Computation 12, likewise one script carrying its
symbolic induction, its off-face control and its two positive controls,
and the symbolic certificates of G.2, together with the exact grids,
horizons, starts and seeds used for every number reported here. One
convention there is worth stating, because every path-dependent date in
C.9 and Computation 11 turns on it: Definition 1 declares the
*incumbent’s* rest point as the start, and at the counterexample cell
the incumbent split is the corner, so a deviation to $\phi=0.6894$ is
evaluated from the rest point $\phi=1$ induces and not from its own.
Starting from its own instead leaves $(\ast)$, $(\ast\ast)$ and the
growth factor untouched, all three being rest-point objects, and moves
the dates: of the two checked, the cumulated breach runs $1190\to1193$
and the date-wise one $87\to85$. Those two were checked and the rest
were not, so the convention is recorded rather than the shift being
characterised. The package uses no proprietary software and no external
data. One notational difference is worth flagging to a reader moving
between the paper and the package: the transition wedge is $\Omega$ in
the paper and carries an earlier symbol in the numerical kernels, which
are left as they ran so that every published figure remains reproducible
from the code that produced it.

The components named above are files, and naming them here is what lets
a referee check that the inventory and the package agree. The
constant-share kernel is `bprime_constant_share_nash.py` and the
feedback corroboration is the grid solve `bprime_mpe_solve.py`; the two
triangulate, and neither is evidence for the other. The sweep drivers
are `bprime_csn_sweep.py`, which solves every cell from one common
start, and `bprime_stationary_sweep.py`, which solves each as a
self-consistent stationary equilibrium — the distinction of D.2.
Appendix E’s rule pricers are `bprime_tau_state_contingent.py`,
`bprime_tau_orbit_valuation.py`, which prices the orbit from the orbit
rather than from a distant start, `bprime_capitalist_feedback.py` for
his own feedback class, `bprime_capitalist_leader_reply.py` for E.8, and
`bprime_pareto_reply_verify.py` for E.7. Appendix F’s comparisons are
`bprime_gamma_form_robustness.py` for the composite and
`bprime_placement_discriminator.py` for the outer map. C.9 is
`curvature_datewise_concavity_2026_08_06_fa90bbe3.py` with its
refutation hunt `curvature_refutation_hunt_2026_08_06_fa90bbe3.py` and
its closed form `curvature_closed_form_lng_2026_08_06_fa90bbe3.py`;
Section 8.7’s joint-coordinate certificate is
`joint_tau_varpi_concavity_2026_08_06_691659cf.py` and the
full-depreciation one is
`full_depreciation_joint_concavity_2026_08_06_024e5ae1.py`. The symbolic
certification of G.2 is carried by `bprime_theorem_proofs_symbolic.py`,
`bprime_envelope_derivations_symbolic.py`,
`bprime_mpe_symbolic_checks.py` and
`bprime_homogeneity_appendix_checks.py`, with the existence results in
`existence_stationary_profile_2026_08_04.py` and the two-route agreement
of Theorem 3 with the grid in `existence_gridcheck_2026_08_04.py`. The
recomputations G.1$'$ lists under (O) are
`constant_share_nash_new_objective_2026_08_07_a22e7cc1.py`,
`computation1_support_sweeps_new_objective_2026_08_07_a22e7cc1.py`,
`computations_3_and_12_new_objective_2026_08_07_a22e7cc1.py` and
`rate_criterion_sweeps_new_objective_2026_08_07_a22e7cc1.py`; a reader
checking G.1$'$ against the package should find nothing else there.
Computation 6’s three grids are
`rate_margin_loop_gain_2026_08_04_142f8925.py`,
`tax_margin_corner_loop_gain_2026_08_04_142f8925.py` and
`tax_margin_every_split_2026_08_04_142f8925.py`, and its $\sigma=12$
cell is in `computation6_sigma_scope_witness_2026_08_11_da3fd552.py`,
which reads the three grid definitions out of those drivers rather than
restating them, so that an edit to any grid breaks the certificate
instead of silently outdating the text. The two profiles at which both
clauses of Definition 1 are checked together are certified by
`definition1_joint_at_self_consistent_profile_2026_08_11_543e1dba.py`,
which reads both out of the Computation 3 artifact rather than retyping
them, reproduces a banked row of the Section 8.7 certificate before
extending it, and carries as its control the same stencil in
$(\tau,\phi)$, where the verdict is required to fail.

# References

- Barro, R. J. (1990). “Government Spending in a Simple Model of
  Endogenous Growth.” *Journal of Political Economy* 98(5, Part 2):
  S103–S125.
- Futagami, K., Y. Morita, and A. Shibata (1993). “Dynamic Analysis of
  an Endogenous Growth Model with Public Capital.” *Scandinavian Journal
  of Economics* 95(4): 607–625.
- Huato, J. (2005). “Inequality and Growth: A Two-Player Dynamic Game
  with Production and Appropriation.” Working paper (arXiv:2304.01855).
- Lancaster, K. (1973). “The Dynamic Inefficiency of Capitalism.”
  *Journal of Political Economy* 81(5): 1092–1109.
- Long, N. V., and K. Shimomura (1998). “Some Results on the Markov
  Equilibria of a Class of Homogeneous Differential Games.” *Journal of
  Economic Behavior & Organization* 33(3–4): 557–566.
