# Durable Capital and the Assigned Capital-Income Tax
Carlos Galindo Escajeda
2026-09-01

**JEL.** O33, D33, E11, H21, E62

**Keywords.** durable capital; assigned capital-income tax; reproduction of the workforce; Chamley–Judd; unowned labour

------------------------------------------------------------------------

## Nontechnical abstract

A tax on capital income fills a public stock that reproduces labour nobody owns. A fraction of capital survives each period. The law that fills the public stock does not use depreciation. A zero tax still means a zero public stock.

When capital lasts, log-affine owner values disappear, and the owner’s preferred tax varies with the state. At Cobb–Douglas driving the tax to zero drives capital income to zero with it, and the owner’s preferred tax never falls below a floor written in the discount factor, labour’s share and the reproduction weight. The floor rises as capital becomes more durable. Chamley and Judd treat tax revenue as a transfer to workers. Straub and Werning change elasticities inside Judd’s model. This paper changes what the revenue is.

------------------------------------------------------------------------

## Technical abstract

Capital obeys

$$
K'=(1-\delta)K+i(1-\tau)e^{E_C},\qquad\delta\in(0,1].
$$

The public-stock law is $G'=\varphi\tau e^{E_C}$. Hence $\tau=0$ implies $G'=0$ for every $\delta$. At $\delta=1$ capital is rebuilt in full from after-tax profit.

The map $k\mapsto\ln\bigl((1-\delta)e^{k}+i(1-\tau)e^{E_C}\bigr)$ is not affine in $k$ when $\delta<1$. Affine-in-logs closure of the owner’s Bellman equation therefore fails even at $\sigma=1$. One-generation closed-form peaks are not exact constants for $\delta<1$.

At a stationary ratio the owner’s first-order condition in $\tau$, holding $(d,i)$ fixed, equates the marginal loss on the after-tax pie to the marginal value of $G'$ through future $L$. On the domain $\theta_R<1$, $\gamma>0$ that second term is strictly positive. The candidate is therefore interior.

**Theorem (paths).** There is no assigned owner path with $\tau_t\to 0$ and $\{E_{C,t}\}$ bounded above (Proposition 3). At $\sigma=1$ that qualifier is not needed: every path with $\tau_t\to 0$ carries labour and capital income to zero (Proposition 5), and every assigned-optimal path stays above $\bar\tau$ (Proposition 10), so a convergent assigned-optimal path has $\tau_\infty\ge\bar\tau$. Permanent shut-down is not assigned-optimal (Proposition 4).

**Theorem (floor).** At $\sigma=1$ the assigned owner’s best response at *any* state, for every $\delta\in(0,1]$, satisfies $\tau^*\ge\bar\tau=c/(1+c)>0$ with

$$
c=\frac{\beta^2(1-\omega)(1-\alpha)\gamma(1-\theta_R)}{(1-\omega)+\dfrac{\beta}{1-\beta}}
$$

(Proposition 10). At a capital-stationary state the denominator is $(1-\omega)+\beta\delta/(1-\beta)$, so the floor is strictly decreasing in $\delta$ and tends to $\beta^2(1-\alpha)\gamma(1-\theta_R)$ as $\delta\to 0$ (Proposition 11). Durability raises the floor rather than lowering it.

------------------------------------------------------------------------

## Nontechnical introduction

Capital is owned. Successor labour is not. A tax on capital income fills a public stock that helps reproduce that labour. Capital that lasts more than one generation is the object Chamley (1986) and Judd (1985) use to send a capital-income tax to zero.

Their planner is not the assigned owner. Their revenue does not rebuild an unowned labour stock. When capital lasts one generation, a take from current profit and a capital-income tax are the same map into next period’s consumption, capital, and public stock. When some capital survives, that map splits. The tax still funds the public stock. Surviving machines no longer have to be rebuilt in full from after-tax profit.

The question is whether the owner’s reason to fund that stock dies when capital becomes long-lived. On the Cobb–Douglas face it does not: sending the tax to zero sends capital income to zero with it, and the owner’s own preferred tax stays above a positive constant of the parameters.

The vanishing-tax path is not a destination capital reaches by choosing technique. Lemmas 3–5 and Propositions 3 and 5 are a contradiction: if the tax goes to zero with capital income bounded above, the public stock and then labour go to minus infinity, which cannot sit with bounded capital income. That rules the path out. It does not say that capital’s preferred direction empties labour’s share until the tax preference collapses. Preferred direction, on the generational face, is a constant indexed by a reproduction weight. This paper’s assigned tax, once capital lasts, is not that constant. Coupling the two as a self-destruction loop is not a theorem of either object.

What the assigned owner will not shut is the public stock that reproduces labour he does not own. Marx’s collated condition is that “the maintenance and reproduction of the working class is, and must ever be, a necessary condition to the reproduction of capital” (*Capital* I, ch. 23). Here that condition is the strictly positive loading of next period’s public stock in the owner’s continuation, on the domain $\theta_R<1$, $\gamma>0$. The law that maps this period’s spending into next period’s labour is this model’s, not his. Machines that survive ($\delta<1$) split the map from after-tax profit into new capital; they do not remove that loading. Chamley and Judd send a capital-income tax to zero when the revenue is a transfer. This paper changes what the revenue is.

