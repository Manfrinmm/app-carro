# O que Software irá fazer?

- Motorista:
  - Nome.
  - E-mail;
  - Senha.
  - Telefone.
  - CPF.
  - Foto do rosto.
  - Carro:
    - Modelo.
    - Placa.
    - Cor.
  - Ativo:
    - Motorista habilitado.
    - Motorista não habilitado.
  - Foto com CNH ao lado do rosto.
  - Comprovante de endereço.
  - Certidão de antecedentes criminais.
  - Foto de CNH.
- Cliente:
  - Nome.
  - E-mail;
  - Senha.
  - Telefone.
  - CPF.
  - Foto do rosto.
- Traçar rota entre motorista, passageiro e destino.
- Histórico de corridas por passageiros e motoristas.
- Chat de passageiro com motorista da corrida atual.
- Enviar mensagem administrativa para os motorista.
- Tarifas:
  - Deslocamento para o local do passageiro.
  - Deslocamento para o destino do passageiro.
  - Horários especiais:
    - A noite (19h - 5hr).
    - Finais de semanas e feriados.
- Valor da corrida:
  - Valor estimado da rota (Tarifas).
  - Débitos pendentes:
    - Cancelamento da corridas anteriores.
    - Valor remanescente da corrida anterior.
- Integrar com maps:
  - Abrir a rota para o destino.
- RealTime de deslocamento de motoristas.
- Motivos de cancelamentos do motorista:
  - Endereço errado.
  - Passageiro não entrou.
  - Percepção de risco.
  - Local de difícil acesso.
  - Outro:
    - Uma Caixa de texto descrevendo o motivo de cancelamento.
- Motivos de cancelamentos do passageiro:
  - Ultrapassou o tempo estimado ( Somente válido quando ultrapassar o tempo estimado de chega do motorista até o local do passageiro).

## RN

- Corridas só podem ser iniciadas sem débitos anteriores.
- Motorista pode aceitar corrida em até 5 segundos, caso não aceite, passar para o próximo.
- Solicitação de corrido para o motorista mais próximo do passageiro.
- Cancelamentos feitos a partir de passageiros com a opção `ultrapassou o tempo estimado`, não será acrescidos de débitos.

# O que Usuário irá fazer?

### ADMIN

- Autorizar cadastro de motorista.
- Visualizar histórico das corridas:
  - Motorista.
  - Passageiro.
- Mandar mensagens para os motorista e passageiros.
- CRUD Tarifas.
- Visualizar solicitações de quitações de dividas de passageiros.
- CRUD de Passageiro e Motorista.
- Visualizar deslocamentos de motoristas em tempo real.

### Motorista

- Solicitação cadastral.
- Visualizar solicitação da corrida:
  - passageiro:
    - Nome.
    - Foto.
  - Trajeto.
  - Valor estimado da corrida.
- Chat com passageiro da corrida atual.
- Cancelar corrida atual.
- Visualizar mensagens da administração.
- Ticket para administração.
- Solicitar alteração dos dados pessoais.

### Passageiro

- Alterar os dados pessoais.
- Visualizar valor estimado de uma rota.
- Visualizar motorista da corrida atual:
  - Nome.
  - Foto.
  - Carro.
- Conversar com o motorista após confirmação da corrida.
- Cancelar corrida atual:
  - Visualizar a taxa de cancelamento (Tarifa de deslocamento do motorista).
  - Caso tenha passado do prazo estimado de chegada do motorista, zero taxa.
- Ticket para administração.
- Visualizar histórico de corrida:
  - Motorista:
    - Nome.
  - Data.
  - Valor da corrida.
  - Trajeto.
- Quitar débitos anteriores:
  - Solicitar um boleto no valor dos débitos anteriores.
