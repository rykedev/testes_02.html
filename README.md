# 💖 Efeito de Corações com o Mouse

Um projeto simples, interativo e elegante feito com **HTML**, **CSS** e **JavaScript** puro (Vanilla JS). Ao mover o cursor pela tela, uma trilha de corações animados é gerada dinamicamente, acompanhada de uma mensagem central.

## 🚀 Funcionalidades

- **Trilha de Corações:** Criação dinâmica de elementos HTML (`❤️`) na posição exata do cursor.
- **Animações Fluidas:** Efeito de flutuação (*float up*), expansão e esvanecimento (*fade out*) utilizando CSS Keyframes.
- **Limpeza de Memória:** Remoção automática dos elementos criados após a animação, prevenindo sobrecarga da página.
- **Design Moderno:** Fundo escuro (*Dark Mode*) com brilho suave (*text-shadow*) e tipografia centralizada.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura base da aplicação.
- **CSS3:** Estilização, temas e animação (`@keyframes floatUp`).
- **JavaScript (ES6+):** Manipulação da DOM e tratamento do evento `mousemove`.

## 📦 Como Usar / Executar

1. **Faça o download ou clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. **Abra o projeto:**
   Navegue até a pasta do projeto e abra o arquivo `test_2.html` (ou renomeie para `index.html`) em qualquer navegador web.

> 💡 **Dica:** Não é necessária a instalação de nenhuma dependência ou servidor local para executar este projeto.

## ⚙️ Como Funciona o Código

1. **Escuta de Eventos:** O JavaScript monitora o movimento do ponteiro com `mousemove`.
2. **Criação de Elementos:** A cada movimento do cursor, uma nova `<div>` com o emoji de coração é instanciada.
3. **Posicionamento:** As propriedades `e.pageX` e `e.pageY` determinam as coordenadas exatas para posicionar o elemento.
4. **Animação & Limpeza:** A animação CSS flutua e esconde o coração em 1 segundo. Em seguida, o `setTimeout` remove o nó da árvore DOM para otimizar o uso da memória.

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, alterar e compartilhar!
