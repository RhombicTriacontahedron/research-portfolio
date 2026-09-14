# The Margin a Tax Cannot Reach
Carlos Galindo Escajeda
2026-09-01

# Abstract

An economy accumulates two stocks out of one period’s output. Capital is owned, and its owner decides how
much of his net income to reinvest. The workforce is produced from worker consumption and a public input,
and no agent may hold a claim on it. Set a benevolent planner who levies a capital-income tax and splits
the proceeds against an agent who chooses the period’s allocation outright. On a tractable face — one
period a generation, full depreciation, logarithmic objectives — the two choose the *same* tax and the
*same* split, and differ in one coordinate. A logarithmic owner reinvests a fixed share $i^{*}$ of his net
income whatever the tax (Straub and Werning 2020, §2.2), while the Pareto-optimal division at weight
$\lambda$ on the worker is $i(\lambda)=w_K/(w_C+w_K)$, which exceeds $i^{*}$ for every $\lambda>0$ and
equals it at $\lambda=0$. The planner’s shortfall is exactly
$(w_C+w_K)\,D_{\mathrm{KL}}\!\left(i(\lambda)\,\|\,i^{*}\right)$. The separation does not come from the
unownable stock: the fiscal instruments reach that stock’s accumulation margin in full, and both classes
want the same amount spent on it. It comes from the ownable stock, and it is zero exactly when the state
places no weight on labour. Nor does closing it require a state that holds capital. What fails is any
instrument levied on a base the owner’s consumption and reinvestment share; a subsidy to reinvestment paid
out of the take, holding no capital, attains the agent’s allocation at every interior weight.

# 1. Introduction

A state that both taxes capital and holds it is usually read one of two ways: as a planner correcting a
market failure, or as a claimant taking a cut. Whether there is a third reading turns on a single
question, and the question is the burden this paper sets itself. If a benevolent planner who sets the same
tax and the same spending split, holding no capital, attains whatever a capital-holding state attains,
then nothing here is new — the claim has collapsed into the fifty-year-old proposition that a cooperative
solution improves on a non-cooperative one (Lancaster 1973). The result below is that he does not attain
it, that the whole of the shortfall is one coordinate, and that the coordinate is not the one the obvious
argument points at.

**Baselines, because the counterfactual decides the meaning and the answer changes sign across them.**
Five objects are compared in what follows, and every comparison names which.

-   **B0, the non-cooperative benchmark.** The worker class holds the fiscal instruments and the owner
    holds the reinvestment decision. This is *not* capitalism; it is labour-controlled fiscal policy inside
    a capitalist economy.
-   **B1, a small fiscal state:** $\tau \to 0$ at the same split. This is what “pure capitalism” means here,
    and it means nothing else.
-   **B2, the benevolent planner.** Pareto weight $\lambda$ on the worker; instruments $(\tau,\varphi)$;
    holds no capital; the private owner still chooses his own reinvestment rate.
-   **B3, a state that also holds capital**, investing a share $\psi$ of the tax take in capital while the
    private owner chooses his own reinvestment in response.
-   **B4, the relaxation**: an agent who sets the period’s four output shares directly, subject to the
    no-labour-tax bound $s_W \ge 1-\alpha$ of Section 2. B4 is an upper bound on what any capital-holding
    arrangement could attain, which is why it is the right thing to test a planner against.

Theorem 1 is **B2 against B4**, and so are Propositions 1–4. Section 7 reports B3 against B4, and a
planner who also subsidises reinvestment against B4; neither is a proposition of this paper. Remark 2 is
the only statement made against B1. Against B0 a mediating state moves the tax
*down* and leaves workers *worse* off; against B1 it moves the tax *up*. Same theorem, opposite answer —
which is why no reader should be left to supply the baseline himself.

