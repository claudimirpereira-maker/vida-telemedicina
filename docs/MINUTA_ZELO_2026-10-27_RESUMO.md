> **HISTÓRICO — SUBSTITUÍDO PELA MINUTA V2.** As inconsistências de vencimento dia 20 e tarifa desde 1.999 vidas foram corrigidas no PDF V2 de 27/10/2026. Consulte a documentação vigente: [Minuta Zelo V2 — resumo e pendências](MINUTA_ZELO_V2_2026-10-27_RESUMO.md). Este arquivo permanece apenas para rastreabilidade da revisão anterior.

---

# VIDA — Minuta Zelo Saúde de 27/10/2026 (resumo operacional)

**Fonte:** minuta White Label de 18 páginas, recebida em 27/10/2026.  
**Situação:** documento recebido; assinatura ainda não comprovada.  
**Privacidade:** não reproduzir o PDF integral, CPFs, endereços residenciais nem assinaturas neste repositório público.

## Condições da minuta

| Parâmetro | Conteúdo documentado |
|---|---|
| Fornecedora | Zelo Saúde, white label, PA 24h e especialidades (cláusulas 2 e 5) |
| Setup | R$ 1.500, vencimento 28/10/2026; não reembolsável após disponibilização (3.4; Anexo I) |
| White label | Marca, cores e subdomínio; entrega em até 10 dias após pagamento e envio dos elementos de marca (3.2.2 e 3.5) |
| Mínimo ordinário | 500 vidas, R$ 1.950/mês (3.2.1 e Anexo I) |
| Promoção | R$ 975 em cada um dos 4 primeiros períodos, **somente enquanto houver até 250 vidas ativas** (Anexo I) |
| Gatilho da promoção | Ao superar 250 vidas em qualquer dos 4 primeiros períodos, aplica-se mínimo ordinário de **R$ 1.950** (Anexo I) |
| Desde o 5º período | Mínimo ordinário de R$ 1.950 (Anexo I) |
| Tarifa-base | R$ 3,90 por vida; R$ 3,60 de escala, com divergência de faixa no Anexo I |
| Especialidades | 1% da base total ativa; acesso somente com encaminhamento por médico da plataforma (5.2–5.3) |
| Excedentes | Sujeitos a tabela não juntada à minuta; valores e período de apuração pendentes (5.3.1) |
| Fidelidade | 12 meses, renovação e pré-aviso de 60 dias; esclarecer cláusulas 9.1, 9.2 e 9.5 |
| Reajuste | IPCA anual; revisão extraordinária negociável se IPCA acumulado superar 10% (3.6) |
| SLA | 99% disponibilidade; créditos em condições específicas, contorno 12h e mitigação/restabelecimento 48h se aplicáveis (7.4–7.5) |
| Inadimplência | Suspensão após atraso superior a 5 dias; possível rescisão e multa de 2 mensalidades se superior a 30 dias (8) |
| Não concorrência | Limitação para mesmo cliente durante a vigência; multa de 3 meses do faturamento médio (10.2) |
| Alteração para CNPJ | Aditivo contratual previsto após regularização da pessoa jurídica (Anexo I) |

## Cronograma expresso no Anexo I

- 28/10/2026: setup R$ 1.500.
- 08/12/2026, 08/01/2027, 08/02/2027, 08/03/2027: cada período com mínimo promocional R$ 975 **somente para até 250 vidas**.
- 08/04/2027 e meses subsequentes: mínimo ordinário R$ 1.950.
- Se houver 251–499 vidas em algum mês promocional, não calcular apenas vidas × R$ 3,90; a regra documental exige **mínimo ordinário R$ 1.950**.

## Divergências a corrigir antes da assinatura

1. **Faixa de preço contraditória:** Anexo I, p. 17, informa R$ 3,90 para 250–3.000 vidas e R$ 3,60 a partir de 1.999 vidas, faixas que se sobrepõem. O simulador mantém a negociação de R$ 3,60 desde 3.001 vidas **como premissa pendente de retificação expressa**.
2. **Vencimentos contraditórios:** Anexo I, p. 16, menciona dia 20 do mês subsequente, mas também dia 08 e um calendário expresso de pagamentos. O simulador exibe dia 08, com ressalva.
3. **Sem tabela de excedentes:** faltam valor por consulta, definição de unidade de uso de 1% e período de apuração.
4. **Descrição do produto:** tabela da cláusula 3.1 descreve PA 24h, enquanto a cláusula 5 inclui especialidades; confirmar que estão dentro da mesma tarifa.
5. **Rescisão:** esclarecer a fidelidade de 12 meses e o aviso de 60 dias, inclusive em distrato.
6. **App nativo:** a minuta garante subdomínio com personalização visual, não aplicativo próprio nativo.
7. **Qualificação:** a minuta prevê substituição futura de pessoa física pelo CNPJ regularizado.
8. **Assinatura:** ainda não comprovada.

## Registro de implementação no dashboard VIDA 1.2.0

- Nova seção de resumo contratual: Minuta Zelo.
- Regra de cobrança corrigida para gatilho de 250 vidas nos quatro primeiros períodos.
- Minuta original não publicada no GitHub por conter dados pessoais; cópia deve permanecer em ambiente privado.
- Valores de excedentes de especialidade não projetados por falta de documentação.
- Migração automática das preferências locais das versões 1.0/1.1 preserva dados comerciais e realizados quando existentes.

Este arquivo é um resumo gerencial e não substitui assessoria jurídica.
