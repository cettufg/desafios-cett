# Sistema de Biblioteca Digital Web

## Ideia
O sistema deverá ter um sistema de autenticação (cadastro e registro) para usuários normais, o usuário poderá gerenciar obras publicadas, atribuindo relacionamento com registros já cadastrados (Instituição e Pesquisador), conforme modelo abaixo. 
Obs: Busque utilizar o máximo do framework Quasar, agregando agilidade no desenvolvimento e padronização nos componentes do projeto.
Obs 2: Será disponibilizado um repositório (boilerplate) com o Laravel e Inertia JS para o Quasar (Vuejs) já pré-configurados com JWT(Caso opte por utilizar o Vue de forma externa).

## Modelo do Banco de Dados 
<img src="https://i.imgur.com/UYn4ONd.png" alt="modelo"  />

## Objetivos 
- [ ] Criar as listas e elementos para uma aplicação web que que atue como uma biblioteca digital para armazenar, disponibilizar e consultar obras.
- [ ] As obras devem ser vinculadas a pesquisadores inseridos em um cadastro próprio. Também deve um cadastro de país, cidade e instituição vinculada à obra

# Desenvolvimento

## Configurações de Acesso
- [ ] Configurar mecanismo de login e cadastro.
- [ ] Criar um usuário especial para teste.
- [ ] Manutenção (criação, edição e exclusão) de País e Cidade apenas por usuário com acesso especial.
- [ ] Desenvolver todos os CRUDs das entidades presentes no modelo apresentado acima.

## Design e Estilo
- [ ] Seguir padrão do material design (Padrão do Quasar), realizando apenas ajustes pontais com o TailwindCSS. 

## Validação de Campos
- [ ] Validar campos de cadastro e edição das entidades presentes no modelo.

## Upload de Arquivos
- [ ] Durante o cadastro e edição das obras publicadas, o usuário deverá anexar um documento PDF.

## Bonus (Opcional)
- [ ] Testes automatizados
- [ ] Aderencia à padrões de projeto e desenvolvimento.