**What the paper contributes.** That a logarithmic owner’s saving share does not move with a
capital-income tax is not new: Straub and Werning (2020, §2.2) state it for a two-class economy of this
kind, and show that a planner who must save through the owners of capital faces a wedge as a result. This
paper adds the comparison with an agent who also sets the owner’s division, on a face where that
comparison closes. First, the planner’s reachable set is a codimension-one slice of the allocation set,
and its normal is the owner’s consumption–investment margin (Proposition 2). Second, the failure cannot
be traded against anything. The objective is additively separable across that direction, so no
second-best retuning of the tax partly substitutes for the missing instrument, and the planner’s tax and
split are the ones he would have chosen with the instrument in hand (Proposition 3). Third, the shortfall
has a closed form: a Kullback–Leibler divergence between the division the state wants and the division the
owner chooses, zero exactly when the state is the owner’s agent (Theorem 1). Fourth, the missing
instrument is not ownership. The instruments that fail are those levied on a base the owner’s consumption
and reinvestment share; a subsidy to reinvestment, with no holding, reaches the relaxation at every
interior weight (Sections 6 and 7).

**And the obvious mechanism is wrong**, which is worth saying plainly because it is the mechanism this
argument seems to call for. One would expect the separation to come from the stock nobody may own: a
private owner prices capital through his own accumulation decision, nothing prices the workforce, and an
agent holding both would face both margins at once. Proposition 4 refutes that reading of this economy.
Switch the public input out of both classes’ payoffs entirely and the separation is unchanged; both
classes want the same amount spent on the workforce, so there is no conflict on that margin to resolve;
and the owner’s own value function prices the workforce strictly positively — it is untradeable, not
unpriced. The separating margin is the *ownable* stock.

Section 2 sets out the economy. Section 3 establishes what the planner can reach, Section 4 what he
cannot and by how much, Section 5 which margin does the separating, Section 6 what the result is not and
which instruments do reach the margin, and Section 7 what a capital-holding state does and what is not
settled.

# 2. The economy

Two classes, two produced stocks, and one period a generation.

**Technology.** Output is $Y_t = K_t^{\alpha} N_t^{1-\alpha}$, with $\alpha \in (0,1)$ capital’s share and
$N_t$ the workforce. Three stocks are carried: capital $K$, the workforce $N$, and a public stock $G$.
Capital and the public stock depreciate fully within the period, so each is simply the previous period’s
provision,
$$K_{t+1} \;=\; i_t\,(1-\tau_t)\,\alpha Y_t , \qquad G_{t+1} \;=\; \varphi_t\,\tau_t\,\alpha Y_t ,$$
while the workforce is produced from worker consumption and the inherited public stock supplied per
worker, $z_t \equiv G_t/N_t$:
$$N_{t+1} \;=\; A\; N_t^{\,1-\gamma\theta}\; C_{W,t}^{\,\gamma\theta}\; z_t^{\,\gamma(1-\theta)} ,
\qquad \gamma \in (0,1),\;\; \theta \in (0,1] . \tag{R}$$
Reproduction has total elasticity $\gamma$ in the two produced inputs, divided $\gamma\theta$ to worker
consumption and $\gamma(1-\theta)$ to the public stock; the workforce’s own carry-over is the residual, so
(R) is homogeneous of degree one and $N$ persists with net elasticity $1-\gamma$. The polar case
$\theta=1$, in which the public stock drops out of reproduction altogether, is used in Section 5 and
nowhere else.

**Instruments and shares.** A capital-income tax $\tau$ is levied on $\alpha Y$; a share $\varphi$ of the
take funds the public input and the remainder is paid to workers. The owner reinvests a share $i$ of his
net capital income. The period’s output therefore divides into four shares,
$$s_C = (1-i)(1-\tau)\alpha, \quad s_K = i(1-\tau)\alpha, \quad
s_W = (1-\alpha)+(1-\varphi)\tau\alpha, \quad s_G = \varphi\tau\alpha , \tag{S}$$
for owner consumption, capital accumulation, worker consumption and the public input. They sum to one
identically, so the allocation set lies in the three-simplex. There is no labour tax, so worker
consumption never falls below labour’s share: $s_W \ge 1-\alpha$, with equality when the whole take funds
the public input, $\varphi=1$.

