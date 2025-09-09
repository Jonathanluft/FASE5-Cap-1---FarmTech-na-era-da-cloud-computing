# Sistema de Sensores e Controle com ESP32

# FIAP - Inteligência artificial e data science

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

## Nome do grupo
25

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/company/inova-fusca">Guilherme Campos Hermanowski </a>
- <a href="https://www.linkedin.com/company/inova-fusca">Gabriel Viel </a>
- <a href="https://www.linkedin.com/company/inova-fusca"> Matheus Alboredo Soares</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Jonathan Willian Luft </a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/company/inova-fusca">Leonardo Ruiz Orabona</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">ANDRÉ GODOI CHIOVATO</a>


Link para o nosso notebook colab:
- <a href="https://colab.research.google.com/drive/1X1vuIPBoZQW58g0KXeV9qYC9JwHUDQ6E?usp=sharing">Google Colab</a>


------------------------------*CUSTOS AWS*--------------------------------------

[My Estimate - Calculadora de Preços da AWS_SP2.pdf](https://github.com/user-attachments/files/22224546/My.Estimate.-.Calculadora.de.Precos.da.AWS_SP2.pdf)

[My Estimate - Calculadora de Preços da AWS_virginia2.pdf](https://github.com/user-attachments/files/22224547/My.Estimate.-.Calculadora.de.Precos.da.AWS_virginia2.pdf)


<img width="666" height="623" alt="Captura de tela 2025-09-08 225659" src="https://github.com/user-attachments/assets/566d4ab4-2161-4c6a-9686-32d71734a246" />

<img width="647" height="621" alt="Captura de tela 2025-09-08 225705" src="https://github.com/user-attachments/assets/681aa2b4-cac3-488d-8c8f-23cd4a47c310" />


▶ A escolha da região de São Paulo com duas instâncias **t4g.micro**, monitoramento avançado e possibilidade de integração com serviços de alta disponibilidade foi considerada a mais adequada neste estudo por equilibrar desempenho, confiabilidade e baixa latência. Em um cenário hipotético, os dados coletados viriam de máquinas em operação no Brasil, e o objetivo principal seria evitar falhas nesses equipamentos, já que elas poderiam levar a grandes perdas financeiras. Hospedar a API localmente reduziria a latência para cerca de 20 ms, garantindo maior agilidade no envio e processamento. Além disso, a configuração com duas instâncias poderia ser associada ao **Amazon EC2 Auto Scaling** e ao **Elastic Load Balancing (ELB)**, assegurando que, em caso de falha ou manutenção de uma instância, outra continuasse ativa, evitando interrupções e perda de dados críticos para a análise preditiva. O tipo de instância escolhido, com 1 GB de RAM, foi avaliado como suficiente para esse contexto, apresentando mais estabilidade do que a versão nano.

▶ O monitoramento detalhado no **Amazon CloudWatch** também foi analisado como recurso valioso, permitindo acompanhar métricas de desempenho em tempo real e configurar alertas para agir de forma preventiva. Embora os dados coletados não sejam sensíveis e, portanto, pudessem ser enviados para o exterior, manter a operação no Brasil contribui para reduzir riscos de **problemas de compliance**, uma vez que transferências internacionais de dados estão sujeitas a interpretações legais e regulatórias. Nesse sentido, mesmo com um custo superior em relação a alternativas mais simples, essa arquitetura foi discutida como um modelo teórico robusto, resiliente e escalável, servindo apenas para fins educacionais e como exercício de planejamento estratégico de infraestrutura em nuvem.

--------------------------------------------------------------------------------
