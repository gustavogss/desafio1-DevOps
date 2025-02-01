# Desafio: Implementação de Práticas de DevSecOps em uma aplicação durante todo o ciclo de desenvolvimento 

## Resolução do desafio: 

### 1. Diagnóstico Cultural (C de CALMS)
Processo Selecionado: Deploy Manual em Produção

1- Descrição Atual:
O deploy é realizado manualmente pela equipe de operações.
Não há padronização, o que resulta em inconsistências e erros frequentes.
Comunicação limitada entre as equipes de desenvolvimento e operações, gerando frustração.
Pontos de Atrito:

Falta de Automação: O processo é suscetível a erros humanos e demorado.
Ausência de Padronização: Procedimentos informais dificultam a resolução de problemas.
Barreira de Comunicação: As equipes operam em silos, sem colaboração efetiva.
Oportunidades de Melhoria:

Adotar ferramentas de integração e entrega contínua (CI/CD).
Promover maior colaboração entre equipes, introduzindo rituais como daily meetings conjuntas.

### 2. Automação (A de CALMS):
Solução Proposta: Implementação de um Pipeline de CI/CD

***Ferramentas Sugeridas***:
- GitLab CI/CD ou GitHub Actions: Para orquestrar build, testes e deploy automatizados.
- Docker: Para criar imagens padronizadas e portáveis das aplicações.
- Kubernetes ou AWS ECS: Para gerenciar containers e escalar as aplicações automaticamente.
  
***Plano de Implementação***:

- Fase 1: Configurar um repositório centralizado para o código e integração com CI/CD.
- Fase 2: Automatizar testes unitários, testes de integração e criação de imagens Docker.
- Fase 3: Criar scripts de deploy automatizado para ambientes de staging e produção.
- Fase 4: Monitorar e ajustar o pipeline com base em métricas de desempenho.

### Minimizando Resistências:
Treinamentos práticos para as equipes em novas ferramentas.
Demonstração dos benefícios da automação, destacando ganhos de eficiência.

1. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS)
Métricas Relevantes:
- Lead Time: Tempo entre a conclusão do desenvolvimento e o deploy em produção.
- Taxa de Sucesso do Deploy: Proporção de deploys bem-sucedidos.
- Número de Incidentes: Monitorar a redução de problemas após a automação.
- MTTR (Mean Time to Recovery): Tempo médio de recuperação após incidentes.

***Plano de Compartilhamento de Conhecimento***:
- Documentação: Criar um repositório central com guias, procedimentos e melhores práticas.
Sessões de Treinamento: Realizar workshops mensais para discutir processos e novas ferramentas.
- Comunicação Contínua: Estabelecer um canal no Slack ou MS Teams para troca de ideias e resolução de problemas.

1. Três Maneiras do DevOps:
- Primeira Maneira (Acelerar o Fluxo)
Ação: Automatizar o pipeline de CI/CD e adotar containers com Docker.
Impacto: Reduzir o tempo médio de deploy de 2 dias para algumas horas, permitindo entregas mais rápidas e confiáveis.

- Segunda Maneira (Ampliar o Feedback)
Ação: Implementar monitoramento contínuo com ferramentas como Prometheus e Grafana.

Impacto: Permitir a detecção precoce de problemas e uma comunicação direta entre desenvolvimento e operações para correções rápidas.

- Terceira Maneira (Experimentar e Aprender)
Ação: Criar um ambiente de sandbox para experimentação.

Impacto: Incentivar os desenvolvedores a testar novas tecnologias e metodologias sem impacto na produção.

### Resultados Esperados:
Redução no Lead Time: De 2 dias para 6 horas ou menos.
Aumento na Taxa de Sucesso dos Deploys: De 80% para 95%.
Diminuição de Incidentes Semanais: De 2 para menos de 1 incidente.
Redução no MTTR: De 4 horas para menos de 1 hora.

### Conclusão
Esse plano promove uma transformação cultural e operacional, alinhada aos princípios de CALMS e às Três Maneiras do DevOps, criando um ambiente colaborativo, ágil e inovador na Tech.
