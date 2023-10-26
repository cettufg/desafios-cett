# Aplicativo Móvel de Gestão de Publicações (Obras literárias) de Autor/Pesquisador (usuário).

## Ideia
Criar uma aplicação multiplaforma (Android e IOS) para gestão de usuário (cadastro e login) e de obras (publicações).
O aplicativo é uma versão simplificada do sistema web. 
Não há um layout padrão, utilize dos componentes ou de bibliotecas (lembre-se de citar no readme) de terceiros para facilitar o desenvolvimento.

Inspirações e sugestão de layout: <a href="https://imgur.com/a/asgTifX" target="_blank">https://imgur.com/a/asgTifX</a>

## Objetivo

- [ ] Construir um aplicativo móvel utilizando React Native, Expo, TypeScript e Tailwind para um usuário(autor/pesquisador) que permita o cadastro, visualização, edição e exclusão de suas publicações.
- [ ] Para o backend, é a livre a escolha do Laravel ou do Node (com o framework de sua escolha, como Express e Prisma, por exemplo ou um <a href="https://mockapi.io" target="_blank">mockAPI</a>.
- [ ] O aplicativo deve ser totalmente responsivo e ter comportamento identicos nas plataformas Android e IOS, no sentido de usabilidade.

## Template inicial do projeto:

Link: https://github.com/cettufg/biblioteca-app

## Entidades:
### Autor: 
- Nome completo; 
- Email;
- Senha;
- Data de nascimento; 
- Sexo; 
- Documento; e 
- Universidade.

### Publicação: 
- Titulo;
- Data de publicação;
- Assunto;
- Lingua/idioma;
- Licença;
- Thumbnail (imagem de apresentação); e
- Arquivo (pdf);

## Desenvolvimento

- [ ] **Tela de Cadastro e Login de Autor(Usuário)**:
   - Login (Email e Senha);
   - Cadastro (Todas as informações listadas anteriormente).

- [ ] **Tela de Lista de Publicações (Home)**:
   - Exibir uma lista de publicações com seus detalhes reduzidos (nome e data de publicação).
   - Permitir visualização de detalhes em modal de destaque.

- [ ] **Tela de Detalhes da Publicação**:
   - Exibir detalhes completos de uma publicação selecionada, incluindo autor(es).
   - Permitir o download do arquivo de vaga.

- [ ] **Tela de Adicionar/Editar Publicação**:
   - Permitir a adição de uma nova publicação com todos os elementos da entidade.
   - Permitir a edição de uma tarefa existente.

## Bônus (opcional)

- [ ] **Testes Automatizados**:
   - Escrever testes automatizados para as principais funcionalidades do aplicativos.

- [ ] **Uso e criação de componentes reutilizáveis**:
   - Aplicar melhores práticas de programação criando componentes e utilizando compoenentes de bibliotecas que afetem positivamente o desenvolvimento.
  
- [ ] **Build e Implantação**:
   - Gerar executável de publicação para uma plataforma de distribuição, como a App Store ou o Google Play Store (.apk ou .ipa).

## Dicas e Sugestões
- Use o Expo para iniciar o projeto e aproveitar seus benefícios, como hot-reloading e fácil configuração.
- Use o React Navigation para criar a navegação entre as telas.
- Utilize o AsyncStorage para armazenar as arquivos localmente.
- Considere a usabilidade e a experiência do usuário ao projetar a interface do aplicativo.

