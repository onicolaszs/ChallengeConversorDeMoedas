# 💱 Conversor de Moedas

Um projeto simples e funcional desenvolvido em Java que realiza conversão de moedas em tempo real utilizando a ExchangeRate API.
No programa, o usuário pode escolher diferentes opções de conversão, informar o valor desejado e visualizar o resultado de forma clara e formatada.
O sistema também exibe as taxas atuais da moeda base (USD), permite conversões manuais e automáticas e mantém um histórico de conversões durante a execução.

---

## 🚀 Funcionalidades

✔️ Consulta taxas de câmbio em tempo real<br>
✔️ Conversão entre diferentes moedas (USD, BRL, EUR, GBP)<br>
✔️ Conversão manual escolhendo origem e destino<br>
✔️ Conversões rápidas pré-definidas (ex: USD → BRL)<br>
✔️ Histórico de operações realizadas<br>
✔️ Interface simples via terminal<br>
✔️ Tratamento de erros e validação de moeda<br>

---

## 🧠 Como funciona

Ao iniciar o programa, ele faz uma requisição para a API com a moeda base (USD).<br>
As taxas de conversão são carregadas e exibidas ao usuário.<br>
O menu principal oferece várias opções de conversão.<br>
O usuário escolhe a opção, digita o valor desejado e o cálculo é feito automaticamente.<br>
A conversão é exibida na tela e armazenada no histórico.<br>

---

## 🛠️ Tecnologias utilizadas

Java 21<br>
HTTP Client (java.net.http) para requisições à API<br>
Gson para desserialização de JSON<br>
ExchangeRate API para dados de câmbio<br>
IntelliJ IDEA como ambiente de desenvolvimento<br>
Paradigma de programação orientada a objetos (POO)<br>

---

## 📝 Considerações finais

Esse é mais um projeto desenvolvido no programa Alura + Oracle Next Education, com o objetivo de reforçar conceitos importantes do desenvolvimento em Java, como consumo de APIs externas, tratamento de exceções, boas práticas de organização em camadas (Service, Client e Main) e manipulação de respostas JSON.
