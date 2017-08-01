% Phenomenology of Heavy QCD Axion \hfill\tiny arXiv:1607.01936, in preparation
% Hajime Fukuda (Kavli IPMU) \tiny with T.T. Yanagida, M. Ibe, M. Nojiri and O.Jinnouchi
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H ../header -->
# Outline
1. Heavy axion - Why and How?
1. Comprehensive Phenomenology of Visible Heavy Axion Models
1. Future search prospects


# Strong CP Problem
* QCD should break CP symmetry
$$
\theta = \theta_\text{YM} + \arg\det(Y_uY_d)
$$
* The PQ mechanism can set $\theta=0$.
    * The original model has been excluded.


# What is the Alternative?
* Roughly, two choices:
    * Larger $f_a$ / Heavier $m_a$

## Axion Mass
* From QCD,
$$
{m_a}^2 \simeq \frac{m_q \Lambda^3}{{f_a}^2}
$$

# Invisible Axion
* Large $f_a$ is straightforward
    * Just adding a new scalar and a scalar/Fermion
* $f_a$ has to be greater than $10^{9\mbox-10}$ GeV


# How to Make an Axion Heavier?
* Another gauge theory with the same $\theta$ is needed 

\begin{center}
\begin{tikzpicture}
\fill [gray] (10, -1.75) circle (0.25);
\draw [olive, ultra thick]  (7, -1) sin (8,0) cos (9,-1) sin (10,-2) cos (11,-1) sin (12, 0) cos (13,-1);
\draw [teal, ultra thick] (7, 0) sin (8,2) cos (9, 0) sin (10, -2) cos (11, 0) sin (12, 2) cos (13, 0);
\end{tikzpicture}
\end{center}
\tiny Rubakov 1997; Berezhiani, Gianfagna and Giannotti 2000\newline Hook 2014, HF, Harigaya, Ibe and Yanagida 2015, Albaid, Dine and Draper 2015\newline
(Kobakhidze 2016), (Gherghetta, Nagata and Shifman 2016)


# What is the gauge theory?
* Only known way is using a copy of SM
    * We assume $\mathbb Z_2$ parity
    * $\theta$s hardly run so $\mathbb Z_2$ may be spontaneously broken

# $m_a$ VS $f_a$

\begin{center}
\begin{tikzpicture}
\draw [->, ultra thick] (-10, -2.75) -- (0.5, -2.75);
\draw [->, ultra thick] (-4.75, -6) -- (-4.75, 0.5);
\draw (-0.3, -3.05) node[olive] {Large $m_a$};
\draw (-3.7, 0.3) node[olive] {Large $f_a$};
\draw (-7.5, -1) node[text width=110,text badly ragged] {KSVZ/DFSZ type axion like models: always alive but not easy to see};
\draw (-7.5, -4.5) node[text width=110,text badly ragged] {Weinberg-Wilczek like models: already excluded};
\draw (-2.2, -1) node[text badly centered] {\Huge ?};
\draw (-2.2, -4.5) node[text badly centered] {\Huge \color{olive}{?}};
\end{tikzpicture}
\end{center}

# Setup

* SM and the copy is necessary
* How do we introduce PQ sym.?
    * Weinberg-Wilczek type
    * KSVZ type
