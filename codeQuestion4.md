**Domanda 1:**
_Qual è il metodo migliore per clonare l’oggetto chef, e perché?_
Lo Spread Operator è l'unico modo per copiare oggetti che al loro interno hanno delle funzioni, non possiamo però parlare un vero e proprio clone perche andremo a copiare solo il riferimento.

**Domanda 2:**
_Qual è il metodo migliore per clonare l’oggetto restaurant, e perché?_
StructuredClone copia oggetti complessi come Date e Promise
