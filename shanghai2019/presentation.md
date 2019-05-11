% Direct Detection of Ultralight Dark Matter via Astronomical Ephemeris \hfill\small 1801.02807 PLB
% \underline{Hajime Fukuda}, S. Matsumoto, T. T. Yanagida
% May 15, 2019 <!--- pandoc -t beamer -V theme:metropolis -V fontsize:14pt -o presentation.pdf presentation.md -H ./header -->
---
institute: T. D. Lee Institute
---

## Introduction
* Dark matter is one of the most rigid new physics
* Which mass range?

## Particle DM Mass Range

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


## Particle DM Mass Range

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

## Outline

* Introduction to Ultralight DM
* DM Collision Effects
* Cross Section Estimation
* Discussion and Summary

# Introduction to Ultralight DM

## Ultralight DM

* DM for $10^{-22}\,\text{eV} \lesssim m_\text{DM} \lesssim \text{eV}$
* Must be Bosonic
* $m\sim10^{-22}\,\text{eV}$: "Fuzzy DM"
    * \small _e.g._ Hu, *et al.*, 2000
* \normalsize Moduli d.o.f.?
* Non-thermally produced
    * Coherent oscillation
    * Decay of defects


## Measure DM properties

* Suppose DM has non-gravitational interaction. How could we detect them?
    * Production
    * Indirect Detection
    * \bf Direct Detection

## Direct Detection
* One recoil momentum: $\Delta p \propto m$
* Number density: $n_\text{DM} \propto m^{-1}$
    * Total recoil: $\Delta p_\text{tot} \propto n_\text{DM} \Delta p \propto m^0$
* The drawback is to choose a good target
* We propose to use the **celestial bodies** in the solar system

## Why Celestial Bodies?
* The measurements are good enough
    * "Ephemeris", $\Delta R / R \sim 10^{-10}$
* Large quantum mechanical enhancement

# DM Collision Effects

## Motion of Celestial Bodies

* The entire solar system moves w.r.t. the galaxy
    * $v_s \sim 10^{-3}$
* Each planets rotates
    * $v_p \sim 10^{-4}$

\begin{center}
\begin{tikzpicture}
\draw [orange, thick, fill] (0, 0) circle [x radius=0.2, y radius=0.2];
\draw [thick] (0, 0) circle [x radius=1, y radius=0.5, rotate=30];
\draw [teal, thick, fill] (0.85, 0.5) circle [x radius=0.1, y radius=0.1];
\draw [->, ultra thick] (-1.1, 0) -- (-2.5, 0);
\draw [->, thick] (1, 0.65) -- (1.1, 0.47);
\end{tikzpicture}
\end{center}

## Motion of DM

* The DM velocity obeys Gaussian dist.
    * $v_0 \sim 10^{-3}$
* $v < v_\text{esc}$, $v_\text{esc} \simeq 600\,\text{km}/\text{s}$

## DM Collision

* Consider the observer on the celestial body (*e.g.* us, on the Earth)

\begin{center}
\begin{tikzpicture}
\draw [teal, thick, fill] (0, 0) circle [x radius=1, y radius=1];
\draw [->, ultra thick] (-3.0, -1) -- (-1.1, -1);
\draw [->, ultra thick] (-3.0, 0) -- (-1.1, 0);
\draw [->, ultra thick] (-3.0, 1) -- (-1.1, 1);
\draw (-3.2, 0) node[anchor=east] {DM};
\end{tikzpicture}
\end{center}

* The observer feels DM "wind" of $v\sim10^{-3}$, which (de-)accelerate the object

## Comparison with the Ephemeris

* Now, we know the position of each planets for decades by the ephemeris
* On the other hand, 
$$
M \vec{a} = \int \text{d}\Omega \frac{\text{d}\sigma}{\text{d}\Omega} n v \vec{q}(\Omega).
$$
* We want to know the differential cross sect., ${\text{d}\sigma}/{\text{d}\Omega}$

# Cross Section Estimation

## Interaction

* Assume, between DM $\phi$ and nucleon $N$,
$$
\Delta \mathcal L = \frac{c_N}2 \phi^2 \bar{N}N,
$$
where
$$
c_N = \frac{f_N m_N}{\Lambda^2},
$$
and $\Lambda$ is the cutoff scale.

## Naive Estimation - Starting Point

* Naively,
$$
\frac{\text{d}\sigma}{\text{d}\Omega} = N \frac{{c_N}^2}{(4\pi)^2},
$$
where $N = M / m_N \sim 10^{50\mbox-58}$

* Given $\Lambda\gg v_\text{EW}$, the momentum transfer is smaller than usual WIMPs
* However, Quantum mechenical effects enhance the cross section

## Enhancement Effects
* The cross section gets enhanced by
    * Stimulated emission
    * Coherent effect

## Enhancement Effects
* The cross section gets enhanced by
    * **Stimulated emission**
    * Coherent effect

## Stimulated Emission
* *e.g.* LASER
$$
\langle n + 1 | a^\dagger | n\rangle \propto \sqrt{n + 1}
$$

* This is because of the state normalization
$$
|n\rangle = \frac{1}{\sqrt{n!}} (a^\dagger)^n |0\rangle
$$

* Producing a Boson in the Boson bg. gets enhanced

