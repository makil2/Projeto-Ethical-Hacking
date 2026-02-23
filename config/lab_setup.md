# Configuração do Ambiente de Laboratório

Para replicar este projeto, as seguintes configurações foram aplicadas:

### 1. VirtualBox Network
* **Tipo:** Placa de Rede Exclusiva de Hospedeiro (Host-Only).
* **Adaptador:** `vboxnet0`.
* **DHCP:** Desativado (IPs fixos recomendados).

### 2. Máquina Alvo (Metasploitable 2)
* **IP:** 192.168.56.102
* **Serviços Ativos:** SMB (Port 445), FTP (Port 21), Apache (Port 80).

### 3. Máquina Atacante (Kali Linux)
* **IP:** 192.168.56.101 (mesma sub-rede).
* **Ferramenta:** Medusa v2.3 instalada 
