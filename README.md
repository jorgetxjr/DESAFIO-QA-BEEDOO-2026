# Desafio QA Beedoo 2026
## Análise inicial da aplicação
Em um teste exploratório, verifiquei o que a aplicação faz em seu core, identificando as suas capacidades.
Deste ponto, tomei notas e fiz um rascunho, usando de IA - ChatGPT - com um certo nível de especialização - provido pelo curso de QA (LumeStack) que concluir recentemente.
Esta IA foi usada para avaliar este rascunho. Ela não reconheceu a princípio que era um rascunho, mesmo sendo afirmado no prompt que era um rascunho.
Mesmo assim, as informações oferecidas sobre edge cases foram importantes.
Outra análise que fiz foi verificar os códigos HTML para ver se seus identificadores eram simples ou complexos para a implantação de automatizações.

Por esta análise inicial, creio que o objetivo desta aplicação seja servir como um "cardápio de cursos", mostrando o que a plataforma tem a oferecer. Para isso, a aplicação oferece o cadastro, visualização e exclusão dos cursos existentes. Vejo que pelo menos nos cursos on-line, deveria ter a possibilidade de clicar no card do curso e levar para a URL cadastrada para a sua respectiva inscrição.

Vejo como crítico que a aplicação esteja adesa com as regras de negócio estabelecias, assim com as as histórias de usuário de cada funcionalidade. Desta forma, cursos e informaçãoes completamente não aderentes já seriam barrados em um primento momento, evitando uma massa de dados inválidos e degradando a experiência do usuário final.

## Decisões tomadas para criação dos testes
O maior desafio encontrado foi não conhecer as regras de negócio da aplicação. Ou mesmo não ter algum manual.
Por tanto, tive que inferir algumas situações de uso da aplicação.

## Explicação do seu raciocínio durante a análise
O primeiro ponto é saber se as funcionalidades "funcionam". Botões, links e o que mais for "interagível" na página.
Depois, por não conhecer as regras de negócio, inferi algumas funcionalidades - como por exemplo, admitir que todos os campos do formulário de cadastro são obrigatórios de serem preenchidos.