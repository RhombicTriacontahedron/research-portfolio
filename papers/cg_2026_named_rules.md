# Implementation after the Rule Is Named
Carlos Galindo Escajeda
2026-09-01

**JEL.** D82, O33, D33, E11, H21

**Keywords.** named social-choice rule; incentive compatibility;
ratification; assigned programmes as primitives

------------------------------------------------------------------------

## Nontechnical abstract

A tax on capital income funds a public stock that reproduces labour
nobody owns. The owner of capital and the worker want different rates.
This paper asks a narrower question. Once a rule has named one of those
rates — or a compromise between them — can a mechanism produce that rate
when the weight that indexes it is known only to one class?

Assigned programmes exist before any mechanism. A rule is a map from
that weight to a feasible policy. Implementation is whether some
mechanism produces the image of the map.

If everyone sees the weight, any feasible named rule is implemented by
selecting its image. If firms keep control of the machine mix, only the
tax remains political. If one class alone sees the weight, that class
will report its own assigned programme truthfully. It will not report
the other class’s tax truthfully, and it will not report a compromise
tax truthfully wherever that compromise moves with the report. The
private-ownership recipe that sets the tax to zero after a reshuffle of
capital shuts the public stock. In the log payoffs used below that
shut-down is ruin for both classes. A reshuffle of capital still does
not transfer next period’s labour, and a single statutory tax is not two
personalised prices for the public stock.

------------------------------------------------------------------------

## Technical abstract

Outcome space $\mathcal{X}$ is the set of constant instruments. Under a
mandate $\mathcal{X}=\{(\tau,d,i)\}$. Under ratification
$\mathcal{X}=\{(\tau,i)\}$ with $d\equiv d_M$. Type space $\Theta=(0,1)$
for $\theta_R$, either common knowledge or privately observed by one
named party. Named rules

$$
\begin{aligned}
f_C(\theta_R)&=(\tau_C,d_C,i_C)(\theta_R),\\
f_W(\theta_R)&=(\tau_W,d_W,i_W)(\theta_R),\\
f_\lambda(\theta_R)&=(\tau(\lambda),d(\lambda),i(\lambda))(\theta_R),\\
f_\times(\theta_R)&=(\tau_C,d_W,i_\star)(\theta_R),\\
f_0(\theta_R)&=(0,d_M,i_C(\theta_R)).
\end{aligned}
$$

The last map is the private-ownership recipe written as a social-choice
rule. Its tax coordinate is identically zero, so $G'=0$. On the domain
$\tau_C(\theta_R)>0$, hence $f_0(\theta_R)$ is not a point of
$[\tau_C,\tau_W]$.

On the domain used below each of $f_C$, $f_W$, and $f_\lambda$ lands in
$\mathcal{X}$. The map $f_\times$ is a feasible function and is not the
programme of either assigned chooser or of any $\lambda\in[0,1]$.

Complete information implements any feasible named $f$ by selection. No
incentive constraint appears.

Let the owner observe $\theta_R$ privately. The direct mechanism for
$f_C$ satisfies

$$
V_C\bigl(f_C(\hat\theta_R),\theta_R\bigr)\;\le\;V_C\bigl(f_C(\theta_R),\theta_R\bigr)
\qquad\text{for all }\theta_R,\hat\theta_R\in\Theta.
$$

Under ratification, at fixed $d=d_M$ and fixed $i$, the same inequality
holds with $\tau_C$ in place of $f_C$. It fails for $\tau_W$:
$\partial\tau_W/\partial\theta_R<0$ at fixed shares, $\tau_C<\tau_W$,
and $V_C$ is strictly decreasing in $\tau$ on $(\tau_C,1)$, so a small
upward misreport raises $V_C$. The dual statements hold when the worker
is the named holder of $\theta_R$. Own-programme incentive compatibility
is Proposition 4. The ratified mediant is Proposition 11. Constant taxes
are incentive-compatible; a strictly decreasing selection above $\tau_C$
is not, for the owner (Propositions 6$'$ and 7$'$). In general, at fixed
direction, a differentiable tax schedule that is locally
incentive-compatible for the holder of the type is, at each type, flat
or equal to the holder’s own peak (Corollary 1).

------------------------------------------------------------------------

## Nontechnical introduction

Capital is owned. Successor labour is not. A tax on capital income fills
a public stock that helps reproduce that labour. Each class, if it held
the instruments as a constant policy, would choose a different tax and,
when machines can substitute for labour, a different mix of machines.
Those assigned programmes are primitives here.

A social-choice rule names one feasible policy for each value of the
private-reproduction weight. Implementation asks whether a mechanism
produces that policy. The question is empty until the rule, the
institution, and the information structure are named.

Two institutions. A mandate leaves the machine mix political.
Ratification has firms set the mix that maximises current output; only
the tax remains political.

A reading that treats ratification as the device that makes a compromise
tax impossible over-claims what is proved. Own-programme incentive
compatibility holds under both institutions (Proposition 4). A
type-contingent compromise that moves with the report fails under
ratification (Proposition 11). At unit elasticity it also fails under a
mandate, because every listed chooser wants the same direction and the
remaining instrument is the tax (Proposition 13). Off that face, a
report that moves tax and direction together is not signed from the two
loadings alone. Leaving the machine mix to firms is therefore not what
dooms the compromise.

