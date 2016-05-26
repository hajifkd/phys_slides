% Possibility of the Heavy QCD Axion \hfil\tiny arXiv:1504.06084, 1602.07909
% Hajime Fukuda (Kavli IPMU) \newline\scriptsize in collabolation with: C.W. Chiang, K. Harigaya, M. Ibe and T.T. Yanagida
% \today
<!--- 
pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H <(echo '\usefonttheme{professionalfonts}\usepackage{txfonts}')
-->
# Strong CP Problem
* QCD should break CP symmetry
$$
\theta = \theta_\text{YM} + \arg\det(Y_uY_d)
$$
* However, the violation looks very small
$$
|\theta| \lesssim 10^{-10}
$$

# Peccei-Quinn mechanism \tiny Peccei & Quinn, 1977
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
    * Larger $f_a$, *invisible axion*
    * Heavier $m_a$, *heavy axion*
    
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

\tiny Rubakov 1997; Berezhiani, Gianfagna and Giannotti 2000\newline Hook 2014, HF, Harigaya, Ibe and Yanagida 2015, Albaid, Dine and Draper 2015\newline (Gherghetta, Nagata and Shifman 2016)

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

# Copy of SM
$$
\theta = \theta_\text{YM} + \tikz[baseline=(x.base)] {
  \node(x)[rectangle, fill=teal!20, rounded corners] {$\arg\det(Y_uY_d)$};
  }
$$

* $\theta'$ must also have Yukawa sector
* Thus, we need a complete copy of SM
    * We assume $\mathbb Z_2$ parity, which is spontaneously broken

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

# Use of spontaneous $\mathbb Z_2$ breaking
* Recall
$$
{m_a}^2 \simeq \frac{m_q' \Lambda'^3}{{f_a}^2}
$$
* We have to increase $m_q' \propto v'$ and $\Lambda'$
    * For $\Lambda'$, we introduce color charged particles and change their masses.

# Cosmological Properties 
* $\gamma'$ is massless 
    * The axion must decouple before QCD PT
* Seesaw mechanism in $\nu'$ is forbidden
    * $\nu'$s have large Dirac mass
    * No fine-tuning: $\sigma_{\mathbb Z_2} = \sigma_{B'-L'}^2/M_\text{Pl}$
    
<!---
# Stable Particle
* Two of the followings are stable

|       |$e'$|$\nu'$|${\pi^\pm}'$|($p'$)|
|:-----:|:--:|:----:|:----------:|:----:|
|$B'-L'$|$-1$|$-1$  | $0$        |$+1$  |
|$Q'$   |$-1$|$0$   |$\pm1$      |$+1$  |

* $\nu'$ must be unstable
-->

# Low Energy Spectrum
Axion $a$\phantom{hogehogehogehogehoge}
: $m_a\gtrsim 400\,\text{MeV}$

Vector like quark $\psi, \psi'$
: $m_\psi=\frac{1}{\sqrt2}gf_a\gtrsim 900\,\text{GeV}$

Dilaton $s$\phantom{hogehogehoge}
: $m_s=\sqrt{2\lambda}f_a$\tikz[baseline=(x.base)] {
  \node (x) {$\gtrsim \mathcal O(100)\,\text{GeV}$};\pause
  \node [rectangle, rounded corners, fill=teal!20, minimum width={100pt}] {$\simeq 750\,\text{GeV}$??};
}

<!---
# Effective Lagrangian

\begin{eqnarray*}
\mathcal L &=& \frac{s}{f_a}\partial a\partial a + 
N_1\frac{\alpha_s}{8\pi}\frac{s}{f_a} GG+
 N_2\frac{\alpha}{8\pi}\frac{s}{f_a} F^{(\prime)}F^{(\prime)} \\
 &&+N_1\frac{\alpha_s}{8\pi}\frac{a}{f_a} G\tilde{G}+
 N_2\frac{\alpha}{8\pi}\frac{a}{f_a} F^{(\prime)}\tilde{F}^{(\prime)} \\
\end{eqnarray*}

* Since higher dim. op.s destroy domain walls, $N_1\ne1$ is allowed
-->

# Dilaton Decay
* Obviously, $\displaystyle\frac{s}{f_a}\partial a\partial a$ is the strongest
* Almost no $s\to2\gamma^{(\prime)}$ decay
* Does it fail? \pause - **No!**

# Photons and Photon Jets
* ECAL can't count the number of $\gamma$
    * Use "$s\to2a$, $a\to2\text{ collinear $\gamma$}$" mode
<!---    * TRT, a tracker just before ECAL, is able to count converted photons, although $4\gamma$ seems still allowed-->


\begin{center}
\begin{tikzpicture}
\node [circle, white, fill=teal] (s) at (5, 0) {$s$};
\node [circle, white, fill=orange!90!black] (a1) at (3.5, -0.5) {$a$};
\node [circle, white, fill=red!90!black] (g11) at (3.5-1.72, -0.5-1.14) {$\gamma$};
\node [circle, white, fill=red!90!black] (g12) at (3.5-2.05, -0.5+0.195) {$\gamma$};
\node [circle, white, fill=orange!90!black] (a2) at (6.5, 0.5) {$a$};
\node [circle, white, fill=red!90!black] (g21) at (6.5+1.72, 0.5+1.14) {$\gamma$};
\node [circle, white, fill=red!90!black] (g22) at (6.5+2.05, 0.5-0.195) {$\gamma$};
\draw [->, ultra thick] (s) -- (a1);
\draw [->, ultra thick] (s) -- (a2);
\draw [->, thick] (a1) -- (g12);
\draw [->, thick] (a1) -- (g11);
\draw [->, thick] (a2) -- (g22);
\draw [->, thick] (a2) -- (g21);
\end{tikzpicture}
\end{center}

<!---
# How to Distinguish the Jet
* Some fraction of photons is converted into $e^+e^-$ in the detectors
* Several properties are different
    * The conversion rate
    * The acceptance...
    
\tiny Draper _et al._ 2012, Ellis _et al._ 2013, ...; \newline
Dasgupta _et al._ 2016, HF, Ibe, Nojiri in preparation
-->

# Axion Decay
## Lagrangian
$$
\mathcal L_a = N_1\frac{\alpha_s}{8\pi}\frac{a}{f_a} G^{(\prime)}\tilde{G}^{(\prime)}+ 
N_2\frac{\alpha}{8\pi}\frac{a}{f_a} F^{(\prime)}\tilde{F}^{(\prime)} $$

* We need large BR
    * $\text{BR}(s\to4\gamma)=\text{BR}(a\to2\gamma)^{\color{red!90!black}2}$
* $a\mbox-G\mbox-G$ coupling looks too strong

# Is Large BR Possible?
## Two possibility
* $m_a < 3m_\pi$, the threshold of $a\to2g$
* Use the mixings with mesons

<!---
# $m_a < 3m_\pi$
* An axion lives too longer
* Typically, 
$$
\gamma\Gamma^{-1} \sim \frac{100\,\text{GeV}}{m_a}\left(\frac{4\pi}{\alpha}\right)^2 \frac{{f_a}^2}{{m_a}^3}
\gtrsim \mathcal O(1)\,\text{m}
$$
-->

# Mixings with Mesons
* The phase space suppresses $a\to3\pi$


\begin{center}
\includegraphics[width=8cm]{width.pdf}
\end{center}

# Summary
* The heavy axion is possible
* We need a complete copy of SM
* The diphoton excess can be explained as the dilaton using our model
