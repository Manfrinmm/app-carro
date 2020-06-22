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
  - Cidade origem.
  - Ativo:
    - Motorista habilitado.
    - Motorista não habilitado. (default)
  - Forma de pagamento:
    - Dinheiro.
    - Cartão.
    - Ambos.
  - Cadastramento:
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
  - Cidade origem.
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
    - Cancelamento das corridas anteriores.
    - Valor remanescente da corrida anterior. (O que faltou pagar)
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
  - Ultrapassou o tempo estimado (Somente válido quando ultrapassar o tempo estimado de chegada do motorista até o local do passageiro).

## RN

- Quando um cadastramento de motorista for negado, permitir reenviar novamente as fotos necessários para o cadastramento e excluir as fotos antigas do servidor.
- Corridas só podem ser iniciadas sem débitos anteriores.
- Solicitação de corrido para o motorista mais próximo do passageiro.
- Motorista pode aceitar corrida em até 5 segundos, caso não aceite, passar para o próximo.
- Cancelamentos feitos a partir de passageiros com a opção `ultrapassou o tempo estimado`, não será acrescidos de débitos.
- Passageiro informar forma de pagamento para corrida atual:
  - Dinheiro: Buscar apenas motoristas que aceitam `Dinheiro` e `Ambos`.
  - Cartão: Buscar apenas motoristas que aceitam `Cartão` e `Ambos`.
- Passageiro informar qual cidade atual.

# O que Usuário irá fazer?

### ADMIN

- Autorizar cadastro de motorista:
  - Visualizar dados de cadastramento.
  - Recusar ou aceitar:
    - Aceitar: Motorista apto para prosseguir com uso da plataforma.
    - Recusar: Descrever o motivo.
- Visualizar histórico das corridas:
  - Por motorista.
  - Por passageiro.
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
- Ticket para administração.
- Visualizar histórico de corrida:
  - Motorista:
    - Nome.
  - Data.
  - Valor da corrida.
  - Trajeto.
- Quitar débitos anteriores:
  - Solicitar um boleto no valor dos débitos anteriores. (Ticket)
