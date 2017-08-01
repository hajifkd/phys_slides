% 極めて軽いダークマターの\newline 新しい検出方法 \hfill\small In preparation
% \underline{Hajime Fukuda}, T.T. Yanagida, S. Matsumoto
% \today <!--- pandoc -t beamer -V theme:metropolis -V fontsize:17pt -o presentation.pdf presentation.md -H ../header -->
---
institute: Kavli IPMU, U. Tokyo
---

# Introduction
* DMは最も確立したBSMの一つ
* 質量は？

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


# Ultralight DM

* DM for $10^{-22}\,\text{eV} \lesssim m_\text{DM} \lesssim \text{eV}$
* Must be Bosonic
* CDMになれる
    * Coherent oscillation/decay of defects/...
* Several interesting astrophysical signature
    * \small _e.g._ Hu, *et al.*, 2000
* \normalsize Moduli? ALP?

# 今日の本題
* 軽いDMを検出する方法を考えたい
    * Indirect detection
    * Production
    * $\text{\color{red}Direct detection}$

# Direct Detection
* One recoil, $q \sim p = mv$, is small
* However, $n_\text{DM} \sim \rho / m$ is quite large
* The total momentum transfer: $Q \propto qn \sim v\rho$
    * 実は小さくなくてもよい
* **断面積に量子力学的なenhancement効果**

# 問題
* 何をターゲットにすればいいか？
    * Measurement must be precise enough
    * Large enhancement
* 正しいenhancementの見積もり

# Enhancement Effect
* 2種のEnhancement効果
    * Stimulated emission (誘導放射)
    * Coherent effect on the target

# Stimulated Emission
* 例: レーザー
$$
\mathcal{A} = \langle \gamma | a^\dagger | 0 \rangle
$$
$$
\to \mathcal{A}' = \langle (N + 1) \gamma | a^\dagger | N \gamma \rangle = \sqrt{N + 1} \mathcal A
$$

* なぜなら
$$
|N \gamma \rangle = \frac{1}{\sqrt{N!}} \left(a^\dagger\right)^N |0 \rangle
$$
より、$a^\dagger | N \gamma \rangle = \sqrt{N + 1} | (N + 1) \gamma \rangle$だから

# Stimulated Emission
* 相空間の粒子密度を$\mathcal O$とすると、$\sigma \propto \mathcal O + 1$
    * ただし、
    $$
    \int \frac{\text{d}^3k}{(2\pi)^3} \mathcal O(k) = n
    $$

# Enhancementの大きさ
* 銀河内でDMは$v\sim10^{-3}$のガウス分布
* DMが均一だと思えば
$$
\mathcal O \sim \frac{\rho}{m} \frac{1}{(mv)^3} \sim 10^3 \left(\frac{\text{eV}}{m}\right)^4
$$
* 軽ければ軽いほど大きくなる
    * 軽いDMによい

# 使えるか？
* DMのfinal state分布を知らないと使えない
* coherent oscillationしていると、ダメ？

\begin{center}
\begin{tikzpicture}
\draw [olive, thick, fill] (0, 0) circle [x radius=1, y radius=1];
\draw [->, ultra thick] (1, -0.3) -- (2, -0.6);
\draw [olive, thick, fill] (1, 2) circle [x radius=1, y radius=1];
\draw [->, ultra thick] (0, 2.4) -- (-0.8, 2.72);
\draw [olive, thick, fill] (3, 1) circle [x radius=1, y radius=1];
\draw [->, ultra thick] (3, -0.1) -- (3, -1.1);
\draw [<->, ultra thick] (4.1, 2) -- (4.1, 0);
\draw (4.3, 1) node[anchor=west] {$R_J \gtrsim r \gtrsim \frac{1}{mv}$};
\end{tikzpicture}
\end{center}

# Enhancement Effect
* 2種のEnhancement効果
    * Stimulated emission - $\times$ (or $\bigtriangleup$)
    * Coherent effect on the target

# Coherent Effect
* e.g. Coulomb scattering

\begin{center}
\begin{tikzpicture}
\draw [ultra thick] (0, 0) -- (4, 0);
\draw [ultra thick] (4, 0) -- (8, 0.8);
\draw [teal, thick, snake it] (4, 0) -- (6.5, -2.5);
\draw [olive, thick, fill] (6.71, -2.71) circle [x radius=1, y radius=1];
\draw (0, 0.1) node[anchor=south west] {\large $e$};
\draw (5.61, -2.71) node[anchor=east] {Nucleus (charge $Z$)}; \draw [->, ultra thick] (4.0, -0.9) -- (5.0, -1.9);
\draw (4.6, -1.6) node[anchor=east] {$q^\mu$}; \draw [<->, ultra thick] (6.71, -1.71) -- (6.71, -3.71); \draw (6.8, -2.71) node[anchor=west] {$R$};
\end{tikzpicture}
\end{center}

* For $qR < 1$, $\sigma\propto Z^2$ !

# Coherent Effect
* 「低$q$で細かい構造は絶対見えない」
* いわゆるDMのSpin-independent散乱と一緒
    * $\sigma \sim [Z\sigma_p + (A - Z)\sigma_n]^2 |F(q)|^2$
    * 軽いDMも、spin-independentでないとダメ
* それだけ？他に条件は？Form factor?

