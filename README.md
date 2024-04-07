


# RF_06 - configuração de roteamento e criação de tabelas do sistema

#### Autor: @gabrielbdsm - Gabriel barbosa dos santos martiliano

- - -
#### Revisor : @CaesarCrew - João Pedro

| Item | Descrição |
| ---  | --- |
| Caso de Uso | configuração de roteamento e criação de tabelas do sistema |
| Resumo |  Esta requisição detalha a configuração das rotas e do banco de dados para a aplicação de consultas médicas, abrangendo funcionalidades como login, cadastro de usuários, marcação, edição e exclusão de consultas, criação de consultas por usuários e secretárias, e criação de agendas para secretárias.  |
| Ator primário |  Desenvolvedor |
| Atores secundários |  Não possui |
| Pré-condição | O sistema deve estar instalado e configurado para utilizar o Composer.O arquivo configuração deve estar configurado corretamente com as informações de conexão com o banco de dados.Mysql deve está configurado corretamente.|
| Pós-condições |  O banco de dados está configurado e possui as tabelas necessárias para armazenar informações de usuários, consultas e agendas.O sistema de rotas estão configuradas corretamente.
|


## Descrição Sucinta:
Esta requisição define as etapas para configurar as rotas e o banco de dados da aplicação de consultas médicas. O desenvolvedor deve adicionar as rotas necessárias para funcionalidades como login, cadastro de usuários, marcação, edição e exclusão de consultas, criação de consultas por usuários e secretárias, e criação de agendas para secretárias. As informações de conexão com o banco de dados devem ser configuradas no arquivo .env, e as tabelas já estão criadas para armazenar dados de usuários, consultas e agendas..


## Fluxo principal:

1. O desenvolvedor identifica as funcionalidades que precisam de rotas e decide os caminhos para essas funcionalidades.
2. O desenvolvedor cria as rotas no arquivo de configuração de rotas da aplicação, como o arquivo router.php.
3. Para cada rota criada, o desenvolvedor especifica qual método do controlador deve ser chamado quando a rota é acessada
4. O desenvolvedor configura as informações de conexão com o banco de dados no arquivo de configuração.

## Fluxos Alternativos:
N/A

## Exceções:
| Código | Descrição                                        |
|--------|--------------------------------------------------|
|    |           |

## Campos do Formulário:
| Campo | Obrigatório? | Editável? | Formato |
| --- | --- | --- | --- |

## Opções dos Usuários:
| Item | Descrição | Atalho |
| --- | --- | --- |

