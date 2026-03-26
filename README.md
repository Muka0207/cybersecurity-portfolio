# 🛡️ Cibersegurança & Infraestrutura | Portfólio Prático

**Samuel Araújo Cocchi Amaral** *Graduando em Cibersegurança | Analista em Formação | Blue & Red Team* 📍 São Paulo, SP, Brasil | 🔗  https://www.linkedin.com/in/samuel-araujo-608532271/  |  ✉️ mr.oreo0207@gmail.com  | 📞 11 93465-5319

---

## 👨‍💻 Sobre Mim
Profissional de TI com sólida base em redes corporativas e infraestrutura, atualmente focado em Cibersegurança Tática. Trago a experiência de estagiário na IDT Corporation (Net2Phone) e formações técnicas em Informática (Senac) e Eletrônica (ETEC). 

Minha abordagem de segurança é orientada ao ciclo completo (*Kill Chain*): não apenas explorar vulnerabilidades em laboratórios (*Red Team*), mas principalmente projetar e aplicar mitigações de rede, *hardening* de servidores e auditorias de conformidade (*Blue Team*).

🎓 **Educação:** Cibersegurança - Faculdade Impacta (Previsão: Jun/2027)  
🏆 **Certificações Ativas:** Cisco CCNA | Cisco IT Essentials

---

## 🛠️ Stack Tecnológico & Habilidades

* **Offensive Security (Red Team):** Enumeração de Serviços (Nmap, Netdiscover), Análise de Vulnerabilidades (OpenVAS/Greenbone), Exploração (Metasploit Framework, Exploit-DB, Hydra), Bypass de controles legados.
* **Defensive Security (Blue Team):** Hardening de Servidores (Windows Server/IIS, Linux/Apache/WordPress), Mitigação em Nível de Kernel (Netfilter/iptables), Patching, Gestão de Identidade e Acesso (SSH Keys, RBAC).
* **Infraestrutura & Redes:** Roteamento e Comutação (Cisco), Análise de Tráfego, Topologias de Rede Seguras.

---

## 🔬 Projetos em Destaque: Laboratório de Auditoria e Mitigação

Este repositório documenta auditorias ponta a ponta realizadas em um ambiente de laboratório isolado, englobando ecossistemas Windows e Linux.

### 1. 🐧 Auditoria e Hardening: Metasploitable (Linux)
* **Red Team:** Exploração de *backdoor* crítico em serviço legado (vsftpd 2.3.4), Execução Remota de Comandos (RCE) via Samba (CVE-2007-2447), e *deploy* malicioso em Apache Tomcat. Escalonamento de privilégios via força bruta com *downgrade* criptográfico no OpenSSH 4.7p1.
* **Blue Team:** Contenção de perímetro via *firewall* (iptables `DROP`), mitigação de configurações padrão, auditoria de senhas fracas e reestruturação de acesso SSH.
* 📄 **[Ver Playbooks e Relatórios Táticos](./Auditorias_e_Pentests/Metasploitable)**

### 2. 🪟 Auditoria e Contenção: Máquina Shadow (Windows Server)
* **Red Team:** Exploração da vulnerabilidade crítica SMBv1 (EternalBlue).
* **Blue Team:** Mitigação tática via PowerShell e aplicação de políticas de *Patching* corporativo.
* 📄 **[Ver Playbook de Defesa](./Auditorias_e_Pentests/Windows_Shadow)** *(Link em construção)*

### 3. 🌐 Auditoria Web: Máquina Storm (Windows 10)
* **Red Team:** Exploração de serviços de áudio e sequestro de token no Microsoft IIS.
* **Blue Team:** Estratégias de mitigação e controle de acesso a serviços web.
* 📄 **[Ver Documentação](./Auditorias_e_Pentests/Windows_Storm)** *(Link em construção)*

### 4. 🔒 Hardening de CMS: Máquina CSEC (Linux Ubuntu)
* **Red Team:** Comprometimento via exploração de *backdoor* no ProFTPD 1.3.3c.
* **Blue Team:** Implementação de *Hardening* em ecossistema Apache/WordPress, incluindo o bloqueio de ataques de amplificação bloqueando XML-RPC via `.htaccess`.
* 📄 **[Ver Relatórios Ofensivos e Mitigação](./Auditorias_e_Pentests/Linux_CSEC)** *(Link em construção)*

---
*Nota: Todos os testes documentados neste repositório foram executados em ambientes de laboratório locais, estritamente controlados e com autorização prévia, para fins puramente acadêmicos e de pesquisa em Segurança da Informação.*
