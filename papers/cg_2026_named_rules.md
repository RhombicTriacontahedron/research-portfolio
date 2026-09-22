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

Assigned programmes exist before any mechanism: each is the constant
value of one instrument that a class would choose if it alone chose that
instrument. A rule is a map from that weight to a feasible policy.
Implementation is whether some mechanism produces the image of the map.

If everyone sees the weight, any feasible named rule is implemented by
selecting its image. If firms keep control of the machine mix, only the
tax remains political. If one class alone sees the weight, that class
will report its own assigned programme truthfully. It will not report
the other class’s tax truthfully, and it will not report a compromise
tax truthfully wherever that compromise moves with the report. The
private-ownership recipe that sets the tax to zero after a reshuffle of
capital shuts the public stock. In the log payoffs used below that
shut-down is ruin for both classes. A reshuffle of capital that leaves
workers without capital income does not make the classes agree on the
tax, because the tax falls on income the owner consumes and the two
classes value capital differently. A single statutory tax is not two
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
f_W(\theta_R)&=(\tau_W(\theta_R),d_W(\theta_R),\bar\imath),\\
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
that is continuous at the true type is not, for the owner (Propositions
6$'$ and 7$'$). In general, at fixed direction and investment share, a
differentiable tax schedule that is locally incentive-compatible for the
holder of the type is, at each type, flat or equal to the holder’s own
peak (Corollary 1).

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
mandate, because every listed chooser wants the same direction and, with
the investment share held fixed, the remaining instrument is the tax
(Proposition 13). Off that face, a report that moves tax and direction
together is not signed from the two loadings alone. Leaving the machine
mix to firms is therefore not what dooms the compromise.

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
hold no assets. Production is CES with elasticity $\sigma$,
$\rho=1-1/\sigma$, and technology is a point
$(A,B)=(d^{\varepsilon},(1-d)^{\varepsilon})$ of a frontier indexed by
the direction $d\in(0,1)$, $\varepsilon>0$. Write $k,n,g$ for the logs
of $K$, $L$ and the public stock $G$, $a=\ln A$, $b=\ln B$, and
$x=b+k-a-n$ for the logged effective capital–labour ratio.
$E_C=\ln(s_KY)$ and $E_W=\ln(s_LY)$ are the logs of capital’s and
labour’s incomes. They are taken to first order about a reference ratio
$\bar x$, at which the factor shares $s_K$, $s_L$ are evaluated: $$
E_C=\text{const}+a_1(b+k)+(1-a_1)(a+n),\qquad E_W=\text{const}+a_2(b+k)+(1-a_2)(a+n),
$$ with $a_1=\rho+(1-\rho)s_K$ and $a_2=(1-\rho)s_K$, the slopes of
$\ln(s_KY)$ and $\ln(s_LY)$ in $x$ at $\bar x$. Under Cobb–Douglas
($\rho=0$) both equal capital’s share and the expansion is exact. The
owner saves a share $i$ of after-tax capital income, and a public stock
$G$ is filled by an in-kind tax on capital income at the corner
$\varphi=1$: $$
\ln C_C=\ln(1-i)+\ln(1-\tau)+E_C,\qquad k'=\ln i+\ln(1-\tau)+E_C,\qquad g'=\ln\tau+E_C .
$$ Labour evolves as $$
n'=n+\gamma\theta_R(E_W-n)+\gamma(1-\theta_R)(g-n).
$$ Worker felicity is $n$. Owner felicity is
$(1-\omega)\ln C_C+\omega k$. Common discount $\beta\in(0,1)$. The
*licensed box* is $\beta,\gamma,\theta_R,\omega\in(0,1)$ with
$a_1,a_2\in(0,1)$: every $s_K\in(0,1)$ when $\sigma\ge1$, and
$s_K\in(1-\sigma,\sigma)$ when $\tfrac12<\sigma<1$.

