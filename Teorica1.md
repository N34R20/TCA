# La construccion del cuerpo de los Numeros reales

1870 G.Cantor

$(\mathbb{Q}, <)$ es un cuerpo ordenado, donde $\mathbb{Q}$ son los numeros racionales y $<$ es una relacion de orden

**Definicion**:

una _sucesion racional_ es una tira infinita de numeros racionales $$a_1, a_2, .. , a_n, a_{n+1}, ...$$ indexada por elementos de $\mathbb{N}$

**Definicion**:

una sucesion racional se llama _fundamental_ (O _de Cauchy_) si, y solo si, $\forall \epsilon \in \mathbb{Q} > 0$ existe un $n_0(\epsilon) \in \mathbb{N}$ tal que para todo $n \geq n_0(\epsilon)$ $$|a_{n+k} - a_n| < \epsilon$$ $\forall k \in \mathbb{N}$ 

cuanto mas achique el epsilon mas fuerte es la condicion y por ende tendre que ir mas lejos en la recta para encontrar el $n_0$ que cumple, pero se que siempre existe uno que lo cumple.

**ejemplo:**

$a_n:= \frac{1}{n}$, tomamos $\epsilon = \frac{a}{b} \in \mathbb{Q} > 0$

$$|a_{n+k} - a_n| = |\frac{1}{k+n} - \frac{1}{n}| = \frac{1}{n} - \frac{1}{n-k} = \frac{n-k-n}{n(n-k)} = \frac{-k}{n(n-k)}$$

Como sabemos que $\frac{k}{n-k} < 1$ entonces $$\frac{-k}{n(n-k)} < \frac{1}{n} < \frac{a}{b}$$

Para asegurarnos que $\frac{1}{n}$ sea menor que el epsilon, el $n$ tiene que ser al menos mas grande que $b$.

Si $n>b \rightarrow \frac{1}{n} < \frac{1}{b} \leq \frac{a}{b}$

Entonces concluimos que $(\frac{1}{n})_{n \in \mathbb{N}}$ es una sucesion fundamental

### Algunas propiedades

- **proposicion:** toda sucesion fundamental es acotada

**demostracion:** Sea $(a_n)_{n \in \mathbb{N}}$ una sucesion fundamental




- **proposicion:** si tomamos $(a_n)_{n \in \mathbb{N}}$ y $(b_n)_{n \in \mathbb{N}}$ dos sucesion fundamentales entonces;
    
    - $(a_n + b_n)_{n \in \mathbb{N}}$ 
    - $(a_n - b_n)_{n \in \mathbb{N}}$ 
    - $(a_n  b_n)_{n \in \mathbb{N}}$ 

    Tambien lo son

Sea $\mathcal{S} = \{(a_n)_{n \in \mathbb{N}}\}$ tal que $(a_n)_{n \in \mathbb{N}}$ es una sucesion fundamental.
Osea $\mathcal{S}$ es el conjunto de todas las sucesiones fundamentales racionales.
Podemos definir una relacion de equivalencia $\sim$ de la siguiente manera