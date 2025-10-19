# 🔐 Segurança de Redes e Sistemas

Este repositório contém todo o Conteudo Dado Nas Aulas Laboratórios e Fichas de Exercicios da unidade curricular De Segurança de Redes e Sistemas do curso de Informática (2.º ano, UMAIA).

Para esta Cadeira Foram Utilizados e Estudados Conteudos Cisco bem como utilizado nos casos praticos a Plataforma Emuladora Cisco Packet Tracer.

Para alem disso Foi ainda Desenvolvido um Projeto Colaborativo "PBL" entre duas Cadeiras Segurança de Redes e Sistemas e  Redes e Comunicação de Dados 2 que consistia na elaboraçao e configuração e devida proteção de uma topologia de uma universidade.
Este Trabalho estara todo num repositório a parte com o devido enunciado explicação e Desenvolvimento 

---

## 🚀 Estrutura do Repositório

📂 [CISCO_NOTEPADS](./CISCO_NOTEPADS) — Notepads de Configuração <br>
📂 [NETWORK_SECURITY_LABS](./NETWORK_SECURITY_LABS) — Laboratórios Prático <br>
📂 [NETWORK_SECURITY_SLIDES](./NETWORK_SECURITY_SLIDES) — Slides Teoricos

---

## 📌 Conteúdos Abordados

### Network Security Fundamentals
- Princípios **CIA** (Confidencialidade, Integridade, Disponibilidade)  
- Ameaças comuns (malware, DoS/DDoS, MITM, phishing)  
- Modelos de defesa: **defense-in-depth**, zero trust  
- Hardening de dispositivos: gestão de patches, **AAA**, logging, NTP, backups  
- Segmentação e **VLANs**, firewalls, IDS/IPS  
- Criptografia em trânsito (SSH, TLS, IPsec)

### Access Control Lists (ACLs)
- **ACLs IPv4**: padrão vs. estendidas  
- Ordem de avaliação e **implicit deny**  
- Direção (**in/out**) e interfaces vs. linhas VTY  
- Boas práticas: numeradas vs. nomeadas, comentários, objetos (quando aplicável)  
- Casos de uso: filtragem de tráfego, limitar gestão, base para QoS

### Layer 2 Security Considerations
- **Port Security**: limite de MAC, sticky MAC, modos de violação (protect/restrict/shutdown)  
- **DHCP Snooping** e **IP Source Guard**  
- **Dynamic ARP Inspection (DAI)**  
- Proteções **STP**: BPDU Guard, Root Guard, Loop Guard  
- **Storm Control** e controlo de broadcast/multicast  
- Mitigação de **VLAN hopping**: desativar DTP, VLAN nativa dedicada, permitir apenas VLANs necessárias


---

# 🎯 Objetivos

1. **Aquisição de conhecimentos básicos na área da Segurança de Redes e Sistemas**  
   Compreender princípios, ameaças e boas práticas de proteção de infraestruturas e dados.

2. **Domínio de conceitos fundamentais na configuração de políticas de controlo de acesso IP em routers**  
   Configurar e validar **ACLs** e outras políticas de filtragem/segmentação em equipamentos de routing.

3. **Estudo e mitigação de ataques na camada de nível 2 do modelo OSI**  
   Identificar vetores comuns (MAC flooding, VLAN hopping, ARP spoofing, DHCP attacks) e aplicar mecanismos de defesa (Port Security, DAI, DHCP Snooping, IP Source Guard, STP guards).

4. **Continuidade de preparação para certificação Cisco CCNA**  
   Consolidar bases técnicas e práticas que suportem a progressão para a certificação **Cisco CCNA**.



--- 

## 🛠️ Tecnologias Utilizadas

- [**Cisco Packet Tracer**](https://www.netacad.com/courses/packet-tracer) – Plataforma de simulação de redes
- [**GNS3**](https://www.gns3.com/) – Emulador/simulador de redes para topologias reais com IOS/VMs (QEMU/VirtualBox/VMware)

---

## 👤 Autor

Repositório individual desenvolvido por [**Pedro Venda**](https://github.com/PedroVenda27)