**Assigned programmes.** An assigned programme is the solution of a
restricted game with one player and one instrument. Class $j$ alone
chooses a constant value of one instrument to maximise $V_j$, subject to
the laws of motion above, with every other instrument held at a given
constant. It is not a Nash equilibrium of a game in which both classes
choose at once, and it is not a Ramsey plan. The value coefficients do
not depend on the instruments (Lemma A.1), so $V_j$ is a sum of separate
terms in $\tau$, $d$ and $i$, and a class’s peak in one instrument does
not depend on where the others are held. The same terms are maximised in
every period and in every state, so the restriction to a constant value
is without loss: a choice that varied with the date or with the state
would do no better (Appendix A). The tax and the direction have interior
peaks for both classes. The investment share has one only for the owner,
$i_C$. The worker’s value rises in $i$ at every $i$ (Lemma A.4), so the
worker’s programme holds $i$ at a given constant $\bar\imath\in(0,1)$
that no report moves.

At $\varphi=1$ and fixed companions the tax payoffs are strictly concave
in $\tau$ with peaks $\tau_C<\tau_W$ displayed below (all proved in
Appendix A). For $\sigma>1$ and $\theta_R>0$, $s_L/\sigma<d_C<d_M$ and
$d_W>d_C$. The worker lies above $d_M$ if and only if
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
f_W(\theta_R)&=(\tau_W(\theta_R),d_W(\theta_R),\bar\imath),\\
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
condition is attached to it. The worker’s investment coordinate
$\bar\imath$ is the given constant of the worker’s programme. The
mediant $f_\lambda$ is taken for $\lambda\in(0,1)$, where its investment
coordinate is interior. At $\lambda=0$ its peaks are the owner’s, and at
$\lambda=1$ its peaks in $(\tau,d)$ are the worker’s.

**Information.** Either $\theta_R$ is common knowledge, or $\theta_R$ is
privately observed by one named party and the other party and the
mechanism designer know only $\Theta$ and the named rule.

**Institution.** Mandate or ratification, as above.

**Direct mechanism.** A direct mechanism for a named $f$ asks the holder
of $\theta_R$ for a report $\hat\theta_R\in\Theta$ and enforces
$f(\hat\theta_R)$. No other message set is used.

The assigned tax peaks, at $\varphi=1$ and at fixed shares, are
(Appendix A, Lemma A.2)

$$
\begin{aligned}
\tau_C&=\frac{\beta^2\gamma(1-\theta_R)\,(s_L/\sigma)}{1-\beta+\beta\gamma(1-\theta_R)+\beta\gamma\theta_R(s_K/\sigma)},\\[4pt]
\tau_W&=\frac{(1-\theta_R)\bigl(1-\beta+\beta s_L/\sigma\bigr)}{1-\theta_R+\theta_R(s_K/\sigma)}.
\end{aligned}
$$

On the licensed box both payoffs are strictly concave in $\tau$ at fixed
companions, with unique peaks $\tau_C<\tau_W$ (Lemma A.2). Holding $d$
and $i$ fixed, $[\tau_C,\tau_W]$ is the tax Pareto interval. For
$\sigma>1$ and $\theta_R>0$, $s_L/\sigma<d_C<d_M$ and $d_W>d_C$. The
worker lies above $d_M$ if and only if $\theta_R>\bar\theta$ (Lemma
A.3). Complementary loadings: $\partial\tau_C/\partial\theta_R<0$;
$\partial d_C/\partial\theta_R>0$ only for $\sigma>1$; at $\sigma=1$
every listed chooser wants $d=1-\alpha$ and the tax gap remains.

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
restriction on preferences. For $\sigma\neq1$ the owner’s programme is
not available in its direction coordinate, since $d_C\neq d_M$, and the
worker’s is available only at $\theta_R=\bar\theta$. A mediant with
$\lambda\in(0,1)$ then equals $d_M$ if and only if
$\theta_R>\bar\theta$, and at exactly one $\lambda$. At $\sigma=1$ every
listed chooser wants $d_M$, and ratification removes no direction that
any of them would choose. That fact is not used as an incentive
constraint.

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

1.  The classes disagree about the tax for two reasons, each strictly
    signed on the licensed box (Lemma A.5). The tax is paid out of
    capital income, which the owner consumes and the worker does not.
    And the owner’s felicity loads capital, with weight
    $a_1(1-\omega)+\omega$, while the worker’s loads it with none. Hence
    $\tau_C(\theta_R)<\tau_W(\theta_R)$ at every $\theta_R$.
2.  The dropped-hypothesis recipe $f_0$ sets $\tau=0$ and $G'=0$. By
    Lemma 0 and Proposition 8 every interior tax strictly
    Pareto-dominates that recipe for the two assigned objectives.