The weight $\theta_R$ is how much of labour’s reproduction is paid from
wages rather than from the public stock. That stock is filled from
capital income. Marx treats the wage bill as “only a particular
historical form of appearance of the fund which he must himself produce
and reproduce” (*Capital* I, ch. 23). A tax on capital income that fills
the public stock is another form of appearance of the same fund: an
incidence statement, not a claim about whose labour produced the output.
A mechanism that elicits $\theta_R$ is asking a class to report that
split. “Capital is reckless of the health or length of life of the
labourer, unless under compulsion from society” (*Capital* I, ch. 10). A
named rule is that compulsion in this instrument set. The proofs do not
use the quotation; they use incentive compatibility of assigned
programmes.

Two information structures. The weight may be common knowledge, or it
may be seen only by one named class. Common knowledge creates no
incentive to lie. Private observation does.

A hybrid that pairs the owner’s tax with the worker’s mix is written
down because the two instruments load different channels. Proposition 3
records that the pairing satisfies no single programme’s first-order
conditions.

The private-ownership recipe — reshuffle capital, then markets, with the
tax off — is written down because it is what the second welfare theorem
would do in this environment. Naming it as a rule lets that operation be
accepted or rejected. No extra message space is required for the test.
The peaks and payoffs used below are stated in this paper.

------------------------------------------------------------------------

## Primitives

Two classes of fixed measure. Owners hold $K$. Workers supply $L$ and
hold no assets. Production is CES with elasticity $\sigma$. Factor
shares $s_K$, $s_L$ are evaluated at a reference effective
capital–labour ratio $\bar x$. A public stock $G$ is filled by an
in-kind tax on capital income: $G'=\tau e^{E_C}$ at the corner
$\varphi=1$. Labour evolves as $$
n'=n+\gamma\theta_R(E_W-n)+\gamma(1-\theta_R)(g-n).
$$ Worker felicity is $n$. Owner felicity is
$(1-\omega)\ln C_C+\omega k$. Common discount $\beta\in(0,1)$. Assigned
programmes are the constant policies each class would hold. At
$\varphi=1$ and fixed companions the tax payoffs are strictly concave in
$\tau$ with peaks $\tau_C<\tau_W$ displayed below. For $\sigma>1$ and
$\theta_R>0$, $s_L/\sigma<d_C<d_M$ and $d_W>d_C$. The worker lies above
$d_M$ if and only if
$\theta_R>\bar\theta:=\beta s_L/[s_K(1-\beta)+\beta s_L]$. Loadings:
$\partial\tau_C/\partial\theta_R<0$; $\partial d_C/\partial\theta_R>0$
only for $\sigma>1$; at $\sigma=1$ every listed chooser wants
$d=1-\alpha$. At interior $i_C$, $V_{C,i}=0$ and $V_{W,i}>0$.

**Outcome space.** Interior constant instruments are points of
$\mathcal{X}$. Under a mandate,

$$
\mathcal{X}=\bigl\{(\tau,d,i):\tau\in(0,1),\;d\in(0,1),\;i\in(0,1)\bigr\}.
$$

Under ratification firms set $d=d_M=s_L$, and

$$
\mathcal{X}=\bigl\{(\tau,i):\tau\in(0,1),\;i\in(0,1)\bigr\}.
$$

The extended space is $\bar{\mathcal{X}}=\mathcal{X}\cup\{\tau=0\}$,
with the same companions. At $\varphi=1$ the payoff in the tax is
$V_j=M_j\ln(1-\tau)+N_j\ln\tau+H_j$ with $M_j,N_j>0$ on the licensed box
and $H_j$ free of $\tau$. The convention on $\{\tau=0\}$ is
$V_j=\lim_{\tau\to 0^+}V_j=-\infty$. Class-specific Lindahl tax-prices
for $G$ are not coordinates of $\bar{\mathcal{X}}$.

**Type space.** $\Theta=(0,1)$ indexes $\theta_R$. No second private
type is introduced.

**Named rules.** On the licensed domain,

$$
\begin{aligned}
f_C(\theta_R)&=(\tau_C(\theta_R),d_C(\theta_R),i_C(\theta_R)),\\
f_W(\theta_R)&=(\tau_W(\theta_R),d_W(\theta_R),i_W(\theta_R)),\\
f_\lambda(\theta_R)&=\arg\max_{x\in\mathcal{X}}\bigl\{\lambda V_W(x;\theta_R)+(1-\lambda)V_C(x;\theta_R)\bigr\},\\
f_\times(\theta_R)&=\bigl(\tau_C(\theta_R),d_W(\theta_R),i_\star(\theta_R)\bigr),\\
f_0(\theta_R)&=\bigl(0,d_M,i_C(\theta_R)\bigr).
\end{aligned}
$$

Under ratification $f_0$ is read as $(0,i_C(\theta_R))$. That point lies
in $\bar{\mathcal{X}}$ and not in $\mathcal{X}$.

Under ratification the direction coordinate is deleted and each rule is
read as its fiscal projection, with $d\equiv d_M$. The symbol $i_\star$
is any feasible investment share named by the hybrid; no first-order
condition is attached to it.

**Information.** Either $\theta_R$ is common knowledge, or $\theta_R$ is
privately observed by one named party and the other party and the
mechanism designer know only $\Theta$ and the named rule.