**Preferences.** The worker maximises $\sum_t \beta^t \ln N_t$: his objective is the reproduction of his
class, and consumption enters only as an input to it. The owner maximises
$\sum_t \beta^t\!\left[(1-\omega)\ln C_{C,t} + \omega \ln K_t\right]$, with $\omega \in [0,1)$ — the
logarithmic case of a felicity over the composite $C_C^{1-\omega}K^{\omega}$. Both discount at
$\beta \in (0,1)$.

**The face, and what is taken from elsewhere.** On this face each class’s value function is affine in
$(\ln K, \ln N, \ln G)$ and each class’s policy is a constant share containing no state and no instrument
of the other class, so the economy closes in dominant strategies rather than in a game; in logarithms it
is a linear-state game, and the degeneracy is the known property of a named class rather than a feature
of this economy (Dockner, Jørgensen, Long and Sorger 2000, §7.2–§7.3). Write the owner’s coefficients
$(a,b,c)$ and the worker’s $(p,q,r)$ for
$(\ln K, \ln N, \ln G)$ respectively. They solve
$$\begin{aligned}
a &= (1-\omega)\alpha + \omega + \beta\!\left(a\alpha + b\gamma\theta\alpha + c\alpha\right), &
p &= \beta\!\left(p\alpha + q\gamma\theta\alpha + r\alpha\right), \\
b &= (1-\omega)(1-\alpha) + \beta\!\left(a(1-\alpha) + b(1-D) + c(1-\alpha)\right), &
q &= 1 + \beta\!\left(p(1-\alpha) + q(1-D) + r(1-\alpha)\right), \\
c &= \beta\, b\, \gamma(1-\theta), & r &= \beta\, q\, \gamma(1-\theta),
\end{aligned} \tag{C}$$
with $D \equiv \gamma(1-\theta)+\gamma\theta\alpha$. Writing $Q \equiv 1-\alpha\beta+\beta\gamma(1-\theta+\alpha\theta)$
and $\Delta \equiv (1-\beta)Q$, the closed forms are
$$p = \frac{\alpha\beta\gamma\,(\theta+\beta(1-\theta))}{\Delta}, \quad
b = \frac{(1-\alpha)\,(1-\omega(1-\beta))}{\Delta}, \quad
c = \frac{\beta\gamma(1-\alpha)(1-\theta)(1-\omega(1-\beta))}{\Delta}, \quad
r = \frac{\beta\gamma(1-\theta)(1-\alpha\beta)}{\Delta},$$
each strictly positive on $(0,1)^4\times[0,1)$ for $\theta<1$, and $a$ is pinned by the identity
$a(1-\alpha\beta) = (1-\omega)\alpha+\omega+\alpha\beta(b\gamma\theta+c) > 0$.

*Attribution.* The face, the affine value functions, the dominant-strategy closure, the coefficient system
(C) and its closed forms are established in companion work on this economy (Galindo Escajeda 2026, at
its baseline $\gamma_K=1$) and are used here without re-derivation; so are the two classes’ preferred
taxes $\tau_C$ and $\tau_W$, the fact that both classes prefer the *same* split $\varphi(\tau)$ (its
Proposition 7), the Pareto interval $[\tau_C,\tau_W]$, and the weighted tax $\tau(\lambda)$ of Remark 1
(its Proposition 8). Propositions 1–4 and Theorem 1 are this paper’s own; the invariance of a logarithmic
owner’s saving share that Proposition 2 uses is not (Straub and Werning 2020, §2.2).

*So what.* The economy has three instruments’ worth of freedom in the allocation — the tax, the split and
the reinvestment rate — and a fiscal authority owns two of them. Everything below is about the third.

# 3. What a planner can reach

Fix a Pareto weight $\lambda \in [0,1]$ on the worker and write
$$w_C = (1-\lambda)(1-\omega), \quad
w_K = \beta\!\left(\lambda p + (1-\lambda)a\right), \quad
w_W = \beta\gamma\theta\!\left(\lambda q + (1-\lambda)b\right), \quad
w_G = \beta\!\left(\lambda r + (1-\lambda)c\right).$$

