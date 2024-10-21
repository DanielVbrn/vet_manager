
## Membros da Equipe
- **Daniel Vitor**
- **Lays Emanuelly**
- **Gabriel Silva**
- **Alexandro**


# Sistema de Gestão para Clínicas Veterinárias

Sistema web para facilitar o gerenciamento completo de uma clínica veterinária, oferecendo funcionalidades que ajudam no agendamento de consultas, controle do histórico médico dos animais e gerenciamento do estoque de medicamentos.


## Link de Acesso ao documento
### [Documento referente ao sistema](https://docs.google.com/document/d/1b9vYRi0DKIG2BCphYtzIrefsfd6hIAjXGl3MwSpvkFs/edit?usp=sharing)

## Funcionalidades Principais

### 1. Agendamento de Consultas
Permite que os tutores dos animais agendem consultas de forma online, escolhendo data, horário e o veterinário disponível. O sistema gera lembretes automáticos por e-mail ou SMS para evitar ausências, e a clínica pode facilmente gerenciar e visualizar os horários disponíveis.

- **Regras de Negócio**:
  - Apenas horários disponíveis são mostrados para agendamento.
  - Cancelamentos ou reagendamentos podem ser feitos com antecedência mínima (ex.: 24 horas).
  - Notificações automáticas são enviadas aos tutores antes das consultas.

### 2. Prontuário Médico Eletrônico
Cada animal cadastrado possui um prontuário médico digital, atualizado a cada consulta. O prontuário inclui diagnósticos, tratamentos, vacinas aplicadas e exames realizados, oferecendo fácil acesso ao histórico completo do paciente para o veterinário e o tutor.

- **Regras de Negócio**:
  - Cada animal possui um prontuário único e seguro, acessível apenas por veterinários autorizados.
  - O prontuário é atualizado após cada atendimento, contendo informações detalhadas sobre diagnósticos e tratamentos.

### 3. Gerenciamento de Medicamentos e Estoque
A clínica pode controlar o estoque de medicamentos e insumos utilizados. Cada receita emitida pelo veterinário reduz automaticamente o estoque correspondente, e o sistema gera alertas quando os níveis de estoque estiverem baixos, facilitando o gerenciamento de reposições.

- **Regras de Negócio**:
  - Medicamentos são vinculados às receitas, e seu estoque é atualizado automaticamente.
  - Alertas de reposição são emitidos quando o estoque atinge um valor mínimo.
  - Apenas veterinários autorizados podem prescrever medicamentos.

## Tecnologias Utilizadas

- **Frontend**: React.js ou Vue.js para uma interface amigável e intuitiva.
- **Backend**: Node.js com Express ou Laravel para lidar com a lógica de negócios e comunicação com o banco de dados.
- **Banco de Dados**: PostgreSQL ou MySQL para armazenar dados de pacientes, tutores e consultas.
- **Autenticação**: JWT (JSON Web Token) para autenticação segura de usuários.
- **Notificações**: Integração com APIs de envio de e-mails ou SMS para notificações automáticas.


