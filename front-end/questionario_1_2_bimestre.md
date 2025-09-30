1. Qual método do DOM você usaria para selecionar o primeiro elemento que corresponde a um seletor CSS específico (por exemplo, uma classe ou um ID)?

Resposta: document.querySelector()

2. O que acontece se você tentar acessar uma variável declarada com let ou const antes de sua declaração em JavaScript?

Resposta: Um erro de referência (ReferenceError) é lançado devido ao temporal dead zone (TDZ).

3. Qual das seguintes afirmações sobre JSON é verdadeira?

Resposta correta (geralmente):

JSON é uma notação de texto leve para troca de dados, baseada em JavaScript.
(Se quiser as opções, me envie!)

4. Em JavaScript, qual é a principal diferença entre == e ===?

Resposta:

== compara valores com coerção de tipo.

=== compara valores e tipos, sem coerção.

5. Qual é o propósito da Promise em JavaScript?

Resposta:
Gerenciar operações assíncronas e permitir tratamento mais claro de sucesso (.then) e falhas (.catch).

6. Como a API fetch do JavaScript difere do XMLHttpRequest tradicional?

Resposta:

fetch usa Promises, tem uma sintaxe mais limpa e moderna.

XMLHttpRequest é baseado em callbacks, mais verboso e menos intuitivo.

7. Qual é a ordem correta de eventos para o carregamento de uma página web e seus recursos?

Resposta:
DOMContentLoaded → load

DOMContentLoaded: Quando o HTML é totalmente carregado e analisado.

load: Quando todos os recursos (imagens, CSS etc.) também foram carregados.

8. Qual é o principal benefício de usar AJAX (Asynchronous JavaScript and XML)?

Resposta:
Atualizar partes da página sem recarregá-la completamente (experiência mais fluida para o usuário).

9. Em JavaScript, o que é um 'closure' (fechamento)?

Resposta:
É quando uma função "lembra" do escopo onde foi criada, mesmo após esse escopo ter sido finalizado.

10. Qual é a forma correta de converter um objeto JavaScript em uma string JSON?

Resposta:
JSON.stringify(objeto)

11. Qual das seguintes opções é uma desvantagem potencial de usar document.getElementById() em vez de document.querySelector()?

Resposta:
getElementById() só funciona com IDs. querySelector() é mais flexível (suporta qualquer seletor CSS válido).

12. Qual método de requisição HTTP é mais apropriado para enviar novos dados para o servidor?

Resposta:
POST

13. O que a palavra-chave this se refere dentro de uma função de seta (arrow function)?

Resposta:
Herda o this do escopo léxico onde foi definida (não cria seu próprio this).

14. Qual das seguintes afirmações sobre o spread operator (...) em JavaScript é verdadeira?

Resposta correta (geralmente):
Pode ser usado para copiar ou mesclar arrays e objetos, e também para expandir elementos em chamadas de função.

15. Em JavaScript, o que significa 'callback hell'?

Resposta:
É quando há muitos callbacks aninhados, tornando o código difícil de ler e manter.
Exemplo típico:doSomething(function(result) {
  doSomethingElse(result, function(nextResult) {
    anotherThing(nextResult, function(finalResult) {
      // etc...
    });
  });
});

