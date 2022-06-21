<h1 align="center">Sistema Delegacia</h1>

<p align="center">Esse projeto é uma aplicação específica usando alguns metódos de Engenharia de Software.</p>

---

#### História de usuário:  
    Como Bruna, quero fazer um boletim de ocorrência policial no local que eu desejar, para que eu não tenha que
    ir à delegacia e otimizar o meu tempo
    
#### Caso de uso:

![CasoDeUsoDelegacia](https://user-images.githubusercontent.com/77236515/174889824-51e6f61e-9227-48e6-bee9-475515d4fefd.png)

#### Detalhamento para <<CRUD>> Conta sistema:
Sumário: Mantém o cadastro usuários do sistema.
  Atores:
- Usuário: pessoa que possui um smartphone com serviço de localização e o sistema instalado.
Pré-condições:
a)  O usuário deve ter um e-mail.
b)  O usuário deve ter acesso à Internet. 
Fluxo básico:
1) Usuário inicia o caso de uso.
2) Sistema exibe tela de cadastro de Usuário.
3) Usuário informa e-mail do Usuário.
4) Sistema verifica existência do Usuário informado.
5) Caso o Usuário exista, os seus dados são recuperados e exibidos na tela.
- Sistema habilita opção de alteração de dados ou exclusão.
-  Caso o Usuário selecione a opção de exclusão.
-  Sistema solicita a confirmação da exclusão do Usuário.
-  Se o Usuário confirmar a exclusão, o sistema exclui o Usuário selecionado.
-  Sistema finaliza o caso de uso.
-  Caso o Usuário selecione a alteração de dados.
-  Sistema habilita edição da tela de cadastro de Usuário.
-  Usuário altera os dados desejados.
-  Sistema valida os dados.
-  Sistema grava os novos dados do Usuário.
-  Sistema finaliza caso de uso.
6) Caso o Usuário não exista, sistema exibe habilita inclusão na tela de cadastro de Usuário.
-  Usuário informa os dados da novo Usuário.
-  Sistema valida os dados.
-  Sistema grava os dados da novo Usuário.
7) Sistema finaliza caso de uso.
Pós-condições:
a)  O usuário está com o cadastro atualizado no sistema.
  
#### Detalhamento de registro de ocorrência:
Sumário: este caso de uso permite que o usuário registre uma ocorrência.
Ator(es):
- Usuário geral: qualquer pessoa que tenha a delegacia digital instalada em seu smartphone.
Pré-condição(ões):
a. Usuário deve estar logado no sistema
Fluxo de eventos:
Fluxo principal:
1) Sistema inicia caso de uso.
2) Sistema mostra opção de registrar ocorrência
3) Usuário seleciona esta opção
4) Sistema mostra as opções de estado
5) Usuário seleciona estado
6) Sistema informa com orientações
7) Sistema tem um botão para usuário prosseguir
8) Usuário seleciona este botão
9) Sistema mostra os dados pessoais a serem informados
10) Usuário informa os dados
11) Sistema mostra opção do crime sofrido pelo usuário
12) Usuário seleciona opção
13) Sistema pergunta quais são os participantes da ocorrência
14) Usuário informa quais são estes
15) Sistema pede para usuário descrever o evento ocorrido
16) Usuário descreve o evento ocorrido
17) Sistema faz perguntas sobre o evento
18) Usuário responde essas perguntas
20) Sistema encerra caso de uso
Fluxo(s) alternativo(s):
Pós-condição:
a) Sistema registra boletim de ocorrência  
  
 #### Detalhamento de acompanhar ocorrência:
Sumário: este caso de uso permite que o usuário registre uma ocorrência.
Ator(es):
- Usuário geral: qualquer pessoa que tenha a delegacia digital instalada em seu smartphone.
Pré-condição(ões):
a) Usuário deve estar logado no sistema
Fluxo de eventos:
Fluxo principal:
1) Sistema inicia caso de uso
2) Sistema exibe filtros de acompanhamento do BO
3) Caso o usuário selecione exibir tudo
    - Sistema exibe tudo
4) Caso usuário queira selecionar por meio do protocolo
     - Sistema disponibiliza o campo
     - Usuário digita protocolo
     - Usuário clica pesquisar
     - Sistema busca BO
5) Caso o usuário queira selecionar pelo periodo/natureza
     - Sistema disponibiliza campo de data de periodo (inicio e fim)
     - Usuário entra com os dados
     - Usuário clica em pesquisar
     - Sistema pesquisa com base nas entradas do usuário
6) Sistema encerra caso de uso
Pós-condição:
a) Sistema registra boletim de ocorrência  
b) Sistema mostra para o usuário a situação atual da ocorrência

 ### Ferramenta para construir o diagrama
- [Visual Paradigm](https://online.visual-paradigm.com/pt/)