3.  Under Premise P a reshuffle of $K$ moves only the levels
    $H_j(\kappa)$, so the interval $[\tau_C,\tau_W]$ is the same at
    every owners’ share $\kappa$. No class-preserving reshuffle of $K$
    produces a unanimous tax. Every two-class Pareto tax, once a public
    instrument is restored, lies in that interval.

Successor labour $L'$ is not an owned endowment, so no coordinate of
$\bar{\mathcal{X}}$ transfers it. That removes an instrument a planner
might want, but it is not what separates the peaks. Facts 1 and 3 rest
on who pays the tax and on what each class’s felicity counts, and
neither is a statement about who owns $L'$. Premise P is where the
incidence is held fixed: a reshuffle that gave workers capital income
would change who bears the tax, and that is the transfer P excludes.

Bergstrom and Cornes (1983) independence of the *set* of efficient
public quantities from private-good distribution holds under P: the set
does not move with $\kappa$. Separation still fails: there is no unique
efficient plan to hold fixed while transferring $K$, and the
dropped-hypothesis recipe is shut-down of $G$. Class-specific Lindahl
prices (Foley 1970) are a different instrument set.

**Proposition 12 (Uniform tax is not Lindahl).** At $\varphi=1$,
$G'=\tau e^{E_C}$. Every point of $\bar{\mathcal{X}}$ funds $G$ from
capital income only: the owner’s statutory contribution is
$\tau e^{E_C}$ and the worker’s statutory contribution is $0$. On the
licensed box $N_W>0$, so $V_{W,\tau}>0$ on $(0,\tau_W)$. A Lindahl
equilibrium for $G$ requires personalized prices at which both classes
demand the implemented $G'$. At the statutory prices that
$\bar{\mathcal{X}}$ carries, the worker demands the level of $G'$
produced by $\tau_W$, and the owner the level produced by
$\tau_C<\tau_W$. Hence no point of $\bar{\mathcal{X}}$, at the statutory
prices it carries, is a Lindahl equilibrium for $G$.

*Proof.* Personalized prices $(p_C,p_W)$ are not coordinates of
$\bar{\mathcal{X}}$. The implied statutory pair is $(p_C,0)$ in units of
capital income, with the owner bearing the whole cost. At that pair each
class’s most preferred $G'$ is the one produced by its assigned tax
peak, because the assigned programme is the choice of $\tau$ by one
class under exactly this incidence. On $(0,\tau_W)$ the worker wants
more, since $V_{W,\tau}>0$ there (Lemma 0 and $N_W>0$), and
$V_W\to-\infty$ as $\tau\to 0^+$ rules out $G'=0$. On $(\tau_W,1)$ the
worker wants less. At $\tau_W$ the owner, whose peak is $\tau_C<\tau_W$
(Lemma A.2), wants less. No $\tau\in[0,1)$ is demanded by both classes
at these prices. $\square$

A mandate that selects a point of $[\tau_C,\tau_W]$ funds $G$. It does
not construct $(p_C,p_W)$. Whether the allocation at some point of
$\bar{\mathcal{X}}$ could be supported by personalised prices outside it
is a different question, which Proposition 12 does not address.

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
type. For the worker, $f_W(\theta_R)$ maximises $V_W(\cdot;\theta_R)$
over the points of $\mathcal{X}$ with $i=\bar\imath$, because the terms
in $\tau$ and $d$ are separate from the term in $i$ (Lemmas A.1–A.3).
Every report yields a point with $i=\bar\imath$, and the same argument
applies. $\square$

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
$\tau_\lambda'\neq 0$ the direct mechanism for
$(\tau_\lambda(\theta_R),1-\alpha,i)$, with $i$ held fixed, is not
locally incentive-compatible for either named holder of $\theta_R$.

*Proof.* At $\sigma=1$ directional disagreement is deleted. The common
peak equals $d_M=1-\alpha$. A report cannot gain on $d$. The remaining
instrument is $\tau$ at companions $(d_M,i)$. That is Proposition 11.
$\square$

For $f_\lambda$ itself, whose investment coordinate moves with the
report, the sign of $V_{j,i}\,i_\lambda'$ is not established, and
Proposition 13 says nothing about it.

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
3.  If $s:\Theta\to(0,1)$ is strictly decreasing and continuous at
    $\theta_R$, and $s(\theta_R)>\tau_C(\theta_R)$, the direct mechanism
    for $s$ is not locally incentive-compatible for the owner at
    $\theta_R$.

