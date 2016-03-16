% Possibility of the Heavy QCD Axion
% Hajime Fukuda (Kavli IPMU)
% \today
<!--- 
pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md
-->
# Strong CP Problem
* CP symmetry in QCD should be broken
$$
\theta = \theta_\text{YM} + \arg\det(Y_uY_d)
$$
* However, the violation looks very small
$$
|\theta| \lesssim 10^{-10}
$$

# Peccei-Quinn mechanism \tiny Peccei and Quinn, 1977
## $\text{U}(1)_\text{PQ}$ Symmetry
$$
q_L\to e^{i\alpha} q_L,\ \ \theta\to\theta+2T(R)\alpha
$$

* $\text{U}(1)_\text{PQ}$ must be broken at $f_a$ and a pseudo NG Boson $a$ appears\
\hfill \tiny Weinberg 1978, Wilczek 1978

# Their Original Model
* The VEVs of 2HDM break EW gauge group and $\text{U}(1)_\text{PQ}$ simultaneously
* It's simple and minimal, but experimentally excluded

# Which Direction?
* There are roughly two ways to achieve the PQ mechanism
    * Larger $f_a$, weaker interactions
    * Heavier $m_a$, evading astro constraints
    
# Axion Mass and Decay Constant
## Axion Mass
$$
{m_a}^2 \simeq \frac{m_q \Lambda^3}{{f_a}^2}
$$

* Heavier $m_a$ with sufficiently large $f_a$ is hence difficult

# Larger $f_a$ isn't Easy, Either
* Why does no higher dim. op. exist?
$$
\Delta \mathcal L = c\frac{\phi^5}{M_\text{Pl}}
$$
$$
\Rightarrow\Delta \theta \simeq c\frac{{f_a}^3}{M_\text{Pl}{m_a}^2} \gg 10^{-10},
$$
even for the WW axion

# Realizing a Heavy Axion
* (Rubakov, 1997) suggested *a consistent way* to achieve a heavy axion

# How to Make an Axion Heavier?
* Another gauge theory is needed 

\begin{center}
\begin{tikzpicture}
\fill [gray] (10, -1.75) circle (0.25);
\draw [olive, ultra thick]  (7, -1) sin (8,0) cos (9,-1) sin (10,-2) cos (11,-1) sin (12, 0) cos (13,-1);
\draw [teal, ultra thick] (7, 0) sin (8,2) cos (9, 0) sin (10, -2) cos (11, 0) sin (12, 2) cos (13, 0);\pause
\draw [<->, ultra thick] (9.5, -2.3) -- (10.5, -2.3);
\draw (10, -2.7) node {Then how can we align the two $\theta$s?};
\end{tikzpicture}
\end{center}

# $\theta$ and $\theta'$
* As was shown, $\theta$ comes from two parts:
$$
\theta = \theta_\text{YM} + \arg\det(Y_uY_d)
$$
* Aligning each parts looks easy

# Copy of SM
$$
\theta' = \theta_\text{YM} + \tikz[baseline=(x.base)] {
  \node(x)[rectangle, fill=teal!20, rounded corners] {$\arg\det(Y_uY_d)$};
  }
$$

* $\theta'$ must have Yukawa sector
* Thus, we need a complete copy of SM
    * We call it as a "mirrored" copy 

# Our Model