**Institution.** Mandate or ratification, as above.

**Direct mechanism.** A direct mechanism for a named $f$ asks the holder
of $\theta_R$ for a report $\hat\theta_R\in\Theta$ and enforces
$f(\hat\theta_R)$. No other message set is used.

Imported peaks used below, at $\varphi=1$ and at fixed shares,

$$
\begin{aligned}
\tau_C&=\frac{\beta^2\gamma(1-\theta_R)\,(s_L/\sigma)}{1-\beta+\beta\gamma(1-\theta_R)+\beta\gamma\theta_R(s_K/\sigma)},\\[4pt]
\tau_W&=\frac{(1-\theta_R)\bigl(1-\beta+\beta s_L/\sigma\bigr)}{1-\theta_R+\theta_R(s_K/\sigma)}.
\end{aligned}
$$

On the licensed box both payoffs are strictly concave in $\tau$ at fixed
companions, with unique peaks $\tau_C<\tau_W$. Holding $d$ and $i$
fixed, $[\tau_C,\tau_W]$ is the tax Pareto interval. For $\sigma>1$ and
$\theta_R>0$, $s_L/\sigma<d_C<d_M$ and $d_W>d_C$. The worker lies above
$d_M$ if and only if $\theta_R>\bar\theta$. Complementary loadings:
$\partial\tau_C/\partial\theta_R<0$; $\partial d_C/\partial\theta_R>0$
only for $\sigma>1$; at $\sigma=1$ every listed chooser wants
$d=1-\alpha$ and the tax gap remains.

------------------------------------------------------------------------

## Complete information

When $\theta_R$ is common knowledge the named rule is a known point of
$\mathcal{X}$.

**Proposition 1 (Selection under a mandate).** Under complete
information and a mandate, a mechanism implements $f$ if and only if it
selects $f(\theta_R)$. Incentive compatibility is empty.

The feasible set is $\mathcal{X}$. Complete information and an
unconstrained mandate reduce implementation to selection (Dasgupta,
Hammond and Maskin 1979, in the complete-information reading that
dispenses with a message game). Assigned points $f_C(\theta_R)$ and
$f_W(\theta_R)$ are available. The mediant $f_\lambda(\theta_R)$ is
available. Each is a well-defined map on the licensed domain.

**Proposition 2 (Selection under ratification).** Under complete
information and ratification, a mechanism implements $f$ if and only if
it selects the fiscal projection of $f(\theta_R)$ at $d=d_M$. The
political object that remains is a point of the tax interval
$[\tau_C,\tau_W]$ together with a feasible $i$, at that locked
direction.

Ratification is an institutional restriction on $\mathcal{X}$, not a
restriction on preferences. The assigned programmes $f_C$ and $f_W$ are
not available in their direction coordinate. A mediant equals $d_M$ if
and only if $\theta_R>\bar\theta$, and only at one $\lambda$. That fact
is not used as an incentive constraint.

------------------------------------------------------------------------

## Coherence of the hybrid

$f_\times$ is a function from $\Theta$ into the mandate set
$\mathcal{X}$ once $i_\star(\theta_R)$ is named. Feasibility of the
function is not coherence of a programme.

**Proposition 3 (Emptiness as a programme).** There is no assigned
chooser in $\{C,W\}$ and no weight $\lambda\in[0,1]$ such that
$f_\times(\theta_R)$ satisfies that chooser’s or that planner’s
first-order conditions in $(\tau,d)$ jointly, on the licensed domain
where $\tau_C(\theta_R)\neq\tau_W(\theta_R)$ and
$d_C(\theta_R)\neq d_W(\theta_R)$.

*Proof.* The owner’s assigned first-order condition in the tax is
$\tau=\tau_C$. The worker’s assigned first-order condition in direction
is $d=d_W$. Those two equalities are the tax and direction coordinates
of $f_\times$. They are not the two first-order conditions of $V_C$,
because $d_C\neq d_W$ on the stated domain. They are not the two
first-order conditions of $V_W$, because $\tau_C\neq\tau_W$. The planner
$f_\lambda$ is a mediant: $\tau(\lambda)=\tau_C$ if and only if
$\lambda=0$, and $d(\lambda)=d_W$ if and only if $\lambda=1$. No
$\lambda$ satisfies both. $\square$

Opposite monotonicity of $\tau_C(\theta_R)$ and $d_C(\theta_R)$ along
$f_C$ for $\sigma>1$ is a property of the peaks. It is not an emptiness
statement about $f_\times$, and it is not a message-space obstruction.

Until $f_\times$ is rewritten as the solution of a single programme, it
is not a candidate for an incentive-compatibility statement. The
remainder of the paper does not use $f_\times$.

------------------------------------------------------------------------

## The private-ownership rule

The Second Welfare Theorem’s operation with its hypothesis on $L'$
dropped, rather than repaired, is the private-ownership recipe: a
reshuffle of $K$, competitive factor payments, and no public instrument.
That recipe, written as a rule, is $f_0\in\bar{\mathcal{X}}$. A Lindahl
scheme with class-specific tax-prices for $G$ (Foley 1970) is a repair
of the hypothesis and is not a point of $\bar{\mathcal{X}}$.

