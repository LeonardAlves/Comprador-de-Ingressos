🎟️ Sistema de Compra de Ingressos
Este projeto contém uma função em JavaScript que permite a compra de ingressos para diferentes setores de um evento, verificando a disponibilidade antes de concluir a compra.

📌 Funcionalidade
O sistema permite que o usuário selecione o tipo de ingresso (Pista, Superior ou Inferior) e a quantidade desejada.
Caso haja disponibilidade, a compra é confirmada e o número de ingressos restantes é atualizado na interface.

🔧 Como Funciona?
1️ O usuário escolhe o tipo de ingresso e a quantidade desejada.
2️ A função comprar() identifica o tipo selecionado e chama a função correspondente (comprarPista(), comprarSuperior() ou comprarInferior()).
3️ A função verifica se há ingressos disponíveis.
4️ Se houver ingressos suficientes, a quantidade é reduzida e a compra confirmada.
5️ Se não houver ingressos suficientes, um alerta informa a indisponibilidade.

📝 Tecnologias Utilizadas
✅ HTML → Estruturação dos campos e exibição dos ingressos disponíveis
✅ CSS → (Opcional) Estilização da interface
✅ JavaScript → Manipulação do DOM para controle da compra e atualização dos ingressos
