
Projeto: Jogo Cyberpunk (Interface de Linha de Comando - CMD)


#Objetivo: Desenvolver um jogo no estilo Cyberpunk com mecânicas básicas e ambientação textual, rodando exclusivamente no CMD.
Investimento Inicial: Zero (utilização de ferramentas e plataformas gratuitas)
Banco de Dados: Relacional (MySQL
Linguagem: Python ou C
Interface Gráfica: Nenhuma (tudo será executado via linha de comando)
Metodologia: Scrum com Sprints semanais

#Etapas do Projeto
1. Planejamento Inicial
Visão do Jogo:
Estilo: Cyberpunk (mundo distópico, alta tecnologia, decadência social).
Personagens: Humanos, ciborgues, hackers (tudo em texto, com segurança).
Mecânica: Jogo baseado em narrativa e decisões, com desafios de hacking, exploração e combate.
Plataforma: Desktop, via CMD (Windows, Linux).
Ferramentas Gratuitas:
Editor de Código: Visual Studio Code (Python) ou Code::Blocks (C)
Banco de Dados: MySQL/PostgreSQL (hospedagem local)
Controle de versão: Git (GitHub ou GitLab)
Documentação: Google Docs ou Notion
Bibliotecas:
Python: sqlite3(opção alternativa para BD local), os, syspara interações com o sistema.
C: Bibliotecas padrão de C para interações com arquivos e banco de dados.
2. Requisitos
Funcionais:
Sistema de narrativa interativa com decisões de diálogo.
Sistema de inventário e itens (gerenciado via texto).
Combate por turnos (texto baseado, com uso de armas e habilidades).
Interação com NPCs para completar missões.
Sistema de hacking com quebra-cabeças lógicos ou minijogos de texto.
Não-funcionais:
Código leve e rápido.
Otimização de desempenho para rodar em qualquer sistema com CMD.
Persistência de dados no banco de dados relacional.

Sprints Semanais

#Sprint 1: Estudo e Setup Inicial

Objetivo: Configurar o ambiente de desenvolvimento e escolher as ferramentas definitivas.
Tarefas:
Estudar a documentação do MySQL/PostgreSQL.
Crie um repositório Git para controle de versão.
Defina uma estrutura básica do jogo (menu, personagens, narrativa inicial).
Configurar o banco de dados relacional e definir as tabelas de usuários, personagens, inventário e progresso.

#Sprint 2: Sistema de Personagens e Inventário

Objetivo: Implementar o sistema de caracteres jogáveis ​​e inventário.
Tarefas:
Criar um sistema de criação de personagens com diversidade textual (ex: escolha de raça, profissão).
Desenvolva a mecânica de inventário: adicionar, remover e exibir itens.
Persistir o estado do inventário no banco de dados.
Enviar alterações no Git.

#Sprint 3: Sistema de Combate por Turnos

Objetivo: Desenvolver o sistema de combate por turnos baseado em texto.
Tarefas:
Implementar sistema de combate simples (escolher ataques, defesa, fugir).
sistema de pontos de vida e adição de barra de energia.
Exibir feedback em texto (ex: "Você derrotou o inimigo. Ele perdeu 10 pontos de vida").
Conecte o sistema ao banco de dados para salvar progresso e status.

#Sprint 4: Diálogos e Missões com NPCs

Objetivo: Desenvolver o sistema de interação com NPCs e missões.
Tarefas:
Crie um sistema de diálogos com diversas escolhas (texto).
Implementar missões básicas (ex: coleta de itens, derrota inimigos).
Armazenar o progresso de missões e interações no banco de dados.

#Sprint 5: Sistema de Hacking e MiniJogos

Objetivo: Criar um sistema de hacking baseado em texto e desafios lógicos.
Tarefas:
Implementar mini-jogos de hacking (quebra-cabeças de senha, matemática, lógica simples).
Crie uma mecânica de progressão de habilidade de hacking (ex: níveis de dificuldade).
Integre o sistema com o banco de dados para salvar o progresso de hacks.
Sprint 6: Testes e Correções de Bugs

Objetivo: Testar a estabilidade do jogo e corrigir bugs.
Tarefas:
Testar todas as mecânicas renovadas (combate, diálogos, missões, hacking).
Corrigir bugs encontrados durante os testes.
descoberto o código para rodar de forma fluida no CMD.

#Sprint 7: Interface de Texto e Polimento Final

Objetivo: Finalizar a interface de linha de comando com exibição clara e fluida.
Tarefas:
Polir a exibição de texto (organização, clareza de escolhas e feedback).
Adicione efeitos simples de animação via texto (ex: “...” para criar suspense).
Teste a usabilidade geral do jogo.
Banco de Dados
Tabelas propostas:

Usuários: Armazenar informações de progresso do jogador.
Personagens: Dados do personagem jogável e NPCs (atributos, habilidades, status).
Inventário: Tabela para gerenciamento de itens coletados ou usados ​​pelo jogador.
Missões: Status de missões (completas, pendentes).
Controle de Qualidade
Testes Automáticos: Usar bibliotecas de testes unitários como unittestem Python ou um framework de testes para C.
Testes de usuário: Realize testes com amigos e colegas para ajustar a experiência e detectar bugs.
Entrega e Iterações Futuras
Versão 1.0: Entrega do jogo com as mecânicas básicas (combate, NPCs, missões, habilidades, hacking).
Futuras Iterações: Expansão do conteúdo (mais missões, NPCs, desafios de hacking complexos).
