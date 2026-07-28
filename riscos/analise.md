análise estruturada dos riscos previamente identificados, seguida de uma matriz qualitativa de probabilidade vs. impacto:

---

## 1. Análise estruturada dos riscos

### Risco 1: Instabilidade na integração com o sistema de prontuário  
- **Descrição:** A API externa apresenta documentação insuficiente e mudanças frequentes, causando falhas na integração.  
- **Possíveis impactos no projeto:** Atrasos no cronograma, retrabalho da equipe, comprometimento da entrega final (funcionalidade crítica).  
- **Fatores que influenciam a ocorrência:** Dependência de fornecedor externo, falta de documentação clara, mudanças não comunicadas.  
- **Probabilidade:** Alta  
- **Impacto:** Alto  
- **Justificativa:** A integração é crítica e já apresenta instabilidades; o impacto direto compromete o valor do produto.  

---

### Risco 2: Alterações frequentes nos requisitos de agendamento  
- **Descrição:** Stakeholders solicitam mudanças no fluxo de agendamento, incluindo novas regras de negócio.  
- **Possíveis impactos no projeto:** Aumento de esforço, atrasos, escopo instável, risco de falhas por mudanças constantes.  
- **Fatores que influenciam a ocorrência:** Requisitos em evolução, falta de congelamento de escopo, pressão dos stakeholders.  
- **Probabilidade:** Alta  
- **Impacto:** Médio  
- **Justificativa:** Mudanças são recorrentes, mas podem ser gerenciadas com processos de controle; impacto é relevante, mas não crítico como a integração.  

---

### Risco 3: Sobrecarga da equipe de desenvolvimento  
- **Descrição:** Equipe pequena (4 devs e 1 tester) enfrenta dificuldades para cumprir prazos devido ao aumento da carga de trabalho.  
- **Possíveis impactos no projeto:** Atrasos, queda na qualidade, aumento de erros e retrabalho.  
- **Fatores que influenciam a ocorrência:** Escopo crescente, prazos apertados, recursos limitados.  
- **Probabilidade:** Média  
- **Impacto:** Alto  
- **Justificativa:** A sobrecarga já foi relatada; impacto pode ser significativo na qualidade e prazo, mas há alternativas de mitigação (replanejamento ou reforço da equipe).  

---

### Risco 4: Comunicação e coordenação em equipe distribuída  
- **Descrição:** A distribuição da equipe pode gerar falhas de comunicação e desalinhamento de prioridades.  
- **Possíveis impactos no projeto:** Retrabalho, atrasos em entregas, perda de alinhamento entre módulos.  
- **Fatores que influenciam a ocorrência:** Distância física, dependência de ferramentas de comunicação, necessidade de coordenação frequente.  
- **Probabilidade:** Média  
- **Impacto:** Médio  
- **Justificativa:** Equipes distribuídas frequentemente enfrentam esse desafio; impacto é relevante, mas pode ser mitigado com práticas ágeis e ferramentas adequadas.  

---

### Risco 5: Impacto na qualidade devido a prazos apertados  
- **Descrição:** Pressão para cumprir cronogramas pode levar a redução de testes ou implementação apressada.  
- **Possíveis impactos no projeto:** Defeitos em produção, baixa satisfação dos usuários, retrabalho pós-entrega.  
- **Fatores que influenciam a ocorrência:** Cronograma agressivo, sobrecarga da equipe, mudanças de requisitos.  
- **Probabilidade:** Média  
- **Impacto:** Alto  
- **Justificativa:** A pressão por prazos já foi relatada; impacto direto na qualidade é crítico, especialmente em software de saúde.  

---

### Risco 6: Dependência crítica de sistema externo  
- **Descrição:** O funcionamento do aplicativo depende diretamente da integração com o prontuário eletrônico.  
- **Possíveis impactos no projeto:** Produto sem valor caso a integração falhe; atraso ou inviabilidade da entrega.  
- **Fatores que influenciam a ocorrência:** Dependência de terceiros, falta de controle sobre mudanças externas.  
- **Probabilidade:** Alta  
- **Impacto:** Alto  
- **Justificativa:** Risco estrutural do projeto; sem integração, o produto não atende ao objetivo principal.  

---

## 2. Matriz Qualitativa de Riscos

| Probabilidade \ Impacto | Baixo | Médio | Alto |
| ------------------------ | ----- | ----- | ---- |
| **Alta**                 |       | Alterações de requisitos | Instabilidade na integração; Dependência crítica |
| **Média**                |       | Comunicação em equipe distribuída | Sobrecarga da equipe; Impacto na qualidade |
| **Baixa**                |       |       |      |

---

## Observações gerais
- A classificação é qualitativa e baseada apenas nas informações fornecidas; pode variar com dados adicionais.  
- A integração externa e a dependência crítica são os riscos mais graves, exigindo atenção prioritária.  
- Alterações de requisitos e sobrecarga da equipe são riscos relevantes, mas com maior possibilidade de mitigação.  
- Comunicação distribuída e prazos apertados impactam coordenação e qualidade, exigindo práticas de gestão adequadas.  

