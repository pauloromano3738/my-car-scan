# Especificações do Projeto

O My Car Scan é um aplicação que permite visualizar dados importantes sobre o desempenho do veículo em tempo real através de um adaptador ELM327. Com ele, o usuário pode monitorar a temperatura do motor, rotação, consumo de combustível e outros parâmetros, tudo na tela do seu celular ou computador. Além disso, o usuário pode cadastrar meus carros na aplicação.

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve permitir que os usuários criem uma conta, fornecendo nome, e-mail e senha.| ALTA | 
|RF-002| A aplicação deve validar o formato do e-mail garantindo que ele seja único e que a senha atenda a critérios de segurança.    | ALTA |
|RF-003| A aplicação deve permitir que usuários cadastrados façam login usando e-mail e senha. | ALTA |
|RF-004| A aplicação deve validar as credenciais do usuário e garantir que a senha seja comparada de forma segura. | ALTA |
|RF-005| A aplicação deve permitir que o usuário cadastre múltiplos carros, informando fabricante, modelo e ano. | ALTA |
|RF-006| A aplicação deve estabelecer comunicação Bluetooth com o adaptador ELM327. | ALTA |
|RF-007| A aplicação deve enviar comandos OBD-II para o ELM327 e receber os dados do veículo em tempo real. | ALTA |
|RF-008| A aplicação deve exibir os dados do veículo (ex: RPM, consumo, temperatura) em tempo real na interface do usuário. | ALTA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsiva, adaptando-se a diferentes tamanhos de tela. | MÉDIA | 
|RNF-002| A aplicação deve ser compatível com os principais navegadores. |  MÉDIA | 
|RNF-003| A aplicação deve garantir a segurança dos dados do usuário. |  ALTA |
|RNF-004| A aplicação deve exibir os dados do veículo com o mínimo de latência possível. |  ALTA |
|RNF-005| A aplicação deve manter a conexão com o ELM327 de forma estável, evitando perdas de dados. |  ALTA |

## Diagrama de Casos de Uso
 
<img src="./img/diagramaCasoDeUso.png" alt="Diagrama de Casos de Uso">

## Diagrama de Classes

O diagrama de classes ilustra graficamente como será a estrutura do software, e como cada uma das classes da sua estrutura estarão interligadas. Essas classes servem de modelo para materializar os objetos que executarão na memória.

(CONTINUAR)

## Modelo ER (Projeto Conceitual)

O Modelo ER representa através de um diagrama como as entidades (coisas, objetos) se relacionam entre si na aplicação interativa.

<img src="./img/modeloEr.png" alt="Modelo ER">

## Projeto da Base de Dados

O projeto da base de dados corresponde à representação das entidades e relacionamentos identificadas no Modelo ER, no formato de tabelas, com colunas e chaves primárias/estrangeiras necessárias para representar corretamente as restrições de integridade.
 
<img src="./img/projetoDaBaseDeDados.png" alt="Projeto da Base de Dados">

## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

(CONTINUAR)
 
