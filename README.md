$$\\begin{array}{rrclcl}
\\displaystyle \\min\_{ } & {C_{max}} \\\\
\\textrm{s.t.} 
& \\displaystyle \\sum\_{t=0}^{MaxTime} ( t*x_{ijt} ) +  p_{ij} \\leq & C_{max} \\\\
& \\displaystyle \\sum\_{t=0}^{MaxTime} ( t\*x_{ijt} ) +  p_{ij} \\leq & \\displaystyle \\sum\_{t=0}^{MaxTime} ( t\*x_{\delta(i)jt} ) \\\\
& \\displaystyle \\sum\_{t=1}^{n} \\sum\_{\tau=t-p_{ij}+1}^{t} x_{ij\tau} & \\leq & 1 \\\\
& \\displaystyle  x_{ijt}  & \\in & (0,1)  \\\\
\\end{array}$$
