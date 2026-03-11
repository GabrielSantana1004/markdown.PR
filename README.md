# style gide do projeto
##linguagem typescript
### Variaveis
´´´
sempre acione a tipagem pratica

´´´
´´´

// ruim
nome = "Vai Curintia";
nome: any = "Vai Corintia";

// bom
nome: string= 'sem mundial';
´´´
---

´´´

evite o uso de "else"

´´´
´´´

// ruim

if (a == b)
    console.log("iguais")
else
    Console.log("diferentes")

// bom

if (a == b)
    console.log("iguais")
if (a != b)
    console.log("diferentes")
´´´