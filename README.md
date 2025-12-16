# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 16/12/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Cassiano Proença

## Introdução

Este relatório apresenta o processo de implementação de ferramentas da AWS na empresa *Abstergo Industries*, realizado por [Nome do Responsável pelo Projeto]. O objetivo deste projeto é explorar três serviços da AWS com foco em redução de custos operacionais, enquanto potencializamos a infraestrutura de TI da empresa, visando maior eficiência, escalabilidade e flexibilidade.

## Descrição do Projeto

O projeto de implementação foi dividido em três etapas, cada uma com objetivos específicos e serviços da AWS que se alinham com as necessidades da Abstergo, uma empresa farmacêutica focada em distribuição de medicamentos. A seguir, são descritas as ferramentas selecionadas para o projeto:

### Etapa 1: Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de dados
- **Descrição de caso de uso:**  
  O Amazon S3 é uma solução de armazenamento de objetos altamente escalável, durável e acessível. Para uma empresa farmacêutica como a Abstergo, que lida com grandes volumes de dados (informações de clientes, estoque, registros de distribuição, entre outros), o S3 proporciona uma redução significativa de custos, pois elimina a necessidade de investimentos em infraestrutura de servidores locais. Além disso, o S3 oferece alta durabilidade dos dados, segurança e facilidade de acesso, essenciais para a operação de negócios farmacêuticos que requerem compliance com regulamentações, como a ANVISA.
  
  **Redução de Custos:**  
  O uso do Amazon S3 permite a redução de custos com armazenamento físico de dados, além de possibilitar um pagamento apenas pelo uso, sem necessidade de grandes investimentos iniciais.

### Etapa 2: Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Processamento e computação em nuvem
- **Descrição de caso de uso:**  
  O Amazon EC2 oferece instâncias escaláveis de servidores virtuais, permitindo à Abstergo ajustar a capacidade de processamento conforme a demanda. Com um modelo de pagamento sob demanda, a Abstergo pode reduzir custos operacionais ao pagar apenas pelos recursos de computação que utilizar, evitando a necessidade de manter servidores ociosos. O EC2 também permite a implementação de sistemas de gerenciamento de inventário e processamento de dados, essenciais para as operações diárias da empresa.
  
  **Redução de Custos:**  
  Ao usar o EC2, a Abstergo evita gastos excessivos com infraestrutura física de servidores, como compra, manutenção e atualização de hardware. A flexibilidade do EC2 permite ajustar os recursos conforme a necessidade, evitando desperdícios.

### Etapa 3: AWS Lambda
- **Foco da ferramenta:** Computação sem servidor (Serverless)
- **Descrição de caso de uso:**  
  O AWS Lambda permite executar código sem a necessidade de gerenciar servidores. Essa funcionalidade é ideal para processos automatizados, como o envio de alertas para a equipe de distribuição quando novos lotes de medicamentos chegam ao estoque ou a atualização de dados em tempo real. O uso de AWS Lambda elimina custos com servidores dedicados para executar funções específicas, permitindo que a Abstergo foque em suas atividades principais enquanto automatiza operações secundárias.
  
  **Redução de Custos:**  
  O AWS Lambda permite reduzir custos com infraestrutura ao eliminar a necessidade de servidores dedicados para execução de funções simples. Como a cobrança é baseada no número de execuções, a Abstergo paga apenas pelo tempo de execução real do código, promovendo uma economia significativa.

## Conclusão

A implementação das ferramentas da AWS na Abstergo Industries proporcionará os seguintes benefícios:  
- **Redução de custos operacionais** com armazenamento, processamento e automação de processos.  
- **Escalabilidade** para crescer conforme a demanda sem precisar de grandes investimentos em infraestrutura física.
- **Segurança e conformidade** com regulamentações, especialmente importantes para a indústria farmacêutica.  

Recomenda-se a continuidade da utilização das ferramentas implementadas e a exploração de novas soluções tecnológicas que possam melhorar ainda mais a eficiência dos processos internos da Abstergo.

## Anexos

- [Manual do Amazon S3](https://aws.amazon.com/s3/)
- [Guia do EC2](https://aws.amazon.com/ec2/)
- [Documentação do AWS Lambda](https://aws.amazon.com/lambda/)

**Assinatura do Responsável pelo Projeto:**  
Cassiano Proença

---

## Imagem do Banco de Dados

![Data Center](file:///mnt/data/A_photograph_showcases_a_data_center_with_rows_of_.png)