*Proof.* Claim 1: the implemented tax does not depend on the report.
Claim 2 is Proposition 6. Claim 3: $V_C$ is strictly decreasing in
$\tau$ on $(\tau_C(\theta_R),1)$. Because $s$ is strictly decreasing and
continuous at $\theta_R$, a small upward misreport lowers the
implemented tax. For a small enough lie the new tax remains in
$(\tau_C(\theta_R),s(\theta_R)]$, so $V_C$ rises. $\square$

**Proposition 7$'$ (Dual elicitation).** Let $d=d_M$ and let $i$ be
fixed. Let the worker privately observe $\theta_R$.

1.  Every constant rule $\tau(\theta_R)\equiv\bar\tau\in(0,1)$ is
    incentive-compatible.
2.  The direct mechanism for $\tau_W(\cdot)$ is incentive-compatible
    (Proposition 7).
3.  If $s:\Theta\to(0,1)$ is strictly decreasing and continuous at
    $\theta_R$, and $s(\theta_R)<\tau_W(\theta_R)$, the direct mechanism
    for $s$ is not locally incentive-compatible for the worker at
    $\theta_R$.

*Proof.* Claim 1 as in Proposition 6$'$. Claim 2 is Proposition 7. Claim
3: $V_W$ is strictly increasing in $\tau$ on $(0,\tau_W(\theta_R))$.
Because $s$ is strictly decreasing and continuous at $\theta_R$, a small
downward misreport raises the implemented tax. For a small enough lie
the new tax remains in $[s(\theta_R),\tau_W(\theta_R))$, so $V_W$ rises.
$\square$

Continuity matters in claim 3. A strictly decreasing schedule that jumps
across the holder’s peak at $\theta_R$ can make truth locally optimal
there, and the differentiability hypothesis of Corollary 1 is what
excludes such jumps. A constant compromise can be imposed without using
the type. Where a differentiable schedule moves with the report,
truth-telling at first order puts it on the holder’s own peak (Corollary
1 below). The tax interval is the set of undominated constant taxes.

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
the licensed box $V_j$ is strictly concave in $\tau$ with its peak at
$\tau_j$ (Lemma 0), so $V_{j,\tau}$ is strictly decreasing and vanishes
on $(0,1)$ only at $\tau_j$. $\square$

The argument uses strict concavity of $V_j$ in $\tau$ and an interior
peak, and nothing else about the payoff. The logarithmic form of the
licensed box is one case. With
$V_j=M_j(1-\tau)^{1-\eta}/(1-\eta)+N_j\tau^{1-\eta}/(1-\eta)$, $\eta>0$,
$\eta\neq 1$, and $M_j$, $N_j$ as in Lemma A.2, whose limit at $\eta=1$
is the logarithmic form, the conclusion is the same.

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

This is a delegation problem. A decision maker who cannot use transfers
elicits information from an informed party (Melumad and Shibano 1991),
and the design problem reduces to choosing a set of decisions from which
the informed party picks its preferred one (Alonso and Matouschek 2008).
Corollary 1 is the first-order form of that reduction for a
one-dimensional type, and the censored peak is an interval delegated to
the owner. The reduction belongs to that literature. Here it sorts the
rules that the classes and a planner would name: the holder’s own
programme passes, and the other class’s programme and every compromise
that moves with the report fail.

Under a mandate a report of $f_\lambda$ moves $\tau$ and $d$ together.

------------------------------------------------------------------------

## Neighbouring objects

The information structure used is a one-dimensional private type and a
direct mechanism (Myerson 1979). Complete-information implementation is
selection on a named feasible set (Dasgupta, Hammond and Maskin 1979).
Without transfers, a direct mechanism that the holder answers truthfully
hands each type its preferred point of the rule’s image, so a truthful
rule is a set of taxes delegated to the holder (Melumad and Shibano
1991; Alonso and Matouschek 2008). Corollary 1 is the local form of that
fact.

Foley (1970) puts personalized prices on a public good in the commodity
space. Proposition 12 is the statement that no point of
$\bar{\mathcal{X}}$ carries those prices: the worker’s statutory price
of $G$ is zero.

