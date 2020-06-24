# TrabalhoRoteamentos

Topologia da rede

![Screenshot_1](https://user-images.githubusercontent.com/67288159/85567752-8031e000-b607-11ea-93a4-3b3260d70f2d.png)


Configuração OSPF

Router2

Network 192.168.20.0 255.255.255.0 area 0
Network 192.168.1.0 255.255.255.0 area 0
Network 192.168.2.0 255.255.255.0 area 0

Router1
Network 192.168.2.0 255.255.255.0 area 0
Network 192.168.3.0 255.255.255.0 area 0

Router0

Network 192.168.1.0 255.255.255.0 area 0
Network 192.168.4.0 255.255.255.0 area 0

Router3

Network 192.168.3.0 255.255.255.0 area 0

Network 192.168.4.0 255.255.255.0 area 0

Network 192.168.5.0 255.255.255.0 area 0
router bgp 100

neighbor 192.168.5.5

redistribute ospf 1

Configuração EIGRP

router EIGRP 200

Router5

Network 192.168.5.0

Network 192.168.6.0

Network 192.168.7.0

router bgp 200 

redistribute EIGRP 200


Router6

Network 192.168.7.0

Network 192.168.9.0

Router7

Network 192.168.6.0

Network 192.168.8.0

Router8

Network 192.168.9.0

Network 192.168.8.0

Network 192.168.30.0

Segue link para download do projeto no packet tracer: [trabalhoGB.zip](https://github.com/gabriel-sippel/TrabalhoRoteamentos/files/4826010/trabalhoGB.zip)
