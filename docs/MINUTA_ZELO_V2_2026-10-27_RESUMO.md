# VIDA — Zelo Saúde · Minuta White Label V2

**Documento-base:** Minuta V2, datada de 27/10/2026, 18 páginas.  
**Conferência:** confronto textual página a página com a minuta anterior (18 páginas); apenas duas linhas alteradas: uma na página 16 e uma na página 17.  
**Situação:** minuta V2 recebida. Este registro **não atesta assinatura**.  
**Privacidade:** dados pessoais, endereços e assinaturas não são reproduzidos no GitHub público.

## Correções confirmadas

| Item | Antes (V1) | Agora (V2) | Status |
|---|---|---|---|
| Vencimento na regra geral de faturamento, Anexo I p.16 | dia 20 do mês subsequente | **dia 08 do mês subsequente**, correspondente ao cronograma mensal | Corrigido |
| Limiar da tarifa de escala, Anexo I p.17 | R$ 3,60 a partir de 1.999 vidas (sobreposição) | **R$ 3,60 a partir de 3.001 vidas** | Corrigido |

Todo o restante do conteúdo textual da minuta V2 corresponde à minuta anterior, inclusive a redação de fidelidade, não concorrência, plataforma white label e cláusulas assistenciais. A diferença de número de bytes entre PDFs não implica terceira mudança textual.

## Condições comerciais vigentes na minuta V2

- **Fornecedora selecionada:** Zelo Saúde, PA 24h, telemedicina white label e especialidades conforme cláusulas 2 e 5.
- **Setup:** R$ 1.500, vencimento previsto para 28/10/2026 (Anexo I).
- **Tarifa-base:** R$ 3,90/vida/mês de 250 a 3.000 vidas; **R$ 3,60/vida/mês a partir de 3.001 vidas** (Anexo I, p.17).
- **Mínimo ordinário:** 500 vidas, R$ 1.950/mês (3.2 e Anexo I).
- **Promoção de entrada:** primeiro ao quarto período com mínimo de 250 vidas, R$ 975/mês **somente até 250 vidas ativas**. Se a base superar 250 durante a promoção, passa a valer o mínimo ordinário de 500 vidas (Anexo I). O quarto período vence 08/03/2027.
- **Quinto período e posteriores:** mínimo ordinário de R$ 1.950, iniciando em 08/04/2027.
- **Vencimento:** dia **08** do mês subsequente, conforme texto geral e cronograma expresso da V2 (Anexo I). Cronograma expresso: 08/12/2026, 08/01/2027, 08/02/2027, 08/03/2027 e de 08/04/2027 em diante.
- **Especialidades:** até 1% da base total de vidas ativas, condicionadas a encaminhamento por médico da plataforma. Excedentes podem gerar cobranças adicionais conforme tabela que não acompanha o documento (5.2 e 5.3).
- **Prazo da plataforma personalizada:** até 10 dias após pagamento do setup e envio dos elementos de identidade visual; entrega inclui ambiente de marca, cor e subdomínio próprio na plataforma da fornecedora. Aplicativo nativo próprio não está expressamente prometido (3.2.2 e 3.5).
- **Operação comercial:** início em até 30 dias após disponibilização (6.1), mesmo que isso não interrompa a cobrança mínima.
- **Fidelidade:** 12 meses, renovação, aviso prévio de 60 dias, com redações potencialmente sensíveis sobre rescisão e distrato (9).
- **Inadimplência:** possibilidade de suspensão após atraso superior a 5 dias e multa contratual associada a rescisão por atraso superior a 30 dias (8).
- **Não concorrência:** durante a vigência para mesmo cliente/ente atendido, com multa prevista (10.2).
- **Reajuste:** IPCA anual, com possibilidade de revisão antecipada negociada se IPCA acumulado superar 10% (3.6 e Anexo I).
- **SLA:** disponibilidade mínima de 99% ao mês e regras de compensação, mitigação e comunicação de incidentes (7.4 e 7.5).
- **Qualificação futura:** substituição de pessoa física por pessoa jurídica após regularização de CNPJ, via alteração contratual (Anexo I).

## Obrigações que permanecem abertas

1. **Comprovar assinatura final.** O PDF entregue contém texto de campos e identificação de partes, mas não foi demonstrado instrumento formalmente assinado.
2. **Obter tabela de excedentes de especialidades**, com preço, unidade de contagem, período de apuração, autorização/aviso e limites.
3. **Revisar cláusulas 9.1–9.5:** compatibilizar fidelidade de 12 meses e possibilidade de rescisão mediante 60 dias, inclusive em distrato.
4. **Esclarecer a grade assistencial faturada:** cláusula comercial 3.1 menciona PA 24h; cláusula 5 descreve PA 24h mais especialidades/teleorientações. Recomenda-se confirmação de escopo de preço.
5. **Aguardar regularização do CNPJ** e formalizar alteração do contratante conforme Anexo I.
6. **Validar aplicativo nativo se for necessário ao produto VIDA:** white label definido na minuta é ambiente web personalizado, não app próprio.

## Atualização técnica do projeto

- Dashboard VIDA **1.3.0** (GitHub branch `main`) passa a referenciar **Minuta V2** e exibir as correções como resolvidas.
- A lógica financeira de 250/500 vidas e tarifa a partir de 3.001 **permanece inalterada**, pois já correspondia às condições negociadas e agora ficou alinhada ao texto corrigido.
- Migração de `localStorage` da versão 1.2 para a 1.3, preservando parâmetros comerciais, metas, realizados e histórico.
- Nenhum PDF contendo informações pessoais foi disponibilizado no site ou GitHub público.

Documento gerencial de apoio, não substitui parecer jurídico.
