% Direct Detection of Ultralight Dark Matter via Astronomical Ephemeris \hfill\small 1801.02807
% \underline{Hajime Fukuda}, T.T. Yanagida, S. Matsumoto
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:14pt -o presentation.pdf presentation.md -H ./header -->
---
institute: Kavli IPMU, U. Tokyo
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

## Ultralight DM

* DM for $10^{-22}\,\text{eV} \lesssim m_\text{DM} \lesssim \text{eV}$
* Must be Bosonic
* Non-thermally produced
* Suppose DM has non-gravitational interaction. How could we detect them?

## Direct Detection
* One recoil momentum: $\Delta p \propto m$
* Number density: $n_\text{DM} \propto m^{-1}$
    * Total recoil: $\Delta p_\text{tot} \propto n_\text{DM} \Delta p \propto m^0$
* Need to choose a good target
* We propose to use the **celestial bodies** in the solar system

## Why Celestial Bodies?
* Celestial bodies feel DM "wind", getting accelerated
* The measurements are good enough
    * "Ephemeris", $\Delta R / R \sim 10^{-10}$
* Large quantum mechanical enhancement

# Cross Section Estimation

## Interaction

* Assume an effective interaction between DM and nucleon $N$
$$
\Delta \mathcal L = \frac{c_N}2 \phi^2 \bar{N}N,
$$
where
$$
c_N = \frac{f_N m_N}{\Lambda^2},
$$
$\Lambda$ is the cutoff scale.

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
    * Scattering of a DM in the DM bg. gets enhanced

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

## $N_\text{targ}^2$ Scaling is Wrong
* Naively, $\sigma\propto N_\text{targ}^2$
    * (The interaction must be "spin-independent")
* For very large $N$, Born approximation fails and this is no more the case

## Real Cross Section
* How the planets look like to DM?
    * Uniform sphere $\to$ **Constant potential sphere**
* **Schrödinger eq. with** $V(r) = V_0 \Theta(R - r)$

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

# Result and Summary

## Result
* 3 Params: DM mass $m$, the cutoff $\Lambda$ and $B$
* Given $m$ and $\Lambda$, if $B$ is too large, it is excluded
* We have shown the upper bound of $B$ in terms of $m$ and $\Lambda$
* Among the Earth, Sun, Saturn and Moon, the best one is used for each point

## Result
\begin{center}
\includegraphics[width=10\TPHorizModule]{result.pdf}
\end{center}

## Summary
* For ultralight DM $m\ll \text{eV}$, the celestial bodies in the solar system can be good targets for the direct detection
* Depending on the DM distribution, it can be excluded
