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

# Summery