$G'=\varphi\tau e^{E_C}$. Under $f_0$, $\tau=0$, hence $G'=0$ at every
type.

**Lemma 0 (Boundary values).** For $j\in\{C,W\}$ and fixed companions,
$V_j(\tau)\to-\infty$ as $\tau\to 0^+$ and as $\tau\to 1^-$, and $V_j$
is finite on $(0,1)$ with peak $N_j/(M_j+N_j)$.

*Proof.* On the licensed box $M_j,N_j>0$ and
$V_j=M_j\ln(1-\tau)+N_j\ln\tau+H_j$. $\square$

**Proposition 8 (Shut-down).** For every $\theta_R$ in the licensed
domain and every $(d,i)$, every $\tau\in(0,1)$ strictly Pareto-dominates
$\tau=0$ for $(V_C,V_W)$. In particular
$f_0(\theta_R)\notin[\tau_C,\tau_W]$. Zero tax and full confiscation
are, for both classes, the same boundary value $-\infty$. The statement
uses essentiality of $G$ in the log class. The local statement on
$(0,\tau_C)$ is that both values rise in $\tau$ on that interval.

**Proposition 9 (Implementation of $f_0$ is uninformative).** Under the
convention of Lemma 0,
$V_j(f_0(\hat\theta_R);\theta_R)=V_j(f_0(\theta_R);\theta_R)=-\infty$
for both $j$ and every pair of types, so the direct mechanism for $f_0$
is weakly incentive-compatible for either holder. If a positive
inherited stock made $V_j(f_0)$ finite, incentive compatibility in the
coordinate $i_C(\hat\theta_R)$ would require $i_C$ to be the holder’s
peak at companions $(0,d_M)$, which is not used here.

**Premise P.** A reshuffle of $K$, indexed by the owners’ share
$\kappa$, enters $V_j$ only through $H_j(\kappa)$, with $H_C$ increasing
and $H_W$ decreasing in $\kappa$, both concave. It leaves class labels,
worker felicity $n$, and the shares at $\bar x$ unchanged.

Assigned programmes here are derived with two classes of fixed measure
and with workers holding no assets. Premise P is not implied by that
environment. A transfer of $K$ to workers that made worker felicity
include capital income would exit that environment. P is the restriction
that keeps the peaks.

**Proposition 10 (Non-separation under P).** Assume P. On the licensed
domain, at fixed $(d,i)$:

1.  No $\kappa$ yields unanimity over $\tau$: the peaks $\tau_C<\tau_W$
    do not depend on $\kappa$.
2.  Every Pareto optimum over $(\tau,\kappa)$ has tax in
    $[\tau_C,\tau_W]$. For $\lambda\in(0,1)$ that tax is the planner
    peak $\tau_\lambda$ of Proposition 11.
3.  No $\kappa$ selects $\tau=0$.

*Proof.* Under P the first-order condition in $\tau$ for
$\lambda V_W+(1-\lambda)V_C$ does not involve $\kappa$ and returns
$\tau_\lambda$. Proposition 11 places $\tau_\lambda$ in
$(\tau_C,\tau_W)$ for $\lambda\in(0,1)$. The endpoints are the assigned
peaks. Lemma 0 excludes $\tau=0$. $\square$

$f_0$ is Pareto-dominated by every interior tax, whatever the
distribution of $K$ under P. Restoring a single public instrument $\tau$
puts every two-class Pareto tax in $[\tau_C,\tau_W]$. Under P that
interval does not move with $\kappa$. Bergstrom–Cornes independence of
the *set* therefore holds. Unanimity does not: no $\kappa$ collapses
$\tau_C$ onto $\tau_W$. There is no unique efficient tax to fix and then
implement by transferring $K$. A mandate that selects a point of the
interval funds $G$.

**Theorem (Separation).** The second welfare theorem uses transfers of
owned endowments to separate a production-and-provision plan from
distribution (Arrow 1951; Debreu 1959). In this environment three facts
hold.

1.  Successor labour $L'$ is not an owned endowment. No coordinate of
    $\bar{\mathcal{X}}$ transfers it.
2.  The dropped-hypothesis recipe $f_0$ sets $\tau=0$ and $G'=0$. By
    Lemma 0 and Proposition 8 every interior tax strictly
    Pareto-dominates that recipe for the two assigned objectives.
3.  Under Premise P the assigned peaks satisfy
    $\tau_C(\theta_R)<\tau_W(\theta_R)$ independently of the owners’
    share of $K$. The interval $[\tau_C,\tau_W]$ is therefore the same
    at every such $\kappa$. No class-preserving reshuffle of $K$
    produces a unanimous tax. Every two-class Pareto tax, once a public
    instrument is restored, lies in that interval.

Bergstrom and Cornes (1983) independence of the *set* of efficient
public quantities from private-good distribution holds under P: the set
does not move with $\kappa$. Separation still fails: there is no unique
efficient plan to hold fixed while transferring $K$, successor labour is
not transferable, and the dropped-hypothesis recipe is shut-down of $G$.
Class-specific Lindahl prices (Foley 1970) are a different instrument
set.