**Proposition 1 (the objective is Cobb–Douglas in the shares).** *Up to terms containing no instrument,
the $\lambda$-weighted objective is*
$$W \;=\; w_C \ln s_C + w_K \ln s_K + w_W \ln s_W + w_G \ln s_G . \tag{1}$$
*For $\theta<1$ all four weights are strictly positive on $\lambda \in (0,1)$. Two degeneracies occur at
the boundary of the declared domain and both are used below: $w_C=0$ at $\lambda=1$, and $w_G=0$ at
$\theta=1$, where the public stock leaves both classes’ payoffs.*

*Proof.* Substituting (S) into each class’s Bellman right-hand side and collecting, the owner’s
instrument-dependent block is $(1-\omega)\ln s_C + \beta a \ln s_K + \beta b \gamma\theta \ln s_W + \beta c \ln s_G$
and the worker’s is $\beta p \ln s_K + \beta q \gamma\theta \ln s_W + \beta r \ln s_G$; every remaining term
is a function of the inherited state alone, since $\ln Y$ enters both classes’ continuations with
coefficients free of $(\tau,\varphi,i)$. Taking the $\lambda$-weighted sum gives (1) with the stated
weights. Positivity follows from $b,c,p,q,r>0$ and $a>0$. $\square$

**Proposition 2 (the planner’s reachable set is a codimension-one slice).** *The map
$(\tau,\varphi,i)\mapsto(s_C,s_K,s_W,s_G)$ has rank three, and the map $(\tau,\varphi)\mapsto s$ has rank
two. The direction the planner loses is*
$$\frac{\partial s}{\partial i} \;=\; (1-\tau)\alpha\,(-1,\,+1,\,0,\,0) ,$$
*owner consumption moved into capital, touching neither worker consumption nor the public input.
Moreover the privately chosen rate*
$$i^{*} \;=\; \frac{\beta a}{(1-\omega)+\beta a}$$
*contains neither $\tau$ nor $\varphi$, so B2’s reachable set is exactly the slice
$\{\,s_K/(s_C+s_K) = i^{*}\,\}$ and no fiscal instrument moves off it.*

*Proof.* The Jacobian ranks are immediate from (S). For $i^{*}$: of the owner’s four instrument terms
only the first two contain $i$, so taking $(\tau,\varphi)$ as given he maximises
$f(i) = (1-\omega)\ln s_C + \beta a \ln s_K$ with $s_C=(1-i)(1-\tau)\alpha$ and $s_K=i(1-\tau)\alpha$. The
factor $(1-\tau)\alpha$ is common to both logarithms and so drops from the first-order condition
$-(1-\omega)/(1-i) + \beta a / i = 0$, whose unique root in $(0,1)$ is $i^{*}$. That root is the maximum
and not merely a stationary point: $f''(i) = -(1-\omega)/(1-i)^2 - \beta a/i^2 < 0$ on $(0,1)$, since
$\omega<1$ and $a>0$, so $f$ is strictly concave there and $f\to-\infty$ at both endpoints. The
coefficient $a$ solves (C), which contains no instrument. $\square$

**Proposition 3 (no second-best retuning exists).** *Write $\Sigma \equiv s_C+s_K = (1-\tau)\alpha$. Then*
$$w_C \ln s_C + w_K \ln s_K \;=\; (w_C+w_K)\ln \Sigma \;+\; \left[\,w_C \ln(1-i) + w_K \ln i\,\right] ,$$
*so $\partial^2 W/\partial i\,\partial\tau = \partial^2 W/\partial i\,\partial\varphi = 0$ identically, at
every $\lambda$. The outer problem in $(\tau,\varphi)$ is therefore the same whether the division $i$ is
free or pinned: B2 and B4 choose the **same** tax and the **same** split, and the entire difference
between them is the one coordinate of Proposition 2.*

*Proof.* By Proposition 1 the objective is $\sum_j w_j \ln s_j$, so only the $s_C$ and $s_K$ terms carry
$i$. Substitute $s_C=(1-i)\Sigma$, $s_K=i\Sigma$ and expand the logarithms; the first bracket contains
no $i$ and the second no $(\tau,\varphi)$. The value of the inner problem in $i$ at fixed $\Sigma$ thus
differs between free and pinned $i$ by a constant in $\Sigma$, so the two outer problems have identical
first-order conditions. $\square$

