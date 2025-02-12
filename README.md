Descrição do Site HairDay
=
O site HairDay é uma plataforma de agendamento online para um salão de corte de cabelo, desenvolvida com HTML, CSS, e JavaScript. A integração com uma API permite buscar e renderizar os agendamentos existentes, atualizando a lista em tempo real.

Funcionalidades Principais
=
Seleção de Data e Horário: Os clientes podem escolher a data e o horário desejados para o atendimento. O salão oferece horários flexíveis, das 9h da manhã até as 21h da noite.

Informação do Cliente: Ao criar um agendamento, é necessário informar a data,turno manhã,tarde ou noite,horario disponivel e o nome do cliente.

Listagem dos Agendamentos: Após clicar em "Agendar", o nome do cliente, data e horário ficam listados na página, cada item inclui um campo para deletar o agendamento.

Mensagens Personalizadas: Uma mensagem é exibida após cada ação realizada (agendar ou cancelar).

Integração com API
=
A aplicação se conecta à uma API para:

Buscar todos os agendamentos existentes;

Renderizar esses agendamentos na página inicial;

Bloquear automaticamente os horários já reservados;

Atualizar a lista sempre que um novo agendamento for criado ou removido.

Tecnologias Utilizadas
=
Para desenvolver essa aplicação web dinâmica:

HTML - Estrutura básica da página.

CSS - Estilização visual.

JavaScript - Lógica interativa (envio/recebimento de dados via API).

Webpack Server: Ferramenta utilizada para monitorar alterações no código durante o desenvolvimento.

Execução do Projeto
=
Para iniciar a aplicação localmente:

Instalar dependências necessárias via npm (npm install).

Iniciar servidor local usando Webpack (npm run start).
