# resumo-do-lab5
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.


Governança, segurança e conformidade no Azure.

Você pode usar ferramentas e serviços como a Política do Azure e o Microsoft Defender for Cloud para estabelecer políticas corporativas e planejar suas estratégias de governança. Essas ferramentas e serviços impõem e automatizam as decisões de governança da sua organização. Use a ferramenta de benchmark de governança antes de iniciar seu planejamento de governança para identificar possíveis lacunas na abordagem de governança de nuvem da sua organização. Para obter mais informações sobre como desenvolver processos de governança, consulte Metodologia de governança.

    Azure Policy
    Microsoft Defender para Nuvem

A Política do Azure ajuda você a criar, atribuir e gerenciar políticas. Essas políticas impõem regras aos recursos para que eles continuem em conformidade com os padrões corporativos e com os SLAs (Contratos de Nível de Serviço). A Política do Azure verifica seus recursos para identificar recursos que não são compatíveis com políticas corporativas. Por exemplo, você pode ter uma política que permite que apenas um tamanho específico de máquina virtual (VM) seja executado em seu ambiente. Quando você implementa essa política, a Política do Azure avalia as VMs existentes em seu ambiente e quaisquer novas VMs implantadas. A avaliação da política gera eventos de conformidade a serem usados para monitoramento e relatórios.

Use políticas comuns para:

    Impor a marcação para recursos e grupos de recursos.
    Restringir as regiões para recursos implantados.
    Restringir SKUs caras para recursos específicos.

https://learn.microsoft.com/pt-br/training/modules/describe-features-tools-azure-for-governance-compliance/
    Audite o uso de recursos opcionais importantes, como discos gerenciados pelo Azure.

Aplicar uma política

Para aplicar uma política a um grupo de recursos:

    Acesse Azure Policy.
    Selecione Atribuir uma política.