------------------------------------------------------------------------

## Environment

Two classes of fixed measure. Owners hold $K$. Workers supply $L$ and hold no assets. Production is CES with elasticity $\sigma$. Factor shares $s_K$, $s_L$ at a reference effective capital–labour ratio $\bar x$. Logged income composites $E_C=\ln s_K+\psi+a+n$ and $E_W=\ln s_L+\psi+a+n$. Direction $d$, investment share $i$, capital-income tax $\tau$, in-kind share $\varphi$. Worker felicity $n$. Owner felicity $(1-\omega)\ln C_C+\omega k$. Common discount $\beta$. Labour law:

$$
n'=n+\gamma\theta_R(E_W-n)+\gamma(1-\theta_R)(g-n).
$$

**Modified capital law.**

$$
\begin{aligned}
\ln C_C&=\ln(1-i)+\ln(1-\tau)+E_C,\\
K'&=(1-\delta)K+i(1-\tau)e^{E_C},\\
g'&=\ln(\varphi\tau)+E_C.
\end{aligned}
$$

At $\delta=1$, $K'=i(1-\tau)e^{E_C}$. Tax formulas below that recover a one-generation peak are written at $\varphi=1$. The same corner is used here unless a sentence names the split.

------------------------------------------------------------------------

## Laws that survive

**Lemma 1 (Public stock).** $G'=\varphi\tau e^{E_C}$ does not depend on $\delta$. At $\varphi=1$, $\tau=0$ implies $G'=0$ for every $\delta\in(0,1]$.

**Lemma 2 (Loss of affinity).** For $\delta\in(0,1)$,

$$
k'=\ln\bigl((1-\delta)e^{k}+i(1-\tau)e^{E_C}\bigr)
$$

is not an affine function of $k$. Affine-in-logs closure of the owner’s Bellman equation therefore fails even on the Cobb–Douglas face $\sigma=1$, where the composites $E_C$, $E_W$ remain affine.

*Proof.* Differentiate $k'$ twice in $k$. The second derivative is