**Proposition 12 (Uniform tax is not Lindahl).** At $\varphi=1$,
$G'=\tau e^{E_C}$. Every point of $\bar{\mathcal{X}}$ funds $G$ from
capital income only: the owner’s statutory contribution is
$\tau e^{E_C}$ and the worker’s statutory contribution is $0$. On the
licensed box $N_W>0$, so $V_{W,\tau}>0$ on $(0,\tau_W)$. A Lindahl
equilibrium for $G$ requires a personalized price $p_W$ at which the
worker demands the implemented $G'$, and $p_W=0$ only if that demand is
satiated. Satiation fails on $(0,\tau_W)$. Hence no point of
$\bar{\mathcal{X}}$ is a Lindahl equilibrium for $G$.

*Proof.* Personalized prices $(p_C,p_W)$ are not coordinates of
$\bar{\mathcal{X}}$. The implied statutory pair is $(p_C,0)$ in units of
capital income. Lemma 0 and $N_W>0$ give a finite peak $\tau_W\in(0,1)$
and $V_W\to-\infty$ as $\tau\to 0^+$, so the worker is not satiated at
$G'=0$ and is not satiated at any $G'$ produced by $\tau\in(0,\tau_W)$.
A zero worker price is then not a Lindahl price. $\square$

A mandate that selects a point of $[\tau_C,\tau_W]$ funds $G$. It does
not construct $(p_C,p_W)$.

------------------------------------------------------------------------

## Private $\theta_R$ under a mandate

The holder of the type is named. The other class does not report.

**Proposition 4 (Own-programme incentive compatibility).** Suppose the
owner privately observes $\theta_R$. On the licensed domain the direct
mechanism for $f_C$ is incentive-compatible for the owner:

$$
V_C\bigl(f_C(\hat\theta_R),\theta_R\bigr)\;\le\;V_C\bigl(f_C(\theta_R),\theta_R\bigr)
\qquad\forall\,\theta_R,\hat\theta_R\in\Theta.
$$

Suppose instead the worker privately observes $\theta_R$. The direct
mechanism for $f_W$ is incentive-compatible for the worker by the same
argument with $W$ in place of $C$.

*Proof.* By construction of the assigned programme,
$f_C(\theta_R)\in\arg\max_{x\in\mathcal{X}}V_C(x;\theta_R)$ on the
licensed domain. The menu $\{f_C(\hat\theta_R):\hat\theta_R\in\Theta\}$
is a subset of $\mathcal{X}$ that contains the maximiser
$f_C(\theta_R)$. The owner therefore does not gain by naming any other
type. The worker case is identical. $\square$

The argument is the single-agent revelation principle applied to an
assigned peak (Myerson 1979). It does not use a crossing condition in
$\theta_R$. It does not use $\sigma>1$. It uses interiority only to the
extent that the peaks lie in $\mathcal{X}$.

**Proposition 5 (Mediant off Cobb–Douglas).** Let $\lambda\in(0,1)$ and
let the owner privately observe $\theta_R$. For $\sigma>1$, a report of
$f_\lambda$ moves $\tau$ and $d$ together. Along $f_C$ the loadings have
opposite signs. Those loadings do not sign the net change in $V_C$.

The menu $\{f_\lambda(\hat\theta_R)\}$ does not contain $f_C(\theta_R)$.
A report moves $\tau$ and $d$ together. Along $f_C$ the loadings have
opposite signs: $\partial\tau_C/\partial\theta_R<0$ and
$\partial d_C/\partial\theta_R>0$. A mediant path that remains between
the assigned peaks inherits that tension. The net effect on $V_C$ is not
signed from those loadings alone. The same stop applies to $f_W$ offered
to the owner under a mandate.

**Proposition 13 (Mandate mediant at $\sigma=1$).** At $\sigma=1$, every
listed chooser wants $d=1-\alpha$. Holding $i$ fixed, the mandate
problem for $f_\lambda$ in $(\tau,d)$ reduces to the ratified problem in
$\tau$ at that common direction. Proposition 11 therefore applies under
a mandate: for $\lambda\in(0,1)$, $\tau_C<\tau_\lambda<\tau_W$,
$\tau_\lambda$ is not constant on $\Theta$, and at every type where
$\tau_\lambda'\neq 0$ the direct mechanism is not locally
incentive-compatible for either named holder of $\theta_R$.

*Proof.* At $\sigma=1$ directional disagreement is deleted. The common
peak equals $d_M=1-\alpha$. A report cannot gain on $d$. The remaining
instrument is $\tau$ at companions $(d_M,i)$. That is Proposition 11.
$\square$

------------------------------------------------------------------------

## Ratification under private $\theta_R$

Ratification deletes $d$. Companions $i$ that are not named by the
fiscal rule are held fixed, as in the tax interval at fixed companions.

**Lemma (Worker’s tax declines in the type).** At fixed shares,
$\partial\tau_W/\partial\theta_R<0$ on $\Theta$.

*Proof.* Write $A=1-\beta+\beta s_L/\sigma>0$ and $B=s_K/\sigma>0$, both
independent of $\theta_R$ at fixed shares. Then

$$
\tau_W=\frac{A(1-\theta_R)}{1-\theta_R+\theta_R B}.
$$

Differentiating,

$$
\frac{\partial\tau_W}{\partial\theta_R}
=\frac{A\bigl[-(1-\theta_R+\theta_R B)-(1-\theta_R)(-1+B)\bigr]}{(1-\theta_R+\theta_R B)^2}
=\frac{-AB}{(1-\theta_R+\theta_R B)^2}<0.
$$

