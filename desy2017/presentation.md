% Direct Detection of Ultralight Dark Matter \hfill\small In preparation
% \underline{Hajime Fukuda}, S. Matsumoto, T.T. Yanagida
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H ../header -->
---
institute: Kavli IPMU, U. Tokyo
---

# Introduction
* DM: one of the most established BSM
* How heavy is the mass?

# Particle DM Mass Range

\begin{center}
\begin{tikzpicture}
\fill [olive] (-0.3, -4) rectangle (0.9, 0);
\fill [olive] (9.6, -4) rectangle (11, 0);
\draw [->, ultra thick] (0, -4) -- (11, -4);
\foreach \x / \y in {-22/0.9, -17/1.8, -12/2.7, -7/3.6, -2/4.5, 3/5.4, 8/6.3, 13/7.2, 18/8.1, 23/9, 28/9.9}
  \draw (\y, -3.9) -- (\y, -4.1) node[anchor=north] {\small $10^{\x}$};
\draw (11, -4.1) node[anchor=north] {eV};
\draw (-0.3, 0) node[anchor=north west] {\small dSph};
\draw (11.2, 0) node[anchor=north east] {\small $m>M_\text{Pl}$};
\draw (5, -2) node[anchor=north] {\LARGE Vast Region!};
\end{tikzpicture}
\end{center}


# Particle DM Mass Range

\begin{center}
\begin{tikzpicture}
\fill [olive] (-0.3, -4) rectangle (0.9, 0);
\fill [olive] (9.6, -4) rectangle (11, 0);
\draw [->, ultra thick] (0, -4) -- (11, -4);
\foreach \x / \y in {-22/0.9, -17/1.8, -12/2.7, -7/3.6, -2/4.5, 3/5.4, 8/6.3, 13/7.2, 18/8.1, 23/9, 28/9.9}
  \draw (\y, -3.9) -- (\y, -4.1) node[anchor=north] {\small $10^{\x}$};
\draw (11, -4.1) node[anchor=north] {eV};
\draw [teal, thick] (3,-3) circle [x radius=2.1, y radius=0.8];
\draw [<-, ultra thick] (3, -3) -- (5, -2) node[anchor=south west,align=center] {Region of Interest\\in this talk};
\end{tikzpicture}
\end{center}


# Ultralight DM

