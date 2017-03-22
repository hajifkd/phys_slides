% How should we tackle the strong CP problem? \tiny Based on 1703.01112 1504.06084 1602.07909 1702.00227
% Hajime Fukuda (Kavli IPMU, U. Tokyo)
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H ../header --slide-level=2-->
## Outline
1. Strong CP Problem and the solutions
1. Challenge for the origin of Peccei-Quinn symmetry
1. Our study
    1. "Gauged" axion
    1. Heavy axion

# Strong CP Problem and the Solutions

## Strong CP Problem
* Yang-Mills theory in 4D has $\theta$ vacua, which can be written in Lagrangian: $\Delta \mathcal L \sim \theta F\tilde F$ *\tiny(see Seiberg 10)*
* Non-zero $\theta$ breaks CP symmetry: $|\theta_{QCD}|\lesssim 10^{-10}$
* $\theta_{QCD}$ consists of two parts, $\theta_{YM}$ and $\text{arg}(\text{det}(Y_uY_d))$
    * We expect the latter is around $J\sim10^{-5}$, at least
    * No reason to cancel
* Why is $\theta_{QCD}$ so small? - *Strong CP Problem*
* Anthoropic principle cannot be used *\tiny see Ubaldi 08, for instance*

## The Solutions
* As far as I know, there are roughly two ways
* Spontaneous CP Breaking (e.g. Nelson-Barr Mechanism)
    * Complicated and not so easy *\tiny Dine and Draper. 15 for detail*
* Use of anomaly

## Anomaly and $\theta$
* Chiral (non-vectorial) $\text{U}(1)$ symmetries in 4D generally have anomalies
$$\partial J \sim F\tilde F$$
* The chiral rotation only moves $\theta$ - $\theta$ becomes unphysical!
* This is why we do not have "Weak CP Problem"...
$$\partial J_L \sim W\tilde W + F\tilde F \ \ \therefore\bar{e}_R \to e^{-i\theta_w/3}\bar{e}_R, L_L \to e^{i\theta_w/3}L_L, \theta_w\to 0$$

## Peccei-Quinn Mechanism
* In a nutshell, "if a symmetry were anomalous in QCD, $\theta$ would be unphysical"
* The anomaly never disappear (e.g. Anomaly Matching)
* That anomaly must have low-energy consequence!
    * Massless *colored* Fermion
        * (For historical reason, this is usually not referred as PQ)
    * Pseudo NGB with $\Delta \mathcal L \sim \frac{a}{f_a} G\tilde G$
        * Peccei and Quinn 1977, Weinberg 1978, Wilczek 1978

## With Massless Colored Fermion
* No additional massless Fermion is allowed in SM
* May *up* be massless? - So called *"massless up" solution*
* Inconsistent with chiral perturbation?
    * Still instanton may save it? *\tiny Georgi and McArthur 81*
* (Un)fortunately, lattice people finally concluded it is inconsistent

## Axion, the Main Topic!
* Among many ways, the simplest is KSVZ axion

|              |$\text{SU}(3)_{QCD}$|$\text{U}(1)_{PQ}$|
|:------------:|:------------------:|:----------------:|
|$\phi$        | $1$                | $1$              |
|$\psi_L$      | $3$                | $-1$             |
|$\bar{\psi}_R$| $\bar{3}$          | $0$              |

* The Lagrangian is $\Delta\mathcal L \sim \phi \bar{\psi}_R\psi_L - V(\phi)$
* With the "wine-bottle" $V(\phi)$, $\text{U}(1)_{PQ}$ is spontaneously broken and axion appears, with $\Delta \mathcal L \sim \frac{a}{f_a} G\tilde G$

## Axion Mass
* $\text{U}(1)_\text{PQ}$ is not exact - the axion, $a$, has mass
* From the chiral condensation,
$${m_a}^2 \sim \frac{m_q{\Lambda_{QCD}}^3}{{f_a}^2} \sim \left(1\,\text{meV}\,\frac{10^9\,\text{GeV}}{f_a}\right)^2$$
* $f_a$: axion decay constant, $\sim \langle\phi\rangle$