$\square$

The loading $\partial\tau_C/\partial\theta_R<0$ follows from the
displayed formula for $\tau_C$ at fixed shares.

**Proposition 6 (Ratified taxes).** Let $d=d_M$ and let $i$ be fixed.
Suppose the owner privately observes $\theta_R$.

1.  The direct mechanism for $\tau_C(\cdot)$ is incentive-compatible for
    the owner.
2.  The direct mechanism for $\tau_W(\cdot)$ is not. For every
    $\theta_R$ in the licensed domain there exists
    $\hat\theta_R>\theta_R$ such that

$$
V_C\bigl(\tau_W(\hat\theta_R),d_M,i;\theta_R\bigr)
\;>\;
V_C\bigl(\tau_W(\theta_R),d_M,i;\theta_R\bigr).
$$

*Proof.* Claim 1 is Proposition 4 read on the ratified outcome space:
$\tau_C(\theta_R)$ maximises $V_C(\tau,d_M,i;\theta_R)$ in $\tau$, so
the menu of own peaks contains the maximiser.

Claim 2. On the licensed box $V_C$ is strictly concave in $\tau$ with
unique peak $\tau_C(\theta_R)<\tau_W(\theta_R)$. Hence $V_C$ is strictly
decreasing in $\tau$ on $[\tau_C(\theta_R),1)$. The lemma gives $\tau_W$
strictly decreasing and continuous in the report. A sufficiently small
upward misreport therefore lowers the implemented tax while leaving it
above $\tau_C(\theta_R)$, which raises $V_C$. $\square$

**Proposition 7 (Dual holder).** Let $d=d_M$ and let $i$ be fixed.
Suppose the worker privately observes $\theta_R$. The direct mechanism
for $\tau_W(\cdot)$ is incentive-compatible for the worker. The direct
mechanism for $\tau_C(\cdot)$ is not: $V_W$ is strictly increasing in
$\tau$ on $(0,\tau_W)$, $\tau_C(\theta_R)<\tau_W(\theta_R)$, and
$\partial\tau_C/\partial\theta_R<0$, so a small downward misreport
raises $V_W$.

*Proof.* Own-peak inclusion gives the first sentence. For the second,
strict concavity of $V_W$ in $\tau$ with peak $\tau_W$ implies that
$V_W$ rises when $\tau$ rises on $(0,\tau_W)$. A downward misreport
raises $\tau_C$ while leaving it below $\tau_W$. $\square$

**Proposition 6$'$ (What ratification can elicit).** Let $d=d_M$ and let
$i$ be fixed. Let the owner privately observe $\theta_R$.

1.  Every constant rule $\tau(\theta_R)\equiv\bar\tau\in(0,1)$ is
    incentive-compatible.
2.  The direct mechanism for $\tau_C(\cdot)$ is incentive-compatible
    (Proposition 6).
3.  If $s:\Theta\to(0,1)$ is strictly decreasing and
    $s(\theta_R)>\tau_C(\theta_R)$, the direct mechanism for $s$ is not
    locally incentive-compatible for the owner at $\theta_R$.

*Proof.* Claim 1: the implemented tax does not depend on the report.
Claim 2 is Proposition 6. Claim 3: $V_C$ is strictly decreasing in
$\tau$ on $(\tau_C(\theta_R),1)$. Because $s'<0$, a small upward
misreport lowers the implemented tax. For a small enough lie the new tax
remains in $(\tau_C(\theta_R),s(\theta_R)]$, so $V_C$ rises. $\square$

**Proposition 7$'$ (Dual elicitation).** Let $d=d_M$ and let $i$ be
fixed. Let the worker privately observe $\theta_R$.

1.  Every constant rule $\tau(\theta_R)\equiv\bar\tau\in(0,1)$ is
    incentive-compatible.
2.  The direct mechanism for $\tau_W(\cdot)$ is incentive-compatible
    (Proposition 7).
3.  If $s:\Theta\to(0,1)$ is strictly decreasing and
    $s(\theta_R)<\tau_W(\theta_R)$, the direct mechanism for $s$ is not
    locally incentive-compatible for the worker at $\theta_R$.

*Proof.* Claim 1 as in Proposition 6$'$. Claim 2 is Proposition 7. Claim
3: $V_W$ is strictly increasing in $\tau$ on $(0,\tau_W(\theta_R))$.
Because $s'<0$, a small downward misreport raises the implemented tax.
For a small enough lie the new tax remains in
$[s(\theta_R),\tau_W(\theta_R))$, so $V_W$ rises. $\square$

A constant compromise can be imposed without using the type. Where a
differentiable schedule moves with the report, truth-telling at first
order puts it on the holder’s own peak (Corollary 1 below). The tax
interval is the set of undominated constant taxes.

If a ratified rule also names $i(\theta_R)$ as a non-constant
coordinate, $V_{C,i}=0$ and $V_{W,i}>0$ at interior $i_C$.[^1]

**Proposition 11 (Ratified mediant, local first-order condition).** Let
$d=d_M$ and let $i$ be fixed. Let $\lambda\in(0,1)$, and write
$\tau_\lambda(\theta_R)$ for the unique maximiser of
$\lambda V_W+(1-\lambda)V_C$ in $\tau$. On the licensed box

