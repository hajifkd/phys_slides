% Collider search for minimal dark matter \small 1703.09675, in preparation
% \underline{Hajime Fukuda}, N. Nagata, H.Otono and S. Shirai
% 2018 July 26
---
institute: Kavli IPMU, U. Tokyo
# pandoc -t beamer -V theme:metropolis -V fontsize:14pt -o presentation.pdf presentation.md -H ../header
---
## Dark Matter Properties
* What characterize the dark matter?
    * Abundance: $\Omega h^2 \sim 0.1$
    * Stability
    * Small interaction b/w SM particles
* The "minimal" candidate $\to$ minimal DM

\begin{textblock*}{0.4\linewidth}(250pt, 175pt)
    {\tiny Cirelli {\it et al.} 05}
\end{textblock*}

## Minimal Dark Matter
* Particle with SU$(2)$ and U$(1)$ charge
* Abundance: WIMP miracle
* Automatically stable for higher SU$(2)$ repr.
* Neutral one is weakly interacting

## DM Charge and Mass

| SU$(2)$ | U$(1)$ | mass |
|:-------:|:------:|:----:|
| 2 | $\frac12$ | 1.1 TeV|
| 3 | 0 | 2.9 TeV|
| $\cdots$ | | |
| 5 | 0 | 9.4 TeV|

* We focus on the Fermionic 5-plet in this talk

\begin{textblock*}{0.4\linewidth}(210pt, 155pt)
    {\tiny Cirelli {\it et al.} 15}
\end{textblock*}

## Detection Methods
* Now we know the interaction and the (upper bound of) mass.
* Then, how do we detect it?
    * Indirect detection
    * Direct detection
    * **Collider experiments**

## Search Strategy
* $\slashed{E}_T + j$: $\sim 3\text{TeV}$ for $100\,\text{TeV}$ collider $\text{\tiny Ismail {\it et al.} 16}$
* **Disappearing tracks** from the decay of **charged partners**

## Charged Partner in the $\text{SU}(2)$ Multiplet
* After EWSB, the 5-plet $\chi$ becomes
$$
\chi = (\chi^{2+}\ \chi^{+}\ \chi^0\ \chi^{-}\ \chi^{2-})
$$

* We have charged Dirac Fermions as the dark matter partner

## Mass Difference
* The radiative correction makes charged partners heavier
* Without EWSB, there's no mass difference
    * **Higgs VEV** $v$ is the typical scale
* $\Delta M \simeq Q^2 \alpha_2 M_W \sin^2\frac{\theta_W}2 \simeq Q^2 166\,\text{MeV} \ll M_\chi$

## Decay Mode and the Lifetime
* The Main decay mode is $\chi^{Q+1} \to \chi^{Q} \pi^+$
    * Width: $\Gamma \sim {G_F}^2 {f_\pi}^2 \Delta m^3$
* The lifetimes are macroscopic!
    * $\tau(\chi^{2+}) \sim 1\,\text{mm}$
    * $\tau(\chi^{+}) \sim 1.7\,\text{cm}$


## $\chi^{+}$ Track in the Collider
* In ATLAS, the pixel detector begins at 3 cm.
    * $\chi^{+}$ may leave the disappearing track!
    * The $p_T$ of $\pi^\pm$ is not large enough to reconstruct its track
    * $\chi^{2+}$ lifetime is too short for the tracker
        * Due to the small $\Delta m$, it doesn't look as a displaced vertex

<!--
## Track of Doubly Charged Partner
* $\chi^{2+}$ lifetime is too short for the tracker
* Looks like a displaced vertex?
* No - due to the small $\Delta m$
-->

## Setup for Disappearing Track Search
* $\chi^{2+}$ decay is almost instantaneously
* $c\tau(\chi^+\to\chi^0\pi^+) \sim 2\,\text{cm}$
    * Count how many disappearing tracks appear

<!--
## What limits the sensitivity?
* How many disappering track can we see?
* How large is the number of the background?

-->

## Number of Signals
* Production cross section for 13 TeV:

\begin{center}
\includegraphics[width=140pt]{xs.pdf}
\end{center}

* Not so small
* Acceptance rate?

## Cut and Acceptance Rate
* MET cut
* Jet PT cut
* Geometrical cut on $\eta$
* Isolation
    * Acceptance: $\mathcal O(\%)$
* **Disappearing condition**
    * $\exp(-L / c\tau\gamma\beta_T)$

\begin{textblock*}{0.4\linewidth}(200pt, 130pt)
    {\tiny ATLAS Collaboration, arXiv:1712.02118}
\end{textblock*}

