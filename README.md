# Workshop OSPF Kalau
Lab feito no EVE-NG do Workshop de OSPF ministrado pelo Gustavo Kalau  


**Passos realizados:**
1. Montagem da topologia
2. Configuração de endereços IP e máscara em cada interface de cada Roteador (10.x.x.x/30)
3. Configuração de endereços de Loopback nos Roteadores R9, R10, R12 e R13 (para simular as redes 192.168.x.x/24)
4. Habilitação do OSPF (ID 10) em cada Roteador
5. Configuração de cada interface à sua respectiva área OSPF
6. Manipulação da eleição de DR/BDR nos Roteadores R5, R12 e R13
7. Configuração de todos os links /30 e interfaces de Loopback para Point-to-Point
8. Configuração da autenticação MD5 entre os Roteadores R1 e R3
9. Redistribuição de rotas EIGRP <-> OSPF (R6 como E1 e R7 como E2)
10. Análise da OSPF Database para visualizar os 6 tipos de LSAs
11. Configuração de Virtual Link entre os Roteadores R5 e R7
