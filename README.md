# WaiterApp

## 📄 Descrição

O WaiterApp é uma ferramenta projetada para facilitar o trabalho de garçons, agilizando o processo de atendimento e gestão de pedidos. O objetivo do app é melhorar a eficiência dos serviços em restaurantes, bares e cafés.

Funcionalidades principais:
- App mobile para o garçom anotar os pedidos
- Dashboard web para visualização dos pedidos realizados
- Comunicação em tempo real com WebSockets

## 🚀 Tecnologias Utilizadas

- React Native
- Expo
- TypeScript
- Styled-components
- Axios
- Outras dependências: ver [package.json](package.json)

## ⚙️ Como Executar o Projeto

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/carlosdancr/waiterapp-app.git
   cd waiterapp-app
   ```

2. **Instale as dependências:**
   ```sh
   npm install
   ```

3. **Inicie o projeto:**
   ```sh
   npm start
   ```
   Ou, para rodar em um dispositivo específico:
   ```sh
   npm run android
   npm run ios
   npm run web
   ```

> **Observação:** Certifique-se de que o backend da aplicação esteja rodando em `http://localhost:3001` para o funcionamento completo do sistema.

## 💡 Exemplos de Uso

- **Produtos separados por categoria:** Os produtos exibidos na interface são organizados conforme a categoria escolhida (ex: Pizzas, Bebidas, Sobremesas), facilitando a navegação para o garçom.

- **Carrinho de pedidos:** O garçom pode adicionar vários produtos ao carrinho antes de finalizar o pedido, permitindo conferência e ajustes antes do envio à cozinha.

- **Cancelamento de pedidos:** Cancele pedidos diretamente pela interface, com feedback visual imediato.

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
