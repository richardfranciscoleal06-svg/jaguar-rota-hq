# Rota Ops Dashboard

Atue como um Desenvolvedor Front-end Sênior especialista em React, Tailwind CSS e UI/UX. Preciso que você crie uma aplicação web completa (Single Page Application) para um painel administrativo e operacional de um servidor de Roleplay (RP) chamado "Jaguaré RP". 

O tema do painel deve ser estritamente baseado na "ROTA" (Rondas Ostensivas Tobias de Aguiar) da PMESP. 

A paleta de cores deve ser tática e escura (Dark Mode): fundos pretos e cinza escuro, com detalhes em cinza claro, branco e toques de bordô/vermelho escuro e dourado (cores tradicionais da ROTA). A fonte deve ser limpa, moderna e com aspecto militar (ex: Roboto, Inter ou Montserrat).

O sistema deve ter uma Área Pública (Landing Page), um Sistema de Login e uma Área Restrita (Painel Interno divido entre Operacional e Administrativo). Use gerenciamento de estado do React para simular toda a lógica de navegação, abas e autenticação.

Crie a seguinte estrutura e funcionalidades:

### 1. NAVEGAÇÃO SUPERIOR (HEADER)

- Logo (placeholder) e texto "1º Batalhão de Choque - ROTA | Jaguaré RP".

- Links da Área Pública: Início, História, Hierarquia, Regulamentos.

- Botão de destaque: "LOGIN" (que abre a tela de autenticação).

### 2. ÁREA PÚBLICA (PÁGINAS ABERTAS)

- **Início (Home):** Dashboard "ROTA EM NÚMEROS" com cards estatísticos e ícones (Drogas, Armamentos, Munições, Bombas, Dinheiro Marcado).

- **Hierarquia:** Tabela de membros dividida por patentes com barra de pesquisa. Colunas: Nome Completo, ID no Jogo, Discord ID, Patente e Função.

- **Regulamentos:** Interface simulando um leitor de documentos, com um menu lateral esquerdo e a área de leitura no centro.

### 3. SISTEMA DE LOGIN E AUTENTICAÇÃO

- Modal centralizado pedindo "ID Operacional" e "Senha".

- Botão "Validar Acesso" que altera o estado da aplicação e libera o menu interno.

- Link "Nova Credencial" que abre um formulário de registro (Nome, Sobrenome, RG Discord, ID Militar, Senha).

### 4. ÁREA RESTRITA - OPERACIONAL (PAINEL INTERNO)

O menu público desaparece e dá lugar a uma Sidebar ou Header interno com:

- **Perfis Táticos:** Lista de operadores com foto, nome, patente e status "ATIVO".

- **Solicitação de Promoção:** Formulário onde o policial vê a patente atual e cola o link do seu relatório para pedir promoção.

- **Central de Rankings:** Abas de "Horas de Patrulha" e "Apreensões R$". Tabela estilo Leaderboard (Top 1, Top 2...).

- **Relatório de Serviço (RSO):** Formulário tático para fim de patrulha. Deve ter: Seleção da Viatura, Composição da Barca (ID do Chefe, Motorista, Auxiliar), Contadores numéricos (+ e -) para Ocorrências, Detidos, Armamento, Drogas, etc., e botão verde "Transmitir RSO".

- **Bate-Ponto:** Terminal mostrando a viatura selecionada, um cronômetro 00:00:00 e o botão "Iniciar Patrulha" (que muda para "Finalizar" ao clicar).

- **Qualificação Operacional:** Painel de avaliação com seletor de "ID do Avaliado" e sliders de 0 a 5.0 (Postura, Disciplina, Atenção, etc.). Exibe a média ponderada final.

### 5. ÁREA DE COMANDO / ADMINISTRATIVA (Acesso Restrito)

Crie uma aba no menu interno chamada "Painel de Comando" com um visual que indique alto privilégio de acesso. Esta área deve conter um submenu com três abas:

- **Gestão de Cadastros (Nova Credencial):** Tabela listando os formulários de registro pendentes. Colunas: Nome, ID Militar, Discord e botões de ação: um botão verde "Aprovar Recruta" e um botão vermelho "Negar".

- **Validação de RSO (Caixa de Entrada):** Uma fila de aprovação com os Relatórios de Serviço enviados pelos policiais. Cada card de relatório deve mostrar quem enviou, a barca, os itens apreendidos e o resumo da ocorrência. Deve conter dois botões: "Validar RSO" (simulando a adição de pontos no ranking) e "Rejeitar/Invalidar".

- **Controle de Patrulhas (Bate-Ponto Ativo):** Um painel em tempo real listando quem está patrulhando no momento. Mostra a viatura, os IDs logados, o tempo de patrulha correndo e um botão de alerta "Forçar Encerramento de Turno" para derrubar a patrulha remotamente.

Construa todos os componentes, priorize um design limpo e de alta qualidade e garanta que os botões do Administrativo alterem o estado visual (ex: ao aprovar um cadastro, ele some da lista; ao rejeitar um RSO, ele é removido da fila).

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/f94a1368-1a49-4967-9903-76b173d2a2d7).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
