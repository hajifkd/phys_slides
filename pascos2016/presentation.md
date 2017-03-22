% A Model of Heavy QCD Axion and the LHC Signature \hfil\tiny arXiv:1504.06084, 1602.07909, 1607.01936
% Hajime Fukuda (Kavli IPMU)
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H ../header -->
# Outline
1. Heavy axion - Why and How?
1. Our model and the LHC signature

# Strong CP Problem
* QCD should break CP symmetry
$$
\theta = \theta_\text{YM} + \arg\det(Y_uY_d)
$$
* The PQ mechanism can set $\theta=0$.
    * The original model has been excluded.

# What is the Alternative?
* Roughly, two choices:
    * Larger $f_a$ / Heavier $m_a$

## Axion Mass
$$
{m_a}^2 \simeq \frac{m_q \Lambda^3}{{f_a}^2}
$$
indicates heavier $m_a$ is difficult.

# Higher Dimensional Operator
$$
\Delta \mathcal L = c\frac{\phi^5}{M_\text{Pl}}
$$
$$
\Rightarrow\Delta \theta \simeq c\frac{{f_a}^3}{M_\text{Pl}{m_a}^2} \gg 10^{-10},
$$
indicates heavier $m_a$ is preferred!

# Realizing a Heavy Axion
* (Rubakov, 1997) suggested *a consistent way* to achieve a heavy axion 

\tiny Rubakov 1997; Berezhiani, Gianfagna and Giannotti 2000\newline Hook 2014, HF, Harigaya, Ibe and Yanagida 2015, Albaid, Dine and Draper 2015\newline
(Kobakhidze 2016), (Gherghetta, Nagata and Shifman 2016)

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

# Copy of SM
$$
\theta = \theta_\text{YM} + \tikz[baseline=(x.base)] {
  \node(x)[rectangle, fill=teal!20, rounded corners] {$\arg\det(Y_uY_d)$};
  }
$$

* $\theta'$ must also have Yukawa sector
* Thus, we need a complete copy of SM
    * We assume $\mathbb Z_2$ parity, which is spontaneously broken

# Our Model

