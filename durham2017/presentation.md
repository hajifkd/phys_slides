% Disappearing track searches for minimal dark matter at the LHC \small 1703.09675, in preparation
% \underline{Hajime Fukuda}, N. Nagata, H.Otono and S. Shirai
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:14pt -o presentation.pdf presentation.md -H ../header -->
---
institute: Kavli IPMU, U. Tokyo
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
* How can we improve the sensitivity?
* What is and how can we reduce the background?

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
    * It still sounds within the range of colliders

## Dark matter @ Colliders
* Basic strategy: $\slashed{E}_T + X$
* Poorer than the thermal mass even for $100\,\text{TeV}$

\begin{center}
\includegraphics[width=6\TPHorizModule]{higgsino_exp.pdf}
\end{center}

\begin{textblock*}{0.4\linewidth}(200pt, 220pt)
    {\tiny Arkani-Hamed {\it et al.} 15}
\end{textblock*}

## Another strategy for minimal dark matters
* **Disappearing tracks** from the decay of **charged partners**

## Take a detailed look at $\text{SU}(2)$ multiplet
$$
\tilde{h} = \begin{pmatrix}\tilde{h}^0 \\ \tilde{h}^+\end{pmatrix}
\text{ or }
\tilde{W} = \begin{pmatrix}\tilde{W}^- \\ \tilde{W}^0 \\ \tilde{W}^+\end{pmatrix}
$$

* Charged partners are *always* there
    * Must be heavier then the neutral one
    * Decayable only to the neutral one $+ X$
* Where does the mass diff. come from?

## Two origin of the mass difference
* No $\text{SU}(2)\times\text{U}(1)$ breakdown, no mass diff.
    * Roughly, $\text{mass diff.} \simeq \text{coupling to Higgs}$
* Mixing with other particles TODO not eff op but the interaction itself?
    * Dimension $5$ op. for Higgsino $(H\tilde{h})^2/\Lambda$
    * Dimension $7$ op. for wino $(H\tilde{W}H^\dagger)^2/\Lambda^3$
* Electroweak correction $\Delta m \sim \frac{\alpha}{4\pi} v_\text{EW}$
    * $350\,\text{MeV}$ for Higgsino
    * $170\,\text{MeV}$ for wino

\begin{textblock*}{0.4\linewidth}(200pt, 200pt)
    {\tiny Yamada 10, Ibe, Matsumoto, Sato 15}
\end{textblock*}

## Mixing with other particles
* This highly depends on UV phisics; *e.g.*
    * For Higgsino - bino or wino-like particle
    * For wino - Higgsino-like particle
* The additional particles *enhance* the coupling to Higgs and thus **to SM particles**
    * Generally speaking, if the mass diff. is large enough, $\sigma_\text{SI}$ is larger than the $\nu$-floor
* As a first 