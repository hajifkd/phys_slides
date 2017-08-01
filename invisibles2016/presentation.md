% Visible Heavy QCD Axion
% Hajime Fukuda (Kavli IPMU)
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H ../header -->
# Strong CP Problem
* There *is* a problem
* Peccei-Quinn mechnanism is the most popular solution
    * $\text{U}(1)_\text{PQ}$ makes $\theta$ unphysical
* But, why is $\text{U}(1)_\text{PQ}$ a symmetry?

# What if $\text{U}(1)_\text{PQ}$ is broken?
\begin{eqnarray*}
&\Delta \mathcal L = \frac{\phi^5}{M_\text{Pl}} \\
\Rightarrow &\mathcal L \sim -{m_a}^2 a^2 + \frac{{f_a}^4a}{M_\text{Pl}} \\
\Rightarrow &\Delta \theta \sim \frac{{f_a}^3}{M_\text{Pl}{m_a}^2} \gg 10^{-10},
\end{eqnarray*}

* Can we make $a$ heavier?

# Rubakov mechanism
* Usually, $f_a$ fixes $a$ mass
* But, if there is a *copy* of SM, $a$ can be heavier

\begin{textblock}{3}(6,5.4)
\fontsize{10pt}{0pt}\selectfont Rubakov, 1997
\end{textblock}

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

# LHC signature
* A particle leads "$\gamma$-jet" signal

\begin{center}
\scalebox{0.8}{
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
}
\end{center}

* We try to distinguish $\gamma$-jet from $\gamma$

\begin{textblock}{3}(6.5,6.5)
\fontsize{6.5pt}{0pt}\selectfont HF, Ibe, Jinnnouch and Nojiri, arXiv:1607.01936
\end{textblock}

# Summary
* We construct a model of a heavy QCD axion
* We study an LHC signal of photon-jets
