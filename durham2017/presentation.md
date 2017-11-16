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
\includegraphics[width=6\TPHorizModule]{higgsino_exp.pdf}
\end{center}

\begin{textblock*}{0.4\linewidth}(200pt, 220pt)
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
    * Mass diff. is much smaller than the thermal mass, $\mathcal O (\text{TeV})$
* For smaller mass diff., *larger lifetimes* are expected
    * $c\tau \sim 0.7\,\text{cm} \left(\frac{\Delta m}{350\,\text{MeV}}\right)^{-3}$ for Higgsino
    * $c\tau \sim 7\,\text{cm} \left(\frac{\Delta m}{160\,\text{MeV}}\right)^{-3}$ for wino

## Disappearing tracks in colliders
\begin{center}
\includegraphics[width=6\TPHorizModule]{ATLAS.pdf}
\end{center}
* The charged partner goes through the pixel detector

## Two origin of the mass difference
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
* Roughly, $\text{mass diff.} \simeq \text{coupling to Higgs}$
    * The additional particles *enhance* the coupling to Higgs and thus **to SM particles**
    * If the mass diff. is large enough, $\sigma_\text{SI}$ is larger than the $\nu$-floor
* As a first 