---

1.  **No-Code:** O que é o desenvolvimento **no-code** e qual a sua principal vantagem em relação ao desenvolvimento tradicional?
2.   R: O desenvolvimento no-code é uma abordagem que permite criar aplicações e automações sem a necessidade de codificação, utilizando interfaces visuais e ferramentas intuitivas. Sua principal vantagem é democratizar o acesso ao desenvolvimento de software, permitindo que pessoas sem conhecimento técnico possam criar soluções rapidamente.

3.  **Linguagem de Programação:** Cite uma linguagem de programação de back-end comumente utilizada em conjunto com **HTML**, **CSS** e **JavaScript** para criar aplicações web completas.
4.  
  R: Uma linguagem de programação de back-end comumente utilizada em conjunto com HTML, CSS e JavaScript para criar aplicações web completas é o Python, especialmente com frameworks como Django ou Flask.

PHP (com frameworks como Laravel)

Java (Spring Boot)

Node.js (JavaScript no back-end)

C# (ASP.NET).

4.  **HTML:** Qual o principal objetivo do **HTML**? Qual a diferença entre uma tag `<h1>` e `<h6>`?
5.  
R: O HTML (HyperText Markup Language) é a linguagem de marcação usada para estruturar o conteúdo de uma página web. Ele organiza os elementos como textos, imagens, links, botões, tabelas e formulários, servindo como a “espinha dorsal” da web.

✅ Diferença entre <h1> e <h6>
As tags <h1> até <h6> são títulos (headings) usados para hierarquizar o conteúdo:

<h1>: título mais importante da página. Normalmente é usado uma única vez, representando o tema principal.

<h6>: título menos importante, usado para subtítulos de níveis muito baixos.

6.  **CSS:** Como o **CSS** contribui para o desenvolvimento web? Qual a função da propriedade `margin`?
7.   R:O CSS (Cascading Style Sheets) contribui para o desenvolvimento web permitindo controlar a aparência e o design das páginas. Enquanto o HTML define a estrutura (títulos, parágrafos, imagens, botões etc.), o CSS é responsável por definir cores, tamanhos, espaçamentos, alinhamentos, fontes, animações e o layout geral. Isso garante que os sites sejam mais agradáveis, organizados e fáceis de usar.

Função da propriedade margin:

A propriedade margin define o espaço externo de um elemento, ou seja, a distância entre a borda do elemento e os outros elementos ao redor dele.

8.  **JavaScript:** Qual a função do **JavaScript** em uma página web? Qual a diferença entre `let`, `const` e `var`?
9.  R: O JavaScript tem a função de tornar a página web interativa e dinâmica.
Enquanto o HTML define a estrutura e o CSS o estilo, o JavaScript permite:

Manipular elementos da página (DOM);

Reagir a eventos (cliques, digitação, rolagem etc.);

Criar animações e efeitos;

Validar formulários;

Consumir e enviar dados para servidores (APIs).

🔹 Diferença entre var, let e const:
Palavra-chave	Escopo	Pode ser alterada?	Pode ser redeclarada?	Observações
var	Função	✅ Sim	✅ Sim	Antiga, sofre hoisting (pode gerar erros)
let	Bloco	✅ Sim	❌ Não (no mesmo escopo)	Mais usada para variáveis que mudam
const	Bloco	❌ Não (valor fixo)	❌ Não	O valor não pode ser reatribuído, mas objetos/arrays podem ser modificados internamente

10.  **Git:** O que é **Git** e qual a sua principal finalidade no desenvolvimento de software?
11.  R:O Git é um sistema de controle de versão distribuído.
Ele é usado para registrar, organizar e gerenciar as mudanças feitas no código-fonte durante o desenvolvimento de software.

🔹 Principal finalidade:

Controlar versões do projeto: permite voltar a versões anteriores se algo der errado.

Trabalho em equipe: vários desenvolvedores podem colaborar no mesmo projeto sem sobrescrever o trabalho uns dos outros.

Histórico de alterações: registra quem fez cada mudança, quando e por quê.

Branches (ramificações): possibilita criar linhas de desenvolvimento independentes (por exemplo, para novas funcionalidades ou correções), que depois podem ser unidas ao projeto principal.

📌 Em resumo: o Git garante organização, segurança e colaboração eficiente no desenvolvimento de software.

