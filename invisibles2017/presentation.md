% Novel Method for Detecting Ultralight Dark Matter \hfill\small In preparation
% \underline{Hajime Fukuda}, T.T. Yanagida, S. Matsumoto
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H ../header -->
---
institute: Kavli IPMU, U. Tokyo
---

# Introduction
* Dark matter is one of the most rigid new physics
* Which mass range?

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


# Ultralight DM (a.k.a. Fuzzy DM)

* DM for $10^{-22}\,\text{eV} \lesssim m_\text{DM} \lesssim \text{eV}$
* Must be Bosonic
* Advantages in the small scale structure over WIMP\hfill\small Hu, *et al.*, 2000
* \normalsize May be from moduli d.o.f.


# Most Important Point

* How could we detect them?
    * Production - $\times$
    * Indirect Detection - $\times$ (or $\bigtriangleup$)
    * \bf Direct Detection

# Direct Detection
* One recoil may be small
    * Not enough to detect itself
* However, $n_\text{DM}$ is quite large
* $\text{\bf What is an appropriate target?}$
    * Measurement must be precise enough
    * Large enhancement

# Enhancement Effect
* The cross section gets enhanced by
    * Stimulated emission
        * We don't include since DM distribution is unknown
    * \bf Coherent effect on the target

# Coherent Effect
* e.g. Coulomb scattering

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

# Coherent Effect
* Naively, $\sigma\propto N_\text{targ}^2$
* The larger, the better
* $\text{\bf Use planets as the target!}, N\sim 10^{50\mbox-58}$
    * Measurement is very accurate, $\Delta v / v\Delta t \lesssim 10^{-(17\mbox-19)}\,\text{s}^{-1}$

# Real Cross Section
* Unfortunately, simple $N_\text{targ}^2$ scaling is wrong
    * Incident wave is too disturbed
* Planets looks as uniform sphere to DM
* $\text{\bf Schrödinger eq. with\ } V(r) = V_0 \Theta(R - r)$
    * Coherent effect is now properly included

# Real Cross Section
\begin{center}
\includegraphics[width=6\TPHorizModule]{crosssect.pdf}
\end{center}

# Final Result
* For the best target, we need one order more
    * $\sigma\sim {m_\text{DM}}^2/\Lambda^4, \Lambda\sim10^{13}\,\text{GeV}\ (m \lesssim 10^{-14}\,\text{eV})$

\begin{center}
\includegraphics[width=6\TPHorizModule]{result.pdf}
\end{center}
