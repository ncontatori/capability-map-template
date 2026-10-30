# Roadmap de capacidades (exemplo fictício)

Iniciativas derivadas do heatmap e da classificação TIME do [portfólio](application-portfolio.csv).

```mermaid
gantt
    title Roadmap 2027 — capacidades prioritárias
    dateFormat  YYYY-MM-DD
    axisFormat  %b/%y
    section Relacionamento e atendimento
    Atendimento omnichannel no ITSM (APP-005)   :a1, 2027-01-01, 120d
    Desativar Help Desk Antigo (APP-009)        :a2, after a1, 45d
    section Captação e matrícula
    Regras de bolsas no CRM (APP-001)           :b1, 2027-02-01, 90d
    Eliminar planilhas de bolsas (APP-007)      :b2, after b1, 30d
    section Experiência acadêmica
    Discovery do sistema acadêmico (APP-003)    :c1, 2027-03-01, 60d
    Migração por domínio — fase 1               :c2, after c1, 180d
    section Dados e inteligência
    Modelo de dados do aluno 360 (APP-006)      :d1, 2027-01-15, 150d
```

## Iniciativas

| Iniciativa | Capacidade | Aplicações | Resultado esperado | ADR |
|---|---|---|---|---|
| Atendimento omnichannel | Relacionamento e atendimento | APP-005, APP-009 | −1 sistema; visão única de solicitações | a criar |
| Regras de bolsas no CRM | Precificação e bolsas | APP-001, APP-007 | Fim das planilhas; trilha de auditoria | a criar |
| Modernização acadêmica | Gestão de cursos e avaliação | APP-003 | Redução de acoplamento e risco de obsolescência | a criar |
| Aluno 360 | Plataforma de dados | APP-006 | Indicadores de retenção confiáveis | a criar |

Cada iniciativa relevante deve gerar um ADR — veja [architecture-decision-records](https://github.com/ncontatori/architecture-decision-records).
