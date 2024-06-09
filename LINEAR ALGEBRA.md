
# Característica de uma matriz A

- **Passar a matriz sob forma de escada**
- **car(A) = n.º de pivôs**
### Exemplo
Considerando a seguinte matriz:
 $$ \begin{array}{cc} 1 &2 &3 &4 \\ 0 &1 &2 &2 \\ 0 &0 &0 &2 \\ 0 &0 &0 &0\end{array} $$

A característica desta matriz é o **número de pivôs**, logo car(A) = 3.
## Classificação de sistemas

- Se car(A) < car(A|b) o sistema é **impossível**
- Se car(A) = car(A|b) o sistema é **possível**

	Sendo K = car(A) = car(A|b) e n o número de incógnitas em estudo
	
	- O sistema é **possível e determinado** se K = n
	- O sistema é **possível e indeterminado** se K < n, com **grau n - K**


---
# Determinantes

-  O determinante de uma matriz é calculado através da subtração da soma de todas as suas diagonais (principais e secundárias)

## Propriedades dos determinantes

1. det(A) = det($A^T$)
2. det($\alpha$A) = $\alpha^n$det(A), onde n $\in$ N (ordem da matriz)
3. det(AB) = det(A) $\times$ det(B). Em particular,
	- det($A^k$) =$(det(A))^k$, k $\in$ N
	- Se A é não singular, det(A)^-1 = $\frac{1}{det(A)}$





