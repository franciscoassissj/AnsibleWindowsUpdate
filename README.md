### Projeto Atualizações Windows Server via Ansible.

Projeto destinado a agilizar o processo de atualização dos Servidores Windows Server.

Vamos ser sinceros, para nós, Administradores de Servidores Microsoft, as atualizações são críticas para a administração de rotina do Windows Server. Mesmo com tudo ocorrendo de forma tranquila, principalmente nos ambientes de Desenvolvimento e Homologação, fica aquela tensão quando vamos para o de Produção, sempre.☹️

O tempo é um dos gargalos no procedimento, pois quem faz isso de forma manual, mesmo tendo um WSUS devidamente configurado fazendo parte da Infraestrutura, acessar o servidor, atualizar e agendar o restart para um horário adequado e depois verificar se o KB específico foi instalado com sucesso, demanda umas horas na tarefa.

Com o Ansible, no primeiro momento, pretendemos automatizar o procedimento de instalar as atualizações e agendar o restart dos servidores para as 06:00 da manhã.