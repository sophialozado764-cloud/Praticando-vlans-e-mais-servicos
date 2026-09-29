# 
# 🌐 Projeto de Rede -Praticando vlans e mais servicos- Cisco Packet Tracer
 Nesse projeto tivemos o grande desafio de implementarmos duas redes distindas de uma mesma empresa,uma unidade localizada em Coontagm e outra em Betim, não somente isso incluímos duas VLANS, que são destinadas exclusivamente para visitantes, uma em cada unidade, para a segurança da rede.
 
## 🚀 Tecnologias Utilizadas
* **Cisco Packet Tracer** (Versão 9.0.0.0810)
* **Protocolos de Roteamento:** RIP
* **Serviços:**  DHCP, DNS, HTTP e E-MAIL
* **Segurança:** VLANs, Acesso de Gerrenciamento
 
## 📐 Topologia da Rede
Nossa topologia para nossas redes são: 
* **Topologia Híbrida** (analisando em geral)
  
* **Topologia em estrela nas LANs** (analisando as cidades)
* -> é uma topologia em estrela pois tem um dispositivo central que concentra todas as conexões, no caso seriam respectivamente: Switch_Contagem e Switch_Betim.
  
* **Topologia Ponto a ponto na WAN** (analizando a conexão entre as cidades)
* -> é uma topologia ponto a ponto pois é uma conexão direta e exclusiva entre os rotiadores (nós). 
 
 * **👷‍♀️ REDES COOPORATIVAS E DE VISITANTES   🙍**
* **VLAN 10:** Contagem (para visitantes) (Rede: 193.167.11.254/24)
* **VLAN 20:** Contagem (coorporativa) (Rede: 10.254.254.254/8)
* **VLAN 1:** Betim (coorporativa) (Rede: 192.168.10.254/24)
* * **VLAN 10:** Betim (visitantes) (Rede: 11.254.254.254/8)
 
## 🛠️ Como Executar o Projeto
  1. Baixe e instale o [Cisco Packet ([https://www.netacad.com/pt/articles/news/download-cisco-packet-tracer]).
2. Faça o clone deste repositório ou baixe o arquivo ".pkt".
3. Abra o arquivo ".pkt" no software.
4. Aguarde os indicadores de link/broadcast ficarem verdes e realize os testes de conectividade ("ping" ou modo simulação).

 **📚 Para aprendermos um pouco mais...📚**
 
* **O que são Nós e Links?**
* São termos que foram criados para padronizar a comunicação entre profissionais ou não, da área de tecnologia.
  
* **Nós 💻**
* -> É todo e qualquer dispositivo físico que possua um endereço (seja Mac ou IP), que processa, cria ou rotea dados.

* **🔌  Links**
* -> São os meios de transmissão por onde os dados trafegam (bites e bytes),
* eles podem ser meios físicos como: cabos, exemplo cabo UDP ou meios sem fio/wirilles exemplo: rede wi-fi via home-routher. A função dos links é transportar os dados de um nó a outro.
---


Desenvolvido por: Sophia (https://github.com/sophialozado764-cloud/) 🚀