$$
\tau_C(\theta_R)<\tau_\lambda(\theta_R)<\tau_W(\theta_R).
$$

The map $\tau_\lambda$ is not constant on $\Theta$. At every type where
$\tau_\lambda'(\theta_R)\neq 0$, the direct mechanism for $\tau_\lambda$
is not locally incentive-compatible for either named holder of
$\theta_R$.

*Proof.* At $\tau=\tau_C$, $V_{C,\tau}=0$ and $V_{W,\tau}>0$, so the
planner derivative is $\lambda V_{W,\tau}>0$. At $\tau=\tau_W$,
$V_{W,\tau}=0$ and $V_{C,\tau}<0$, so the planner derivative is
$(1-\lambda)V_{C,\tau}<0$. Strict concavity of both payoffs in $\tau$
gives a unique planner peak strictly between the assigned peaks.

As $\theta_R\to 1$, the displayed formulas give $\tau_C\to 0$ and
$\tau_W\to 0$, hence $\tau_\lambda\to 0$ by the sandwich. At any
interior $\theta_R$, $\tau_\lambda(\theta_R)>\tau_C(\theta_R)>0$. A
function that is positive on $(0,1)$ and tends to $0$ at $1$ is not
constant on $\Theta$.

Differentiating the holder’s payoff in the report at truth gives
$V_{j,\tau}(\tau_\lambda(\theta_R),\theta_R)\,\tau_\lambda'(\theta_R)$.
At $\tau_\lambda$, $V_{C,\tau}<0$ and $V_{W,\tau}>0$. If
$\tau_\lambda'\neq 0$ that product is nonzero for both $j\in\{C,W\}$.
Truth is then not a local stationary point. $\square$

The argument does not use a convex combination of $\tau_C$ and $\tau_W$.
The planner peak is the maximiser of a weighted sum of values, not a
fixed-weight average of the two tax numbers. Strict decrease of both
endpoints therefore does not imply $\tau_\lambda'<0$ at every type.
Where $\tau_\lambda'=0$, the local first-order condition holds and a
separate comparison is required. The small upward (owner) or downward
(worker) misreport is licensed only on the set where $\tau_\lambda'<0$.
That set is nonempty, because $\tau_\lambda$ is not constant and
$\tau_\lambda\to 0$ as $\theta_R\to 1$.[^2]

Propositions 6$'$, 7$'$ and 11 test particular schedules. The same
first-order argument applies to every schedule.

**Corollary 1 (Truth-telling at first order).** Let $d=d_M$ and let $i$
be fixed. Let $j\in\{C,W\}$ privately observe $\theta_R$, and let
$s:\Theta\to(0,1)$ be differentiable at $\theta_R$. If the direct
mechanism for $s$ is locally incentive-compatible for $j$ at $\theta_R$,
then $s'(\theta_R)=0$ or $s(\theta_R)=\tau_j(\theta_R)$.

*Proof.* Local incentive compatibility makes truth a local maximiser of
$\hat\theta_R\mapsto V_j\bigl(s(\hat\theta_R),d_M,i;\theta_R\bigr)$ on
the open set $\Theta$, so the derivative at truth,
$V_{j,\tau}\bigl(s(\theta_R),\theta_R\bigr)\,s'(\theta_R)$, is zero. On
the licensed box $V_{j,\tau}=N_j/\tau-M_j/(1-\tau)$ vanishes on $(0,1)$
only at the peak $N_j/(M_j+N_j)=\tau_j$. $\square$

At $\sigma=1$ the same statement holds under a mandate for a schedule
that names the common direction $1-\alpha$, because Proposition 13
reduces that problem to this one. A tax schedule can therefore respond
to what the holder of the type reports only by handing the holder its
own peak. Wherever a differentiable schedule is not the holder’s peak,
it is flat. The two can be combined. The owner’s peak censored below at
a constant $\underline\tau$, $s=\max(\tau_C,\underline\tau)$, is
incentive-compatible for the owner: a type whose peak lies above
$\underline\tau$ receives its peak, and a type whose peak lies below
receives $\underline\tau$, the lowest tax on offer, which it prefers to
every higher one because $V_C$ decreases above its peak.

Under a mandate a report of $f_\lambda$ moves $\tau$ and $d$ together.

------------------------------------------------------------------------

## Neighbouring objects

The information structure used is a one-dimensional private type and a
direct mechanism (Myerson 1979). Complete-information implementation is
selection on a named feasible set (Dasgupta, Hammond and Maskin 1979).
Menus that are not own-programme paths lack a monotone-difference
condition along the menu.

Foley (1970) puts personalized prices on a public good in the commodity
space. Proposition 12 is the statement that no point of
$\bar{\mathcal{X}}$ carries those prices: the worker’s statutory price
of $G$ is zero.

Directed-technique points $d_M$, $d_C$, and $d_W$ are assigned or
current-output peaks. The Second Welfare Theorem (Arrow 1951; Debreu
1959) is the theorem whose recipe is $f_0$.

------------------------------------------------------------------------

## Conclusion

