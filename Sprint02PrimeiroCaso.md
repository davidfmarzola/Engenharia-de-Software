<h1 align="center">Sistema de Transporte Público</h1>

<p align="center">Esse projeto é uma aplicação específica usando alguns metódos de Engenharia de Software.</p>

---

#### História de usuário:  
   Como João, gostaria de ser direcionado para o ponto de ônibus ideal em relação à localização atual, para que eu 
   pegue um ônibus que chegará ao destino desejado no menor tempo possível.

#### Caso de uso:

![CasoDeUsoPontoDeOnibus](https://user-images.githubusercontent.com/77236515/170143416-efd83642-a3c3-4159-b5cf-1726c3f39f94.png)

#### Detalhamento para Fazer Login:
Sumário: Fazer cadastro do usuário no Sistema
Atores:
- Usuário: pessoa que possui um smartphone com serviço de localização, sistema instalado.  
Pré-condições:
a)  O usuário deve ter um e-mail.
b)  O usuário deve ter acesso à Internet. 
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
Pós-condições:
a)  O usuário estar com o cadastro atualizado no sistema.
#### Detalhamento para Escolher Destino:
Sumário: Usuário escolhe destino desejado
Atores:
- Usuário: pessoa que possui um smartphone com serviço de localização, sistema instalado.  
Pré-condições:
a)  O usuário deve ter permitido ao sistema
acessar à localização  
Fluxo básico:
1. Usuário inicia o caso de uso.
2. Sistema exibe campo de pesquisa. 
3. Sistema exibe destinos anteriores.
4. Usuário informa o destino.
5. Sistema finaliza caso de uso.
Pós-condições:
a)  Sistema exibe linha do ônibus
b) Sistema exibe ponto de ônibus mais próximo
c) Sistema exibe horário de previsão de chegada do ônibus no ponto
d)Sistema exibe horário de previsão de chegada do ônibus no destino
##### Detalhamento para fazer configurações:
Sumário: Usuário escolhe configuração que
deseja fazer.
  
Atores:
- Usuário: pessoa que possui um smartphone com o sistema instalado.  
Pré-condições: Usuário deve estar logado no sistema
Fluxo básico:
1. Usuário inicia o caso de uso.
2. Sistema exibe opção de configurações
3 Usuário clica em configurações
4. Sistema mostra todas opções de configuração
5 Caso o usuário selecione opção de configurar conta
5.1 Caso o Usuário exista, os seus dados são recuperados e exibidos na tela.
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
5.2. Caso o Usuário não exista, sistema exibe habilita inclusão na tela de cadastro de Usuário.
-  Usuário informa os dados da novo Usuário.
-  Sistema valida os dados.
-  Sistema grava os dados da novo Usuário. 
        6. Caso o usuário selecione a opção de trocar a cor de fundo
           - Sistema exibe as cores disponíveis
           - Usuário seleciona cor
           - Usuário confirma a troca
           - Sistema troca a cor de fundo
Pós-condições:
a)  Usuário tem a conta atualizada
b)  Sistema tem a cor de fundo atualizado
#### Detalhamento para escolher rota:
Sumário: Usuário escolhe rota desejada
Atores:
- Usuário: pessoa que possui um smartphone com serviço de localização, sistema instalado.  
Pré-condições:
a)  O usuário deve ter acesso à internet
b)  Usuário deve ter permitido ao sistema
acessar a localização
c) Usuário deve ter escolhido o destino
Fluxo básico:
1. Usuário inicia o caso de uso.
2. Sistema exibe as opções de rota
3. Sistema exibe o caminho de cada rota no mapa
4. Sistema exibe a distância do local atual até o destino de cada rota
5. Sistema exibe horário de chegada previsto
6. Usuário seleciona rota
5. Sistema finaliza caso de uso.
Pós-condições:
a) Sistema exibe linha de ônibus mais próxima do local
b) Sistema exibe tempo estimado de chegada do ônibus ao ponto de partida
#### Detalhamento para acessar histórico:  
Sumário: Acessar histórico de algo que já foi
utilizado no sistema
  
Atores:
- Usuário: pessoa que possui um smartphone com o sistema instalado.  
Pré-condições:
b)  O usuário deve ter acesso à Internet. os:
  
Fluxo básico:
1. Usuário inicia o caso de uso.
2. Sistema exibe opções
3. Usuário seleciona opção de histórico
4. Sistema exibe opções de histórico
5. Usuário seleciona opção de histórico
6. Sistema exibe histórico de locais de saída ou locais de destino
Pós-condições:
a)  Usuário tem acesso ao histórico desejado
#### Detalhamento para emitir alerta:
Sumário: Usuário emite alerta no sistema
Atores:
    - Usuário: Ser humano que possui um smartphone, com o sistema instalado.
Pré-condições:
    a) Usuário já deve ter escolhido o destino 
    c) Usuário já deve estar a caminho
Fluxo principal:
    1. Sistema inicia caso de uso
    2. Sistema tem a opção de emitir alerta
    3. Usuário seleciona esta opção
    4.  Sistema exibe opções de alerta
    5. Usuário seleciona opção de alerta
    5.1 Caso o usuário selecione a opção de trânsito no local
   - Sistema exibe as opções de trânsito leve, moderado ou pesado
   - Usuário seleciona opção
   - Sistema atualiza informação
   - Sistema atualiza tempo estimado de chegada ao destino
   5.2 Caso o usuário selecione a opção de acidente no local
    - Sistema exibe as opções de acidente leve, médio ou grave
    - Usuário seleciona opção
    - Sistema atualiza informação
    - Sistema atualiza tempo estimado de chegada ao destino
6. Sistema encerra caso de uso
Pós-condições:
a) Sistema alerta os próximos usuário do ocorrido
b) Sistema atualiza tempo de chegada aos próximos pontos

### Ferramenta para construir o diagrama
- [Visual Paradigm](https://online.visual-paradigm.com/pt/)