* We mainly consider KSVZ-like model
    * $\mathcal L \sim \phi\bar{\psi}\psi + \phi\bar{\psi'}\psi'$, $-Q(\phi) = 1 = Q(\psi) = Q(\psi')$

# What we want to do

* We may freely choose $v'$, $\Lambda'$ and $f_a$ with

$$ {m_a}^2 \simeq \frac{m_q' \Lambda'^3}{{f_a}^2} $$

* Which region is still alive? Is it still visible?
* We require DM is included

\tiny HF, Ibe and Yanagida, in preparation

# Axion mass

\begin{textblock}{6}(1.5,1)
\includegraphics[width=6\TPHorizModule]{axionMass.pdf}
\end{textblock}

# Constraints on $m_a$

* When the axion is in the thermal bath, both sectors are in chemical equilibrium

* However, the entropy in the copied sector must small enough
    * The decoupling must occur before QCD PT

* Including the Boltzmann effect, $m_a \gtrsim \mathcal O(1)$ GeV
    * All the other constraints are weaker

# Safe region

\begin{textblock}{6}(1.5,1)
\includegraphics[width=6\TPHorizModule]{axionAlive.pdf}
\end{textblock}

# Constraints on $f_a$

* For KSVZ type, the lower bound comes from the LHC
    * The vector like quark search $\to$ $f_a \gtrsim 1$ TeV

* If $f_a$ becomes large, $m_a$ is now too small

* For $f_a \gtrsim 10^{10}$ GeV, $a$ decouples before QCD PT

# Constraints on $v'$ and $\Lambda'$

* We have to consider thermal relics
* What will remain? $\iff$ What symmetries remain in addition to $\gamma'$?

$$
Q', L' \to 2\text{\ of\ }(e', \nu', {\pi^\pm}')
$$
$$
B' \to (p', n')
$$

# Conditions on $\nu'$

* Lightest particle : $\lesssim \mathcal O(10)$ eV
* 3 possible choises
    * Giving up seesaw and
        * $\nu'$ DM
        * Unstable $\nu'$
    * Ones of $\nu$ are massless
        * Natural if the number of $N$ is 2 


# Case 1: $\nu'$ DM

* Just like ordinary WIMP,

$$\frac{\Omega_{\nu'}}{\Omega_\text{DM}} \sim \frac{1\,\text{pb}}{\langle \sigma v \rangle}\ \ \ \therefore m_\nu' \sim 8\,\text{GeV}\left(\frac{v'}{v}\right)^2 > m_e'$$

* ${\pi^\pm}'$ must decay, so $m_{\nu'} < m_\pi' \propto \sqrt{v'\Lambda'}$
    * $v'\sim v$, $\Lambda' \sim 10^3 \Lambda$ : $m_a$ is too light $\to$ *EXCLUDED*
* Another choise
    * New interactions like $B'-L'$ only in copied sector
    * Little constaints and less interesting

# Case 1: How excluded?

\begin{textblock}{6}(1.5,1)
\includegraphics[width=6\TPHorizModule]{nuDM.pdf}
\end{textblock}

# Case 2: One massless $\nu'$

* $e'$ or ${\pi^\pm}'$ is stable
    * $m_e' > m_\pi'$: $v'/v \sim 10^4 \frac{\Lambda'}{\Lambda} \gtrsim 10^6$; too much $u',d'$ relics

* $e'$ and ($p'$ or $n'$) are stable
    * Which one is DM?

# Baryon mass: which is lighter?

* $m_B \sim c_1 \sum m_q + c_2 \Lambda + c_3 q \alpha \Lambda$
    * $c_i$ are all positive and $c_1\sim 1$

* $p'$
    * QED contribution
* $n'$
    * Heavier constituent quarks

# Baryon mass ratio

\begin{textblock}{6}(1.5,1)
\includegraphics[width=6\TPHorizModule]{baryonRatio.pdf}
\end{textblock}

# Is charged DM possible?

* Helo ellipticity constraint
    * $m_\text{DM} \gtrsim 1 \text{TeV}$ for $\alpha^{-1}\sim100$ \tiny{Agrawal et al., 1610.04611}

* Large Sommerfeld enhancement for late time annihilation
    * If $\text{DM} + \text{DM} \to \text{SM}$ is open, CMB might be disturbed


# DM Candidates

* $e'$
    * WIMP mass $\sim 50$ GeV, inconsistent
* $p'$ (${\Lambda^{++}}'(u'u'u')$)
    * Ellipticity is not a problem
    * $p'$ may annihilate into $a$ and $a\to jj$
    * light q' region is excluded
* $n'$
    * No problem

# Case 2: Available region

\begin{textblock}{6}(1.5,1)
\includegraphics[width=6\TPHorizModule]{masslessNu.pdf}
\end{textblock}

# Case 3: Unstable $\nu'$

* ${\pi^\pm}'$, $e'$ and ($p'$ or $n'$) are stable
* Baryons
    * For light q$'$, $\Omega_{{\pi^\pm}'} > \Omega_{B'}$ since ${\pi^\pm}'$ annihilates by QED$'$
* ${\pi^\pm}'$
    * light q$'$ region is excluded
* ${\Lambda^{++}}'$ may be the DM

# Case 3: Available region

\begin{textblock}{6}(1.5,1)
\includegraphics[width=6\TPHorizModule]{unstableNu.pdf}
\end{textblock}

# Short summary
* Allowed possibilities are
    * $n'$ DM + one massless $\nu'$
    * ${\Lambda^{++}}'$ DM (?)
* NOTE: If we consider exotic cosmology like low reheating temperature, constraints becomes weaker
    * However, the model is not closed and there are still some problems like BAU


# Detection methods
* Collider experiments
    * Vector like quark detection
    * \color{olive} Axion / Dilaton detection
* Astrophysical experiments
    * For charged DM
        * Ellipticity
        * Cosmic ray
    * \color{olive} Decay of Baryon$'$ relics
* Neutrino 

# Axion / Dilaton detection
* For large enough $\sqrt{s}$,
$$
\sigma(pp\to a, s) \sim \left(\frac{\alpha_s}{4\pi}\right)^2 \frac{1}{f_a^2} \sim 10\,\text{fb} \left(\frac{1\,\text{TeV}}{f_a}\right)^2
$$

* $s\to jj\gamma\gamma$ might be hopeful?

# Difference b/w $\gamma$s and $\gamma$-jets
* Some $\gamma$s are "converted"

\phantom{
\includegraphics[width=5.5cm]{ePairPt.pdf}
}

\begin{textblock}{4}(1,4.5)
\includegraphics[width=3.5\TPHorizModule]{cms_slice.jpg}
\end{textblock}

\begin{textblock}{4}(5,3.5)
\includegraphics[width=3.5\TPHorizModule]{CMSRadLength.pdf}
\end{textblock}

# How to Distinguish the Jet
* We simulate trackers in CMS.
    * Conversion, bremsstrahlung, ...
* $p_T^\text{track}$ has greater discrimination power!

\phantom{
\includegraphics[width=5.5cm]{ePairPt.pdf}
}

\begin{textblock}{6}(2,4)
\includegraphics[width=5.5\TPHorizModule]{ePairPt.pdf}
\end{textblock}

\begin{textblock}{3}(6.5,7.5)
\fontsize{6.5pt}{0pt}\selectfont HF, Ibe, Jinnouchi and Nojiri, arXiv:1607.01936
\end{textblock}
 
\begin{textblock}{3}(6.2,6)
\tiny (X:$\gamma$, Y:$2\gamma$, Z:$4\gamma$)
\end{textblock}
 

# Decay of Baryon$'$ relics
* Naturally, $p'/n'$ is unstable like SM $p$
* $\Gamma \propto m^5$, Short lifetime!
* Extragalactic gamma ray background tells
$$
\tau(N' \to l' + a) \gtrsim 10^{28}\,{\rm s}\times \left(\frac{\Omega_{N'}}{\Omega_{DM}} \right)
$$
* If $\Omega_{N'} = \Omega_{DM}$, $\Lambda_\slashed{B} \sim M_\text{Pl}$

# Summary
* We have investigated all the low-energy region for heavy axions
* Depending the scenario, some region is still alive