12.  **Git:** Qual a diferença entre os comandos `git pull` e `git push`?
13.  R: 🔹 git pull

Traz atualizações do repositório remoto para o seu repositório local.

Junta (faz merge ou rebase) as alterações que outros colaboradores enviaram para o servidor com o que você já tem na sua máquina.

É como “baixar” as novidades do projeto.

📌 Exemplo:

git pull origin main


👉 Busca as atualizações do repositório remoto origin na branch main e aplica localmente.

🔹 git push

Envia as suas alterações locais para o repositório remoto.

Atualiza o servidor com os commits que você fez na sua máquina.

É como “subir” as suas mudanças para compartilhar com a equipe.

📌 Exemplo:

git push origin main


👉 Envia seus commits da branch main local para a branch main no repositório remoto origin.

✅ Resumo simples:

git pull = baixar alterações do remoto → local.

git push = enviar alterações do local → remoto.

Quer que eu monte uma ilustração em forma de esquema visual mostrando o fluxo entre computador local e repositório remoto?

14.  **Git:** Explique o que é uma `branch` no **Git** e para que ela serve.
15.  R: .

🔹 O que é?

É um ponteiro para um conjunto de commits.

Permite criar uma “cópia” do código em um ponto específico, onde você pode trabalhar sem alterar a branch principal (geralmente chamada main ou master).

🔹 Para que serve?

Trabalho paralelo: vários desenvolvedores podem trabalhar em funcionalidades diferentes ao mesmo tempo.

Testar novas ideias: você pode experimentar mudanças sem afetar o código estável.

Organização: ajuda a separar correções de bugs, novas funcionalidades e versões do projeto.

Integração controlada: quando a branch está pronta, ela pode ser unida (merge ou rebase) à branch principal.

16.  **GitHub:** O que é **GitHub** e como ele se relaciona com o **Git**?
17.  R: 🔹 O que é o GitHub?

Um serviço na nuvem onde você pode armazenar, compartilhar e colaborar em projetos de software.

Funciona como uma “rede social de desenvolvedores”, com recursos de issues, pull requests, discussões, wiki e muito mais.

Oferece integração com ferramentas de CI/CD (integração e entrega contínuas), automação e deploy.

🔹 Como ele se relaciona com o Git?

O Git é a ferramenta local: você usa na sua máquina para versionar o código.

O GitHub é o servidor remoto: armazena os repositórios e permite sincronizar com outras pessoas.

O fluxo comum é:

Você versiona seu código com Git localmente.

Usa comandos como git push para enviar alterações ao GitHub.

Usa git pull para trazer atualizações do GitHub para sua máquina.

✅ Resumo simples:

Git = ferramenta de controle de versão.

GitHub = plataforma que hospeda repositórios Git e facilita a colaboração online.

18. **GitHub:** Qual a importância de um `README.md` em um repositório do **GitHub**?
19. R: 🔹 Importância do README.md:

Apresenta o projeto

Explica o que o projeto faz, seus objetivos e funcionalidades principais.

Guia de uso

Ensina como instalar, configurar e executar o projeto.

Instruções para colaboração

Explica como contribuir, enviar issues ou pull requests.

Documentação básica

Pode incluir dependências, tecnologias usadas, exemplos de código, screenshots e links úteis.

Primeira impressão

É a primeira coisa que outros desenvolvedores veem ao acessar o repositório, ajudando na credibilidade e profissionalismo do projeto.

📌 Resumo:
O README.md serve como um manual de apresentação e orientação do repositório, facilitando o entendimento do projeto tanto para você quanto para outros desenvolvedores.

20. **Hospedagem:** O que é **hospedagem de projetos web**?
21. R: 🔹 Principais pontos:

Servidores: os arquivos do site (HTML, CSS, JavaScript, imagens, bancos de dados etc.) ficam em computadores especializados, chamados servidores, que estão sempre ligados e conectados à internet.

Disponibilidade online: sem hospedagem, o site só existiria localmente no seu computador. Com hospedagem, ele pode ser acessado de qualquer lugar do mundo.

Domínio: normalmente a hospedagem é associada a um endereço (URL) que os usuários digitam para acessar o site.