## Rich Phenomenology of Axion
* Axion couples with baryons, photons (and leptons)
* Many experiments/observations constrain axions
    * Star lifetime, axion helioscopes, reactors, *etc*.
    * $f_a (\sim \langle\phi\rangle) \gtrsim 10^9\,\text{GeV}$
* Axion coherent oscilation may be the dark matter
    * $\ddot{a}(t) + 3H\dot{a}(t) - {m_a}^2 a(t) = 0 \Rightarrow \rho_a(t) R(t)^3 = \text{const.}$
    * The initial amplitude of oscilation is $\mathcal O(1) f_a$ 
    * For $\Omega h^2 \sim 0.1$, $f_a \sim 10^{12}\,\text{GeV}$

## Summary So Far
* The Standard Model has the Strong CP problem
* The most plausible ($\simeq$ consistent with other observations) solution is the Peccei-Quinn mechanism and axion
* Rich phenomenology, many things to do!

# Challenge for the origin of Peccei-Quinn symmetry

## Big Obstacle for the Peccei-Quinn Mechanism
* $\text{U}(1)_{PQ}$ must be an **extremely** good "symmetry"
$$\Delta \mathcal L = c\frac{\phi^5}{M_\text{Pl}} \Rightarrow \mathcal L_a = -\frac{{m_a}^2}2 a^2 + c\frac{{f_a}^4}{M_\text{Pl}}a$$
Since $\theta_\text{eff} = \langle a\rangle / f_a$, $c \lesssim 10^{-60}$ for $\theta \lesssim 10^{-10}$!
* *Quality problem*
* So, *where does the $\text{U}(1)_{PQ}$ come?*
    * $\text{U}(1)_{PQ}$ is *by definition* not a symmetry
    * Even an exact global symmetry should be broken in Quantum Gravity
    * No anthoropic argument!
        * Accidental or/and "anthoropic-izing" solution

## How Can We Solve It?
* Expecting something in some unknown theory
    * Brane separation, *etc*.
* Using modulies in String Theory
    * Many modulies, many "light" mode
        * Most of them get mass
    * Some of them might be really light
    * The decay constant should be around string / Planck scale
        * Too large for DM, but anthoropic arguments may be used
    * This will be confirmed / excluded by BH superradiance

## How Can We Solve It? (cont.)
* Imposing discrete (gauge) symmetries
    * Discrete symmetries may emerge from gauge symmetry
        * e.g. Abelian Higgs with charge $+2$
    * For $\Delta \mathcal L \sim \mathcal O(1) \frac{\phi^n}{{M_\text{Pl}}^{n - 4}}$, $n \gtrsim 11$!
* Imposing continuous gauge symmetries
* Heavy QCD Axion

# Our Study
## Our Study
* We show two different models as examples
    * "Gauged" axion *\tiny HF, Ibe, Suzuki, Yanagida 1703.01112*
    * Heavy axion *\tiny Chiang, HF, Harigaya, Ibe, Yanagida 1504.06084, 1602.07909, 1702.00227*

# "Gauged" Axion

## "Gauged" Axion
* Needless to say, $\text{U}(1)_{PQ}$ cannot be gauged
* However, gauge symmetry may protect $\text{U}(1)_{PQ}$ *\tiny Georgi, Hall, Wise 81*

## Gauged $\text{U}(1)$ Symmetries and Anomalies
* Chiral $\text{U}(1)$ symmetries generally have anomalies
* How about $\text{U}(1)_{Y}$?
    * There, anomalies from *lepton* and *quark* sectors are cancelled!
    * Conversely, "$\text{U}(1)_{Y}$" in each sector are anomalous
        * Of course, due to Higgs, both sector are connected
        * However, what if we have 2HDM? - Weinberg-Wilczek model
        * $B-L$, $B$ and $L$? $R$-parity?
* Generally, multiple "$\text{U}(1)$" are assembled into one gauged $\text{U}(1)$
* Hence, if a gauged $\text{U}(1)$ exists, anomalous $\text{U}(1)$s may well exist

## Gauged $\text{U}(1)$ and Protection of $\text{U}(1)_{PQ}$
* No operators breaking gauged $\text{U}(1)$ is allowed
* The problem is the connection between two sector
    * Depending on the charge assignment, PQ breaking operators are suppressed

