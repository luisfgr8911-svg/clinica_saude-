# Especificação dos Casos de Uso

###   Login no sistema (Ator: Paciente)

 • Pré-condição: O usuário deve estar cadastrado no sistema e possuir acesso à internet.

 • Pós-condição: Usuário autenticado, sessão iniciada.

 • Fluxo Principal: Usuário digita CPF e senha, o sistema valida as informações e entra no sistema.

 • Fluxo Alternativo de exceção: 

 1. Login inválido (Usuário não cadastrado, realizar cadastro) ||
  (CPF ou senha incorretos. Tente novamente)

 2. Sem acesso à internet: Sua conexão não é particular.

  ###  Agendar consulta (Atores: Paciente, Recepcionista e Médico)
  • Pré-condição: Escolher a especialidade, data e horário para solicitar consulta

  • Pós-condição: Consulta agendada com sucesso.                        

  • Fluxo Principal: Paciente solicita a consulta, recepcionista verifica a  agenda do médico e se estiver disponível marca a consulta.

  • Fluxo Alternativo de Exceção:
  
  1. Data e horário não disponíveis (Agenda do médico lotada)

  2. Lista de espera (O paciente que não conseguir marcar sua consulta devido a agenda do médico será adicionado à fila de espera)

  ### Cancelar consulta (Atores: Peciente e Recepcionista)

  • Pré-condição: 48 horas antes da consulta.

  • Pós-condição: Consulta cancelada com sucesso. 

  • Fluxo Principal: Usuário cadastrado e com acesso ao seu login, realiza o cancelamento de  consulta verificando a antecedência exigida.

  • Fluxo Alternativo de Exceção:

  1. Cancelar consulta com menos de 48 horas para o atendimento

  2. O usuário tenta cancelar uma consulta inexistente (já foi cancelada ou nunca existiu)