\usetikzlibrary{automata,positioning}
\begin{center}
\begin{tikzpicture}
\tikzset{block/.style={rectangle, fill=teal!20, rounded corners, align=center}};
\node [block, fill=olive!20] (phi) {$\phi$};
\node [block, above left=2cm and 0.5cm of phi] (s) {$u_R,d_R,Q_L,e_R,L_L$\\$H,N_R$\\{}};
\node [below=0cm of s, anchor=south, blue!40!white] (psi) {\mbox{\boldmath $\psi$}};
\node [block, above right=2cm and 0.5cm of phi] (p) {$u_R',d_R',Q_L',e_R',L_L'$\\$H',N_R'$\\{}};
\node [below=0cm of p, anchor=south, blue!40!white] (psip) {\mbox{\boldmath $\psi'$}};
\draw [->, ultra thick, blue!40!white] (phi) -- (psi);
\draw [->, ultra thick, blue!40!white] (phi) -- (psip);
\node [above=0.3cm of phi, fill=olive!10] {PQ symmetry};
\draw [<->, ultra thick] (s) -- (p);
\node [above=2.3 cm of phi] {$\mathbb Z_2$};
\end{tikzpicture}
\end{center}

# Breakdown of $\mathbb Z_2$
* $\mathbb Z_2$ must be spontaneously broken
    * Otherwise the axion couldn't be heavy
* Which parameters do we change using spurion $\sigma$?

# Heavy Axion Mass
* Recall
$$
{m_a}^2 \simeq \frac{m_q' \Lambda'^3}{{f_a}^2}
$$
* We have to increase $m_q' \propto v'$ and $\Lambda'$
    * For $\Lambda'$, we introduce color charged particles, $\Phi, \Phi'$, and change their masses.

# Cosmological Properties 
* $\gamma'$ is massless 
    * The axion must decouple before QCD PT
* Seesaw mechanism in $\nu'$ is forbidden
    * $\nu'$s have large Dirac mass
    
# Stable Particle
* Two of the followings are stable

|       |$e'$|$\nu'$|${\pi^\pm}'$|($p'$)|
|:-----:|:--:|:----:|:----------:|:----:|
|$B'-L'$|$-1$|$-1$  | $0$        |$+1$  |
|$Q'$   |$-1$|$0$   |$\pm1$      |$+1$  |

* $\nu'$ must be unstable

# Low Energy Spectrum
Axion $a$\phantom{hogehogehogehogehoge}
: $m_a\gtrsim 400\,\text{MeV}$

Vector like quark $\psi, \psi'$
: $m_\psi=\frac{1}{\sqrt2}gf_a\gtrsim 900\,\text{GeV}$

Dilaton $s$\phantom{hogehogehoge}
: $m_s=\sqrt{2\lambda}f_a$\tikz[baseline=(x.base)] {
  \node (x) {$\gtrsim \mathcal O(100)\,\text{GeV}$};\pause
  \node [rectangle, fill=teal!20, minimum width={100pt}] {$\simeq 750\,\text{GeV}$??};
}

# Effective Lagrangian

\begin{eqnarray*}
\mathcal L &=& \frac{s}{f_a}\partial a\partial a + 
N_1\frac{\alpha_s}{8\pi}\frac{s}{f_a} GG+
 N_2\frac{\alpha}{8\pi}\frac{s}{f_a} F^{(\prime)}F^{(\prime)} \\
 &&+N_1\frac{\alpha_s}{8\pi}\frac{a}{f_a} G\tilde{G}+
 N_2\frac{\alpha}{8\pi}\frac{a}{f_a} F^{(\prime)}\tilde{F}^{(\prime)} \\
\end{eqnarray*}

* Since $f_a$ is low and higher dim. op.s destroy domain walls, $N_1\ne1$ is allowed

# Dilaton Decay
* Obviously, $\displaystyle\frac{s}{f_a}\partial a\partial a$ is the strongest
* Almost no $s\to2\gamma^{(\prime)}$ decay
* Is it failed? \pause - **No!**

# Photons and Photon Jets
* ECAL can't count the number of $\gamma$
    * Use "$s\to2a$, $a\to2\text{ collimated $\gamma$}$" mode \pause
    * TRT, a tracker just before ECAL, is able to count converted photons, although $4\gamma$ seems still allowed

# Axion Decay
## Lagrangian
$$
\mathcal L_a = N_1\frac{\alpha_s}{8\pi}\frac{a}{f_a} G\tilde{G}+ 
N_2\frac{\alpha}{8\pi}\frac{a}{f_a} F^{(\prime)}\tilde{F}^{(\prime)} $$

* We need large BR
    * $\text{BR}(s\to4\gamma)=\text{BR}(a\to2\gamma)^{\color{teal}2}$
* $a\mbox-G\mbox-G$ coupling looks too strong

# Is Large BR Possible?
## Two possibility
* $m_a < 3m_\pi$, the threshold of $a\to2g$
* Use the mixings with mesons

# $m_a < 3m_\pi$
* An axion lives too longer
* Typically, 
$$
\gamma\Gamma^{-1} \sim \frac{100\,\text{GeV}}{m_a}\left(\frac{4\pi}{\alpha}\right)^2 \frac{{f_a}^2}{{m_a}^3}
\gtrsim \mathcal O(1)\,\text{m}
$$

# Mixings with Mesons
* $a\to3\pi$ is suppressed by the phase factor


\begin{center}
\includegraphics[width=8cm]{width.pdf}
\end{center}

# Summary
* The heavy axion is possible
* The diphoton excess can be explained as the dilaton
    * Photon jets may be interesting