## Example of Models *\tiny Barr, Seckel 92, HF, Ibe, Suzuki, Yanagida 17*
|                 |$\text{SU}(3)_{QCD}$|$\text{U}(1)_{g}$|($\text{U}(1)_{PQ}$)|
|:---------------:|:------------------:|:---------------:|:------------------:|
|$\phi_1$         | $1$                | $1$             | $1$                |
|$\psi_{L1,10}$      | $3$                | $-1$            | $-1$               |
|$\bar{\psi}_{R1,10}$| $\bar{3}$          | $0$             | $0$                |
|$\phi_2$         | $1$                | $-10$           | $0$                |
|$\psi_{L2}$      | $3$                | $10$            | $0$                |
|$\bar{\psi}_{R2}$| $\bar{3}$          | $0$             | $0$                |
With interaction: $\Delta \mathcal L \sim \phi_1 \bar{\psi}_{R1,10}\psi_{L1,10} + \phi_2 \bar{\psi}_{R2}\psi_{L2}$

* Breaking Operator: ${\cal L}_{\cancel{PQ}} = \frac{1}{M_{\rm PL}^{7}} \phi_1^{10} {\phi_2^\dagger} + \text{H.c.}$


## How to Build Models?
* Building models are really easy
* Introducing two PQ sector, gauging the diagonal group
    * Always, one linear combination of two PQ currents are anomaly-free in QCD
* The problem is how we can suppress cross-terms
* How "realistic" can the model be? - Future work
* What is the cosmological evolution? - Future work

# Heavy Axion

## Heavy Axion
* As I mentioned, $m_a$ is written in terms of $f_a$, $m_a \sim \sqrt{m_q\Lambda^3}/f_a$
* Okay, let us forget it temporarily
* With PQ-breaking operator $\Delta \mathcal L = c\phi^5/M_\text{Pl}$,
$$\mathcal L_a \sim -\frac{{m_a}^2}2 a^2 + c\frac{{f_a}^4}{M_\text{Pl}}a$$
* Thus, if $m_a$ were bigger, we could ignore $\Delta \mathcal L$!

## How to Make it Heavier?
* Another gauge theory with the same $\theta$ is needed 

\begin{center}
\begin{tikzpicture}
\fill [gray] (10, -1.75) circle (0.25);
\draw [olive, ultra thick]  (7, -1) sin (8,0) cos (9,-1) sin (10,-2) cos (11,-1) sin (12, 0) cos (13,-1);
\draw [teal, ultra thick] (7, 0) sin (8,2) cos (9, 0) sin (10, -2) cos (11, 0) sin (12, 2) cos (13, 0);
\end{tikzpicture}
\end{center}

## What is the Other Gauge Theory?
* Two way is known
* Use of larger group $\text{SU}(N+3) \supset \text{SU}(3)_{QCD}\times\text{SU}(N)$ *\tiny Dimopoulos 79*
    * Recently Shifman *et al.* 16, used this
    * However, we believe this is almost dead
* Use of a copy of the standard model *\tiny Rubakov 94*
    * This is only the possibility

## Use of the Copy SM *\tiny 1504.06084, 1602.07909, 1702.00227*
* The axion mass is now $m_a \sim \sqrt{m_q'\Lambda'^3}/f_a$
* If the axion is heavier than $\mathcal O(1\mbox{-}10) GeV$, we have no constraint for the axion
    * Cosmology like BBN,...
    * Meson Invisible Decay
    * Astrophysics like SN1978A,...
* We may make $v'$ and $\Lambda'$ large using $\mathbb Z_2$ breaking
* Since we have introduced a copy, many particles are stable
    * We have found that one of them may be the dark matter
        * How to detect it? - Future work

# Summary
## Summary
* The Peccei-Quinn mechanism is probably the most successful solution to the Strong CP problem
* However, its quality is puzzling
* We have proposed two different way to realize good quality
    * "Gauged" axion
        * Gauge symmetry may protect PQ
        * How realistic does it look? - Future work
        * Cosmological evolution - Future work
    * Heavy axion
        * If axion were heavy, quality becomes better
        * Many phenomenology - Future work

