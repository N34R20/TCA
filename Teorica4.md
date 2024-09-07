# Series

- ### gauss

    https://es.wikipedia.org/wiki/Suma_de_Gauss

- ### geometrica

    https://es.wikipedia.org/wiki/Serie_geom%C3%A9trica

- ### armonica

    https://es.wikipedia.org/wiki/Serie_arm%C3%B3nica_(matem%C3%A1tica)

- ### telescopica

    
    https://es.wikipedia.org/wiki/Serie_telesc%C3%B3pica

## Criterios de Convergencia

Sea $\sum^{\infty} a_n$ una serie y $(S_N)_{n\in \N}$ la sucesion de sumas parciales $$S_N = \sum^N a_n$$

Entonces $(S_N)_{n\in \N}$ converge $\leftrightarrow (S_N)_{n\in \N}$ es de Cauchy

$\leftrightarrow$ $\forall \epsilon > 0$, existe $n_0(\epsilon)$ tal que si $N,M > n_0(\epsilon)$ entonces

$$|S_N - S_M| < \epsilon$$

$\leftrightarrow$ $\forall \epsilon > 0$, existe $n_0(\epsilon)$ tal que si $N,M > n_0(\epsilon)$ entonces

$N>M$
$$|a_1 + ... + a_N - a_1 - ... - a_M| < \epsilon$$

Notese que $a_1 + ... + a_N = S_N$ y que $- a_1 - ... - a_M = S_M$

$$= |a_{M+1} + a_{M+2} + .. + a_N| < \epsilon$$

(Criterio necesario y suficiente sobre las colas de la serie)

### Criterio necesario de Cauchy:

Supongamos que \sum^




**Criterio**: Si $\sum^{\infty} a_n$ converge, entonces $lim_{n \rightarrow \infty} a_n = 0$ 

- **obs**: la vuelta no vale.
    por ejemplo: $$\sum^\infty \frac{1}{n}$$ no converge y sin embargo $$lim_{n \rightarrow \infty} \frac{1}{n} = 0$$ 


### Series de terminos Positivos

- **obs**: Si $a_n \geq 0 \forall n$, entonces $\sum a_n$ converge $\leftrightarrow$ la sucesion de sumas parciales es acotado (pues la sucesion de sumas parciales es una sucesion creciente pues los $a_n$ son $\geq 0$)

### Criterio de Comparacion

Sean $\sum a_n$ y $\sum b_n$ dos series de terminos positivos. Entonces

1. Si $lim \frac{a_n}{b_n} = L, l \neq 0, +\infty$ entonces $\sum a_n$ converge $\leftrightarrow \sum b_n$ converge

2. Si $lim \frac{a_n}{b_n} = 0$ y $\sum b_n$ converge entonces $\sum a_n$ tambien converge

3. Si existe $n_0$ tal que $a_n \geq b_n \forall n \leq n_0$ y $\sum b_n$ converge $\leftrightarrow \sum a_n$ tambien converge