Directed-technique points $d_M$, $d_C$, and $d_W$ are assigned or
current-output peaks. The Second Welfare Theorem (Arrow 1951; Debreu
1959) is the theorem whose recipe is $f_0$.

------------------------------------------------------------------------

## Scope

Two restrictions carry the statements about private ownership, and the
incentive results for interior rules use neither.

Premise P is used by Proposition 10 and by the third fact of the Theorem
(Separation), and by nothing else. It is the restriction under which a
reshuffle of $K$ moves each class’s level $H_j(\kappa)$ and leaves the
tax terms $M_j$ and $N_j$, and with them the peaks, where they were. The
first fact of the Theorem, the tax gap and its two sources in Lemma A.5,
holds without it.

Essentiality of $G$ in the log class, $V_j\to-\infty$ as $\tau\to0^+$,
gives the shut-down result its global reach: every interior tax, and not
only a small one, strictly Pareto-dominates $\tau=0$ (Proposition 8, the
second fact of the Theorem, the third claim of Proposition 10).
Proposition 9 uses it as well. For any payoff that is strictly concave
in $\tau$ on $[0,1)$ with the same interior peaks, both values rise on
$[0,\tau_C]$, so every tax in $(0,\tau_C]$ strictly Pareto-dominates
$\tau=0$ at the same companions. Proposition 12 needs only interior tax
peaks ordered $\tau_C<\tau_W$.

The incentive results for interior rules, Propositions 4, 6, 6$'$, 7,
7$'$, 11 and 13 and Corollary 1, use four properties of the tax payoffs.
Each is differentiable and strictly concave in $\tau$ with an interior
peak; the peaks are ordered $\tau_C<\tau_W$; each peak falls in
$\theta_R$; and both tend to $0$ as $\theta_R\to1$. Propositions 4 and
13 work in the mandate space and use two further facts: the payoff
separates into terms in $\tau$, $d$ and $i$ (Lemma A.1), and the
direction peaks are interior, and common at $\sigma=1$ (Lemma A.3). None
of the incentive results uses the value of $V_j$ at $\tau=0$. The
logarithmic form of the licensed box is one payoff with these four
properties, and the family in the remark after Corollary 1 is another.

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
transfer of capital that preserves the classes does not repair it. The
classes disagree about the tax because it is paid out of capital income,
which the owner consumes and the worker does not, and because the
owner’s felicity counts capital while the worker’s counts only labour.
Each source is strictly signed on the licensed box (Lemma A.5). The
private-ownership recipe $f_0$ sets $\tau=0$ and so $G'=0$. With log
payoffs that recipe is ruin for both classes, and every interior tax
strictly Pareto-dominates it (Lemma 0, Proposition 8). Under Premise P a
reshuffle of $K$ moves each class’s level $H_j(\kappa)$ and leaves the
tax Pareto interval $[\tau_C,\tau_W]$ where it was (Proposition 10).
Bergstrom–Cornes independence of the *set* therefore holds, and
unanimity fails: no reshuffle of $K$ brings $\tau_C$ onto $\tau_W$ or
selects $\tau=0$. Under P, then, redistributing capital cannot stand in
for the public instrument. That no one owns successor labour removes an
instrument, but it is not the source of the disagreement. P is a
restriction, not a consequence: a transfer that gave workers capital
income would change who bears the tax, and would leave the two-class
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
where it moves, with the investment share held fixed (Propositions 11
and 13). A constant tax is incentive-compatible for either holder
(Propositions 6$'$ and 7$'$). A state that does not observe $\theta_R$
can therefore let a tax schedule respond to it only by handing the
holder its own peak, and must hold the tax fixed elsewhere. For
$\sigma>1$ under a mandate a report moves tax and direction together,
and whether a compromise can then be elicited is not signed by the
loadings alone (Proposition 5).

Fourth, a uniform tax on capital income cannot be read as a system of
Lindahl prices. Every point of $\bar{\mathcal{X}}$ funds $G$ from
capital income alone, so the worker’s statutory price of $G$ is zero. At
those prices the worker demands the level of $G$ produced by $\tau_W$,
and the owner, who pays the whole cost, the level produced by $\tau_C$,
so no point of $\bar{\mathcal{X}}$, at those prices, is a Lindahl
equilibrium (Proposition 12). Foley’s repair needs personalised prices,
which this instrument set does not contain, and whether some allocation
in $\bar{\mathcal{X}}$ could be supported by such prices is left open.
Under P the Pareto interval does not move with $\kappa$ and contains no
unanimous point (Proposition 10). A mandate that selects a point of
$[\tau_C,\tau_W]$ funds $G$ at a single statutory price. Which point it
selects is a choice between the classes, and neither a price system nor
a transfer of capital makes that choice for it.