A public stock $G$, filled by a tax on capital income, enters the law of
motion of successor labour, which no one owns. The assigned programmes
of the two classes exist before any mechanism. This paper asks whether a
named rule for that tax can be implemented when the weight $\theta_R$
that indexes it is private, and whether the private-ownership recipe of
the second welfare theorem can replace statutory provision. Complete
information reduces implementation to selection: of the named point
under a mandate, of its fiscal projection at $d_M$ under ratification
(Propositions 1 and 2). Beyond that, four conclusions follow.

First, the second welfare theorem’s separation fails here, and a
transfer of capital does not repair it. Successor labour is not an owned
endowment, so no coordinate of $\bar{\mathcal{X}}$ transfers it. The
private-ownership recipe $f_0$ sets $\tau=0$ and so $G'=0$. With log
payoffs that recipe is ruin for both classes, and every interior tax
strictly Pareto-dominates it (Lemma 0, Proposition 8). Under Premise P a
reshuffle of $K$ moves each class’s level $H_j(\kappa)$ and leaves the
tax Pareto interval $[\tau_C,\tau_W]$ where it was (Proposition 10).
Bergstrom–Cornes independence of the *set* therefore holds, and
unanimity fails: no reshuffle of $K$ brings $\tau_C$ onto $\tau_W$ or
selects $\tau=0$. Under P, then, redistributing capital cannot stand in
for the public instrument. P is a restriction, not a consequence: a
transfer that gave workers capital income would leave the two-class
environment in which the peaks are derived.

Second, ratification narrows the outcome space, and it is not what
defeats a compromise. When firms set the machine mix at the
current-output point $d_M=s_L$, direction leaves $\mathcal{X}$
(Proposition 2). For $\sigma>1$ that point lies above the owner’s peak,
$d_C<d_M$, and below the worker’s exactly when $\theta_R>\bar\theta$.
The tax and the investment share remain political. A compromise fails
without ratification as well: at $\sigma=1$ under a mandate every listed
chooser wants the same direction, and the mediant fails exactly as it
does under ratification (Proposition 13). The hybrid $f_\times$, which
pairs the owner’s tax with the worker’s direction, satisfies no single
programme’s first-order conditions and is not a programme (Proposition
3).

Third, private information confines a truthful tax schedule to flat
stretches and the holder’s own peak. With direction fixed, a
differentiable schedule that is locally incentive-compatible for the
holder of $\theta_R$ is, at each type, flat or equal to the holder’s
peak (Corollary 1). The propositions are instances. Each class reports
its own assigned programme truthfully (Proposition 4). Neither reports
the other’s tax truthfully: an owner who holds the type over-reports it
to pull $\tau_W$ down toward $\tau_C$, and a worker under-reports it to
push $\tau_C$ up toward $\tau_W$ (Propositions 6 and 7). The compromise
$\tau_\lambda$ lies strictly between the peaks, moves on $\Theta$, and
fails local incentive compatibility for either holder at every type
where it moves (Propositions 11 and 13). A constant tax is
incentive-compatible for either holder (Propositions 6$'$ and 7$'$). A
state that does not observe $\theta_R$ can therefore let a tax schedule
respond to it only by handing the holder its own peak, and must hold the
tax fixed elsewhere. For $\sigma>1$ under a mandate a report moves tax
and direction together, and whether a compromise can then be elicited is
not signed by the loadings alone (Proposition 5).

Fourth, a uniform tax on capital income cannot be read as a system of
Lindahl prices. Every point of $\bar{\mathcal{X}}$ funds $G$ from
capital income alone, so the worker’s statutory price of $G$ is zero.
The worker is not satiated on $(0,\tau_W)$, where $V_{W,\tau}>0$, so a
zero price is not a Lindahl price and no point of $\bar{\mathcal{X}}$ is
a Lindahl equilibrium (Proposition 12). Foley’s repair needs
personalised prices, which this instrument set does not contain. Under P
the Pareto interval does not move with $\kappa$ and contains no
unanimous point (Proposition 10). A mandate that selects a point of
$[\tau_C,\tau_W]$ funds $G$ at a single statutory price. Which point it
selects is a choice between the classes, and neither a price system nor
a transfer of capital makes that choice for it.

------------------------------------------------------------------------

## References

Arrow, K. J. (1951). An extension of the basic theorems of classical
welfare economics. In J. Neyman (ed.), *Proceedings of the Second
Berkeley Symposium on Mathematical Statistics and Probability*.
University of California Press.

Bergstrom, T. C., and R. C. Cornes (1983). Independence of allocative
efficiency from distribution in the theory of public goods.
*Econometrica* 51(6): 1753–1765.

Dasgupta, P., P. Hammond, and E. Maskin (1979). The implementation of
social choice rules: some general results on incentive compatibility.
*Review of Economic Studies* 46(2): 185–216.

Debreu, G. (1959). *Theory of Value*. Yale University Press.

Foley, D. K. (1970). Lindahl’s solution and the core of an economy with
public goods. *Econometrica* 38(1): 66–72.

Myerson, R. B. (1979). Incentive compatibility and the bargaining
problem. *Econometrica* 47(1): 61–73.

Samuelson, P. A. (1954). The pure theory of public expenditure. *Review
of Economics and Statistics* 36(4): 387–389.

[^1]: The local tax arguments hold $i$ fixed.

[^2]: Where $\tau_\lambda'=0$ a separate comparison is required.
