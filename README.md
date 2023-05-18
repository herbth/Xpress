

$$\\begin{array}{rrclcl}
\\displaystyle \\min\_{ } & {C_{max}}, &\quad&\quad (obj)\\\\
\\textrm{s.t.} 
& \\displaystyle \\sum\_{t=0}^{MaxTime} ( t*x_{ijt} ) +  p_{ij} \\leq & C_{max}, &\quad o_{ij} \in \omega &(1)\\\\
& \\displaystyle \\sum\_{t=0}^{MaxTime} ( t\*x_{ijt} ) +  p_{ij} \\leq & \\displaystyle \\sum\_{t=0}^{MaxTime} ( t\*x_{\delta(i)jt} ),  &\quad \forall o_{ij} \in \omega \\textrm{ and } \delta(i) \\neq 0 &(2) \\\\
& \\displaystyle \\sum\_{t=1}^{n} \\sum\_{\tau=t-p_{ij}+1}^{t} x_{ij\tau} & \\leq & 1 , \forall i = 1...m , t= 0,...,MaxTime  &(3)\\\\
& \\displaystyle  x_{ijt}  & \\in & (0,1)  \\\\
\\end{array}$$ 