------------------------------------------------------------------------

## References

Alonso, R., and N. Matouschek (2008). Optimal delegation. *Review of
Economic Studies* 75(1): 259–293.

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

Melumad, N. D., and T. Shibano (1991). Communication in settings with no
transfers. *RAND Journal of Economics* 22(2): 173.

Myerson, R. B. (1979). Incentive compatibility and the bargaining
problem. *Econometrica* 47(1): 61–73.

## Appendix A. The assigned programmes

Throughout, the parameters lie in the licensed box and the instruments
are constant. Write $D=\gamma(1-\theta_R)+\gamma\theta_Ra_2$, and note
$1-a_1=s_L/\sigma$ and $a_2=s_K/\sigma$. In the state $(k,n,g)$ the
transitions have the rows $(a_1,1-a_1,0)$ for $k'$ and $g'$ and
$(\gamma\theta_Ra_2,1-D,\gamma(1-\theta_R))$ for $n'$, each non-negative
and summing to one, so with $\beta<1$ every discounted sum below
converges.

**Lemma A.1 (Value coefficients).** *Write the owner’s value as
$v_C+a_kk+a_nn+a_gg$ and the worker’s as $v_W+pk+qn+rg$. Then* $$
\begin{aligned}
a_k&=\omega+m_Ca_1+\beta a_n\gamma\theta_Ra_2, &\qquad p&=\beta\bigl[(p+r)a_1+q\gamma\theta_Ra_2\bigr],\\
a_n&=m_C(1-a_1)+\beta a_n(1-D), &\qquad q&=1+\beta\bigl[(p+r)(1-a_1)+q(1-D)\bigr],\\
a_g&=\beta a_n\gamma(1-\theta_R), &\qquad r&=\beta q\gamma(1-\theta_R),
\end{aligned}
$$ *with $m_C=(1-\omega)+\beta(a_k+a_g)$. Each system has a unique
solution, and every coefficient is positive:* $$
m_C=\frac{(1-\omega+\beta\omega)(1-\beta+\beta D)}{(1-\beta)(1-\beta a_1+\beta D)},\quad a_n=\frac{m_C(1-a_1)}{1-\beta+\beta D},\quad q=\frac{1-\beta a_1}{(1-\beta)(1-\beta a_1+\beta D)},\quad p+r=\frac{\beta qD}{1-\beta a_1}.
$$

*Proof.* Substitute the transitions into felicity plus $\beta$ times the
conjectured value. Apart from terms in the instruments, the owner’s
objective loads $E_C$ with weight $m_C$ (through $\ln C_C$, $k'$ and
$g'$) and $E_W$ with weight $\beta\gamma\theta_Ra_n$ (through $n'$); the
worker’s loads $E_C$ with $\beta(p+r)$ and $E_W$ with
$\beta\gamma\theta_Rq$. Matching the coefficients on $k$, $n$ and $g$
gives the two systems. For the owner, adding the $k$- and $g$-equations
gives $m_C(1-\beta a_1)=1-\omega+\beta\omega+\beta^2a_nD$, and the
$n$-equation gives $a_n(1-\beta+\beta D)=m_C(1-a_1)$; eliminating $a_n$
gives $m_C$. For the worker, adding the $p$- and $r$-equations gives
$(p+r)(1-\beta a_1)=\beta qD$, and substituting into the $q$-equation
gives $q$. Every factor is positive on the box, and
$p=\beta[(p+r)a_1+q\gamma\theta_Ra_2]>0$. $\square$

Because the coefficients do not depend on the instruments, the terms in
each instrument are the same in every period, and a constant policy’s
payoff is those terms divided by $1-\beta$ plus terms free of the
instrument. Each peak below is therefore the maximiser of one period’s
terms. The same substitution writes the payoff of any sequence of
instruments as the discounted sum of those one-period terms plus terms
free of the instruments. No sequence therefore does better than the
constant peak, and in this deterministic environment neither does a rule
that makes the instrument depend on the state.