**Remark 1 (what that common tax is).** At the provision corner $\varphi=1$ the no-labour-tax constraint
binds with equality and the common tax is $\tau(\lambda) = w_G/(w_C+w_K+w_G)$, which rises with $\lambda$
across exactly $[\tau_C,\tau_W]$, with $\tau(0)=\tau_C>0$ for $\theta<1$ and $\tau(1)=\tau_W$. This is
Proposition 8 of Galindo Escajeda (2026) and is not re-derived here; it is quoted because it makes the force of
Proposition 3 concrete. The kill test the paper set itself asked whether a planner *constrained* to the
same tax and split falls short. Proposition 3 answers a stronger question: he is not constrained, and he
falls short anyway.

*So what.* The comparison economists would reach for — hold the fiscal instruments fixed and ask what
ownership adds — is not a handicap imposed on the planner. It is what he does.

# 4. The separation, and its size

**Theorem 1.** *Fix $\lambda \in [0,1]$.*

*(i) The Pareto-optimal division of the owner’s net income is $i(\lambda) = w_K/(w_C+w_K)$.*

*(ii) $i(\lambda) > i^{*}$ for every $\lambda \in (0,1]$, and $i(0) = i^{*}$ exactly.*

*(iii) The planner’s shortfall against B4 is*
$$\Delta(\lambda) \;=\; (w_C+w_K)\; D_{\mathrm{KL}}\!\left(i(\lambda)\,\middle\|\,i^{*}\right)
\;=\; (w_C+w_K)\left[\,i(\lambda)\ln\frac{i(\lambda)}{i^{*}} + (1-i(\lambda))\ln\frac{1-i(\lambda)}{1-i^{*}}\right] ,$$
*which is strictly positive for $\lambda \in (0,1]$ and zero at $\lambda = 0$. At the corner $\lambda=1$
the second term is $0\cdot\ln 0$ and is read under the usual convention $0\ln 0 = 0$; with that reading
$\Delta$ is continuous there, its value coinciding with $\lim_{\lambda\to1^-}\Delta(\lambda)$.*

*Proof.* (i) By Propositions 1 and 3 the inner problem is $\max_i\, w_K \ln i + w_C \ln(1-i)$, strictly concave
with $f''(i) = -w_K/i^2 - w_C/(1-i)^2 < 0$, whose stationary point is $w_K/(w_C+w_K)$. At $\lambda=1$,
$w_C=0$ and the objective $w_K \ln i$ is increasing, so the maximiser is the corner $i=1$, which the share
formula also returns.

1.  Clear the difference over the positive denominators $(w_C+w_K)$ and $(1-\omega)+\beta a$:
    $$w_K\!\left[(1-\omega)+\beta a\right] - \beta a\,(w_C+w_K)
    = \beta(1-\omega)\!\left[\lambda p + (1-\lambda)a - (1-\lambda)a\right]
    = \beta(1-\omega)\,\lambda\, p .$$
    The cleared gap is a monomial. Since $\beta>0$, $\omega<1$ and $p>0$, it is strictly positive exactly when
    $\lambda>0$ and zero exactly when $\lambda=0$.

2.  Write $S = w_C+w_K$ and $x = i(\lambda)$, so that $w_K = Sx$ and $w_C = S(1-x)$. Then
    $$\Delta(\lambda) = \left[w_K \ln x + w_C \ln(1-x)\right] - \left[w_K \ln i^{*} + w_C \ln(1-i^{*})\right]
    = S\!\left[x\ln\frac{x}{i^{*}} + (1-x)\ln\frac{1-x}{1-i^{*}}\right],$$
    which is $S$ times a Kullback–Leibler divergence and so is non-negative, vanishing only at $x=i^{*}$. By

3.  that happens only at $\lambda=0$. At $\lambda=1$ the divergence degenerates: $x=1$, so its second
    term is $0\ln 0 = 0$ and the first is $-\ln i^{*} > 0$, giving $\Delta(1) = -w_K \ln i^{*}$ since
    $S=w_K$ there. This is the continuous extension, not a separate case — the direct expression
    $w_K\ln x + w_C\ln(1-x)$ is indeterminate at $x=1$, while its limit as $\lambda\to1^-$ exists and equals
    $-w_K\ln i^{*}$. $\square$

