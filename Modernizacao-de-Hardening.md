
# [Slide 1] Modernização de hardening
### Sempre que uma conta é criada na núvem, ela deve passar pelos procedimentos de hardenização.
- Hardening é um processo de mapeamento das ameaças, mitigação dos riscos e execução das atividades corretivas, com foco na infraestrutura e objetivo principal de torná-la preparada para enfrentar tentativas de ataque

- Redução de vulnerabilidade.
- Automação do processo.
- Modernização de documentação técnica.


# [Slide 2] Princípios de design
<details close>
<summary><b>Permitir a rastreabilidade</b></summary>
• Monitoramento, alerta e audição de ações e alterações no ambiente em tempo real.<br>
• Integração da coleta de logs e métricas aos sistemas para investigar e executar ações automaticamente.
</details>

<details close>
<summary><b>Gerenciamento de identidades</b></summary>
<br><b>• Identidades humanas</b><br>
Administradores, desenvolvedores, operadores e clientes de seus aplicativos precisam de uma identidade para acessar seus ambientes e aplicativos da AWS.<br>
<br><b>• Identidade de máquina</b><br>
Aplicativos de carga de trabalho, ferramentas operacionais e componentes precisam de uma identidade para solicitar serviços da AWS.<br>
<br><b>• Provedor de identidade centralizado - AzureAD</b><br>
Gerenciamento do acesso em vários aplicativos e serviços, através do AzureAD é gerenciando e revogando o acesso de um único local.<br>
<br><b>• Usar credenciais temporárias</b><br>
Exigencia que as identidades adquiram credenciais temporárias dinamicamente.<br>
<br><b>• AWS Organization</b><br>
Federação em várias contas no AWS Organization é configurada a origem de identidade no AWS IAM Identity Center (successor to AWS Single Sign-On) e especificado onde seus usuários e grupos são armazenados.
</details>

<details close>
<summary><b>Detecção</b></summary>
<br><b>• AWS CloudTrail</b>
<br>Fornece o histórico de eventos da atividade da conta da AWS, incluindo ações realizadas por meio do Console de Gerenciamento da AWS, SDKs da AWS, ferramentas da linha de comando e outros serviços da AWS.<br>
<br><b>• AWS Config </b>
<br>Monitora e registra as configurações de recursos da AWS e permite automatizar as tarefas de avaliação e correção em relação às configurações desejadas.<br>
<br><b>• Amazon CloudWatch Logs </b>
<br>Um agente que coleta os logs no sistema operacional e nos aplicativos em execução e os armazena automaticamente.
</details>

<details close>
<summary><b>Automatizar práticas recomendadas de segurança</b></summary>
Utilizando ferramentas de automação, todas as etapas do hardening são entregues automaticamente quando uma nova conta é criada ou quando uma conta está fora de compliance.
</details>

<details close>
<summary><b>Monitoramento e Observabilidade</b></summary>
Utilizando 
</details>

# [Slide 3] Importância do Trabalho
- Excelência Operacional
- Segurança
- Confiabilidade
- Eficiência de performance
- Otimização de custos


# Links
[Cloudtrail](https://aws.amazon.com/pt/cloudtrail/)<br>
[Config](https://aws.amazon.com/pt/config/)<br>
[Guardduty](https://aws.amazon.com/pt/guardduty/)<br>
[Security hub](https://aws.amazon.com/pt/security-hub/)<br>
[VPC](https://aws.amazon.com/pt/vpc/)<br>
[Flow logs](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/flow-logs.html)<br>
[Cloudwatch](https://aws.amazon.com/pt/cloudwatch/)<br>
[Cloudwatch Logs](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/CWL_GettingStarted.html)<br>
[Assign logs](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/Subscriptions.html)<br>
[Logs Insights](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/AnalyzingLogData.html)<br>
[Well-Architected Framework](https://d1.awsstatic.com/whitepapers/architecture/AWS-Reliability-Pillar.pdf)<br>
[Solicitação de credenciais de segurança temporárias](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_temp_request.html)<br>
[AWS IAM Identity Center](https://aws.amazon.com/pt/iam/identity-center/)
