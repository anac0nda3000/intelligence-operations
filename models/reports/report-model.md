# [Título do Relatório]
[Nome da campanha, amostra, incidente ou investigação] – [Data]

# 1. Objetivo
[Explique em 1–2 frases o que o relatório analisa.]
Ex.: Este relatório apresenta uma análise inicial de uma amostra de malware distribuída por meio de e-mails de phishing direcionados ao setor financeiro.

# 2. Contexto
[Descreva rapidamente o cenário que motivou a análise.]
Ex.: Nos últimos dias, observou-se aumento no envio de e-mails contendo anexos .doc com macros maliciosas. Amostras similares foram reportadas por [fonte pública], indicando possível campanha coordenada.

# 3. Sumário dos Principais Achados
- [Achado 1]
- [Achado 2]
- [Achado 3]
- [Impacto potencial resumido]

# 4. Evidências e Detalhes Técnicos

## 4.1 Indicadores (IOCs)
**Hashes:**
- MD5:
- SHA256:

**Endereços IP/Domínios:**
- IP:
- Domínio:
- URL:

## 4.2 Táticas, Técnicas e Procedimentos (MITRE ATT&CK)
- **Tática:** [Ex. Initial Access]
- **Técnica:** [Ex. T1566.001 – Spearphishing Attachment]
- **Descrição curta:** [Explique em 1 frase como essa técnica aparece na campanha.]

## 4.3 Comportamento Observado
[Descreva em parágrafos curtos ou bullets.]
Ex.:
- O arquivo contém macro VBA que baixa um payload hospedado em domínio comprometido.
- O malware estabelece persistência via chave Run no registro.
- Comunicação C2 via HTTP para /update.php.

## 4.4 Análise Complementar (opcional)
[Inclua qualquer outra evidência relevante: timeline, fl]()
