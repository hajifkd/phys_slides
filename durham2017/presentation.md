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
*How heavy mass can we reach?
* How can we reduce the background?

# What is and why the disappearing track search?

## Dark matter charge

* Neutral component must be there
    * This fixes $\text{U}(1)_Y$ charge

|                   | $\tilde h$ | $\tilde W$ |     | ... |
|:-----------------:|:----------:|:----------:|:---:|:---:|
| $\text{SU}(2)_L$  | $2$        | $3$        | $3$ | ... |
| $\text{U}(1)_Y$   | $1/2$      | $0$        | $1$ | ... |

* As an example, consider Higgsino($\tilde h$)-like and wino($\tilde W$)-like DM

## Dark matter mass
* Thermal abundance fixes the mass
    * $1.1\,\text{TeV}$ for Higgsino-like DM
    * $3\,\text{TeV}$ for wino-like DM
        * (Use them as canonical values)
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
\text{ or }
\tilde{W} = \begin{pmatrix}\tilde{W}^- \\ \tilde{W}^0 \\ \tilde{W}^+\end{pmatrix}
$$

* Charged partners are *always* there
    * Must be heavier then the neutral one

## Mass difference and the lifetime
* No $\text{SU}(2)\times\text{U}(1)$ breakdown, no mass diff.
    * Mass diff. is much smaller than the thermal mass
* For smaller mass diff., *larger lifetimes* are expected
    * $c\tau(\chi^+\to\chi^0\pi^+) \sim 0.7\,\text{cm} \left(\frac{\Delta m}{350\,\text{MeV}}\right)^{-5}$ for Higgsino
    * $c\tau(\chi^+\to\chi^0\pi^+) \sim 7\,\text{cm} \left(\frac{\Delta m}{160\,\text{MeV}}\right)^{-3}$ for wino
* I'll discuss the canonical value for $\Delta m$ later

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
    * $160\,\text{MeV}$ for wino

\begin{textblock*}{0.4\linewidth}(200pt, 175pt)
    {\tiny Yamada 10, Ibe, Matsumoto, Sato 15}
\end{textblock*}

## Mixing with other particles
* This highly depends on UV phisics; *e.g.*
    * For Higgsino - bino or wino-like particle
    * For wino - Higgsino-like particle
* Roughly, $\text{mass diff.} \simeq \text{coupling to Higgs}$
    * The additional particles enhance the coupling to Higgs and thus **to SM particles**
    * If the mass diff. is large enough, direct detection cross section is larger than the $\nu$-floor

 \begin{textblock*}{0.4\linewidth}(220pt, 225pt)
    {\tiny HF, Nagata, Otono, Shirai 17}
\end{textblock*}

## Setup for disappearing track serach
* Assume only radiative mass difference;
    * $c\tau(\chi^+\to\chi^0\pi^+) \sim 0.7\,\text{cm}$ for Higgsino
    * $c\tau(\chi^+\to\chi^0\pi^+) \sim 7\,\text{cm}$ for wino
    * (Such "decoupling" DM models are also theoretically motivated)
* Then, ask how far we can see?

# How heavy mass can we reach?

## Conventional study
* current ATLAS/CMS

## Conventional study
\begin{center}
\includegraphics[width=151pt]{conv_disap_higgsino.pdf}
\includegraphics[width=148pt]{conv_disap_wino.pdf}
\end{center}
\begin{textblock*}{0.4\linewidth}(200pt, 170pt)
    {\tiny Arkani-Hamed {\it et al.} 15}
\end{textblock*}

* For Higgsino, even $100\,\text{TeV}$ is still not enough!
* Do we really need $100\,\text{TeV}$ or more?

## What limits the sensitivity?
* Numerous Higgsinos/winos are *there*
* We can *not* see enough disappearing tracks
* Why? -  Matter of analysis/tracker

## Look inside the tracker

## Improvement to $2$-point search

## Result
\begin{center}
\includegraphics[width=150pt]{higgsino.pdf}
\includegraphics[width=150pt]{wino.pdf}
\end{center}

# How can we reduce the background?

## Fight against the background
* One of the reasons to require $4$ points is to reduce the BG
* For $2$-pt search, we must do harder than now

## What is the background
* Misidentification of kink tracks
* **Fake disappearing tracks**

## Fake disappearing tracks

## Reduce them by additional points
\begin{textblock*}{0.4\linewidth}(240pt, 250pt)
    {\tiny HF, Nagata, Otono, Shirai in prep}
\end{textblock*}

# Summary
## Summary
* Disappearing track is essential for the minimal dark matter search
* We need to
    * not only increase the energy but also improve trackers
    * estimate and reduce the background