% Disappearing track searches for minimal dark matter at the LHC \small 1703.09675, in preparation
% \underline{Hajime Fukuda}, N. Nagata, H.Otono and S. Shirai
% \today
---
institute: Kavli IPMU, U. Tokyo
# pandoc -t beamer -V theme:metropolis -V fontsize:14pt -o presentation.pdf presentation.md -H ../header
---
## What is the dark matter?
* Dark matter with good theoretical motivation
    * Electroweak WIMP
    * QCD Axion *etc.*
* In this talk, I focus on **$\text{SU}(2)_L$-charged Fermionic DM**

## How can we detect them?
* Three strategies
    * Direct detection
    * Indirect detection
    * **Collider** - Main topic in this talk
* They are complementary

## Outline
* What is and why the disappearing track search?
* How heavy mass can we reach?
* How can we reduce the background?

# What is and why the disappearing track search?

## Dark matter charge

* Neutral component must be there
    * This fixes $\text{U}(1)_Y$ charge

|                   | $\tilde h$ | $\tilde W$ |     |     |     | ... |
|:-----------------:|:----------:|:----------:|:---:|:---:|:---:|:---:|
| $\text{SU}(2)_L$  | $2$        | $3$        | $3$ | $4$ | $5$ | ... |
| $\text{U}(1)_Y$   | $1/2$      | $0$        | $1$ | ... | ... | ... |

* As an example, consider Higgsino($\tilde h$)-like DM
    * Same goes for wino-like and other DM 

## Dark matter mass
* Thermal abundance fixes the mass
    * $1.1\,\text{TeV}$ for Higgsino-like DM
        * (Use this as canonical values)
    * It still sounds within the range of colliders

## Dark matter @ Colliders
* Basic strategy: $\slashed{E}_T + X$
* Poorer than the thermal mass even for $100\,\text{TeV}$

\begin{center}
\includegraphics[width=200pt]{higgsino_exp.pdf}
\end{center}

\begin{textblock*}{0.4\linewidth}(250pt, 235pt)
    {\tiny Arkani-Hamed {\it et al.} 15}
\end{textblock*}

## Another strategy
* **Disappearing tracks** from the decay of **charged partners**

## Take a detailed look at $\text{SU}(2)$ multiplet
$$
\tilde{h} = \begin{pmatrix}\tilde{h}^0 \\ \tilde{h}^+\end{pmatrix}
$$

* Charged partners are *always* there
    * Must be heavier then the neutral one

## Mass difference and the lifetime
* No $\text{SU}(2)\times\text{U}(1)$ breakdown, no mass diff.
    * Mass diff. is much smaller than the thermal mass
* For smaller mass diff., *larger lifetimes* are expected
    * $c\tau(\chi^+\to\chi^0\pi^+) \sim 0.7\,\text{cm} \left(\frac{\Delta m}{350\,\text{MeV}}\right)^{-3}$ for Higgsino

## Disappearing tracks in colliders
\begin{center}
\includegraphics[width=280pt]{ATLAS.pdf}
\end{center}
* A charged partner decays inside the tracker region $\to$ *Disappearing* track
    * The $p_T$ of $\pi^\pm$ is not large enough to reconstruct its track

## Two origin of the mass difference
* Mixing with other particles
* Radiative correction $\Delta m \sim \frac{\alpha}{4\pi} v_\text{EW}$
    * $350\,\text{MeV}$ for Higgsino

## Mixing with other particles
* This highly depends on UV phisics; *e.g.*
    * For Higgsino - bino or wino-like particle
* Roughly, $\text{mass diff.} \simeq \text{coupling to Higgs}$
    * The additional particles enhance the coupling to Higgs and thus **to SM particles**
    * If the mass diff. is large enough, direct detection cross section is larger than the $\nu$-floor

 \begin{textblock*}{0.4\linewidth}(220pt, 215pt)
    {\tiny HF, Nagata, Otono, Shirai 17}
\end{textblock*}

