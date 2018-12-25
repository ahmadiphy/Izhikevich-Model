# Python Class for Izhikevich Neural Model

* Using Runge-Kutta 4th Method
\begin{equation}
\dfrac{dv}{dt}=0.04 v^{2}+5 v+140-u+I
\end{equation}

\begin{equation}
\dfrac{du}{dt}=a(bv-u)
\end{equation}

\begin{equation}
if ~ v=30mv, ~ then: ~~ v\leftarrow c , u\leftarrow u+c
\end{equation}
[Refrence](https://www.izhikevich.org/publications/spikes.htm)
