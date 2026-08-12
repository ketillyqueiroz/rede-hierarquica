## Redes Hierárquicas

Esta atividade foi realizada no Cisco Packet Tracer para compreender a organização de uma rede corporativa utilizando o modelo hierárquico de três camadas: Acesso, Distribuição e Núcleo (Core).

Foram utilizados dois switches Cisco 2960 na camada de acesso, um switch Cisco 3650 na distribuição e um roteador Cisco 4331 no Core.

O endereçamento utilizado foi:

Dispositivo	    |IP	            |Máscara	    |Gateway
PC-Lab01	    |192.168.1.10	|255.255.255.0	|192.168.1.1
PC-Lab02	    |192.168.1.11	|255.255.255.0	|192.168.1.1
PC-Sec01	    |192.168.1.20	|255.255.255.0	|192.168.1.1
PC-Sec02	    |192.168.1.21	|255.255.255.0	|192.168.1.1
Roteador-Core	|192.168.1.1	|255.255.255.0	|—

Todos os dispositivos pertencem à rede 192.168.1.0/24, sendo o roteador 192.168.1.1 configurado como gateway dos computadores.

Após a configuração, foram realizados testes com o comando ping e com o protocolo ICMP, além da utilização do modo Simulation para observar o tráfego passando pelas camadas de Acesso → Distribuição → Core.

A prática permitiu reforçar conceitos de IPv4, gateway, switches, roteadores, ICMP e arquitetura hierárquica de redes.