## Setup for disappearing track search
* Assume only radiative mass difference;
    * $c\tau(\chi^+\to\chi^0\pi^+) \sim 0.7\,\text{cm}$ for Higgsino
    * (Such "decoupling" DM models are also theoretically motivated)
* Then, ask how far we can see.

# How heavy mass can we reach?

## Conventional study
\begin{center}
\includegraphics[width=220pt]{conv_disap_higgsino.pdf}
\end{center}
\begin{textblock*}{0.4\linewidth}(250pt, 200pt)
    {\tiny Arkani-Hamed {\it et al.} 15}
\end{textblock*}

* For Higgsino, even $100\,\text{TeV}$ is still not enough!
* Do we really need $100\,\text{TeV}$ or more?

## What limits the sensitivity?
* Numerous Higgsinos are *there*
* Just we can *not* see enough disappearing tracks
* Why? -  Matter of analysis/tracker

## Look inside the tracker
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

## Improvement to $2$-point search
\footnotesize
\begin{center}
\begin{tikzpicture}[remember picture,overlay]
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

## Result
\begin{center}
\includegraphics[width=250pt]{higgsino.pdf}
\end{center}

# How can we reduce the background?

## Fight against the background
* One of the reasons to require $4$ points is to reduce the BG
* For $2$-pt search, we must do harder than now

## What is the background
* Misidentification of kink tracks
* **Fake disappearing tracks**

## Fake disappearing tracks
\footnotesize
\begin{center}
\begin{tikzpicture}[remember picture,overlay]
\draw [teal, ultra thick] (-2, 1.67) -- (2, 1.67);
\draw [teal, ultra thick] (-2, 0) -- (2, 0);
\draw [dashed, ultra thick] (-4, -2.5) -- (4, -2.5);

\draw [->, orange, thick] (1, -2.5) arc (210:120:4);
\draw [->, orange, thick] (-1, -2.5) arc (180:140:8.087);
\draw [->, gray, thick, dashed] (1, -2.5) -- (0.159124,1.67);

\draw [red, thick] (1-0.2, -2.7) -- (1.2, -2.3);
\draw [red, thick] (1.2, -2.7) -- (1-0.2, -2.3);

\draw [red, thick] (-1-0.2, -2.7) -- (-1 + 0.2, -2.3);
\draw [red, thick] (-1 + 0.2, -2.7) -- (-1-0.2, -2.3);

\fill [blue] (0.49547, 0) circle (0.1);
\draw [blue, thick] (1.101728, 1.67) circle (0.1);
\fill [blue] (0.159124,1.67) circle (0.1);
\end{tikzpicture}
\end{center}

## Reduce them by additional points
\footnotesize
\begin{center}
\begin{tikzpicture}[remember picture,overlay]
\draw [teal, ultra thick] (-2, 1.67) -- (2, 1.67);
\draw [teal, ultra thick] (-2, 0) -- (2, 0);
\draw [dashed, ultra thick] (-4, -2.5) -- (4, -2.5);

\draw [->, orange, thick] (1, -2.5) arc (210:120:4);
\draw [->, orange, thick] (-1, -2.5) arc (180:140:8.087);
\draw [->, gray, thick, dashed] (1, -2.5) -- (0.159124,1.67);

\draw [red, thick] (1-0.2, -2.7) -- (1.2, -2.3);
\draw [red, thick] (1.2, -2.7) -- (1-0.2, -2.3);

\draw [red, thick] (-1-0.2, -2.7) -- (-1 + 0.2, -2.3);
\draw [red, thick] (-1 + 0.2, -2.7) -- (-1-0.2, -2.3);

\fill [blue] (0.49547, 0) circle (0.1);
\draw [red, thick] (1.101728, 1.67) circle (0.1);
\fill [blue] (0.159124,1.67) circle (0.1);
\end{tikzpicture}
\end{center}
\begin{textblock*}{0.4\linewidth}(240pt, 250pt)
    {\tiny HF, Nagata, Otono, Shirai in prep}
\end{textblock*}

# Summary
## Summary
* Disappearing track is essential for the minimal dark matter search
* We need to
    * not only increase the energy but also **improve trackers and analysis**
    * estimate and reduce the background