Recursos adicionais: muitas hospedagens oferecem backup, segurança, bancos de dados, e-mails, SSL (cadeado de segurança) e integração com sistemas de gerenciamento.

📌 Resumo simples:
Hospedagem web é o “lar” do seu site na internet, garantindo que ele esteja disponível para qualquer usuário a qualquer momento.

22. **Hospedagem:** Qual a diferença entre hospedagem **gratuita** e **paga**?
23. R: 🔹 Hospedagem gratuita

Custo: não exige pagamento.

Recursos limitados: espaço em disco, tráfego, número de sites e bancos de dados geralmente reduzidos.

Publicidade: muitas vezes exibe anúncios no seu site.

Domínio: geralmente um subdomínio (ex.: meusite.exemplo.com).

Suporte limitado: atendimento técnico básico ou inexistente.

Indicado para: testes, estudos ou projetos pessoais pequenos.

🔹 Hospedagem paga

Custo: você paga mensal ou anualmente.

Mais recursos: maior espaço, tráfego, múltiplos bancos de dados, backups automáticos.

Sem anúncios: o site fica totalmente seu, sem publicidade externa.

Domínio próprio: permite usar domínios personalizados (ex.: meusite.com).

Suporte profissional: ajuda técnica disponível, normalmente 24/7.

Indicado para: projetos profissionais, lojas virtuais, aplicativos com tráfego médio ou grande.

📌 Resumo simples:

Gratuita = limitada, ideal para aprender ou testar.

Paga = completa, confiável e indicada para projetos sérios.

24. **Hospedagem:** Cite dois exemplos de serviços de hospedagem web.
25. R: Dois exemplos de serviços de hospedagem web são:

HostGator – serviço pago, popular para sites profissionais e lojas virtuais, oferecendo domínio próprio, SSL, bancos de dados e suporte técnico.

GitHub Pages – serviço gratuito, ideal para projetos estáticos (HTML, CSS, JavaScript) e portfólios, permitindo hospedar sites diretamente de repositórios GitHub.

Se quiser, posso listar mais alguns exemplos gratuitos e pagos para comparação rápida.

26. **HTML e CSS:** O que significa a "separação de preocupações" ao usar **HTML** e **CSS** juntos?
27. R: 🔹 Explicando:

HTML: define o que existe na página (textos, imagens, links, botões).

CSS: define como esses elementos aparecem (cores, tamanhos, margens, fontes, posicionamento).

🔹 Vantagens dessa separação:

Organização: facilita a manutenção do código, pois estrutura e estilo ficam em arquivos separados.

Reutilização: o mesmo CSS pode ser usado em várias páginas diferentes.

Flexibilidade: é mais fácil mudar o visual sem alterar a estrutura HTML.

Acessibilidade e desempenho: páginas mais limpas carregam mais rápido e são mais fáceis de adaptar para diferentes dispositivos.

📌 Exemplo prático:

HTML (index.html)

<h1>Olá, mundo!</h1>
<p>Este é um exemplo de separação de preocupações.</p>


CSS (style.css)

h1 {
  color: blue;
  text-align: center;
}
p {
  font-size: 16px;
  color: gray;
}


➡️ Aqui, o HTML define o conteúdo, e o CSS define o estilo, mantendo cada parte em sua responsabilidade.

28. **Git e GitHub:** Qual a vantagem de usar o **Git** localmente para gerenciar seu projeto antes de publicá-lo no **GitHub**? R: 🔹 Principais vantagens:

Controle de versões

Permite salvar o histórico de alterações do projeto, voltar a versões anteriores e corrigir erros sem afetar a versão atual.

Testes e experimentos seguros

Você pode criar branches para testar novas funcionalidades sem interferir na branch principal (main ou master).

Organização do projeto

Mantém os commits organizados com mensagens descritivas, facilitando acompanhar o que foi feito em cada etapa.

Trabalho offline

O Git funciona totalmente localmente; você pode criar commits, branches e fazer merges mesmo sem conexão com a internet.

Preparação para colaboração

Ao ter tudo organizado localmente, enviar para o GitHub (com git push) fica mais seguro e com menos riscos de conflitos ou erros.

📌 Resumo simples:
O Git local permite controlar, testar e organizar seu projeto antes de compartilhá-lo online, garantindo segurança e eficiência no desenvolvimento.