* (See L. Hui's plenary talk)
* DM for $10^{-22}\,\text{eV} \lesssim m_\text{DM} \lesssim \text{eV}$
* Must be Bosonic
* Behaves as CDM
    * Coherent oscillation/decay of defects/...
* Several interesting astrophysical signature
    * \small _e.g._ Hu, *et al.*, 2000
* \normalsize Moduli? ALP?

# Today's topic
* How can we detect ultralight DM?
    * Indirect detection
    * Production
    * $\text{\color{red}Direct detection}$
        * Assume DM and nucleons have non-gravitational interaction

# Direct Detection
* One recoil, $q \sim p = mv$, is small
* However, $n_\text{DM} \sim \rho / m$ is quite large
* The total momentum transfer: $Q \propto qn \sim v\rho$
* **Quantum mechanical enhancement in XS**

# Tasks
* What to be targets?
    * Measurement must be precise enough
    * Large enhancement
      * Our conclusion is *to use planets as targets*
* Enhancement factor?

# Enhancement Effect
* Stimulated emission
* Coherent effect on the target

# Stimulated Emission
* _e.g._ LASER
$$
\mathcal{A} = \langle \gamma | a^\dagger | 0 \rangle
$$
$$
\to \mathcal{A}' = \langle (N + 1) \gamma | a^\dagger | N \gamma \rangle = \sqrt{N + 1} \mathcal A
$$

* Because,
$$
|N \gamma \rangle = \frac{1}{\sqrt{N!}} \left(a^\dagger\right)^N |0 \rangle,
$$
$a^\dagger | N \gamma \rangle = \sqrt{N + 1} | (N + 1) \gamma \rangle$

# Stimulated Emission
* Given the phase space density $\mathcal O$, $\sigma \propto \mathcal O + 1$
    * Note that
    $$
    \int \frac{\text{d}^3k}{(2\pi)^3} \mathcal O(k, x) = n(x)
    $$

# Enhancement
* DM: Gaussian distribution of $v\sim10^{-3}$
* Assuming the distribution is uniform,
$$
\mathcal O \sim \frac{\rho}{m} \frac{1}{(mv)^3} \sim 10^3 \left(\frac{\text{eV}}{m}\right)^4
$$

# Loophole
* We need DM distribution around us
* Not the case for coherent oscillation?

\begin{center}
\begin{tikzpicture}
\draw [olive, thick, fill] (0, 0) circle [x radius=1, y radius=1];
\draw [->, ultra thick] (1, -0.3) -- (2, -0.6);
\draw [olive, thick, fill] (1, 2) circle [x radius=1, y radius=1];
\draw [->, ultra thick] (0, 2.4) -- (-0.8, 2.72);
\draw [olive, thick, fill] (3, 1) circle [x radius=1, y radius=1];
\draw [->, ultra thick] (3, -0.1) -- (3, -1.1);
\draw [<->, ultra thick] (4.1, 2) -- (4.1, 0);
\draw (4.3, 1) node[anchor=west] {$R_J \gtrsim r \gtrsim \frac{1}{mv}$};
\end{tikzpicture}
\end{center}

# Enhancement Effect
* Stimulated emission - $\times$ (or $\bigtriangleup$)
* Coherent effect on the target

# Coherent Effect
* e.g. Coulomb scattering

\begin{center}
\begin{tikzpicture}
\draw [ultra thick] (0, 0) -- (4, 0);
\draw [ultra thick] (4, 0) -- (8, 0.8);
\draw [teal, thick, snake it] (4, 0) -- (6.5, -2.5);
\draw [olive, thick, fill] (6.71, -2.71) circle [x radius=1, y radius=1];
\draw (0, 0.1) node[anchor=south west] {\large $e$};
\draw (5.61, -2.71) node[anchor=east] {Nucleus (charge $Z$)}; \draw [->, ultra thick] (4.0, -0.9) -- (5.0, -1.9);
\draw (4.6, -1.6) node[anchor=east] {$q^\mu$}; \draw [<->, ultra thick] (6.71, -1.71) -- (6.71, -3.71); \draw (6.8, -2.71) node[anchor=west] {$R$};
\end{tikzpicture}
\end{center}

* For $qR < 1$, $\sigma\propto Z^2$ !

# Coherent Effect
* "With small $q$, we can't see internal structures"
* Identical with "Spin-independent scattering"
    * $\sigma \sim [Z\sigma_p + (A - Z)\sigma_n]^2 |F(q)|^2$
    * DM must interact spin-independently also in this case

# Coherence in Detail
* Easy to understand in 1st quantization
* Born Approximation: $\mathcal A \sim m \langle k' | V | k \rangle$
* For many targets:
$$V(x) = \sum_i V_i(x - x_i), \mathcal A_\text{tot} = \sum_i e^{iqx_i} \mathcal A_i$$
* $qx_i\to0$ for all $i$, $\mathcal A_\text{tot} \simeq N \mathcal A$
* Amplitude scales as $N$, XS as $N^2$!
* The lighter the mass is, the smaller $q$ is

# Which Target?
* Enhancement depends on targets
* The bigger, the better
* $\text{\bf The celestial bodies in the solar system}$, $N\sim 10^{50\mbox-58}$
    * Measurement is very accurate, $\Delta v / v\Delta t \lesssim 10^{-(17\mbox-19)}\,\text{s}^{-1}$
* $10^{100}$ times larger $\sigma$?


# Coherence in Detail
* Easy to understand in 1st quantization
* Born Approximation: $\mathcal A \sim m \langle k' | V | k \rangle$
* For many targets:
$$V(x) = \sum_i V_i(x - x_i), \mathcal A_\text{tot} = \sum_i e^{iqx_i} \mathcal A_i$$
* $qx_i\to0$ for all $i$, $\mathcal A_\text{tot} \simeq N \mathcal A$
* Amplitude scales as $N$, XS as $N^2$!

# Coherence in Detail
* Easy to understand in 1st quantization
* $\text{\color{red} Born Approximation: $\mathcal A \sim m \langle k' | V | k \rangle$}$
* For many targets:
$$V(x) = \sum_i V_i(x - x_i), \mathcal A_\text{tot} = \sum_i e^{iqx_i} \mathcal A_i$$
* $qx_i\to0$ for all $i$, $\mathcal A_\text{tot} \simeq N \mathcal A$
* Amplitude scales as $N$, XS as $N^2$!

# What's Wrong?
* $N^2 |F(q)|^2$ enhance is valid only within Born app.
* Born app.: "Initial wave scatters only once"
    * High potential - $\times$
    * $\text{\bf Large object}$ - $\times$
* We need to solve $\text{Schr\"odinger}$ eq. exactly

# e.g. Sun-DM Scattering
\begin{center}
\includegraphics[width=5\TPHorizModule]{crosssect.pdf}
\end{center}
* $\sigma \lesssim \mathcal O (1) \pi R^2$

# Enhancement: in Summary
* Stimulated Emission - ?
* Coherent Effect - OK
* The larger the target is, the better
    * The celestial bodies in the solar system as targets
    * The cross section is at most geometrical

# Constraint
* Constraints from the motion of the celestial bodies
* The solar system moves w.r.t. the DM
* DM-Star scattering $\to$ DM wind, *friction force*
* Periods and distances change

# Actual constraints
* Use Ephemeris
    * Ephemeris: A parameter fit for various quantities for celestial bodies in solar system from observations
* The latest one is numerical
    * Hard to reproduce :(
    * Naive estimation: $\Delta \ln v / \Delta t \sim \Delta L / T^2$

# Cross section and the Size of the Object
* The weaker int. gets enhanced much for the heavier obj.
    * $\sigma_0\sim {m_\text{DM}}^2/\Lambda^4$ $\to$ $\Lambda\lesssim10^{13,14,15,16}\,\text{GeV}$ for Moon, Earth, Jupiter and Sun
* The lighter, the larger the effect is
    * EOM: $F = ma$
* Different region for different objects

# Final Result
* For the best target, we need one order more

\begin{center}
\includegraphics[width=6\TPHorizModule]{result.pdf}
\end{center}

# Summary
* Quantum mechanical enhancement for very light particles
* DM with $m\ll \text{eV}$ can be detectable with coherence enhancement