# もっとくわしく
* 第一量子化のレベルで考えるとわかりやすい
* Born近似: $\mathcal A \sim m \langle k' | V | k \rangle$
* Targetがたくさんあると、
$$V(x) = \sum_i V_i(x - x_i), \mathcal A_\text{tot} = \sum_i e^{iqx_i} \mathcal A_i$$
* $qx_i\to0$ for all $i$, $\mathcal A_\text{tot} \simeq N \mathcal A$
* 振幅が$N$倍、断面積は$N^2$倍！
* 軽いほど$q$が小さくてよい

# 何をターゲットに使うか
* 誘導放射と異なり、ターゲット選びが大事
* 大きいほど良い
* $\text{\bf 太陽系の天体！}, N\sim 10^{50\mbox-58}$
    * Measurement is very accurate, $\Delta v / v\Delta t \lesssim 10^{-(17\mbox-19)}\,\text{s}^{-1}$
* 断面積は$10^{100}$倍！？

# もっとくわしく
* 第一量子化のレベルで考えるとわかりやすい
* Born近似: $\mathcal A \sim m \langle k' | V | k \rangle$
* Targetがたくさんあると、
$$V(x) = \sum_i V_i(x - x_i), \mathcal A_\text{tot} = \sum_i e^{iqx_i} \mathcal A_i$$
* $qx_i\to0$ for all $i$, $\mathcal A_\text{tot} \simeq N \mathcal A$
* 振幅が$N$倍、断面積は$N^2$倍！
* 軽いほど$q$が小さくてよい

# もっとくわしく
* 第一量子化のレベルで考えるとわかりやすい
* $\text{\color{red}\bf Born近似}$: $\mathcal A \sim m \langle k' | V | k \rangle$
* Targetがたくさんあると、
$$V(x) = \sum_i V_i(x - x_i), \mathcal A_\text{tot} = \sum_i e^{iqx_i} \mathcal A_i$$
* $qx_i\to0$ for all $i$, $\mathcal A_\text{tot} \simeq N \mathcal A$
* 振幅が$N$倍、断面積は$N^2$倍！
* 軽いほど$q$が小さくてよい

# 本当の断面積
* $N^2 |F(q)|^2$ enhanceは、Born近似を仮定
* Born近似:『散乱体中で1回しか散乱しない』
    * 相互作用が強いとダメ
    * $\text{\bf 散乱体が大きいとダメ}$
* $\text{Schr\"odinger}$ eq. を真面目に解く

# $\text{Schr\"odinger}$ eq.の解き方
* 簡単のため、一様密度球と近似
* まず、Potentialを求める
    * 定ポテンシャル球 $V(r) = V_0 H(R - r)$なはず
    * $V_0$は、密度の関数なはず
    * 小さな球で、マッチ
        * $V(r)$にBorn近似を適用できる
        * $N^2$ enhancement
        $$
        \sigma = N^2 \sigma_0,\,\,\,\, \sigma_0 = \frac{\Lambda_\text{QCD}^2}{4\pi\Lambda^4}
        $$
        と比べる
* 球対称ポテンシャルなので、部分波展開

# 例:太陽-DM 断面積
\begin{center}
\includegraphics[width=5\TPHorizModule]{crosssect.pdf}
\end{center}
* 断面積は、最大で星の幾何断面積$\pi R^2$程度

# 量子力学的なenhancementのまとめ
* 誘導放射は、よくわからない
* コヒーレント効果は使えそう
* ターゲットは大きいほどよい
    * 太陽系の天体をターゲットに
    * 断面積は幾何断面積が上限

# 制限
* 天体の運動から散乱断面積に制限をかける
* 太陽系は、銀河系に対し動いている
* DM-星散乱は、『DMの風』、摩擦として働く
* 速度が変われば、周期・距離が変化

# 実際の制限
* Ephemeris(天体暦) を使って制限をかける
    * 天体暦とは、様々な観測データから天体の運動をパラメタフィットしたもの
* 最新の天体暦は、数値的天体暦
    * ちょっと大変
    * Naiveに、$\Delta \ln v / \Delta t \sim \Delta L / T^2$ などとする

<!--# 制限と星のサイズ
* $\sigma \propto R^2$
* $\Delta p \sim \sigma n_\text{DM} m_\text{DM} v \Delta t$
* $M \propto R^3$
* $\Delta v \propto \Delta \tau \propto a = \Delta p / m \propto R^{-1}$
* 小さい星のほうがいい？
* いっそ星じゃないほうがいい？
-->

# Cross sectionと星のサイズ
* 重い星ほど、弱い相互作用でも、幾何断面積に達する
    * 軽い星ではenhancementが弱すぎて、幾何断面積までいかない
    * $\sigma_0\sim {m_\text{DM}}^2/\Lambda^4$とすると、月、地球、木星、太陽の順に$\Lambda\lesssim10^{13,14,15,16}\,\text{GeV}$
* 軽い星ほど影響を受けやすい
    * 速度の変化を見る
    * 運動方程式: $F = ma$
* それぞれの星ごとに範囲が異なる

# Final Result
* For the best target, we need one order more

\begin{center}
\includegraphics[width=6\TPHorizModule]{result.pdf}
\end{center}

# Summary
* とても軽い粒子の相互作用には、量子力学的なenhancementがある
* Coherenceを利用できると、天体との相互作用で$m\ll \text{eV}$なDMも検出できるかも