Three readings of the same statement are worth separating.

**The mechanism.** Logarithmic preferences make the owner’s saving share a constant (Straub and Werning
2020, §2.2). A tax changes how
much net income he has; it does not change what fraction of it he consumes. The planner’s two instruments
therefore move the *size* of the owner’s net capital income and never its *division*, and the division is
what the Pareto optimum wants moved.

**The size.** The shortfall is a relative-entropy distance between two Bernoulli divisions — the one the
state wants and the one the market supplies. That is not an accident of the functional form so much as
its content: the objective is a weighted sum of logarithms of shares, and the gap between a
log-score maximiser’s optimum and any other point on the simplex is exactly a divergence.

**The comparative static, and it is the one that matters.** $\Delta(0)=0$, and the cleared gap in (ii)
is $\beta(1-\omega)\lambda p$. A state that is the owner’s agent needs no instrument the planner lacks; the
separation is *zero exactly when the state places no weight on labour*, and the division the state wants
rises strictly with that weight, since $(w_C+w_K)^2\,di(\lambda)/d\lambda = \beta(1-\omega)p > 0$. The
shortfall itself is not proportional to $\lambda$, and no monotonicity of $\Delta$ is claimed. So the
contribution is not that state ownership does something. It is that a state which weights labour at all
wants a division that no tax on the owner’s income can reach.

**Remark 2 (the only claim made against B1).** Against a small fiscal state, $\tau \to 0$, both classes’
payoffs are strictly concave in the tax with $\operatorname{sign}(\partial U_j/\partial\tau) = \operatorname{sign}(\tau_j - \tau)$,
so every $\tau$ below $\tau_C$ is Pareto-dominated and the Pareto set in the tax is exactly
$[\tau_C,\tau_W]$. This is companion work, restated because it fixes what “pure capitalism” can and
cannot mean here. It says nothing about B0, where the ranking reverses.

# 5. Which margin separates

The reading this result invites is that the state spans two stocks where a private owner spans one. On
this economy that reading is false, and it is worth killing precisely because it is the natural one.

**Proposition 4.** *(i) Set $\theta=1$, so that the public input vanishes from reproduction and
$c = r = 0$: it enters neither class’s payoff. The cleared gap of Theorem 1(ii) is unchanged — still
$\beta(1-\omega)\lambda p$ — and $p\big|_{\theta=1} = \alpha\beta\gamma/\!\left[(1-\beta)(1-\alpha\beta+\alpha\beta\gamma)\right] > 0$.
(ii) At every $\tau$, the split of the take that the owner prefers and the split the worker prefers are the
same, $\varphi_C(\tau)=\varphi_W(\tau)$. (iii) $b>0$: the owner’s own value function prices the workforce
strictly positively.*

*Proof.* (i) Setting $\theta=1$ in (C) gives $c=\beta b\gamma(1-\theta)=0$ and $r=\beta q\gamma(1-\theta)=0$,
hence $w_G=0$; substituting into the clearing computation of Theorem 1(ii) leaves it term for term, and
the closed form for $p$ evaluates as stated, positive since $\beta<1$ and $\alpha\beta<1$. (ii) and (iii)
are companion results, re-run here rather than re-derived. $\square$

Each part removes one version of the spanning story.

By (i), the separation owes nothing to the public route into the workforce’s reproduction: shut that
route down entirely and the gap is the same monomial. By (ii), there is no conflict on the reproduction
margin to be resolved by an agent who internalises both sides — the two classes already agree on how much
of the take should go there, and the planner’s $\varphi$ reaches it in full, because $s_G=\varphi\tau\alpha$
*is* his instrument. By (iii), the workforce is not unpriced in the owner’s optimisation. He values it,
with a strictly positive coefficient, through its effect on the output his capital works with. What he
cannot do is *hold a claim* on it — and Proposition 4 shows that this untradeability is not what
separates the two problems.

