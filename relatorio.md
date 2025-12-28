# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** Janeiro de 2025  
**Empresa:** Abstergo Industries  
**Responsável:** José Lúcio Oliveira da Silva Júnior  

---

## Introdução

Este relatório apresenta o processo de implementação de serviços em nuvem na empresa **Abstergo Industries**, realizado por **José Lúcio Oliveira da Silva Júnior**. O objetivo do projeto foi selecionar e implementar **três serviços da Amazon Web Services (AWS)** com foco na **redução imediata de custos operacionais**, sem comprometer a disponibilidade, a segurança e a escalabilidade dos sistemas da empresa.

A adoção de soluções em cloud computing permite à organização otimizar recursos, eliminar desperdícios e pagar apenas pelo uso efetivo da infraestrutura.

---

## Descrição do Projeto

O projeto de implementação de serviços AWS foi dividido em **três etapas**, cada uma com objetivos específicos voltados à redução de custos e à melhoria da eficiência operacional.

---

### Etapa 1: Amazon EC2 Auto Scaling

- **Nome da ferramenta:** Amazon EC2 Auto Scaling  
- **Foco da ferramenta:** Otimização do uso de recursos computacionais  
- **Descrição do caso de uso:**  
  A Abstergo Industries possuía instâncias EC2 superdimensionadas e ativas continuamente, independentemente da demanda. Com a implementação do **Auto Scaling**, foi possível ajustar automaticamente a quantidade de instâncias EC2 conforme o volume de acessos e processamento necessário.  
  Essa abordagem reduziu custos ao evitar a execução de servidores ociosos em períodos de baixa demanda, garantindo desempenho adequado apenas quando necessário.

---

### Etapa 2: Amazon S3 com Storage Classes Inteligentes

- **Nome da ferramenta:** Amazon S3 (Standard, Intelligent-Tiering e Glacier)  
- **Foco da ferramenta:** Redução de custos de armazenamento  
- **Descrição do caso de uso:**  
  Arquivos antigos e pouco acessados estavam armazenados em camadas de alto custo. A utilização do **Amazon S3 Intelligent-Tiering**, em conjunto com políticas de ciclo de vida, permitiu mover automaticamente dados para classes de armazenamento mais econômicas, como **S3 Glacier**.  
  Essa estratégia reduziu significativamente os custos de armazenamento sem perda de dados ou impacto na segurança.

---

### Etapa 3: AWS Cost Explorer e AWS Budgets

- **Nome da ferramenta:** AWS Cost Explorer e AWS Budgets  
- **Foco da ferramenta:** Monitoramento e controle financeiro da nuvem  
- **Descrição do caso de uso:**  
  A falta de visibilidade sobre os gastos em cloud dificultava o controle financeiro. Com a implementação do **AWS Cost Explorer**, a empresa passou a analisar detalhadamente o consumo por serviço e por período.  
  Além disso, o **AWS Budgets** foi configurado para emitir alertas automáticos quando os custos se aproximam de limites pré-definidos, prevenindo gastos excessivos e permitindo ações corretivas imediatas.

---

## Conclusão

A implementação dos serviços AWS na **Abstergo Industries** tem como resultado esperado a **redução de custos operacionais**, maior **controle financeiro**, melhor **utilização dos recursos computacionais** e aumento da **eficiência operacional**.

A adoção dessas soluções demonstra que a computação em nuvem, quando bem gerenciada, é uma aliada estratégica para a sustentabilidade financeira e o crescimento da empresa. Recomenda-se a continuidade do uso dos serviços implementados e a avaliação periódica de novas soluções AWS que possam aprimorar ainda mais os processos internos.

---

## Anexos

- Documentação de configuração do Auto Scaling  
- Relatórios de custos gerados pelo AWS Cost Explorer  
- Políticas de ciclo de vida do Amazon S3  

---

**Assinatura do Responsável pelo Projeto:**  

**José Lúcio Oliveira da Silva Júnior**
