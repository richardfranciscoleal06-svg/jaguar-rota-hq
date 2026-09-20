# Plano — Painel Jaguaré RP

## Resultado
Criar uma aplicação de página única, em português, com identidade tática inspirada na ROTA, área pública, acesso simulado e painel interno operacional e administrativo.

## Estrutura da experiência
- Construir cabeçalho público com Início, História, Hierarquia, Regulamentos e acesso por modal.
- Criar página inicial com apresentação institucional e “ROTA em números”.
- Criar história institucional, tabela pesquisável de hierarquia e leitor de regulamentos.
- Implementar login e solicitação de nova credencial com estados simulados e feedback visual.
- Após o acesso, substituir a navegação pública por um painel interno com menu lateral responsivo.
- Implementar Perfis Táticos, Promoção, Rankings, RSO, Bate-Ponto e Qualificação Operacional.
- Implementar Painel de Comando com cadastros pendentes, validação de RSO e patrulhas ativas; aprovar, rejeitar e encerrar removerá os respectivos itens da tela.

## Direção visual
- Fundo preto e grafite, superfícies metálicas discretas, bordô, dourado envelhecido e verde operacional.
- Tipografia Montserrat, títulos em caixa alta, linhas técnicas, ícones objetivos e hierarquia densa.
- Layout responsivo, com foco em leitura rápida e operação eficiente em desktop e celular.

## Detalhes técnicos
- Estado React local para navegação, autenticação, formulários, cronômetro, abas, contadores, filtros e filas administrativas.
- Componentes reutilizáveis para botões, métricas, tabelas, formulários e navegação.
- Tokens semânticos centralizados no sistema visual; sem persistência real ou servidor externo.
- Metadados próprios da página e verificação final no navegador em desktop e celular.