*So what.* The separating margin is the ownable stock, not the unownable one. What a tax on the owner’s
income cannot imitate is not access to an unpriced asset. It is a hand in how a *priced*, *owned* asset’s
return is divided between consumption and accumulation — and the owner’s first-order condition fixes that
division at a number no such tax appears in.

# 6. What this result is not

The nearest published object is Lancaster (1973), and it is worth stating exactly how this differs, because
if the difference fails the paper has nothing.

Lancaster compares a *cooperative* solution with a *non-cooperative* one and shows the first dominates.
The loss arises because each class internalises only part of investment’s return when the two decide
separately, and closing it requires irredeemable pledges about the future division — a commitment
problem, stated as such. His planner is the unweighted sum of the two classes’ objectives, retaining the
workers’ consumption floor, and is explicitly not an unconstrained first-best. His model carries one
state, capital; his solution concept is open-loop over complete time paths; his horizon is finite and
undiscounted.

The comparison here is a different one. Both sides of it are cooperative and both carry the *same* Pareto
weight. The planner is unconstrained in his own instruments: by Proposition 3 he even chooses the tax and
the split he would have chosen with the missing instrument in hand. What separates them is the *reach of the
instruments*, not the presence of a commitment problem — and on this face there is no commitment problem
to have. The economy closes in dominant strategies, so there is no strategic interaction to sustain and no
pledge anyone needs to make. A planner who could commit to anything he liked would gain nothing, because
what he lacks is not credibility but reach.

The horizon is not this paper’s card, and it should not be played as one. Lancaster’s own footnote says
the infinite-horizon extension can never be made to his bang-bang apparatus, but the infinite-horizon,
discounted, feedback treatment of that lineage exists (Haurie and Pohjola 1987), and it bends the lineage
toward showing cooperation sustainable rather than toward a new inefficiency. The claim here is orthogonal
to that repair: it concerns what a *cooperative* solution can reach with a given instrument set, which is
a question the sustainability literature does not ask.

What reaches the margin, then, is decided by the base an instrument is levied on, not by how many
instruments there are. The owner’s net income enters his consumption and his reinvestment as a common
factor, so no instrument on a base the two share — a capital-income tax, a lump-sum levy, any number of
them — moves $s_K/(s_C+s_K)$ off $i^{*}$. An instrument levied on one side does move it: a subsidy to
reinvestment paid out of the take, or a tax on the owner’s consumption, each at the rate
$i^{*}(1-i^{*})$ per unit at zero. A subsidy $w$ sets the division at any $x \ge i^{*}$ with
$1+w = x(1-i^{*})/\big(i^{*}(1-x)\big)$, and at none below. The negative result of this paper is about the
first set.

*So what.* If the result were a commitment result it would be fifty years old. It is a result about the
base an instrument is levied on, and the two are distinguished by a test: give the planner unlimited
commitment power and this shortfall does not move; give him a subsidy to reinvestment and, at every
interior weight, it closes.

# 7. Scope, and what is not settled

Three states are reported throughout: proved, refuted with a witness, and undischarged. The last is the
honest label for more of this paper than the first.

**Proved.** Propositions 1–4 and Theorem 1, on the face described in Section 2.

**Refuted, with a witness.** The separation is *not* a property of state capital as such: at $\lambda=0$
the planner attains B4 exactly. The spanning reading of the mechanism is refuted by Proposition 4, with
$\theta=1$ as the witness. And the missing instrument is not a holding: a planner holding no capital who
also pays a subsidy $w$ on reinvestment out of the take attains B4 at every $\lambda\in(0,1)$, with the
owner interior at $i^{*}$, $\tau = 1 - s_C/\big((1-i^{*})\alpha\big)$ and $1+w = s_K(1-i^{*})/(i^{*}s_C)$
at B4’s shares; the budget closes with $s_W \ge 1-\alpha$ because B4 satisfies that bound.

**Undischarged, and named.**

