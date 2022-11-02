# Echo_BLE_Renode

Grupo: Arthur, Ester, Jadson, Larissa e Pamela.

ROTEIRO DO PROJETO
- Implementar o periférico que deverá:
    - ter uma característica com permissão de escrita e que irá receber os dados
    - ter uma característica sem permissão e que realiza notificação
        - a notificação deverá ser enviada sempre que um dado for recebido
        - o conteúdo da notificação é o dado recebido com as letras minúsculas convertidas para maiúsculas

- Implementar o central que deverá:
    - procurar e se conectar ao periférico
    - enviar ao periférico o que o usuário escreve no terminal
    - imprimir a resposta enviada pelo periférico

- Testar a implementação no Renode
