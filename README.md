# Challenge ONE - Amigo Secreto

Este projeto é um simples sistema de sorteio de amigo secreto, onde o usuário pode cadastrar vários nomes e o sistema sorteará um nome aleatório.

## Funcionalidades

### Adicionar Nomes
- O usuário pode adicionar vários nomes à lista de participantes do sorteio.
- A interface permite inserir nomes manualmente em um campo de texto.
- Os nomes adicionados ficam visíveis na lista de participantes para facilitar o controle.
  
![Adicionar Nomes](https://github.com/Victor-Tilheri/ChallengeONE-Amigo-Secreto/blob/main/assets/gifs/adicionar.gif?raw=true)

### Sortear Nomes
- Após adicionar os nomes, o usuário pode clicar no botão "Sortear".
- O sistema selecionará aleatoriamente um dos nomes inseridos.
- Os resultados do sorteio serão exibidos para que o usuário possa ver o nome de seu amigo secreto.

![Sortear Nomes](https://github.com/Victor-Tilheri/ChallengeONE-Amigo-Secreto/blob/main/assets/gifs/sortear.gif?raw=true)

### Limpar Lista
- O sistema oferece a opção de limpar todos os nomes cadastrados.
- Após clicar em "Limpar Lista", todos os participantes serão removidos, permitindo que o usuário recomece o sorteio com uma nova lista.

![Limpar Lista](https://github.com/Victor-Tilheri/ChallengeONE-Amigo-Secreto/blob/main/assets/gifs/limpar.gif?raw=true)

### Detecção de Nome Inválido
- O sistema realiza a validação de nomes inseridos.
- Nomes vazios ou com caracteres inválidos serão detectados, e o usuário será alertado para corrigir antes de prosseguir.
- Isso garante que o sorteio seja realizado apenas com dados válidos.

![Detecção de Nome Inválido](https://github.com/Victor-Tilheri/ChallengeONE-Amigo-Secreto/blob/main/assets/gifs/erro%20nome.gif?raw=true)

### Impedimento de Sortear com a Lista Vazia
- O sistema informa ao usuário que é necessário ter pelo menos um nome cadastrado para realizar o sorteio.

![Impedir Sorteio Lista Vazia](https://github.com/Victor-Tilheri/ChallengeONE-Amigo-Secreto/blob/main/assets/gifs/erro%20sortear.gif?raw=true)

## Como Usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Victor-Tilheri/ChallengeONE-Amigo-Secreto.git