## Look Inside the Tracker
\footnotesize
\begin{center}
\begin{tikzpicture}[remember picture,overlay]
\draw [anchor=west] (2.1, 1.5) node {$r=12\,\text{cm}$};
\draw [teal, ultra thick] (-2, 1.5) -- (2, 1.5);
\draw [anchor=west] (2.1, 0.5) node {$r=9\,\text{cm}$};
\draw [teal, ultra thick] (-2, 0.5) -- (2, 0.5);
\draw [anchor=west] (2.1, -0.83) node {$r=5\,\text{cm}$};
\draw [teal, ultra thick] (-2,-0.83) -- (2, -0.83);
\draw [anchor=west] (2.1, -1.5) node {$r=3\,\text{cm}$};
\draw [teal, ultra thick] (-2, -1.5) -- (2, -1.5);
\draw [anchor=west] (4.1, -2.5) node {$r=0\,\text{cm}$};
\draw [dashed, ultra thick] (-4, -2.5) -- (4, -2.5);


\draw [orange, thick] (0, -2.5) -- (-1.8, 2) arc (atan(0.4) + 180:90:0.5);
\draw [->, orange, thick] (-1.3, 2.5 + 0.186) -- (-1.29, 2.5 + 0.186);
\draw [->, gray, thick, dashed] (-1.8, 2) -- (-2.2, 3);

\draw [red, thick] (-0.2, -2.7) -- (0.2, -2.3);
\draw [red, thick] (0.2, -2.7) -- (-0.2, -2.3);

\fill [blue] (-0.4, -1.5) circle (0.1);
\fill [blue] (-0.67, -0.83) circle (0.1);
\fill [blue] (-1.2, 0.5) circle (0.1);
\fill [blue] (-1.6, 1.5) circle (0.1);

\draw [anchor=west] (-4.9, 2.1) node {$r$\,(cm)};
\draw [->, black, ultra thick] (-5, -3) -- (-5, 2.5);
\end{tikzpicture}
\end{center}

## Improvement to $2$-point Search
\footnotesize
\begin{center}
\begin{tikzpicture}[remember picture,overlay]
\draw [anchor=west] (2.1, 1.5) node {$r=12\,\text{cm}$};
\draw [anchor=west] (2.1, 0.5) node {$r=9\,\text{cm}$};
\draw [anchor=west] (2.1, -0.83) node {$r=5\,\text{cm}$};
\draw [anchor=west] (2.1, -1.5) node {$r=3\,\text{cm}$};
\draw [teal, ultra thick] (-2, 1.5) -- (2, 1.5);
\draw [teal, ultra thick] (-2, 0.5) -- (2, 0.5);
\draw [teal, ultra thick] (-2,-0.83) -- (2, -0.83);
\draw [teal, ultra thick] (-2, -1.5) -- (2, -1.5);
\draw [dashed, ultra thick] (-4, -2.5) -- (4, -2.5);

\draw [anchor=north] (0, -2.5) node [text width=160] {\begin{itemize}\item Interacting point is determined by the other jet activities\end{itemize}};
\draw [anchor=west] (-1.4, 0) node [text width=160] {\begin{itemize}\item $3$ points in total is enough!\end{itemize}};

\draw [orange, thick] (0, -2.5) -- (-0.8, -0.5) arc (atan(0.4) + 180:90:0.5);
\draw [->, orange, thick] (-0.3, 0.186) -- (-0.29, 0.186);
\draw [->, gray, thick, dashed] (-0.8, -0.5) -- (-2.2, 3);

\draw [->, green, thick] (0, -2.5) -- (2.5, -0.5);
\draw [->, green, thick] (0, -2.5) -- (-1.8, -1);

\draw [red, thick] (-0.2, -2.7) -- (0.2, -2.3);
\draw [red, thick] (0.2, -2.7) -- (-0.2, -2.3);

\fill [blue] (-0.4, -1.5) circle (0.1);
\fill [blue] (-0.67, -0.83) circle (0.1);
\draw [blue, thick] (-1.2, 0.5) circle (0.1);
\draw [blue, thick] (-1.6, 1.5) circle (0.1);
\end{tikzpicture}
\end{center}

\begin{textblock*}{0.4\linewidth}(210pt, 200pt)
    {\tiny HF, Nagata, Otono, Shirai 1703.09675}
\end{textblock*}

## Result
\begin{center}
\includegraphics[width=200pt]{constraint.pdf}
\end{center}

## Conclusions
* Disappearing track is important for minimal DM search
    * Including SUSY LSP like pure wino or higgsino
* We need to not only increase the energy but also **improve trackers and analysis**
* BG estimation & reduction is needed

# Backup

## What is the Background?
* Misidentification of kink tracks
    * Does not change much for 2-pt strategy 
    * Also, the displaced vertex analysis can be used
* **Fake disappearing tracks**

\begin{textblock*}{0.4\linewidth}(220pt, 180pt)
    {\tiny ATLAS Collaboration, arXiv:1712.02118}
\end{textblock*}

## Higgsino
\begin{center}
\includegraphics[width=250pt]{higgsino.pdf}
\end{center}

## Wino
\begin{center}
\includegraphics[width=250pt]{wino.pdf}
\end{center}
