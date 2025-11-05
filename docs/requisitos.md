
## Regras de Negócios (RN)
## RN01 – Aprovação de Agendamento
Todo agendamento realizado pelo paciente deve ser validado e confirmado pela recepcionista antes de ser considerado efetivo na agenda do médico. Motivo: Evitar duplicidade de horários e garantir controle administrativo.

## RN02 – Limite de Cancelamento
O paciente só pode cancelar uma consulta com até 48 horas de antecedência da data marcada.
Motivo: Permitir que o horário cancelado seja disponibilizado a outros pacientes e evitar prejuízo à clínica.

## RN03 – Agenda Exclusiva por Médico
Cada médico só pode atender um paciente por horário, e não é permitido o agendamento simultâneo no mesmo horário para o mesmo profissional. Motivo: Evitar conflitos de agenda e sobreposição de consultas. 

## RN04 – Cadastro Obrigatório de Paciente
Para agendar, cancelar ou visualizar histórico, o paciente deve estar cadastrado e autenticado no sistema. Motivo: Garantir segurança dos dados e rastreabilidade das ações.

## RN05 – Especialidade Obrigatória no Agendamento
O paciente deve selecionar uma especialidade médica antes de escolher o médico e o horário. Motivo: Facilitar a busca, manter a coerência entre agenda e tipo de atendimento.

## Requisitos Funcionais (RF)

## RF01
O sistema deve permitir que o paciente se cadastre informando nome, CPF, e-mail, telefone e data de nascimento.

## RF02
O sistema deve permitir que o paciente faça login utilizando CPF e senha cadastrados.

## RF03
O sistema deve permitir que o paciente visualize as especialidades médicas disponíveis na clínica.

## RF04
O sistema deve permitir que o paciente selecione um médico e visualize os horários disponíveis para agendamento.

## RF05
O sistema deve permitir que o paciente agende consultas online, escolhendo especialidade, médico, data e horário.

## RF06
O sistema deve permitir que o paciente cancele uma consulta agendada, respeitando as regras de negócio definidas ( até 48h antes).

## RF07 
O sistema deve permitir que o médico visualize sua agenda de consultas em tempo real.

## RF08
O sistema deve enviar notificações automáticas (e-mail ou SMS) de confirmação, alteração ou cancelamento de consultas.

## RF 09 
O sistema deve permitir que o paciente atualize seus dados cadastrais, como endereço, telefone, e-mail e senha.

## RF10
O sistema deve permitir que a recepcionista cadastre e edite informações dos médicos, incluindo especialidade, horários de atendimento e status de disponibilidade.

## Requisitos Não Funcionais (RNF)

## RNF01
O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com uptime mínimo de 99%.

## RNF02
O sistema deve ter tempo de resposta inferior a 3 segundos em todas as operações principais (login, agendamento, consulta de agenda).

## RNF03
O sistema deve garantir segurança e confidencialidade dos dados dos pacientes, conforme a Lei Geral de Proteção de Dados (LGPD).

## RNF04
O sistema deve ser compatível com navegadores modernos (Chrome, Firefox, Edge, Safari) e dispositivos móveis.

## RNF05
A interface do sistema deve ser intuitiva, acessível e responsiva, facilitando o uso por diferentes perfis de usuários.

## RNF06
O sistema deve suportar até 500 acessos simultâneos sem perda perceptível de desempenho.

## RNF07
O sistema deve possuir backup automático diário do banco de dados.

## RNF08
O sistema deve registrar logs de acesso e operações de usuários para fins de auditoria e segurança.

## RNF09
O sistema deve permitir recuperação de senha de forma segura via e-mail cadastrado ou número do celular ( via SMS, enviando link.)

## RNF10
O sistema deve ter layout padronizado e identidade visual da Clínica Saúde+, garantindo coerência com a marca.
