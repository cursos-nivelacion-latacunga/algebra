# Teoria de Conjuntos


**Tema de la clase**  Leyes del algebra de conjuntos. Problemas que se resuelven con las propiedades y operaciones de conjuntos. . 

**Objetivo de la clase** Conocer y aplicar las leyes del algebra de conjuntos para demostrar la igualdad de los mismos y resolver ejercicios de razonamiento de operación con conjuntos.                          

## Leyes del Algerba de conjuntos

1. ***Asociatividad***:

    $(Α∪Β)∪C = Α∪(Β∪C)$

    $(A∩Β)∩C = A∩(Β∩C)$

2. ***Conmutatividad***:

    $Α∪Β = Β∪Α$

    $A∩B = B∩A$

3. ***Distributividad***:

    $A∪(Β∩C) = (Α∪Β)∩(Α∪C)$

    $A∩(Β∪C) = (Α∩Β)∪(Α∩C)$

4. ***Absorción***:

    $A∪(Α∩Β) = Α$

    $A∩(Α∪Β) = A$

5. ***Idempotencia***:

    $A∪Α = Α$

    $B∩Β = Β$

6. ***Identidad***:

    $Α ∪ ∅ = Α$ 

    $Α ∩ U = A$

    $A∪U = U$ 

    $A∩∅ = ∅$

7. ***Complemento***:

    $A∪Α^c = U$ 

    $A∩Α^c = ∅$

    $(A^c)^c = A$ 

    $U^c= ∅$

    $∅^c = U$

8. ***Ley de Morgan***:

    $(A∪B)^c = A^c ∩ Β^c$

    $(A∩Β)^c = A^c ∪ Β^c$

    $A – B = A ∩ Β^c$

## Ejemplos 

Demuestre que: 

1. $(A ∪ A) ∩ (A ∪ B^c) = A$

    Aplicaremos

    $(A ∪ A) ∩ (A ∪ B^c) = A$ Ley de Idempotencia

    $A ∩ (A ∪ B^c) = A$  Ley de Absorcicion 

    $A = A$ LQQD

2. $(Α - B) ∩ Β = ∅$ 

    Aplicaremos 

    $(Α - B) ∩ Β = ∅$  Ley de Morgan

    $(A ∩ B^c) ∩ B = ∅$ Ley Asociativa

    $A∩(B^c ∩ B) = ∅$ Ley Complemento

    $Α ∩ ∅ = ∅$  Ley Identidad

    $∅ = ∅$ LQQD

3. $(B ∩ C) ∪ A = (B ∪ A) ∩ (C ∪ A)$

    Aplicaremos 

    $(B ∩ C) ∪ A = (B ∪ A) ∩ (C ∪ A)$ Ley Conmutativa 


    $A ∪ (B ∩ C) = (B ∪ A) ∩ (C ∪ A)$ Ley Distributiva

    $( A ∪ B) ∩ (A ∪ C) = (B ∪ A) ∩ (C ∪ A)$ Ley Conmutativa

    $(B∪A)∩(C∪A) = (B∪A)∩(C∪A)$ LQQD


4. $(A – B) ∩ (Α - C) = A – (B ∪ C)$ 

    Aplicaremos 

    $(A – B) ∩ (Α - C) = A – (B ∪ C)$  Ley de Morgan

    $(A ∩ Β^c) ∩ (Α ∩ C^c) = A – (B ∪ C)$ Ley Asociativa

    $A ∩ (B^c ∩ Α ) ∩ C^c = A – (B ∪ C)$ Ley Asociativa

    $(A ∩ Α) ∩(Β^c ∩ C^c) = A – (B ∪ C)$ Ley de Idempotencia y Ley de Morgan 

    $A ∩ (Β ∪ C)^c = A – (B ∪ C)$ Ley de Morgan

    $A – (B ∪ C) = A – (B ∪ C)$ LQQD

5.  $(C ∩ A^c) ∪ (B ∩ B^c) = [C- (A ∪ B)] ∪ [(B ∩ C)- ( A ∩ B ∩ C)]$

    Aplicaremos

    $(C ∩ A^c) ∪ (B ∩ B^c) = [C- (A ∪ B)] ∪ [(B ∩ C)- ( A ∩ B ∩ C)]$ Ley Complemento 

    $(C ∩ A^c) ∪ (∅) = [C- (A ∪ B)] ∪ [(B ∩ C)- ( A ∩ (B ∩ C))]$  Ley  Identidad, de Morgan y Asociativa

    $(C ∩ A^c) = [C ∩ (A ∪ B)^c] ∪ [(B ∩ C) ∩ ( A ∩ (B ∩ C))^c]$ Ley de Morgan 

    $(C - A) = [C ∩ (A^c ∩ B^c)] ∪ [(B ∩ C) ∩ ( A^c  ∪ (B ∩ C)^c)]$ Ley Asociativa y Distributiva 

    $(C - A) = [(C ∩ A^c) ∩ B^c)] ∪ [((B ∩ C) ∩  A^c ) ∪ ((B ∩ C) ∩ (B ∩ C)^c)]$ Ley Complemento

    $(C - A) = [(C ∩ A^c) ∩ B^c)] ∪ [((B ∩ C) ∩  A^c ) ∪ (∅)]$  Ley Identidad

    $(C - A) = [(C ∩ A^c) ∩ B^c)] ∪ [((B ∩ C) ∩  A^c )]$ Ley Asociativa

    $(C - A) = [(C ∩ A^c) ∩ B^c)] ∪ [B ∩ (C ∩  A^c )]$ Ley Distributiva

    $(C - A) = (C ∩ A^c) ∩ (B ∪ B^c )]$  Ley Complemento

    $(C - A) = (C ∩ A^c) ∩ (U)]$  Ley Identidad

    $(C - A) = (C ∩ A^c)$  Ley de Morgan

    $(C - A) = (C - A)$ LQQD.

## Bibliografía

- ESPINOZA,Eduardo. 2005. ***Matemática Básica***. Perú:Lima.

- García García, Juan Ignacio; García Sánchez, Pedro A; Urbano Blanco, Juan Manuel, [Fundamentos lógicos de la programación](http://hdl.handle.net/10481/43278), Universidad de Granada.

## Tarea en casa

Página 132. EjercicioS 50, 51 del Libro Matemática Básica.

