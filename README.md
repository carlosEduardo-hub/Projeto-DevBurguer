## Cardápio de Hamburgueria - Delivery Online

Este projeto é um cardápio online de hamburgueria desenvolvido em HTML, CSS, TailwindCSS e JavaScript. Ele permite que os clientes naveguem pelos itens do menu, adicionem-os ao carrinho e finalizem o pedido, o qual é enviado diretamente para o WhatsApp. 

### Funcionalidades:

* **Cardápio Interativo:** Permite que os clientes visualizem os itens do menu com detalhes, como nome, descrição e preço.
* **Carrinho de Compras:** Permite que os clientes adicionem itens ao carrinho, visualizando a lista de produtos selecionados e o valor total do pedido em tempo real.
* **Verificação de Horário:** O projeto verifica a data e hora atuais no momento em que é executado e valida se a hamburgueria está aberta (entre 18h e 23h).
* **Encomenda via WhatsApp:** Caso a hamburgueria esteja aberta, o cliente pode finalizar o pedido e enviá-lo para o número de WhatsApp configurado no projeto. 
* **Notificação de Horário:** Se a hamburgueria estiver fechada, um toast é exibido informando o cliente sobre o horário de funcionamento.

### Tecnologias:

* **HTML:** Estrutura básica do cardápio.
* **CSS:** Estilização do cardápio com a biblioteca TailwindCSS.
* **JavaScript:** Lógica para interação com o usuário, gerenciamento do carrinho, validação do horário e envio do pedido via WhatsApp.

### Como Executar:

1. **Clone o repositório:** `git clone https://github.com/carlosEduardo-hub/cardapio-hamburgueria.git`
2. **Instale as dependências:** `npm install`
3. **Inicie o servidor de desenvolvimento:** `npm run dev`
4. **Abra o projeto:** Acesse o endereço `http://localhost:5173/` em seu navegador.
5. **Personalize:** Modifique o código para ajustar o nome da hamburgueria, número de WhatsApp, itens do menu e preços.

### Demonstração:

Para ver o projeto em funcionamento, acesse: [https://dev-burguer-kappa.vercel.app/](https://dev-burguer-kappa.vercel.app/)