$$
\frac{\partial^2 k'}{\partial k^2}
=(1-\delta)e^{k}\cdot i(1-\tau)e^{E_C}\big/\bigl((1-\delta)e^{k}+i(1-\tau)e^{E_C}\bigr)^2
$$

and is strictly positive when $\delta<1$ and $i(1-\tau)>0$. $\square$

The one-generation peaks

$$
\tau_C=\frac{\beta^2\gamma(1-\theta_R)\,(s_L/\sigma)}{1-\beta+\beta\gamma(1-\theta_R)+\beta\gamma\theta_R(s_K/\sigma)},
\qquad
\tau_W=\frac{(1-\theta_R)\bigl(1-\beta+\beta s_L/\sigma\bigr)}{1-\theta_R+\theta_R(s_K/\sigma)}
$$

were derived under log-affine transitions at $\delta=1$. For $\delta<1$ the assigned tax varies with the state. The convention $V_j=M_j\ln(1-\tau)+N_j\ln\tau+H_j$ requires those transitions.

------------------------------------------------------------------------

## Stationary assigned tax

A stationary point is a triple $(\tau,i,d)$ and a ratio $\bar x$ such that $K'=K$ and the labour and public-stock laws hold with constant $n$ and $g$. Capital stationarity reads

$$
\delta K=i(1-\tau)e^{E_C}.
$$

Hold $(d,i)$ fixed. States are $(K,n,g)$. Timing: $\tau$ enters $g'$ and $K'$, not $n'$.

$$
V(K,n,g)=\max_{\tau\in(0,1)}\bigl\{(1-\omega)\ln C_C+\omega\ln K+\beta V(K',n',g')\bigr\}.
$$

**Proposition 1 (Exact first-order condition).** At an interior optimum, with $I:=i(1-\tau)e^{E_C}$,

$$
\frac{\tau}{1-\tau}=\frac{\beta V_g(K',n',g')}{(1-\omega)+\beta I V_K(K',n',g')}.
$$

The envelope is $V_g(K,n,g)=\beta\gamma(1-\theta_R)V_n(K',n',g')$. On the licensed box $\gamma(1-\theta_R)>0$. If $V_n>0$ and $V_K\ge 0$ at the continuation, the right-hand side is strictly positive and that candidate is interior.

*Proof.* Current utility contributes $-(1-\omega)/(1-\tau)$. State derivatives: $K_\tau'=-I/(1-\tau)$, $g_\tau'=1/\tau$, $n_\tau'=0$. Multiply through by $\tau(1-\tau)$. The envelope in $g$ uses $n'_g=\gamma(1-\theta_R)$ and $K'_g=g'_g=0$. $\square$

The first term grows as $\delta$ falls, because a larger fraction of $K'$ is inherited rather than purchased from after-tax profit, so a tax that shrinks $I$ is a tax on a smaller share of next period’s capital. The second term does not use $\delta$.

**Proposition 2 (Recovery).** At $\delta=1$ the stationary condition of Proposition 1 coincides with the first-order condition that yields the displayed $\tau_C$ under the log-affine expansion. On the domain $\theta_R\in(0,1)$, $\gamma\in(0,1)$ that peak is strictly positive.

**Conjecture 1.** For every $\delta\in(0,1]$ there exists a stationary assigned peak $\tau_C(\delta)\in(0,1)$ on that domain.

**Conjecture 2.** $\liminf_{\delta\to 0}\tau_C(\delta)>0$ whenever $\theta_R$ is bounded away from $1$ and $\gamma>0$. Propositions 10 and 11 below settle this, with an explicit constant and without passing to the limit.

Chamley (1986) and Judd (1985) are statements about $t\to\infty$ at fixed $\delta$. The next section treats that limit.

------------------------------------------------------------------------

## Paths, not only stationary points

Lemma 2 already implies that assigned programmes need not be constant when $\delta<1$. Chamley–Judd is a claim about a tax *path*: $\tau_t\to 0$ as $t\to\infty$. That is the object to accept or reject for the assigned owner.

Write $\rho:=1-\gamma\in(0,1)$ for the own-lag in labour when $E_W$ is carried as an input, and $\eta:=\gamma(1-\theta_R)>0$ on the licensed box. The three weights $\rho$, $\gamma\theta_R$ and $\eta$ sum to one, so a common value of $n$, $E_W$ and $g$ is a rest point. Then

$$
n_{t+1}=\rho n_t+\gamma\theta_R E_{W,t}+\eta g_t.
$$

**Lemma 3 (Public-stock divergence).** Let $\varphi=1$. If $\tau_t\to 0$ and $\{E_{C,t}\}$ is bounded above, then $g_{t+1}=\ln\tau_t+E_{C,t}\to-\infty$.

**Lemma 4 (Labour collapse).** If $g_t\to-\infty$ and $\{E_{W,t}\}$ is bounded above, then $n_t\to-\infty$.

*Proof.* Iterate the labour law. The coefficient on $g_{t-k}$ is $\eta\rho^{k-1}$. If $g\to-\infty$, the moving average of $g$ goes to $-\infty$. A bounded $E_W$ cannot offset it. $\square$

**Lemma 5 (Essential labour).** For $\sigma\in[1,\infty)$, both factors are essential in $Y$. If $n_t\to-\infty$ and $\{k_t\}$ is bounded above, then $E_{C,t}\to-\infty$. If $n_t\to-\infty$ and $k_t\to+\infty$ with $k_t-n_t\to+\infty$, then $s_L\to 0$ when $\sigma>1$ and $E_{C,t}+a_t$ is still pulled down by the collapsing labour input.

*Sketch.* CES with $\sigma<\infty$ has $\lim_{L\to 0}Y=0$ at finite $K$. Cobb–Douglas is $Y=K^\alpha L^{1-\alpha}$, so $n\to-\infty$ sends $\ln Y\to-\infty$ unless $k$ rises in proportion $((1-\alpha)/\alpha)|n|$, which cannot continue forever under $K'\le(1-\delta)K+i e^{E_C}$ once $E_C$ itself is falling. $\square$

**Proposition 3 (Zero terminal tax is not an assigned owner path with bounded composites).** Assume $\varphi=1$, $\theta_R\in(0,1)$, $\gamma\in(0,1)$, $\sigma\in[1,\infty)$, $\omega\in[0,1)$, and that the factor shares $(s_K,s_L)$ stay in a compact subset of $(0,1)^2$ along the path. There is no assigned owner path along which $\tau_t\to 0$ and $\{E_{C,t}\}$ remains bounded above.

*Proof.* Lemma 3 sends $g\to-\infty$. On a compact share set $\ln(s_L/s_K)$ is bounded, and $E_W-E_C$ is that quantity plus a bounded function of $d$; so $E_C$ bounded above gives $E_W$ bounded above. Lemma 4 sends $n\to-\infty$. Lemma 5 then contradicts boundedness of $E_C$. $\square$

The share hypothesis is automatic at $\sigma=1$, where shares are the constants $(\alpha,1-\alpha)$, and it is what the Cobb–Douglas result of Proposition 5 dispenses with.

A vanishing rate on an exploding base would keep $G_t=\tau_t e^{E_{C,t}}$ finite. At Cobb–Douglas that path is not available.

**Proposition 5 (A vanishing tax empties the economy at $\sigma=1$).** Let $\sigma=1$, $\delta\in(0,1]$, $\varphi=1$, $\alpha\in(0,1)$, $\theta_R\in(0,1)$, $\gamma\in(0,1)$, $i\in(0,1)$. Along every feasible path of $(K_t,n_t,\tau_t)$ with $\tau_t\to 0$, both $n_t\to-\infty$ and $E_{C,t}\to-\infty$: labour and capital income go to zero together. No such path keeps capital income bounded away from zero, and by Proposition 10 none of them is assigned-optimal.

*Sketch.* At $\sigma=1$ the labour law reads
$$
n_{t+1}-n_t=\gamma\theta_R\bigl[\ln(1-\alpha)+\alpha x_t\bigr]+\eta\bigl[g_t-n_t\bigr],
\qquad g_t=\ln\tau_{t-1}+E_{C,t-1},
$$
where $x_t:=k_t-n_t$ and $\eta=\gamma(1-\theta_R)>0$, so a vanishing tax enters labour growth with a one-period lag, through $\eta\ln\tau_{t-1}$. Capital obeys
$$
\frac{K_{t+1}}{K_t}=1-\delta+i(1-\tau_t)\alpha e^{-(1-\alpha)x_t}.
$$
If $\tau_t\to 0$ then $\eta\ln\tau_{t-1}\to-\infty$. Labour growth stays non-negative only if $x_t\to+\infty$ fast enough to offset $\ln\tau_{t-1}$. But $x\to+\infty$ sends $K_{t+1}/K_t\to 1-\delta<1$, so $k_t$ falls linearly and $x$ cannot remain large. If $x$ stays bounded, $n\to-\infty$ and then $E_C=\ln\alpha+n+\alpha x\to-\infty$ unless $k$ rises in proportion, which returns to $x\to+\infty$. If $x\to-\infty$, labour growth is even more negative and the same conclusion follows. Hence $n_t\to-\infty$ and $E_{C,t}\to-\infty$. $\square$

The argument uses $\delta>0$ twice: depreciation dominates under capital deepening, and there is no AK residual at $\sigma=1$.[^1]

**Corollary.** At $\sigma=1$ and $\delta\in(0,1]$, neither the bounded-composite qualifier of Proposition 3 nor its share hypothesis is needed: a vanishing tax carries capital income down with it whatever the composites do, and Proposition 10 below puts every assigned-optimal path above a positive constant.

**Corollary (convergent paths).** At $\sigma=1$ and $\delta\in(0,1]$, if an assigned-optimal path satisfies $\tau_t\to\tau_\infty$, then $\tau_\infty\ge\bar\tau>0$, with $\bar\tau$ the constant of Proposition 10. In particular there is no convergent assigned-owner path with a zero long-run capital-income tax.

*Proof.* Proposition 10 gives $\tau_t\ge\bar\tau$ at every date and every state, so any limit lies in $[\bar\tau,1]$. $\square$

**Proposition 4 (Permanent shut-down).** A path with $\tau_t=0$ for all $t\ge T$ is not assigned-optimal for the owner on the licensed box. After $T$, $g_{t}=-\infty$ in the log convention and Lemma 4 applies at once.

Proposition 3 is the contact with Chamley–Judd’s conclusion on this face: the assigned owner has no vanishing-tax path while composites stay bounded.

------------------------------------------------------------------------

## Interior policy at a given state

Existence of a policy at a given state is a statement about the objective. As $\tau$ moves, the next state moves.

Fix a current state $(K,n,g)$ with $K>0$, and fix $(d,i)$. Write

$$
W(\tau)=(1-\omega)\ln(1-\tau)+(1-\omega)E_C(K,n)+\omega\ln K+\beta V\bigl(K'(\tau),n',g'(\tau)\bigr).
$$

Here $n'$ does not depend on $\tau$.

**Proposition 6 (Interior policy at a given state).** Assume $\varphi=1$, $\theta_R\in(0,1)$, $\gamma\in(0,1)$, $\sigma\in[1,\infty)$, $\omega\in[0,1)$, and that $V$ is finite whenever $(K',n',g')$ is finite. Then $W(\tau)\to-\infty$ as $\tau\to 1^-$ and as $\tau\to 0^+$. A maximiser $\tau^*(K,n,g)\in(0,1)$ therefore exists.

*Proof.* As $\tau\to 1^-$, $\ln(1-\tau)\to-\infty$ while $K'\to(1-\delta)K$ and $g'\to E_C$ stay finite. Hence $W\to-\infty$.

As $\tau\to 0^+$, current utility stays finite and $K'\to(1-\delta)K+ie^{E_C}$ stays finite, but $g'=\ln\tau+E_C\to-\infty$. Then $n''$ loads $g'$ with weight $\eta>0$, so $n''\to-\infty$. At finite $K''$, essential labour (Lemma 5) sends subsequent $E_C\to-\infty$, hence subsequent $\ln C_C\to-\infty$. Thus $V(K',n',g')\to-\infty$ and $W\to-\infty$.

$W$ is continuous on $(0,1)$ if $V$ is continuous on interior next states. A continuous function that diverges to $-\infty$ at both ends of $(0,1)$ attains a maximum in $(0,1)$. $\square$

Proposition 6 says the owner at a given state does not shut down and does not confiscate. A stationary peak is a fixed point $\tau=\tau^*(K(\tau),n(\tau),g(\tau))$, where the state is the one induced by the constant policy $\tau$.

**Lemma 6 (Intensive stationarity at $\sigma=1$).** Let $\sigma=1$ and $x:=k-n$. Then
$$
E_W-n=\ln(1-\alpha)+\alpha x,\qquad g-n=\ln(\alpha\tau)+\alpha x,
$$
both independent of scale $n$. Labour stationarity $n'=n$ is
$$
x=x_L(\tau):=-\frac{\theta_R\ln(1-\alpha)+(1-\theta_R)\ln(\alpha\tau)}{\alpha}.
$$
Capital stationarity is
$$
x=x_K(\tau,i,\delta):=\frac{1}{1-\alpha}\ln\Bigl(\frac{i(1-\tau)\alpha}{\delta}\Bigr).
$$
A fully intensive-stationary point at fixed $i$ exists only when $x_L(\tau)=x_K(\tau,i,\delta)$. Equivalently $i$ adjusts:
$$
i(\tau,\delta)=\frac{\delta}{\alpha(1-\tau)}\,e^{(1-\alpha)x_L(\tau)}.
$$
The scale $n$ is not pinned. As $\tau\to 0^+$, $x_L(\tau)\to+\infty$.

*Proof.* Substitute the Cobb–Douglas composites into $n'=(1-\gamma)n+\gamma\theta_R E_W+\eta g$ and set $n'=n$. Capital stationarity divides by $L$. $\square$

**Proposition 7 (What a fixed point still needs).** Let $\sigma=1$ and maintain the hypotheses of Proposition 6. Lemma 6 does not give a state $(K,n,g)$ for every $\tau$ at fixed $i$. It gives a curve $i=i(\tau,\delta)$ on which intensive stationarity holds; the scale $n$ remains a state. Proposition 6 still gives $\tau^*(K,n,g)\subset(0,1)$ at each given state. A stationary peak is a pair $(\tau,i(\tau,\delta))$ that is a best response at some scale of that intensive point.[^2]

*One-step bound, if $V$ is differentiable.* Raise current $g$ by $\Delta>0$ and hold subsequent instruments fixed. Then $n'$ rises by $\eta\Delta$ and, at $\sigma=1$, $E_C'$ rises by $(1-\alpha)\eta\Delta$. Hence
$$
\frac{V(K,n,g+\Delta)-V(K,n,g)}{\Delta}\ge\beta(1-\omega)(1-\alpha)\eta>0.
$$
If $V$ is differentiable, $V_g\ge\beta(1-\omega)(1-\alpha)\eta$. Proposition 1 then gives
$$
\frac{T}{1-T}\ge\frac{\beta^2(1-\omega)(1-\alpha)\eta}{(1-\omega)+\beta I V_K}.
$$
A uniform upper bound on $I V_K$ would produce a uniform $a>0$ with $T\ge a$. Lemma 7 supplies one, and Proposition 10 does not need $V$ differentiable to use it.

What Proposition 7 leaves open is not whether the owner taxes. It is how little he can be made to tax. A stationary peak is a tax the economy can sit at, and the owner’s investment share has to adjust for it to exist; that is a statement about the resting point, not about his conduct on the way there. The economically useful object is a number he never goes below at any state at all, and the rest of this section produces one.

**Proposition 8 (Discrete variation).** Let $\sigma=1$, $\varphi=1$, $\lambda>1$, and fix a current state with finite $E_C$ and investment $I=i(1-\tau)e^{E_C}$. Hold subsequent instruments fixed after the first period. Then
$$
V(K,n,g+\ln\lambda)-V(K,n,g)\ge\beta(1-\omega)(1-\alpha)\eta\ln\lambda>0.
$$
Comparing $W(\lambda\tau)$ with $W(\tau)$ at that state, the public-stock gain is that constant while the current-consumption loss is
$$
(1-\omega)\ln\frac{1-\tau}{1-\lambda\tau}=O(\tau)
$$
as $\tau\to 0^+$, and the capital loss is of order $I\tau$. Hence there exists $\bar\tau(I)>0$ such that $W(\lambda\tau)>W(\tau)$ for all $\tau\in(0,\bar\tau(I))$. No maximiser at that state lies in $(0,\bar\tau(I))$.

*Proof.* Raising $g$ by $\ln\lambda$ raises $n'$ by $\eta\ln\lambda$ and $E_C'$ by $(1-\alpha)\eta\ln\lambda$. Next-period log consumption, at unchanged $(\tau',i')$, rises by that amount. That is the displayed lower bound. The rest is Taylor expansion of $\ln(1-\tau)$ and $K'(\tau)$. $\square$

Proposition 8 does not need $V$ differentiable. Combined with Proposition 6, the assigned owner at any finite-$I$ state rejects both $\tau=0$ and every sufficiently small $\tau$. The threshold there is written in levels of $I$. Measured in logs it is not: that is the content of the next two results, which turn $\bar\tau$ into a constant of the parameters alone.

------------------------------------------------------------------------

## A floor that does not move with the state

The quantity Proposition 7 needs is an upper bound on $\beta IV_K$ that holds at every state and every $\delta$. Since $I\le K'$ by construction, it is enough to bound $K'V_{K'}$ — the sensitivity of owner value to capital measured in logs. That bound is a constant.

**Lemma 7 (Value sensitivity in capital).** Let $\sigma=1$, $\varphi=1$, and fix $(d,i)$. For every state $(k,n,g)$ and every $\Delta>0$,

$$
V(k+\Delta,n,g)-V(k,n,g)\le\frac{\Delta}{1-\beta}.
$$

Neither $\delta$, nor $i$, nor the state appears on the right. Two paths run from states that differ only in capital never diverge: the gap in every state variable is a weighted average of gaps already present, and each set of weights sums to one. Appendix A.1 has the proof.

**Proposition 10 (Uniform floor).** Assume $\varphi=1$, $\sigma=1$, $\alpha\in(0,1)$, $\theta_R\in(0,1)$, $\gamma\in(0,1)$, $\omega\in[0,1)$, and that $V$ is finite at finite states. Put

$$
P:=\beta^2(1-\omega)(1-\alpha)\eta,\qquad
Q:=(1-\omega)+\frac{\beta}{1-\beta},\qquad
c:=\frac{P}{Q},\qquad
\bar\tau:=\frac{c}{1+c}\in(0,1).
$$

Then no maximiser $\tau^*(K,n,g)$ of $W$ lies in $(0,\bar\tau)$ — at any state, for every $\delta\in(0,1]$ and every $i\in(0,1)$.

The proof is a variation, in Appendix A.2. Raise $\tau$ to $\lambda\tau$ with $\lambda>1$. The public stock rises by $\ln\lambda$ and is worth at least $P\ln\lambda$; consumption and capital fall by at most $Qu$ with $u=(\lambda-1)\tau/(1-\lambda\tau)$. The single step that makes $Q$ a constant is to measure the capital loss in logs rather than in levels: the inherited stock $(1-\delta)K$ sits in the denominator, so the loss is at most $u$ whatever $K$, $i$, $Y$ and $\delta$ are. That is the uniform bound on $\beta IV_K$ Proposition 7 asked for.

**Proposition 11 (Durability raises the floor).** Let a state and an $i$ be such that the tax $\tau$ leaves capital stationary, $K'=K$ and hence $i(1-\tau)e^{E_C}=\delta K$. Then the argument of Proposition 10 runs at that tax with $Q$ replaced by $Q(\delta):=(1-\omega)+\beta\delta/(1-\beta)$. Writing $c(\delta):=P/Q(\delta)$, if such a $\tau$ is a maximiser of $W$ at that state then

$$
\frac{\tau^*}{1-\tau^*}\ \ge\ c(\delta)
=\frac{\beta^2(1-\omega)(1-\alpha)\gamma(1-\theta_R)}{(1-\omega)+\dfrac{\beta\delta}{1-\beta}},
$$

and $c(\delta)$ is strictly decreasing in $\delta$, with $c(1)=c$ and

$$
\lim_{\delta\to 0^+}c(\delta)=\beta^2(1-\alpha)\gamma(1-\theta_R)>0 .
$$

*Proof.* At such a state $B(1-\tau)=\delta K$ and $R=(1-\delta)K$, so $k'(\tau)-k'(\lambda\tau)=\ln\bigl(1+\delta(\lambda-1)\tau/(1-\tau-\delta(\lambda-1)\tau)\bigr)$. Only the capital term of Appendix A.2 changes: $u$ becomes that quantity there, and dividing by $\lambda-1$ and letting $\lambda\downarrow 1$ replaces $\beta/(1-\beta)$ by $\beta\delta/(1-\beta)$ in $Q$. Monotonicity and the limit are read off $Q(\delta)$. Capital stationarity pins $ie^{E_C}$, so the substitution is exact at that tax and at no other tax of the same state; below it the capital term is larger and the bound that applies is Proposition 10’s, which holds at every state and every tax whatever $\delta$ is. $\square$

**Corollary (Conjecture 2).** Conjecture 2 holds, and in a form that does not wait for the limit: whenever a stationary assigned peak $\tau_C(\delta)$ exists it satisfies $\tau_C(\delta)\ge c(\delta)/(1+c(\delta))\ge\bar\tau>0$ for every $\delta\in(0,1]$, and $\liminf_{\delta\to 0}\tau_C(\delta)\ge c_0/(1+c_0)$ with $c_0=\beta^2(1-\alpha)\gamma(1-\theta_R)$.

**Corollary (paths, second route).** Every assigned-optimal path satisfies $\tau_t\ge\bar\tau$ for all $t$. In particular no assigned-optimal path has $\tau_t\to 0$. Propositions 3 and 5 reach a wider class — every *feasible* path — by a divergence argument, and say what a vanishing tax does along one; Proposition 10 reaches the optimal paths by a variation, and puts a number on how far from zero they stay.

The economics of the constant is the accounting of the two channels. $P$ is what one log point of public stock is worth to the owner: it reaches him after two periods, through the reproduction weight $\eta=\gamma(1-\theta_R)$ and labour’s share $1-\alpha$. $Q$ is what the same log point costs: consumption today, plus the value of the capital it is bought out of. The second half of that cost is the whole of the durability question, and Proposition 11 answers it. As $\delta$ falls, a smaller share of next period’s capital is purchased out of after-tax profit, so the tax bites a smaller part of it and $Q(\delta)$ falls. Durability does not release the owner from funding the stock. It makes the funding cheaper.

Conjecture 1 at $\sigma=1$ remains a fixed point on the curve $i=i(\tau,\delta)$ of Lemma 6, not the Theorem of the Maximum on $(0,1)$. What Propositions 10 and 11 add is that any such fixed point, and indeed any best response at any state, is bounded away from zero by a constant of the parameters.

------------------------------------------------------------------------

## Stationary first-order condition

An interior stationary FOC at fixed $(d,i)$ has the shape

$$
\frac{\tau}{1-\tau}
=\frac{\beta\gamma(1-\theta_R)\,V_n'}{(1-\omega)+\beta I V_K'}
$$

after using $\delta K=I=i(1-\tau)e^{E_C}$, provided current $g$ is a state and $\tau$ enters $g'$. The displayed one-generation peaks are the special case $\delta=1$ under log-affine $V$.

Three substitutions turn that identity into $\tau_C=B/(A(\delta)+B)$ with $A(\delta)=(1-\omega)+\beta\omega\delta/(1-\beta(1-\delta))$ and $B$ independent of $\delta$. None of them is licensed.

1.  The envelope $V_K=\omega/K+\beta(1-\delta)V_K'$ drops $\partial E_C/\partial K$. Capital income depends on $K$. The omitted term is $(1-\omega)E_{C,K}$ plus continuation through $K'$ and $n'$.
2.  $B=\beta\gamma(1-\theta_R)V_n'$ independent of $\delta$ treats the labour shadow price as a preference parameter. $V_n$ is an equilibrium object. It moves with $K/L$, and $K/L$ moves with $\delta$.
3.  $B$ independent of $\tau$ is affine value in $g$. Lemma 2 records that owner value is not log-affine for $\delta<1$.

As $\tau\to 0$, $g'\to-\infty$ and $V_n'$ is evaluated on that path.

Under the one-generation expansion, $\tau_C\to 0$ as $s_K\to 1$ when $\sigma>1$. Lowering $\delta$ tends to raise $K$ relative to $L$. For $\sigma>1$ that raises $s_K$ and shrinks the owner’s weight on $L$. The public-channel coefficient $\gamma(1-\theta_R)$ does not vanish. At $\sigma=1$ shares are fixed.

------------------------------------------------------------------------

## Contact with Chamley and Judd

**Proposition 9 (Hypotheses).** Judd (1985) and Chamley (1986) obtain $\tau_t\to 0$ from a planner problem in which:

1.  Revenue is not an input into $n'$ through $G'=\varphi\tau e^{E_C}$.
2.  The planner is not the assigned owner.
3.  Labour is not an unowned factor reproduced from a public stock filled by the capital-income tax.
4.  At $\delta=1$, assigned programmes are constants, so the time limit and the stationary tax coincide. On this face they do not (Lemma 2).

Lemma 1 keeps $G$ tied to $\tau$ at every $\delta$. Proposition 1 keeps $V_g$ loaded through $\gamma(1-\theta_R)$ at every $\delta$ on the licensed box. Those facts plus Propositions 5 and 9 are the contact.

A representative-agent public-share formula (Barro 1990) is one number. At $\delta=1$ this economy has a tax interval $[\tau_C,\tau_W]$.

------------------------------------------------------------------------

## Neighbouring objects

Chamley (1986) and Judd (1985) are the durable-capital tax benchmarks; revenue there is not an input into $n'$. Straub and Werning (2020) is a qualification inside that model. Galor and Moav (2006) is the political-economy neighbour: owners fund public skill because it raises profits. Barro (1990) is a single public share. Directed technical change (Acemoglu 2002; Kennedy 1964) supplies the current-output mix.

------------------------------------------------------------------------

## Conclusion

A public stock (G), filled by a tax on capital income, is an input into the reproduction of labour that nobody owns. This paper asks whether that technology still requires a tax when capital survives.

Durability splits a take from current profit from a capital-income tax. The public stock remains $G'=\varphi\tau e^{E_C}$. Log-affine owner values die, so assigned programmes vary with the state. The exact interior first-order condition still loads $V_g$ through $\gamma(1-\theta_R)$. A path with $\tau_t\to 0$ and bounded composites is impossible (Proposition 3). At Cobb–Douglas a tax driven to zero takes labour and capital income to zero with it (Proposition 5): labour growth carries $\eta\ln\tau$, and capital deepening is trapped by depreciation. Every convergent assigned-optimal path therefore has a strictly positive long-run tax.

The answer to the question the paper opens with is therefore a number and not only a sign. The assigned owner’s tax never falls below $\bar\tau=c/(1+c)$, with $c$ the ratio of what one log point of public stock is worth to him — two periods away, through the reproduction weight and labour’s share — to what it costs him in consumption and in capital. Durability enters only the cost, and it lowers it: the more of next period’s capital he inherits rather than buys, the smaller the part of it the tax touches. At the durable limit the floor is $\beta^2(1-\alpha)\gamma(1-\theta_R)$ in odds form, and depends on $\delta$ not at all. The object Chamley and Judd use to send a capital-income tax to zero is, when the revenue reproduces labour nobody owns, the object that holds it up.

------------------------------------------------------------------------

## Appendix A. The uniform floor

### A.1 Proof of Lemma 7

Run the tax path $\{\tau_t\}$ optimal at $(k+\Delta,n,g)$ from both states; it is feasible at both, since $\tau_t\in(0,1)$ is unconstrained by $K$. Write $\Delta_t$, $\nu_t$, $\xi_t$ for the gaps in $k$, $n$, $g$ and $\mu_t:=\alpha\Delta_t+(1-\alpha)\nu_t$ for the gap in $\ln Y_t$, which is the gap in $E_{C,t}$ and in $E_{W,t}$ as well. Then $\xi_{t+1}=\mu_t$ and

$$
\nu_{t+1}=\rho\nu_t+\gamma\theta_R\mu_t+\eta\xi_t ,
$$

a convex combination because $\rho+\gamma\theta_R+\eta=(1-\gamma)+\gamma\theta_R+\gamma(1-\theta_R)=1$. Capital gives

$$
e^{\Delta_{t+1}}=\frac{(1-\delta)K_t}{K_{t+1}}\,e^{\Delta_t}+\frac{i(1-\tau_t)e^{E_{C,t}}}{K_{t+1}}\,e^{\mu_t},
$$

again a convex combination, since the two weights are non-negative and sum to one by the capital law. Hence $z_t:=\max(\Delta_t,\nu_t,\xi_t)$ satisfies $z_{t+1}\le z_t$, and $z_t\le z_0=\Delta$ for all $t$.

The period-$t$ payoff gap is $(1-\omega)\mu_t+\omega\Delta_t$, a convex combination of $\mu_t$ and $\Delta_t$, hence at most $z_t\le\Delta$. Summing with weights $\beta^t$ bounds the value of that path from the lower state by $\Delta/(1-\beta)$ below the value at the upper state. The left-hand side of the lemma is no larger, because the path is optimal above and merely feasible below. $\square$

### A.2 Proof of Proposition 10

Fix a state and a $\tau$ with $\tau/(1-\tau)<c$, and take $\lambda>1$ with $\lambda\tau<1$. Write $R:=(1-\delta)K\ge 0$ and $B:=ie^{E_C}>0$, so that $k'(\tau)=\ln(R+B(1-\tau))$ and

$$
k'(\tau)-k'(\lambda\tau)=\ln\Bigl(1+\frac{B(\lambda-1)\tau}{R+B(1-\lambda\tau)}\Bigr)\le\ln(1+u)\le u,
\qquad u:=\frac{(\lambda-1)\tau}{1-\lambda\tau},
$$

the first inequality because $R\ge 0$ only enlarges the denominator, the second because $\ln(1+u)\le u$. Lemma 7 prices that loss at no more than $u/(1-\beta)$, and it does so at the continuation state whose $g$ has already been raised.

The one-period comparison of Proposition 8 prices the gain from $g'(\lambda\tau)-g'(\tau)=\ln\lambda$ at no less than $\beta(1-\omega)(1-\alpha)\eta\ln\lambda$, holding subsequent instruments fixed. Current utility falls by $(1-\omega)\ln\frac{1-\tau}{1-\lambda\tau}\le(1-\omega)u$. Collecting the three terms,

$$
W(\lambda\tau)-W(\tau)\ \ge\ P\ln\lambda-\Bigl[(1-\omega)+\frac{\beta}{1-\beta}\Bigr]u
= P\ln\lambda-Qu .
$$

Divide by $\lambda-1$ and let $\lambda\downarrow 1$. Since $\ln\lambda/(\lambda-1)\to 1$ and $u/(\lambda-1)\to\tau/(1-\tau)$, the right-hand side tends to $P-Q\,\tau/(1-\tau)$, which is strictly positive exactly when $\tau/(1-\tau)<c$. By continuity some $\lambda>1$ has $W(\lambda\tau)>W(\tau)$, so $\tau$ is not a maximiser. Every $\tau$ in $(0,\bar\tau)$ satisfies $\tau/(1-\tau)<c$, since $t\mapsto t/(1-t)$ is increasing and $\bar\tau/(1-\bar\tau)=c$. $\square$

------------------------------------------------------------------------

## References

Acemoglu, D. (2002). Directed technical change. *Review of Economic Studies* 69(4): 781–809.

Barro, R. J. (1990). Government spending in a simple model of endogenous growth. *Journal of Political Economy* 98(5): S103–S125.

Chamley, C. (1986). Optimal taxation of capital income in general equilibrium with infinite lives. *Econometrica* 54(3): 607–622.

Galor, O., and O. Moav (2006). Das human-kapital: a theory of the demise of the class structure. *Review of Economic Studies* 73(1): 85–117.

Judd, K. L. (1985). Redistributive taxation in a simple perfect foresight model. *Journal of Public Economics* 28(1): 59–83.

Kennedy, C. (1964). Induced bias in innovation and the theory of distribution. *Economic Journal* 74(295): 541–547.

Marx, K. *Capital*, Volume I, chapter 23 (Moore–Aveling translation).

Straub, L., and I. Werning (2020). Positive long-run capital taxation: Chamley–Judd revisited. *American Economic Review* 110(1): 86–119.

[^1]: At $\sigma>1$, $Y/K$ tends to a positive constant as $x\to+\infty$.

[^2]: A continuous self-map of a compact interval would give existence by Brouwer; uniqueness of $\tau^*$ would need concavity of $W$.
