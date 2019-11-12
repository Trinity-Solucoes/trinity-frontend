Trinity - Teste para desenvolvimento frontend
======================

## Proposta

Implementar uma aplicação client-side, que consulte a API do GitHub e mostre os repositórios de um determinado usuário. Esta aplicação deve funcionar nos navegadores mais recentes do mercado.

## API
https://developer.github.com/v3/

## Endpoints
Detalhes de um usuário: https://api.github.com/users/{username}
Repositórios de um usuário: https://api.github.com/users/{username}/repos

## Layout

## Navegação
- Ao buscar um usuário pelo login do github, direcionar para pagina de resultado de busca.
- Se o usuário for encontrado apresentar pagina de detalhes do usuário, caso contrario exibir mensagem amigável Notfound

## Requisitos
- Eu, como usuário, desejo buscar por um usuário do GitHub;
- Eu, como usuário, desejo ver os detalhes desse usuário que foi buscado (número de seguidores, número de seguidos, imagem do avatar, e-mail e bio);
- Eu, como usuário, desejo ver a listagem dos repositórios desse usuário que foi buscado, ordenados pelo número decrescente de estrelas;


## Definição de pronto
- Não é obrigatório o uso de um framework, mas recomendamos React.js ou Angular.
- É obrigatório o uso de rotas.

## Critérios de avaliação
- Organização do projeto: Avalia a estrutura do projeto, documentação e uso de controle de versão;
- Inovação tecnológica: Avalia o uso de tecnologias mais recentes, desde que estáveis;
- Coerência: Avalia se os requisitos foram atendidos;
- Boas práticas: Avalia se o projeto segue boas práticas de desenvolvimento, incluindo segurança e otimização;
- Controle de Qualidade: Avalia se o projeto possui qualidade assegurada por testes automatizados (por exemplo Jest).

## Submissão
- O desafio deve ser entregue pelo GitHub. A aplicação deve estar hospedada (Heroku, Netlify, Firebase, Plunker, etc) As URLs deve ser enviada por email.

## Prazo
- O prazo de entrega é de uma semana
 
Boa Sorte!
