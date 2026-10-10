IIT JAM MA + MS: Differential Calculus PYQs (2019–2026)
Scope and verification note
This is a verified extraction of relevant questions located so far, not yet a guarantee that every eligible question in all 16 papers has been captured. I checked the official IIT JAM paper archive and used the official paper PDFs where text or page images were accessible. Some MS PDFs are image-based, so the 2024–2025 MS audit remains incomplete. No questions below are invented; question numbers and question statements are faithful, concise transcriptions/paraphrases of actual papers. Solutions below are independently worked. Where an official answer key could be checked, the key is noted; otherwise the answer follows from the derivation and is not represented as an official-key cross-check.
Official source archives
Official previous question papers (MA/MS 2019–2025)
Official JAM 2026 question papers and answer keys
Official JAM 2025 paper/key page (MA paper) and MS 2025 paper
Coverage ledger
Year	MA — extracted candidates	MS — extracted candidates	Audit status
2019	Q45–Q48, Q54	Q2, Q3, Q32	Candidate questions verified in official PDF text
2020	Q14, Q15, Q53, Q54	Q32	Candidate questions verified in official PDF text
2021	No target MA item independently confirmed in this pass	Q11, Q34, Q35	MS candidates verified; MA scan not exhaustive
2022	Q32, Q56	Q12, Q32	Candidate questions verified in official PDF text
2023	Q5, Q34	Q7, Q36	Candidate questions verified in official PDF text
2024	Q24, Q25	Q2	MA verified; MS Q2 verified from official PDF page image; MS scan incomplete
2025	Q3, Q27	None confirmed in the pages sampled	MS paper is 67 pages and was not exhaustively screened question-by-question in this pass
2026	Q3, Q6, Q7, Q15, Q33, Q34	Q12, Q41	MA questions cross-checked against master key where applicable; MS questions from official master paper
Important: “No confirmed item” does not mean the paper had no relevant questions. It means this extraction pass did not verify one. To honestly call this exhaustive, the remaining MA 2021 and MS 2024–2025 papers and the unscreened portions of other papers still need a complete question-by-question audit.
---
MA — Mathematical Mathematics
IIT JAM 2019 MA
Official paper: MA 2019 PDF
Q45 — Taylor coefficient at (x=\pi/2)
Question (faithful transcription): Define
[
f(x)=\begin{cases}\dfrac{4(1-\sin x)}{2x-\pi},&x\ne\pi/2,\0,&x=\pi/2.\end{cases}
]
Find the coefficient of (x-\pi/2) in the Taylor expansion about (\pi/2).
Answer: (1).
Solution: Put (t=x-\pi/2). Then (\sin x=\cos t=1-t^2/2+O(t^4)), so
[
f(x)=\frac{4(t^2/2+O(t^4))}{2t}=t+O(t^3).
]
The coefficient of (t) is (1).
Q46 — Absolute maximum minus minimum
Question: For (0\le x\le1),
[
f(x)=\frac{(1+x^{1/3})^3+(1-x^{1/3})^3}{8(1+x)}.
]
Find (\max f-\min f).
Answer: (1/4).
Solution: Let (u=x^{1/3}). The numerator simplifies to (2+6u^2), hence
[
f(x)=\frac{1+3x^{2/3}}{4(1+x)}=\frac{1+3u^2}{4(1+u^3)}.
]
For (0<u<1), the derivative with respect to (u) has the sign of (u(2-u-u^3)>0). Thus it increases on ([0,1]), with (f(0)=1/4) and (f(1)=1/2). Difference: (1/4).
Q47 — Leibniz rule for an integral with variable limits
Question: Let
[
g(x)=\int_{x(x-2)}^{4x-5} \sqrt{1+3t^4},dt.
]
Find (g'(1)).
Answer: (8).
Solution: By Leibniz's rule,
[
g'(x)=\sqrt{1+3(4x-5)^4}\cdot4-\sqrt{1+3[x(x-2)]^4}(2x-2).
]
At (x=1), both limits equal (-1); the lower-limit derivative is zero. Therefore (g'(1)=4\sqrt4=8).
Q48 — Directional derivative at the origin
Question: For
[
f(x,y)=\begin{cases}\dfrac{x^3+y^3}{x^2-y^2},&x^2\ne y^2,\0,&x^2=y^2,\end{cases}
]
find the directional derivative at ((0,0)) in direction ((4/5,3/5)).
Answer: (13/5).
Solution: Along the unit direction (u=(4/5,3/5)),
[
f(tu)=\frac{t^3(64+27)/125}{t^2(16-9)/25}=\frac{13}{5}t.
]
Thus (\lim_{t\to0}f(tu)/t=13/5).
Q54 — Number of critical points
Question: Find the number of critical points of
[
f(x,y)=(x^2+3y^2)e^{-(x^2+y^2)}.
]
Answer: (5).
Solution:
[
f_x=2xe^{-(x^2+y^2)}(1-x^2-3y^2),\quad
f_y=2ye^{-(x^2+y^2)}(3-x^2-3y^2).
]
If both coordinates are nonzero, the equations require (x^2+3y^2=1) and (x^2+3y^2=3) simultaneously, which is impossible. On the axes, the critical points are ( (0,0),(\pm1,0),(0,\pm1)), so there are five.
IIT JAM 2020 MA
Official paper: MA 2020 PDF
Q14 — Existence of a second derivative at a join
Question: For real (a), define (f(x)=(x+a)^2) for (x\le0), and (f(x)=(x+a)^3) for (x>0). For how many values of (a) does (f''(0)) exist?
Answer: none (option A).
Solution: Differentiability at zero first requires matching one-sided first derivatives: (2a=3a^2), so (a=0) or (a=2/3). If (a=0), the left/right limits defining (f''(0)) are (2) and (0). If (a=2/3), they are (2) and (4). Neither matches, so there is no such (a).
Q15 — Differentiability despite discontinuous partial derivatives
Question: Let (g(t)=t^2\sin(1/t)) for (t\ne0), with (g(0)=0), and define (f(x,y)=g(x)+g(y)). Which statement best describes (f) at ((0,0))?
Answer: (f) is differentiable at the origin, but both first partial derivatives are not continuous there (option D).
Solution: Since (|f(x,y)|\le x^2+y^2),
[
\frac{|f(x,y)-f(0,0)|}{\sqrt{x^2+y^2}}\le\sqrt{x^2+y^2}\to0,
]
so the derivative at the origin exists and is zero. For (t\ne0), (g'(t)=2t\sin(1/t)-\cos(1/t)), which oscillates without a limit as (t\to0); hence the partial derivatives are not continuous at the origin.
Q53 — Minimum of a quadratic in two variables
Question: Find the minimum value of (f(x,y)=x^2+xy+y^2-3x-6y+11).
Answer: (2), attained at ((0,3)).
Solution: Set the gradient to zero:
[
2x+y=3,\qquad x+2y=6.
]
This gives ((x,y)=(0,3)). The Hessian (\begin{pmatrix}2&1\1&2\end{pmatrix}) is positive definite, so this is the global minimum. Substitution gives (f(0,3)=2).
Q54 — Taylor polynomial about (x=1)
Question: Let (f(x)=\sqrt{x}+\alpha x), (x>0), and let (g) be the degree-2 Taylor polynomial of (f) at (1). If (g(3)=3), find (\alpha).
Answer: (\alpha=1/2).
Solution:
[
f(1)=1+\alpha,\quad f'(1)=\tfrac12+\alpha,\quad f''(1)=-\tfrac14.
]
Therefore (g(3)=f(1)+2f'(1)+\frac{4}{2}f''(1)=\frac32+3\alpha). Equating this to (3) gives (\alpha=1/2).
IIT JAM 2022 MA
Official paper: MA 2022 PDF
Q32 — Analytic function with accumulating zeros
Question (paraphrase): A function is continuous on ([-1,1]), infinitely differentiable on ((-1,1)), equals its Taylor series at zero throughout ((-1,1)), and satisfies (f(1/n)=0) for every positive integer (n). Which statements about its value at zero and derivative at (1/2) must hold?
Answer: (f(0)=0) and (f'(1/2)=0) for every such function (A and B).
Solution: The Taylor-series condition makes (f) real analytic on the interval. Its zeros (1/n) accumulate at the interior point zero. The identity theorem for real-analytic functions implies (f\equiv0) on ((-1,1)), so its value and derivative are zero.
Q56 — Extrema of a quadratic on a disk and an ellipse
Question (paraphrase): For (f(x,y)=x^2+2y^2-x), find the number of distinct points in the union of the sets where (f) attains its absolute extrema on the unit disk (x^2+y^2\le1) and ellipse (x^2/4+y^2/9\le1).
Answer: (5).
Solution: The unconstrained critical point is ((1/2,0)), the unique minimum and it lies in both regions. On the unit circle, substituting (y^2=1-x^2) gives (2-x^2-x), whose maximum occurs at (x=-1/2), yielding two points because (y=\pm\sqrt3/2). On the ellipse boundary, substitute (y^2=9(1-x^2/4)) to obtain (18-(7/2)x^2-x); its maximum occurs at (x=-1/7), again giving two points. Counting four distinct boundary maxima plus the shared minimum gives (5).
IIT JAM 2023 MA
Official paper: MA 2023 PDF
Q5 — Global extrema of a high-degree polynomial
Question (paraphrase): Let (p(x)=x^{57}+3x^{10}-21x^3+x^2+21), and let (q(x)=p(x)+\sum_{j=1}^{57}p^{(j)}(x)). Which global extrema does (q) admit?
Answer: neither a global maximum nor a global minimum.
Solution: All derivatives added to (p) have degree at most (56). Thus (q) still has leading term (x^{57}) with positive coefficient. Hence (q(x)\to+\infty) as (x\to+\infty) and (q(x)\to-\infty) as (x\to-\infty); it has neither global extremum.
Q34 — What a bound on (f') implies
Question (paraphrase): Suppose (f:(-1,1)\to\mathbb R) is differentiable, (f(0)=0), and (|f'(x)|\le M|x|) for all (x). Which properties at zero are guaranteed: continuity of (f'), differentiability of (f'), differentiability of (ff'), or differentiability of ((f')^2)?
Answer: A, C and D; B is not guaranteed.
Solution: The bound implies (f'(0)=0) and (|f'(x)|\to0), so (f') is continuous at zero. By the mean value theorem, (|f(x)|\le Mx^2/2). Then
[
\left|\frac{f(x)f'(x)}{x}\right|\le\frac{M^2}{2}|x|^2\to0,
\qquad
\left|\frac{(f'(x))^2}{x}\right|\le M^2|x|\to0.
]
So (ff') and ((f')^2) are differentiable at zero. The condition alone does not force (f') itself to be differentiable there.
IIT JAM 2024 MA
Official paper: MA 2024 PDF
Q24 — Continuity of a composition
Question (paraphrase): Consider whether it is possible for (g\circ f) to be continuous at (1), when (P) (f) is continuous but (g) is discontinuous at (1), and (Q) both (f) and (g) are discontinuous at (1).
Answer: both P and Q are possible.
Solution: For P, take (f(x)=0) for all (x), and choose any (g) discontinuous at (1); then (g(f(x))=g(0)) is constant. For Q, let (f(1)=1) and (f(x)=0) when (x\ne1), and choose (g(0)=g(1)=0) while making (g) discontinuous at (1) through its nearby values. Then (g\circ f) can remain constant zero.
Q25 — Counting local maxima and minima
Question: For
[
f(x)=\frac{(x^2+1)^2}{x^4+x^2+1},
]
count its local maxima and local minima on (\mathbb R).
Answer: two local maxima and one local minimum.
Solution: Rewrite
[
f(x)=1+\frac{x^2}{x^4+x^2+1}.
]
Put (t=x^2\ge0). The derivative of (t/(t^2+t+1)) has the sign of (1-t^2), so the maximum occurs at (t=1), i.e. at (x=\pm1), and the minimum at (x=0). Thus there are two maxima and one minimum.
IIT JAM 2025 MA
Official paper: MA 2025 PDF
Q3 — Differentiability of oscillating functions
Question (faithful transcription):
[
f(x)=\begin{cases}x|x|,|\sin(1/x)|,&x\ne0,\0,&x=0,\end{cases}
\quad
g(x)=\begin{cases}x^2\sin(1/x)+x\cos(1/x),&x\ne0,\0,&x=0.\end{cases}
]
Which statement about differentiability at zero is correct?
Answer: (f) is differentiable at zero, but (g) is not (option A).
Solution:
[
f'(0)=\lim_{h\to0}\frac{h|h||\sin(1/h)|}{h}=\lim_{h\to0}|h||\sin(1/h)|=0.
]
For (g),
[
\frac{g(h)-g(0)}h=h\sin(1/h)+\cos(1/h),
]
which has no limit because the cosine term oscillates. So (g'(0)) does not exist.
Q27 — Local extrema of a two-variable function
Question: For (f(x,y)=e^y(x^2+y^2)), how many local minima and local maxima are there?
Answer: one local minimum and no local maximum.
Solution:
[
f_x=2xe^y,\qquad f_y=e^y(x^2+y^2+2y).
]
Critical points are ((0,0)) and ((0,-2)). At ((0,0)), the Hessian is positive definite, giving a strict local minimum. At ((0,-2)), the Hessian determinant is negative, so it is a saddle. There is no local maximum.
IIT JAM 2026 MA
Official paper: MA 2026 PDF, official master key: MA key. The official key confirms Q3=A, Q6=B, Q7=B, Q15=D, Q33=A,C and Q34=B.
Q3 — Differential equation hidden in a derivative condition
Question: On ((1,4)), a differentiable function satisfies
[
f'(x)=(f(x)-\pi x)^2+\pi.
]
Which listed value can (f(3)-f(2)) take? The options include (\pi+1/6).
Answer: (\pi+1/6) (option A).
Solution: Let (u(x)=f(x)-\pi x). Then (u'=u^2). Solutions are (u=0) or (u=1/(c-x)), with the pole outside ((1,4)). For (c=0) (or (c=5)), (u(3)-u(2)=1/6). Thus (f(3)-f(2)=\pi+1/6). The official master key lists option A.
Q6 — Endpoint limits and attainment of extrema
Question (paraphrase): A continuous function on ((1,2)) has one-sided limits equal to (3) at both endpoints. What is necessarily true about boundedness and attainment of maxima/minima?
Answer: bounded, and it attains a maximum or a minimum or both (option B).
Solution: Extend the function continuously to ([1,2]) by setting both endpoint values to (3). By the extreme value theorem the extension is bounded and attains both extrema on the closed interval. If an extremum occurs only at an endpoint, the other type is attained in the interior unless the function is constant; the constant case attains both. Hence at least one of a maximum/minimum is attained on ((1,2)), and possibly both.
Q7 — Rolle’s theorem on infinitely many intervals
Question (paraphrase): A twice-differentiable function satisfies (f(n)=1) for every integer (n). Which derivative property is necessarily true?
Answer: (f'(x)=0) at infinitely many non-integer points (option B).
Solution: For each integer (n), (f(n)=f(n+1)=1). Rolle’s theorem gives some (c_n\in(n,n+1)) with (f'(c_n)=0). These intervals are disjoint, so there are infinitely many such points.
Q15 — Local minima, maxima and saddle points
Question: For (f(x,y)=(x^2-1)^2+(y^2-1)^2), which listed statement about the number of extrema/saddles is true?
Answer: there are exactly four saddle points (option D).
Solution: Critical coordinates satisfy (x\in{-1,0,1}) and (y\in{-1,0,1}). The four points ((\pm1,\pm1)) are minima; ((0,0)) is a local maximum; and ((0,\pm1),(\pm1,0)) are the four saddle points. This agrees with the official master key.
Q33 — Checking differentiability at a joining point
Question (paraphrase): Which of four locally defined functions are differentiable at (x=1)? The options include (|x-1|^3), (|x^2-1|), a piecewise function matching (x^2e^{-x^2}) to the constant (e^{-1}) outside ([-1,1]), and the floor function.
Answer: the first and third functions (A and C).
Solution: (|x-1|^3) has derivative zero from both sides at 1. For the piecewise function, the derivative of (x^2e^{-x^2}) at 1 is (e^{-1}(2-2)=0), matching the derivative of the constant on the right. (|x^2-1|) has unequal one-sided derivatives, and the floor function jumps at 1. The official master key confirms A,C.
Q34 — Continuity of a rational/irrational definition
Question (paraphrase): Let (f(x)=\cos x) for rational (x), and (f(x)=0) for irrational (x). Which listed continuity/integrability statement is true?
Answer: it is continuous at (x=\pi/2) (option B).
Solution: At (x=\pi/2), both rational and irrational sequences give values approaching zero, since (\cos(\pi/2)=0). At zero the rational-sequence limit is 1 while irrational-sequence values are 0, so it is discontinuous there. On ([0,1]), (\cos x\ne0), so it is discontinuous at every point and is not Riemann integrable. The official key confirms B.
---
MS — Mathematical Statistics
IIT JAM 2019 MS
Official paper: MS 2019 PDF
Q2 — Classifying a stationary point
Question: For (f(x,y)=x^3-3xy^2), classify the origin.
Answer: saddle point.
Solution: Along (y=0), (f(x,0)=x^3) changes sign around zero; along (x=0), the function is zero. More directly, along (y=x), (f(x,x)=-2x^3), while along (y=0) it is (x^3). The function takes both positive and negative values arbitrarily close to the origin, so it is a saddle.
Q3 — Derivative of an integral with a variable lower limit
Question: If (F(x)=\int_{x^3}^{4}\sqrt{4+t^2},dt), find (F'(1)).
Answer: (-3\sqrt5).
Solution: By the fundamental theorem of calculus and the chain rule,
[
F'(x)=-\sqrt{4+(x^3)^2}\cdot3x^2.
]
At (x=1), this is (-3\sqrt5).
Q32 — Derivative signs and a global maximum
Question (paraphrase): For a continuous function on (\mathbb R), differentiable except possibly at zero, choose the always-true statement about the signs of (f') on either side of zero.
Answer: if (f'(x)>0) for (x<0) and (f'(x)<0) for (x>0), then (f) has a global maximum at zero (option D).
Solution: The function is increasing on the negative half-line and decreasing on the positive half-line. Thus any value at (x<0) is at most (f(0)), and any value at (x>0) is also at most (f(0)), by continuity and monotonicity.
IIT JAM 2020 MS
Official paper: MS 2020 PDF
Q32 — Saddle points of a polynomial
Question: For (f(x,y)=x^2(2-y)-y^3+3y^2+9y), identify which of ((0,-1),(0,3),(3,2),(-3,2)) are saddle points.
Answer: ((3,2)) and ((-3,2)) (options C and D).
Solution:
[
f_x=2x(2-y),\qquad f_y=-x^2-3y^2+6y+9.
]
All four listed points are critical. The Hessian determinant is
[
D=f_{xx}f_{yy}-f_{xy}^2=2(2-y)(6-6y)-4x^2.
]
At ((\pm3,2)), (D=-36<0), so both are saddle points. The other two have positive Hessian determinant and are extrema, not saddles.
IIT JAM 2021 MS
Official paper: MS 2021 PDF
Q11 — Partial derivatives and differentiability at the origin
Question: Let
[
f(x,y)=\begin{cases}\dfrac{y^3}{x^2+y^2},&(x,y)\ne(0,0),\0,&(x,y)=(0,0).\end{cases}
]
Which statement is false concerning existence/boundedness of partial derivatives, continuity of (f_y), and differentiability of (f) at the origin?
Answer: the claim that (f_y(0,0)) exists and (f_y) is continuous there is false (option C).
Solution: (f_x(0,0)=0) and (f_y(0,0)=\lim_{h\to0}h^3/(h^2h)=1). Away from the origin the partial derivatives exist and are bounded. But
[
f_y(x,y)=\frac{y^2(3x^2+y^2)}{(x^2+y^2)^2}
]
for nonzero points; along the x-axis it is 0, while along the y-axis it is 1, so it is not continuous at the origin. Also (f(0,y)=y), so (f) is not differentiable there. Hence C is the false statement.
Q34 — Extrema of a quadratic on the unit circle
Question: Find the maximum and minimum of (f(x,y)=3x^2+4xy+y^2) subject to (x^2+y^2=1).
Answer: maximum (2+\sqrt5) and minimum (2-\sqrt5) (options C and D).
Solution: The quadratic-form matrix is (A=\begin{pmatrix}3&2\2&1\end{pmatrix}). Its eigenvalues satisfy (\lambda^2-4\lambda-1=0), so (\lambda=2\pm\sqrt5). On the unit circle the maximum and minimum are the largest and smallest eigenvalues.
Q35 — Rolle’s theorem and bounded derivatives
Question (paraphrase): Suppose (f) is twice differentiable on (\mathbb R). Which statements are necessarily true: continuity of (f''); existence of a zero of (f'') if (f'(0)=f'(1)); boundedness of (f') on ([8,10]); boundedness of (f'') on ((0,1))?
Answer: the Rolle statement and boundedness of (f') on ([8,10]) (B and C).
Solution: Apply Rolle’s theorem to (f') on ([0,1]), which is continuous on the closed interval and differentiable on its interior; there exists (c\in(0,1)) with (f''(c)=0). Since (f) is twice differentiable, (f') is continuous; on the compact interval ([8,10]), it is bounded. A derivative need not be continuous or bounded on an open interval, so A and D are not guaranteed.
IIT JAM 2022 MS
Official paper: MS 2022 PDF
Q12 — Continuity, partial derivatives and differentiability
Question: For
[
f(x,y)=\begin{cases}x^2\sin(1/x)+y^2\cos y,&x\ne0,\0,&x=0,\end{cases}
]
which statement is NOT true at ((0,0)): continuity, discontinuity of (f_x), continuity of (f_y), or failure of differentiability?
Answer: the statement “(f) is not differentiable at ((0,0))” is NOT true.
Solution: (|f(x,y)|\le x^2+y^2), including the branch (x=0), where (f=0). Hence (f(x,y)=o(\sqrt{x^2+y^2})) and (f) is differentiable at the origin with derivative zero. However, for (x\ne0), (f_x=2x\sin(1/x)-\cos(1/x)), which has no limit as (x\to0); therefore (f_x) is not continuous there. The function and (f_y) are continuous at the origin.
Q32 — Critical points of a two-variable polynomial
Question: For (f(x,y)=8(x^2-y^2)-x^4+y^4), which statements hold about critical-point count and classification of ((2,2),(-2,0),(0,-2))?
Answer: all four statements are true: 9 critical points, saddle at ((2,2)), local maximum at ((-2,0)), and local minimum at ((0,-2)).
Solution:
[
f_x=4x(4-x^2),\qquad f_y=4y(y^2-4).
]
Thus (x,y\in{0,\pm2}), giving 9 critical points. The Hessian is diagonal with entries (16-12x^2) and (-16+12y^2). At ((2,2)) the signs are opposite, so it is a saddle; at ((-2,0)) both are negative, giving a local maximum; at ((0,-2)) both are positive, giving a local minimum.
IIT JAM 2023 MS
Official paper: MS 2023 PDF
Q7 — Classifying a stationary point
Question: For (f(x,y)=2x^2-xy-3y^2-3x+7y), classify ((1,1)).
Answer: saddle point (option C).
Solution: The gradient vanishes at ((1,1)). The Hessian is (\begin{pmatrix}4&-1\-1&-6\end{pmatrix}), whose determinant is (-25<0). A negative determinant implies a saddle point.
Q36 — Continuity, partial derivatives and differentiability
Question: For
[
f(x,y)=\begin{cases}\dfrac{xy(x+y)}{x^2+y^2},&(x,y)\ne(0,0),\0,&(x,y)=(0,0),\end{cases}
]
which statements are true about continuity, the y-partial at the origin, continuity of the x-partial, and differentiability at the origin?
Answer: A, B and D are true; C is false.
Solution: Since the numerator is order (r^3) and denominator order (r^2), (|f(x,y)|\le Cr), so (f\to0) and it is continuous. Along either coordinate axis the partial derivative at the origin is zero, so B holds. But the x-partial away from the origin has direction-dependent limits; for example it is zero along (y=0), while along (y=x) it tends to (-1/4), so it is not continuous. Also along (y=x=t), (f(t,t)=t); dividing by the distance (\sqrt2|t|) does not tend to zero, so the function is not differentiable at the origin.
IIT JAM 2024 MS
Official paper: MS 2024 PDF
Q2 — Saddle point of a quadratic polynomial
Question: For (f(x,y)=2x^4-3y^2), which classification applies at the origin?
Answer: saddle point (option C).
Solution: Along (y=0), (f(x,0)=2x^4\ge0); along (x=0), (f(0,y)=-3y^2\le0). Arbitrarily near the origin the function takes both positive and negative values, so the origin is a saddle point.
IIT JAM 2025 MS
Official paper: MS 2025 PDF
Audit status: The official PDF is accessible as page images, but the pages sampled in this pass did not show a verified Differential Calculus question. This should not be interpreted as “there are none”; the 67-page paper still needs a systematic question-by-question screen. No MS 2025 item is included as a confirmed PYQ here to avoid guessing.
IIT JAM 2026 MS
Official paper: MS 2026 PDF, official key page: JAM 2026 answer keys
Q12 — Differentiability and local minimum for a piecewise function
Question (faithful transcription): Let (h,g:\mathbb R\to\mathbb R) be bounded and define
[
f(x)=\begin{cases}xg(x)+x^2h(x),&x>0,\cx+dx^2,&x\le0.\end{cases}
]
Statements: P says that if (c=g(0)=h(0)), then (f) is differentiable at zero; Q says that if (f,g,h) are thrice differentiable, (g(0)=0), and (g'(0)+h(0)>0), then (f) has a local minimum at zero. Decide which statement is correct.
Answer: both P and Q are correct (option C).
Solution: For P, (f(0)=0); the left derivative is (c), while the right difference quotient tends to (g(0)), so (c=g(0)) ensures differentiability. For Q, (g(0)=0) gives the right-side expansion (f(x)=[g'(0)+h(0)]x^2+o(x^2)). Since (f) is assumed thrice differentiable across zero, its first derivative at zero must match on both sides (so (c=0)) and its second derivative exists (so (d=g'(0)+h(0)>0)). Thus near zero the leading term is a positive quadratic on both sides, giving a local minimum.
Q41 — Taylor polynomial of (3e^x\cos 2x)
Question: If (p(x)=ax^3+bx^2+cx+d) is the third-degree Taylor polynomial at zero of (f(x)=3e^x\cos2x), find (|a|+|b|+|c|+|d|).
Answer: (16).
Solution: Use
[
e^x=1+x+\frac{x^2}{2}+\frac{x^3}{6}+O(x^4),\quad
\cos2x=1-2x^2+O(x^4).
]
Their product through degree 3 is (1+x-\frac32x^2-\frac{11}{6}x^3). Multiplying by 3 gives coefficients (d=3,c=3,b=-9/2,a=-11/2). Thus the sum of absolute values is (3+3+9/2+11/2=16).
---
High-priority topic index
Topic	Verified questions in this extraction
Limits, continuity, differentiability	MA 2020 Q14–15; MA 2023 Q34; MA 2025 Q3; MA 2026 Q33–34; MS 2021 Q11; MS 2022 Q12; MS 2023 Q36; MS 2026 Q12
Rolle’s theorem / MVT	MA 2026 Q7; MS 2021 Q35
Higher derivatives / Taylor	MA 2019 Q45; MA 2020 Q14, Q54; MS 2026 Q41
Leibniz rule / variable-limit integrals	MA 2019 Q47; MS 2019 Q3
Increasing/decreasing / global extrema	MA 2019 Q46; MA 2022 Q56; MA 2023 Q5; MA 2024 Q25; MA 2026 Q6; MS 2019 Q32
Local maxima/minima / saddle points	MA 2020 Q53; MA 2024 Q25; MA 2025 Q27; MA 2026 Q15; MS 2019 Q2; MS 2020 Q32; MS 2021 Q34; MS 2022 Q32; MS 2023 Q7; MS 2024 Q2
Partial/directional derivatives / total differentiability	MA 2019 Q48, Q54; MA 2020 Q15; MA 2022 Q56; MA 2025 Q27; MS 2021 Q11; MS 2022 Q12; MS 2023 Q36
What is still unverified
This file is a working extraction, not a certified exhaustive list of every differential-calculus item from all 16 MA/MS papers.
MA 2021 has not been fully searched for every matching question.
MS 2024 and MS 2025 need a systematic screen of every question page; the MS 2025 sampled pages did not establish a target item.
The extracted entries do not currently include a separate answer-key citation for every historical answer. Each has a solution, but the older year-specific final keys should be checked systematically before calling every answer officially key-verified.