**Lemma A.2 (Tax peaks).** *At fixed $d$ and $i$,
$V_j=M_j\ln(1-\tau)+N_j\ln\tau+H_j$ with
$(M_C,N_C)\propto(1-\omega+\beta a_k,\ \beta a_g)$ for the owner and
$(M_W,N_W)\propto(\beta p,\ \beta r)$ for the worker, all positive. Each
$V_j$ is strictly concave in $\tau$ with peak $N_j/(M_j+N_j)$, which is
the display for $\tau_C$ and $\tau_W$ in the Primitives. Moreover* $$
\tau_W-\tau_C=\frac{(1-\theta_R)(1-\beta)\bigl[1-\beta+\beta\gamma(1-\theta_R)+\beta\gamma\theta_R s_K/\sigma+\beta s_L/\sigma\bigr]}{\bigl(1-\theta_R+\theta_R s_K/\sigma\bigr)\bigl(1-\beta+\beta\gamma(1-\theta_R)+\beta\gamma\theta_R s_K/\sigma\bigr)}>0,
\qquad
\frac{\partial\tau_C}{\partial\theta_R}=-\frac{\beta^2\gamma\,(s_L/\sigma)\bigl[(1-\beta)+\beta\gamma s_K/\sigma\bigr]}{\bigl(1-\beta+\beta\gamma(1-\theta_R)+\beta\gamma\theta_R s_K/\sigma\bigr)^2}<0 .
$$

*Proof.* The tax enters $\ln C_C$ and $k'$ through $\ln(1-\tau)$ and
$g'$ through $\ln\tau$. For the owner,
$\tau_C=\beta a_g/(1-\omega+\beta a_k+\beta a_g)=\beta a_g/m_C=\beta^2\gamma(1-\theta_R)(1-a_1)/(1-\beta+\beta D)$
by Lemma A.1, which is the display. For the worker,
$\tau_W=r/(p+r)=\gamma(1-\theta_R)(1-\beta a_1)/D$, which is the display
after dividing by $\gamma$. The difference and the derivative follow on
clearing denominators. $\square$

**Lemma A.3 (Directions).** *The direction enters only through
$a=\varepsilon\ln d$ and $b=\varepsilon\ln(1-d)$. For an objective that
loads $E_C$ with weight $M>0$ and $E_W$ with weight $N>0$, the terms in
$d$ are
$\varepsilon\bigl[(Ma_1+Na_2)\ln(1-d)+(M(1-a_1)+N(1-a_2))\ln d\bigr]$,
strictly concave, with peak* $$
d=\frac{s_L}{\sigma}+\rho\,w,\qquad w=\frac{N}{M+N}.
$$ *The current-output point is $d_M=s_L$, since $\ln Y$ loads $b$ with
$s_K$ and $a$ with $s_L$. The owner’s and the worker’s weights are* $$
w_C=\frac{\beta\gamma\theta_R\,s_L/\sigma}{\Lambda},\quad \Lambda=(1-\beta)+\beta\gamma(1-\rho\theta_R);\qquad w_W=\frac{\theta_R(1-\beta a_1)}{H},\quad H=\beta(1-\theta_R)+\theta_R(1-\beta\rho),
$$ *and they satisfy* $$
(w_W-w_C)H\Lambda=(1-\beta)\theta_RQ,\qquad (s_L-w_C)\Lambda=s_L\bigl[(1-\beta)+\beta\gamma(1-\theta_R)\bigr],\qquad (w_W-s_L)H=\bigl(\beta s_L+(1-\beta)s_K\bigr)(\theta_R-\bar\theta),
$$ *with $Q=(1-\beta a_1)+\beta\gamma\bigl(1-\theta_R(1-a_2)\bigr)>0$,
and
$\partial w_C/\partial\theta_R=\beta\gamma(s_L/\sigma)(1-\beta+\beta\gamma)/\Lambda^2>0$.*

