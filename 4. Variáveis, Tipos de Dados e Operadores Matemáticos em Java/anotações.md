# ****Variáveis, Tipos de Dados e Operadores Matemáticos em Java****

# Conceituação

> *"Um espaço na memória do computador, onde se pode guardar valores."*
> 

### Quatro tipos de variáveis:

- Instância: pertence a um objeto
- Classe: pertence a uma classe
- Local: dentro de métodos
- Parâmetro: na assinatura do método

# Criação

> <visibilidade?><modificador?> tipo nome <=valorInicial?>
> 
- Os dados que tem *interrogações são dados opcionais.*

V: "public", "protected" e "private"

M: "static" e "final"

T: tipo de dado

N: nome que é fornecido a variável

VI: um valor inicial, caso se deseje

### Convenções e r**egras:**

- Não deve começar com números
- “$” e “_” devem ser evitados
- São case-sensitive
- Sem espaços
- Não pode ser as palavras reservadas do Java
- Sempre começar com letra minúscula
- Nomes expressivos
- Notação camelo (ex: cadaNovaPalavraComeçaComLetraMaiúscula)
- Quando constante (final) maiúscula e separada por "_" (ex: int final NUMERO_TENTATIVAS = 5)

# Tipos de dados

> *"São valores e consequentemente operações que as variáveis podem assumir e sofrer, respectivamente."*
> 

### Tipificação

- Estática (forte) vs Dinâmica (fraco)
- Primitivo (homogêneo) vs Composto (heterogêneo)
- Textual (char, string)
- Numeral (byte, short, int, long, float, double)
- Lógico (booleano)
- Objeto

# Operadores aritméticos

> *"São símbolos especiais, quais são capazes de realizar ações específicas em um, dois ou mais operandos e, em seguida, retornar um resultado."*
> 

### **Tipos:**

- Pós-fixado: exp++ ou exp--
- Prefixado: ++exp ou --exp
- Aritmético: +, -, *, / e %
- Atribuição: =, +=, -=,*=, /= e %=

# ****Conversões (casting)****

> *"É a transformação de uma determinada variável de tipo menos específico para um tipo mais específico ou vice-versa"*
> 

### **Tipos:**

- Upcast → implícito, não gera problemas
    - promoção de um tipo de dado de menor capacidade de armazenamento, para um tipo de maior capacidade
- Downcast → explícito
    - rebaixamento de um tipo de dado de maior capacidade de armazenamento, para um tipo de menor capacidade
    - precisa dizer para qual tipo será rebaixado
    - possíveis perdas de dados