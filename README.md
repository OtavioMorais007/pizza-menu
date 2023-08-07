# Aplicativo React Pizza

Este é um simples aplicativo React que apresenta um menu de pizzas para uma pizzaria fictícia. Ele exibe várias opções de pizzas junto com seus detalhes e status de disponibilidade. O aplicativo também fornece informações sobre o horário de funcionamento e permite que os usuários façam pedidos durante o horário de operação.

## Tabela de Conteúdo

- [Aplicativo React Pizza](#aplicativo-react-pizza)
  - [Tabela de Conteúdo](#tabela-de-conteúdo)
  - [Primeiros Passos](#primeiros-passos)
  - [Recursos](#recursos)
  - [Componentes](#componentes)
  - [Uso](#uso)
  - [Contribuição](#contribuição)
  - [Licença](#licença)

## Primeiros Passos

Para executar este aplicativo em sua máquina local, siga estas etapas:

1. Clone o repositório em sua máquina local usando:

   ```bash
   git clone https://github.com/your-username/react-pizza-app.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd react-pizza-app
   ```

3. Instale as dependências necessárias:

   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm start
   ```

5. Abra o navegador e visite `http://localhost:3000` para ver o Aplicativo React Pizza em ação.

## Recursos

- Exibir uma lista de opções de pizzas disponíveis a partir de um conjunto de dados predefinido.
- Mostrar detalhes das pizzas, como nome, ingredientes, preço e disponibilidade.
- Indicar pizzas esgotadas com um indicador visual.
- Fornecer informações sobre o horário de funcionamento da pizzaria e permitir fazer pedidos durante o horário de operação.

## Componentes

O Aplicativo React Pizza é composto pelos seguintes componentes:

- `App`: O componente principal do aplicativo que serve como contêiner para o cabeçalho, menu e rodapé.
- `Header`: Exibe o título da pizzaria, "React Pizza".
- `Menu`: Lista as pizzas disponíveis do conjunto de dados `pizzaData`, juntamente com seus detalhes e status de disponibilidade.
- `Pizza`: Representa um item individual de pizza com seu nome, ingredientes, preço e um indicador opcional de "esgotado".
- `Footer`: Exibe o horário de funcionamento da pizzaria e um botão de pedido durante o horário de operação.
- `Order`: Fornece informações sobre o horário de funcionamento da pizzaria e um botão para fazer um pedido.

## Uso

1. Inicie o aplicativo seguindo as instruções em "Primeiros Passos".
2. Ao carregar, você verá o título da pizzaria no cabeçalho.
3. A seção do menu exibirá uma lista de pizzas disponíveis com seus detalhes.
4. Se alguma pizza estiver esgotada, ela será marcada adequadamente.
5. O rodapé mostrará se a pizzaria está aberta e fornecerá opções de pedido durante o horário de operação.

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões de melhorias, sinta-se à vontade para abrir um problema ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE). Você tem a liberdade de usar, modificar e distribuir o código como desejar.