*Proof.* The peak is that of $A\ln(1-d)+B\ln d$ with $A,B>0$, namely
$B/(A+B)$, and $B/(A+B)=(1-a_1)+(a_1-a_2)w$ with $a_1-a_2=\rho$. The
owner’s weights are $m_C$ and $\beta\gamma\theta_Ra_n$, the worker’s
$\beta(p+r)$ and $\beta\gamma\theta_Rq$ (proof of Lemma A.1);
substituting Lemma A.1 gives $w_C$ and $w_W$, using
$\beta D+\beta\gamma\theta_R(1-a_1)=\beta\gamma(1-\rho\theta_R)$. The
three identities and the derivative follow on expanding with
$a_2=a_1-\rho$. $\square$

Every ranking of directions in the text follows. Since
$d_j-d_k=\rho(w_j-w_k)$, $d_j-s_L/\sigma=\rho w_j$ and
$d_M=s_L/\sigma+\rho s_L$, for $\sigma>1$ Lemma A.3 gives
$s_L/\sigma<d_C<d_M$, $d_W>d_C$, and $d_W>d_M$ if and only if
$\theta_R>\bar\theta$;
$\partial d_C/\partial\theta_R=\rho\,\partial w_C/\partial\theta_R$ is
positive exactly when $\sigma>1$; and at $\sigma=1$ every direction
equals $s_L=1-\alpha$.

**Lemma A.4 (Investment).** *The investment share enters the owner’s
objective as $(1-\omega)\ln(1-i)+\beta a_k\ln i$, so $V_{C,i}=0$ at
$i_C=\beta a_k/(1-\omega+\beta a_k)$, and the worker’s as $\beta p\ln i$
with $p>0$, so $V_{W,i}>0$ at every $i$.* The proof is Lemma A.1.
$\square$

**Lemma A.5 (Incidence and felicity).** *Let $\tau^\ast=a_g/(a_k+a_g)$,
the owner’s tax peak with the current-consumption weight $1-\omega$
deleted. Write $X=a_1(1-\omega)+\omega$, $\Omega=1-\beta a_1+\beta D$
and $\Psi=(1-\beta)X+\beta D$. Then $\tau_C<\tau^\ast<\tau_W$, with* $$
\tau^\ast-\tau_C=\frac{\beta\gamma(1-\theta_R)(1-\beta)(1-\omega)(s_L/\sigma)\,\Omega}{(1-\beta+\beta D)\,\Psi},\qquad
\tau_W-\tau^\ast=\frac{(1-\beta)(1-\theta_R)\,X\,\Omega}{(1-\theta_R+\theta_R s_K/\sigma)\,\Psi}.
$$

*Proof.* By Lemma A.2, $\tau_C=\beta a_g/(1-\omega+\beta a_k+\beta a_g)$
and $\tau^\ast=\beta a_g/(\beta a_k+\beta a_g)$ differ only by the
weight $1-\omega$ that the owner’s current consumption puts on
$\ln(1-\tau)$, so
$\tau^\ast-\tau_C=(1-\omega)\beta a_g/[(\beta a_k+\beta a_g)(1-\omega+\beta a_k+\beta a_g)]$,
and Lemma A.1 gives the first display. For the second,
$r=\beta q\gamma(1-\theta_R)$ and $a_g=\beta a_n\gamma(1-\theta_R)$ give
$\tau_W-\tau^\ast=\beta\gamma(1-\theta_R)(qa_k-a_np)/[(p+r)(a_k+a_g)]$,
and Lemma A.1 gives $qa_k-a_np=X/[(1-\beta)\Omega]$. With
$s_L/\sigma=1-a_1$ and $s_K/\sigma=a_2$, every expression here is a
function of $(a_1,a_2)$, and $(\sigma,s_K)\mapsto(a_1,a_2)$ maps the
licensed box onto $(0,1)^2$, so every factor is positive for either sign
of $\rho$. $\square$

The first gap is incidence. The tax is paid out of capital income, which
the owner consumes and the worker does not, so the owner’s peak carries
the weight $1-\omega$ of current consumption and the worker’s carries
nothing in its place. The gap vanishes only at $\omega=1$, outside the
box. The second gap is felicity. $X$ is the loading of the owner’s
current felicity on capital: $(1-\omega)a_1$ through consumption of
capital income and $\omega$ directly. The worker’s felicity $n$ loads
capital with zero. Even with the tax’s bite on consumption removed, the
owner values capital against the public stock more than the worker does.
Neither term is a statement about who owns successor labour.

[^1]: The local tax arguments hold $i$ fixed.

[^2]: Where $\tau_\lambda'=0$ a separate comparison is required.
