# ResultadosDigitosLotofacil

Principais Adaptações:
1. Cores da Lotofácil:
Roxo primário: #672666 (como você especificou)
Roxo secundário: #4a1c49
Modo escuro: #8b3589
2. APIs da Lotofácil:
API principal: https://servicebus2.caixa.gov.br/portaldeloterias/api/lotofacil
API por concurso: https://servicebus2.caixa.gov.br/portaldeloterias/api/lotofacil/{numero}
API completa: https://loteriascaixa-api.herokuapp.com/api/lotofacil
3. Funcionalidades Específicas:
⚡ Sistema de cache inteligente para carregamento ultra-rápido
📊 Análise de dígitos únicos dos 15 números sorteados da Lotofácil
🔍 Filtros avançados por quantidade de dígitos, dígito específico, range de concursos
📈 Análise de frequência e intervalos entre aparições
📋 Resumo automático com estratégias de aposta baseadas nos dados
💾 Downloads em XLS, HTML e TXT
🌙 Tema escuro/claro automático
🔄 Atualização automática a cada 5 minutos
🚫 Modais customizados (sem uso de alert/confirm/prompt)
4. Valores de Referência:
Concurso padrão: 3461 (baseado no JSON fornecido)
Estrutura: Análise dos dígitos únicos presentes nos 15 números sorteados
5. Adaptações para Lotofácil:
15 números sorteados (mais que Quina e Dia de Sorte)
Intervalo médio menor (28 concursos) devido à maior frequência
Mais dígitos únicos por sorteio em média
Estratégias específicas para a natureza da Lotofácil
6. Performance:
Carregamento otimizado com cache
Busca apenas concursos novos quando possível
Fallback para API completa se necessário
Indicadores visuais de progresso
Modais customizados sem dependência de funções nativas do navegador
A aplicação está pronta para uso e analisará automaticamente os dígitos únicos presentes nos sorteios da Lotofácil, mantendo o esquema de cores roxo característico desta modalidade! 💜🎰

Diferencial: Esta versão usa modais customizados em vez de alert(), confirm() e prompt(), garantindo compatibilidade total com o ambiente iframe sandboxed do Poe.