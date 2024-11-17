# Assimilação no Custom System Builder - Configuração de Ficha e Background no Foundry VTT

Este guia explica como configurar uma ficha template de assimilação no **Custom System Builder** no Foundry VTT e como personalizar o fundo da ficha usando Custom CSS.

   **Quero deixar avisado que o sistema de dados de Assimilação ainda não foi implementado, foi só a ficha, mas usando o fast play e a explicação de testes e face de dados da pra jogar muito bem ainda**

---

## 📝 Adicionando uma Ficha Template no Custom System Builder

1. **Acesse o Foundry VTT** e entre no mundo que está utilizando o sistema Custom System Builder.
2. Clique no ícone de engrenagem no canto inferior esquerdo para a aba de **Game Settings**.
3. Vá até a opção **Import templates JSON**.
4. Na aba **File Browser**, clique em **Escolher Arquivo**.
5. Selecione a **Ficha Assimilação** e **Select File**.
6. Depois só criar um **Actor** e selecionar na opção de **Template** a Ficha de assimilação e cliclar no botão ao lado **Reload Template**.


## 🎥 Tutorial

[![Clique para assistir](https://via.placeholder.com/400x200.png?text=Video+Preview)](https://streamable.com/04oypn)

---

## 🎨 Adicionando Backgrounds à Ficha com CSS

Um andendo antes, para isso é necessarios usar um modulo extra : **Custom CSS** 
E se você deseja personalizar o visual da ficha com um fundo estilizado, siga os passos abaixo:

1. Acesse as **Configurações do Sistema** no Foundry VTT.
2. Localize a aba ou opção de **CSS Personalizado**.
3. Insira o seguinte código no editor de CSS:

   ```css
   .custom-system-actor-content {
       background-image: url("https://i.ibb.co/M292Vb1/snapedit-1731517092435.png");
       background-repeat: no-repeat;	
       background-size: cover;
   }
## 🎥 Tutorial

Veja como configurar o background na ficha:

[![Clique para assistir](https://via.placeholder.com/400x200.png?text=Video+Preview)](https://streamable.com/em49ya)

