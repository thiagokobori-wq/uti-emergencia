UTI & EMERGÊNCIA — PROTÓTIPO V1

Como abrir:
1. Extraia o ZIP.
2. Abra index.html em navegador moderno para testar as funções.
3. Para testar instalação PWA/offline, sirva a pasta por HTTPS ou localhost (ex.: servidor local simples) e use "Instalar aplicativo" no navegador.

O que está incluído:
- Censo demonstrativo com edição e evolução ventilatória.
- Biblioteca de medicamentos e diluições transcritas do PDF enviado.
- Cálculo de vazão mínima/máxima quando a faixa consta no documento e dose na vazão atual.
- Calculadora ventilatória com peso predito ARDSNet, VT por PBW, driving pressure, complacência, resistência, auto-PEEP estimada e relações P/F e S/F.

LIMITAÇÕES CRÍTICAS:
- Protótipo local: sem autenticação, backend, sincronização, criptografia, controle de acesso ou trilha de auditoria.
- Dados de censo ficam no armazenamento local do navegador. NÃO inserir dados reais, identificáveis ou sensíveis de pacientes.
- Não é software médico validado e não deve orientar prescrição/administração sem validação clínica e farmacêutica institucional.
- As doses e diluições são transcritas do PDF "JUNTOS MEDICAÇÕES"; campos ausentes ou incompletos foram sinalizados. Confirmar apresentações, volumes finais e concentrações na instituição.
- Algumas apresentações/concentrações do documento podem exigir reconciliação antes de uso (ex.: remifentanila sem concentração da ampola; concentrações finais aproximadas descritas no documento).
- A calculadora ventilatória não diagnostica SDRA automaticamente e não substitui interpretação clínica. Complacência estática depende de medidas adequadas em paciente passivo. Auto-PEEP requer mensuração apropriada (pausa expiratória).

PRÓXIMA ETAPA PARA PRODUÇÃO:
Backend seguro, autenticação individual, papéis de acesso, banco de dados, criptografia, auditoria, backup, política LGPD, validação farmacêutica/médica, testes unitários e validação de usabilidade.
