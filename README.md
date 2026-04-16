🔢 Maior e Menor Número
Programa simples em Python que lê 10 números fornecidos pelo usuário e exibe qual foi o maior e o menor entre eles.

📋 Descrição
O programa solicita ao usuário que digite 10 números inteiros, um por vez. Ao final, exibe o maior e o menor valor informados durante a entrada, sem utilizar funções prontas como max() ou min() — a lógica de comparação é feita manualmente, tornando o código didático e transparente.

🚀 Como executar
Pré-requisito: Python 3.x instalado.
bashpython maior_menor.py
Exemplo de uso
Informe o 1° número: 42
Informe o 2° número: 7
Informe o 3° número: 99
Informe o 4° número: 15
Informe o 5° número: 3
Informe o 6° número: 58
Informe o 7° número: 21
Informe o 8° número: 76
Informe o 9° número: 34
Informe o 10° número: 11

O maior número digitado foi: 99
O menor número foi: 3

🧠 Como funciona

O primeiro número é lido e definido como valor inicial tanto para maior quanto para menor.
Um laço for percorre as entradas restantes (do 2° ao 10°).
A cada iteração, o novo número é comparado com os valores atuais de maior e menor, atualizando-os quando necessário.
Ao fim do laço, os resultados são exibidos.


📁 Estrutura do projeto
├── maior_menor.py   # Código principal
└── README.md        # Este arquivo

🛠️ Tecnologias

Python 3
Estruturas utilizadas: input(), for, if/elif


📄 Licença MIT
Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.
