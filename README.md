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

▶ A escolha da região de São Paulo com duas instâncias **t4g.micro**, monitoramento avançado e possibilidade de integração com serviços de alta disponibilidade foi considerada a mais adequada neste estudo por equilibrar desempenho, confiabilidade e baixa latência. Como os dados, em um cenário hipotético, viriam de máquinas em operação no Brasil, hospedar a API localmente reduziria a latência para cerca de 20 ms, garantindo maior agilidade no envio e processamento. Além disso, a configuração com duas instâncias poderia ser associada ao **Amazon EC2 Auto Scaling** e ao **Elastic Load Balancing (ELB)**, que assegurariam, em teoria, que caso uma instância falhasse ou precisasse de manutenção, outra assumisse automaticamente, mantendo o sistema ativo e evitando interrupções ou perda de dados críticos para análise preditiva. O tipo de instância escolhido, com 1 GB de RAM, foi avaliado como estável e suficiente para o volume esperado, apresentando-se como uma alternativa mais segura que a versão nano.

▶ O monitoramento detalhado habilitado no **Amazon CloudWatch** também foi analisado como ferramenta útil para acompanhar métricas de desempenho em tempo real e configurar alertas que antecipariam problemas antes que afetassem o sistema, reforçando o objetivo de manutenção preditiva. Ainda dentro de um exercício educacional, foi considerado que a integração futura com um Load Balancer possibilitaria ajustar o poder computacional de forma dinâmica, distribuindo requisições entre as instâncias e permitindo que a infraestrutura pudesse escalar conforme o volume de dados aumentasse. Assim, mesmo que o custo seja superior em comparação a opções mais simples, essa arquitetura foi discutida como um modelo teórico robusto, resiliente e escalável, servindo apenas como referência acadêmica e não como uma implementação prática.

