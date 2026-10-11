# DocShield Forensic Vaccine Feed 🛡️

Repositório público oficial de distribuição e atualização de assinaturas forenses para o ecossistema **DocShield**.

## Visão Geral
Este repositório atua como o feed seguro e público de regras de detecção contra:
- **Indirect Prompt Injection** (comandos imperativos e triggers de manipulação de IA);
- **Camuflagem por Cor** (fontes brancas sobre fundo branco);
- **Microtexto** (tamanho inferior a 2.5pt);
- **Texto Off-screen** (conteúdo posicionado fora das margens visíveis da folha);
- **Oclusão Estrutural** (comandos sobrepostos por formas sólidas e caixas brancas);
- **Zero-Width Characters & Steganography** (Unicode invisível).

## Estrutura do Feed
- `signatures_manifest.json`: Versão da vacina, quantidade de regras ativas e data de publicação.
- `default_probes.json`: Dicionário estruturado de padrões forenses e heurísticas validadas.

## Uso no DocShield
O DocShield consulta este repositório **estritamente sob demanda** quando o usuário clica em `Ferramentas > Checar Atualização Online`. Nenhuma conexão em segundo plano é executada automaticamente.

---
*Mantido por Linker · DocShield Security Lab*