\usetikzlibrary{automata,positioning}
\begin{center}
\begin{tikzpicture}
\tikzset{block/.style={rectangle, fill=teal!20, rounded corners, align=center}};
\node [block, fill=olive!20] (phi) {$\phi$};
\node [block, above left=2cm and 0.5cm of phi] (s) {$u_R,d_R,Q_L,e_R,L_L$\\$H,N_R$\\{}};
\node [below=0cm of s, anchor=south, blue!40!white] (psi) {\mbox{\boldmath $\psi$}};
\node [block, above right=2cm and 0.5cm of phi] (p) {$u_R',d_R',Q_L',e_R',L_L'$\\$H',N_R'$\\{}};
\node [below=0cm of p, anchor=south, blue!40!white] (psip) {\mbox{\boldmath $\psi'$}};
\draw [->, ultra thick, blue!40!white] (phi) -- (psi);
\draw [->, ultra thick, blue!40!white] (phi) -- (psip);
\node [above=0.3cm of phi, fill=olive!10] {PQ symmetry};
\draw [<->, ultra thick] (s) -- (p);
\node [above=2.3 cm of phi] {$\mathbb Z_2$};
\end{tikzpicture}
\end{center}

\begin{textblock}{3}(6.5,7.2)
\fontsize{6.5pt}{0pt}\selectfont HF, Harigaya, Ibe and Yanagida, arXiv:1504.06084
\end{textblock}

# Low Energy Spectrum
Axion $a$\phantom{hogehogehogehogehoge}
: $m_a\gtrsim 400\,\text{MeV}$

Vector like quark $\psi, \psi'$
: $m_\psi=\frac{1}{\sqrt2}gf_a\gtrsim 900\,\text{GeV}$

Dilaton $s$\phantom{hogehogehoge}
: $m_s=\sqrt{2\lambda}f_a$\tikz[baseline=(x.base)] {
  \node (x) {$\gtrsim \mathcal O(100)\,\text{GeV}$};\pause
  \node [rectangle, rounded corners, fill=teal!20, minimum width={100pt}] {$\simeq 750\,\text{GeV}$??};
}

\begin{textblock}{6}(4.8,7.2)
\tiny or, "let us consider the LHC signal of the dilaton"...
\end{textblock}

# Effective Lagrangian

\begin{eqnarray*}
\mathcal L &=& \frac{s}{f_a}\partial a\partial a + 
N_1\frac{\alpha_s}{8\pi}\frac{s}{f_a} GG+
 N_2\frac{\alpha}{8\pi}\frac{s}{f_a} F^{(\prime)}F^{(\prime)} \\
 &&+N_1\frac{\alpha_s}{8\pi}\frac{a}{f_a} G\tilde{G}+
 N_2\frac{\alpha}{8\pi}\frac{a}{f_a} F^{(\prime)}\tilde{F}^{(\prime)} \\
\end{eqnarray*}

* $s\partial a\partial a$ is the strongest
* How does it look?

# Photons and Photon Jets
* ECAL can't count the number of $\gamma$
* The decay looks like "diphoton"!
<!---    * TRT, a tracker just before ECAL, is able to count converted photons, although $4\gamma$ seems still allowed-->


\begin{center}
\begin{tikzpicture}
\node [circle, white, fill=teal] (s) at (5, 0) {$s$};
\node [circle, white, fill=orange!90!black] (a1) at (3.5, -0.5) {$a$};
\node [circle, white, fill=red!90!black] (g11) at (3.5-1.72, -0.5-1.14) {$\gamma$};
\node [circle, white, fill=red!90!black] (g12) at (3.5-2.05, -0.5+0.195) {$\gamma$};
\node [circle, white, fill=orange!90!black] (a2) at (6.5, 0.5) {$a$};
\node [circle, white, fill=red!90!black] (g21) at (6.5+1.72, 0.5+1.14) {$\gamma$};
\node [circle, white, fill=red!90!black] (g22) at (6.5+2.05, 0.5-0.195) {$\gamma$};
\draw [->, ultra thick] (s) -- (a1);
\draw [->, ultra thick] (s) -- (a2);
\draw [->, thick] (a1) -- (g12);
\draw [->, thick] (a1) -- (g11);
\draw [->, thick] (a2) -- (g22);
\draw [->, thick] (a2) -- (g21);
\end{tikzpicture}
\end{center}

# Difference b/w $\gamma$s and $\gamma$-jets
* Some $\gamma$s are "converted"

\phantom{
\includegraphics[width=5.5cm]{ePairPt.pdf}
}

\begin{textblock}{4}(1,4.5)
\includegraphics[width=3.5\TPHorizModule]{cms_slice.jpg}
\end{textblock}

\begin{textblock}{4}(5,3.5)
\includegraphics[width=3.5\TPHorizModule]{CMSRadLength.pdf}
\end{textblock}

# How to Distinguish the Jet
* We simulate trackers in CMS.
    * Conversion, bremsstrahlung, ...
* $p_T^\text{track}$ has greater discrimination power!

\phantom{
\includegraphics[width=5.5cm]{ePairPt.pdf}
}

\begin{textblock}{6}(2,4)
\includegraphics[width=5.5\TPHorizModule]{ePairPt.pdf}
\end{textblock}

\begin{textblock}{3}(6.5,7.5)
\fontsize{6.5pt}{0pt}\selectfont HF, Ibe, Jinnouchi and Nojiri, arXiv:1607.01936
\end{textblock}
 
\begin{textblock}{3}(6.2,6)
\tiny (X:$\gamma$, Y:$2\gamma$, Z:$4\gamma$)
\end{textblock}
 

# Axion Decay
## Lagrangian
$$
\mathcal L_a = N_1\frac{\alpha_s}{8\pi}\frac{a}{f_a} G^{(\prime)}\tilde{G}^{(\prime)}+ 
N_2\frac{\alpha}{8\pi}\frac{a}{f_a} F^{(\prime)}\tilde{F}^{(\prime)} $$

* We need large BR
    * $\text{BR}(s\to4\gamma)=\text{BR}(a\to2\gamma)^{\color{red!90!black}2}$
* $a\mbox-G\mbox-G$ coupling looks too strong


# Mixings with Mesons
* The phase space suppresses $a\to3\pi$


\begin{center}
\includegraphics[width=8cm]{width.pdf}
\end{center}

\begin{textblock}{3}(6.5,7.5)
\fontsize{6.5pt}{0pt}\selectfont Chiang, HF, Ibe and Yanagida, arXiv:1602.07909
\end{textblock}

# Summary
* The heavy axion is plausible
* The dilaton may appear at the LHC as a "di-photon-jet" signal.
* "Diphoton" and "Di-photon-jet" is distinguishable using $p_T$
