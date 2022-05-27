<h1 align="center">Meio Ambiente</h1>

<p align="center">Esse projeto é uma aplicação específica usando alguns metódos de Engenharia de Software.</p>

---

#### História de usuário:  
   Como Maria Luiza, gostaria de ter acesso a um site onde eu possa solicitar a avaliação da arborização urbana de uma 
   determinada região, para que em áreas estratégicas sejam instaladas coberturas vegetais e promovam o bem estar ambiental.

#### Caso de uso:

![Captura de Tela (220)](https://user-images.githubusercontent.com/77236515/170603771-24c43323-3d23-4ea6-b299-00db413b83e8.png)

#### Detalhamento para <<CRUD>> Conta sistema:
Sumário: Mantém o cadastro usuários do sistema.  
     
Atores:  
- Usuário: pessoa que possui um smartphone com serviço de localização e o sistema instalado instalado.  
     
Pré-condições:  
a)  O usuário deve ter um e-mail. 
b)  O usuário deve ter acesso à Internet.    
     
Fluxo de eventos:  
     
Fluxo básico:  
1. Usuário inicia o caso de uso.  
2. Sistema exibe tela de cadastro de Usuário.  
3. Usuário informa e-mail do Usuário.  
4. Sistema verifica existência do Usuário informado.  
5. Caso o Usuário exista, os seus dados são recuperados e exibidos na tela.  
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
6. Caso o Usuário não exista, sistema exibe habilita inclusão na tela de cadastro de Usuário.  
-  Usuário informa os dados da novo Usuário.  
-  Sistema valida os dados.  
-  Sistema grava os dados da novo Usuário.  
7. Sistema finaliza caso de uso.  
     
Fluxos alternativos:  
     
Pós-condições:  
a)  O usuário estar com o cadastro atualizado no sistema.  
#### Detalhamento para ver tutorial:
Sumário: Usuário aprenderá a usar o sistema
Pré-condições:
    a) Usuário deve ter uma conta
    b) Usuário deve ter acesso à internet
Fluxo principal:
    1. Sistema inicia caso de uso
    2, Sistema mostra a opção de tutorial na tela inicial
    3. Usuário seleciona esta opção
    4. Sistema direciona usuário para uma nova tela
    4. Sistema mostrar as opções de tutoriais
    5. Sistema mostra ao usuário passo a passo sobre como utilizar de cada funcionalidade
    6. Usuário encerra caso de uso
Pos-condições:
    a) Usuário sabe como usar o sistema
#### Detalhamento para fazer pedido:
Sumário: Este caso de uso permite que o usuário solicite a instalação de vegetação(ões)
Ator(es):
- Usuário geral: qualquer pessoa que tenha o Sistema instalado em seu smartphone com sistema de localização.
Pré-condição(ões):
a) Usuário deve ter acesso à internet
Fluxo de eventos:
Fluxo principal:
1) Sistema disponibiliza opção de fazer pedido
2) Usuário seleciona esta opção
3) Sistema mostra uma nova tela
4) Sistema mostra as opções de imagens, vídeos, aúdio e texto
5) Usuário entra com os dados
6) Usuário confirma pedido
7) Usuário envia pedido
8) Sistema encerra caso de uso
Fluxo(s) alternativo(s):
Pós-condição:
a) Pedido fica em análise
b) Informação acima é disponibiliza para o usuário
#### Detalhamento para verificar status:
Sumário: Sistema verifica se o pedido foi aprovado ou não
Atores: - Usuário: Ser humano com o sistema instalado no smartphone.
Pré-condição:
a)Usuário já deve ter feito o pedido
b)Usuário deve ter acesso à internet
Fluxo Principal:
1)Sistema inicia caso de uso
2)Sistema mostra a opção de verificar status
3)Usuário seleciona esta opção
4)Sistema mostra o estado atual do pedido: em análise, aprovado, negado
5)Sistema encerra caso de uso
Pós-condição:
a)Se aprovado, instalação de coberturas vegetais será feita 
#### Detalhamento para verificar histórico:
Sumário: Verificar históricos dos pedidos feitos.
Atores: - Usuário: Ser humano com o aplicativo instalado em seu smartphone
Pré-Condição: a) Usuário deve estar cadastrado no sistema
Fluxo Principal:
1. Sistema inicia caso de uso
2. Sistema disponibiliza a opção de histórico
3. Usuário seleciona esta opção
4. Sistema mostra os pedidos feitos pelo usuário, locais, situação e se foi feito a instalação ou não
5. Sistema encerra caso de uso
Pós-condição:
a)Usuário relembra sua história no sistema     

 ### Ferramenta para construir o diagrama
- [Visual Paradigm](https://online.visual-paradigm.com/pt/)