## DM Scattering in the DM Background
* $T(P) + \text{DM}(p) \to T(P') + \text{DM}(p')$
* If there are already a number of $\text{DM}(p')$s, the cross sect. becomes much larger

## Most Naive Estimation
* The cross sect. gets $\mathcal N + 1$ times larger
    * $\mathcal N$ is the number of DM per $\text{d}^3p\text{d}^3x / (2\pi)^3$
* Assuming specially uniform dist.,
$$
\mathcal N \sim \frac{n}{p_0^3} \sim 10^{37}\left(\frac{10^{-10}\,\text{eV}}{m}\right)^4.
$$

## DM Distribution in the Galaxy
* DM obeys Gaussian dist., in the *galactic* scale
* Nobody knows how in the solar system scale
* Thus, we parameterized the effect by a factor $B$
    * $B \lesssim \mathcal N + 1$

## Is this discussion correct?
* "Does really stim. emission effective?"
    * "It is just T-inversion of $N$ particle scattering"
    * $\langle n + 1 | S | n \rangle = \left(\langle n | S | n + 1 \rangle\right)^\star$
* However, the larger $n$ is, the rarer it is that only $1$ particle scatters
    * The cross sect. is not $n$ times larger

## How do we evaluate the effect?
* At least, the cross section is smaller than the unitarity bound
* For $p = mv > R_\text{targ}$,
    * $\sigma < 4\pi / p^2$
* For $p < R_\text{targ}$,
    * Scattering occurs with $L < L_\text{max} = pR_\text{targ}$
    * $\sigma < \sum_{L}^{L_\text{max}} 4\pi (2L + 1) / p^2 \sim \pi L_\text{max}^2 / p^2 \sim \pi R_\text{targ}^2$

## Enhancement Effects
* The cross section gets enhanced by
    * Stimulated emission
    * **Coherent effect**

## Coherent Effect
* *e.g.* Coulomb scattering

\begin{center}
\begin{tikzpicture}
\draw [ultra thick] (0, 0) -- (4, 0);
\draw [ultra thick] (4, 0) -- (8, 0.8);
\draw [teal, thick, snake it] (4, 0) -- (6.5, -2.5);
\draw [olive, thick, fill] (6.71, -2.71) circle [x radius=1, y radius=1];
\draw (0, 0.1) node[anchor=south west] {\large $e$};
\draw (5.61, -2.71) node[anchor=east] {Nucleus (charge $Z$)};
\draw [->, ultra thick] (4.0, -0.9) -- (5.0, -1.9);
\draw (4.6, -1.6) node[anchor=east] {$q^\mu$};
\draw [<->, ultra thick] (6.71, -1.71) -- (6.71, -3.71);
\draw (6.8, -2.71) node[anchor=west] {$R$};
\end{tikzpicture}
\end{center}

* For $qR < 1$, $\sigma\propto Z^2$ !

## Coherent Effect
* Naively, $\sigma\propto N_\text{targ}^2$
    * (The interaction must be "spin-independent")
* The larger, the better
* For $N\sim 10^{50\mbox-58}$, $> 10^{100}$ times enhancement?

## $N_\text{targ}^2$ Scaling is Wrong
* What is coherence effect, in detail?

\begin{center}
\begin{tikzpicture}
\draw [ultra thick, snake it] (-3, 0) -- (-1.5, 0);
\draw [->, thick] (-1.2, 0) -- (-0.7, 0);
\draw [-, thick, dashed] (0, 0) -- (0.8, 0.6);
\draw [-, thick, dashed] (0, 0) -- (0.6, -0.4);
\draw [olive, thick, fill] (0, 0) circle [x radius=0.2, y radius=0.2];
\draw [olive, thick, fill] (0.8, 0.6) circle [x radius=0.2, y radius=0.2];
\draw [olive, thick, fill] (0.6, -0.4) circle [x radius=0.2, y radius=0.2];
\end{tikzpicture}
\end{center}

* If each scattering is nearly independent, $\mathcal A_\text{tot} = \sum e^{ik\Delta r_i} \mathcal A_i$
    * This goes $\mathcal A_\text{tot} \sim N \mathcal A$ for ${k\Delta r_i} \ll 1$
        * *e.g.* "spin-independent scattering" for Xenon, ...

## $N_\text{targ}^2$ Scaling is Wrong

* For weak enough interaction, each scattering is usually independent
    * "Born approximation"
* With very large $N$, "scattering" may occur multiple times
    * In other words, Born approximation fails

## Real Cross Section
* How the planets look like to DM?
    * Uniform sphere $\to$ **Constant potential sphere**
* **Schrödinger eq. with** $V(r) = V_0 \Theta(R - r)$
    * $V_0$ must be $V_0(\rho_\text{targ})$
        * Matching $V_0$ for small enough $r$ with $N^2$ enhancement

## Result of the Schrödinger Eq.
\begin{center}
\includegraphics[width=10\TPHorizModule]{crosssect.pdf}
\end{center}

## Short Summary
* The cross sect. gets enhanced by
* Stimulated emission
    * Parameterized by $B$, $B \lesssim 10^{37} (10^{-10}\,\text{eV} / m)^4$
* Coherent effect
    * The cross section becomes as large as the geometrical one

# Discussion and Summary

## Result
* 3 Params: DM mass $m$, the cutoff $\Lambda$ and $B$
* Given $m$ and $\Lambda$, if $B$ is too large, it is excluded
* We have shown the upper bound of $B$ in terms of $m$ and $\Lambda$
* Among the Earth, Sun, Saturn and Moon, the best one is used for each point

## Result
\begin{center}
\includegraphics[width=10\TPHorizModule]{result.pdf}
\end{center}

## Conservative Result
\begin{center}
\includegraphics[width=10\TPHorizModule]{Xsection.pdf}
\end{center}

## Discussion
* Is there any other target?
* Pseudoscalar DM?
    * No coherence, but stimulated emission is still there
* Inelastic scattering?

## Summary
* For ultralight DM $m\ll \text{eV}$, the celestial bodies in the solar system can be good targets for the direct detection
* Depending on the DM distribution, it can be excluded