1.  *The face is a restriction, and it is outside the parent model’s stated domain.* Section 2 sets
    $\sigma_W=\sigma_C=1$, whereas the model this face is drawn from assumes $\sigma>1$. Away from unit
    elasticity the owner’s saving share answers to the tax, so three things belong to this face alone: that
    B2’s reachable set is the *fixed* slice $s_K/(s_C+s_K)=i^{*}$, that Proposition 3’s cross-partials
    vanish, and that the shortfall takes Theorem 1(iii)’s divergence form. Straub and Werning (2020, §2.3)
    work on that domain with a general savings rule and sign the long-run tax; they state no comparison with
    an agent who sets the owner’s saving. Non-attainment itself survives an owner with constant relative
    risk aversion $\sigma>0$ and a logarithmic worker: at the relaxation’s allocation the weighted marginal
    gain from investment is $(1-\lambda)$ times the owner’s own plus $\lambda\beta p/i$, and $p>0$, so the
    owner under-invests there at every $\lambda\in(0,1]$. That argument is checked symbolically and is not
    printed as a proposition. The size of the gap off the face, and a non-logarithmic worker, are
    undischarged.
2.  *What a state holding capital does depends on what the state wants.* Let the state add
    $\psi\tau\alpha Y$ to the one capital stock while the owner keeps all capital income. The owner does not
    then keep $i^{*}$: he best-responds by lowering his own reinvestment rate by
    $(1-\omega)\psi\tau/\big(((1-\omega)+\beta a)(1-\tau)\big)$. A state maximising the $\lambda$-weighted
    objective attains B4 at every $\lambda\in(0,1)$, but only at the corner where the owner’s own
    reinvestment is zero and the state does all the investing; a state maximising its own tax revenue
    attains B4 at no $\lambda\in(0,1)$. The verdict moves with the state’s objective. At $\lambda=1$ nothing
    attains B4, since $i(1)=1$ requires $s_C=0$, hence $\tau=1$. So in this encoding a holding reaches
    nothing the subsidy of Section 6 does not, and reaches it only by displacing the owner’s investment
    entirely. These verdicts are checked symbolically and are not propositions of this paper.
3.  *Other holdings.* A holding that earns its pro-rata share of capital income (no closed form was found);
    a state that matches the owner’s investment by a known rule, under which the owner keeps $i^{*}$ and
    whether B4 is reached depends on the parameters; state-contingent rules; and whether the corner
    implementation of item 2 is time-consistent for the state.
4.  *Positioning rests on two bodies read at source.* Lancaster (1973) is read, and so are pp. 1–13 and
    15–18 of the working-paper version of Straub and Werning (2020); the published text’s pagination is not
    checked. The infinite-horizon repair is taken from a verified abstract. The zero-tax literature Straub
    and Werning revisit, including Judd’s model and Lansing’s logarithmic counterexample, is known here only
    through their rendering of it and is not read at source; nor is the workers’ investment funds paper of
    Pohjola (1983). Nothing here leans on either.

*So what.* The paper establishes a negative about taxes levied on the owner’s income, a closed form for
what they miss, and the fact that an ordinary subsidy to reinvestment supplies it. What it does not
establish is that owning capital adds anything to that subsidy; in the one encoding of a holding that
closes, it adds nothing.

# References

-   Dockner, E., S. Jørgensen, N. V. Long, and G. Sorger (2000). *Differential Games in Economics and
    Management Science*. Cambridge: Cambridge University Press.
-   Galindo Escajeda, C. (2026). “The Unowned Factor: Who Prices the Reproduction of Labour.” Working
    paper.
-   Haurie, A., and M. Pohjola (1987). “Efficient Equilibria in a Differential Game of Capitalism.”
    *Journal of Economic Dynamics and Control* 11(1): 65–78.
-   Lancaster, K. (1973). “The Dynamic Inefficiency of Capitalism.” *Journal of Political Economy*
    81(5): 1092–1109.
-   Pohjola, M. (1983). “Workers’ Investment Funds and the Dynamic Inefficiency of Capitalism.” *Journal of
    Public Economics* 20(2): 271–279.
-   Straub, L., and I. Werning (2020). “Positive Long-Run Capital Taxation: Chamley-Judd Revisited.”
    *American Economic Review* 110(1): 86–119.
