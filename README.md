Olá, bom dia.

Este é meu repositório do treinamento AZ-900 azure na DIO.me

Estou em migração para Dados e meu foco em Azure, este é meu 3 bootcamp na Dio.
estou muito confiante , já aprendi a definição de Cloud
Nuvem e classificações de nuvens
A nuvem pode ser classificada em:
•	Nuvem Pública: infraestrutura fornecida por terceiros (ex.: Microsoft Azure), acessível a múltiplos clientes em modelo multi-tenant.
•	Nuvem Privada: infraestrutura dedicada, usada exclusivamente por uma organização, podendo ser local (on-premises) ou hospedada em data center externo.
•	Nuvem Híbrida: combinação entre nuvem pública e privada, permitindo maior flexibilidade e integração.

# 🚀 Desafio DIO - Criando Máquinas Virtuais e Banco de Dados no Azure  

![Azure Badge](https://img.shields.io/badge/Azure-Cloud-blue?logo=microsoftazure)  
![Status Badge](https://img.shields.io/badge/Status-Concluído-brightgreen)  
![License Badge](https://img.shields.io/badge/License-MIT-lightgrey)  

---

## 📖 Sobre o Projeto  
Este repositório documenta o laboratório do **Desafio de Projeto da DIO**, onde foram criados e configurados recursos no **Microsoft Azure**, incluindo:  
- Máquinas Virtuais (VMs);  
- Banco de Dados SQL.  

O foco está em praticar o provisionamento de recursos na nuvem, entender seus custos e documentar cada etapa para aprendizado contínuo.  

---

## 🎯 Objetivos  
- Criar e configurar uma **Máquina Virtual** no Azure;  
- Configurar um **Banco de Dados SQL**;  
- Documentar o processo com prints de tela;  
- Compartilhar a experiência utilizando o **GitHub**.  

---

## 🛠️ Passo a Passo  

### 1️⃣ Criando a Máquina Virtual  
Parâmetros utilizados:  
- **Região**: East US  
- **Imagem**: Windows Server 2019 Datacenter  
- **Tamanho**: Standard_DS1_v2 (1 vCPU, 3.5 GiB RAM)  
- **Disco do SO**: SSD Premium  
- **Monitoramento**: Habilitado  

📸 Prints:  
![Tela 01 - Azure](./images/tela%2001%20-%20azure.jpg)  
![Tela 02 - Criar Máquina Virtual](./images/tela%2002%20-%20criar%20maquina%20virtual.jpg)  
![Tela 03 - VM](./images/tela%2003%20-%20vm.jpg)  
![Tela 04 - Criar VM](./images/tela%2004%20-%20vm%20criar.jpg)  
![Tela 05 - Valor VM](./images/tela%2005%20vm%20valor.jpg)  
![Tela 06 - Valor VM 2](./images/tela%2006%20vm%20valor%202.jpg)  
![Tela 07 - Discos VM](./images/tela%2007%20-vm%20discos.jpg)  
![Tela 08 - Monitoramento VM](./images/tela%2008%20-%20vm%20monitoramento.jpg)  

---

### 2️⃣ Criando o Banco de Dados SQL  

Etapas:  
1. Acesse **Bancos de Dados SQL** no portal do Azure.  
2. Defina:  
   - Nome do banco  
   - Servidor lógico  
   - Plano de desempenho  
3. Confirme a criação.  

📸 Print:  
![Tela 09 - Criar Banco de Dados](./images/tela%2009%20-%20criar%20banco%20de%20dadis.jpg)  

---

## 📂 Estrutura do Repositório  
```bash
📦 azure-lab
 ┣ 📂 images
 ┃ ┣ tela 01 - azure.jpg
 ┃ ┣ tela 02 - criar maquina virtual.jpg
 ┃ ┣ tela 03 - vm.jpg
 ┃ ┣ tela 04 - vm criar.jpg
 ┃ ┣ tela 05 vm valor.jpg
 ┃ ┣ tela 06 vm valor 2.jpg
 ┃ ┣ tela 07 -vm discos.jpg
 ┃ ┣ tela 08 - vm monitoramento.jpg
 ┃ ┗ tela 09 - criar banco de dadis.jpg
 ┣ 📜 README.md
```

---

## ✅ Resultados  
✔️ VM criada com sucesso  
✔️ Banco de Dados SQL configurado  
✔️ Documentação completa publicada no GitHub  

---

## 👨‍💻 Autor  
Projeto desenvolvido por **Edson Gomes** para o **Desafio de Projeto DIO - Microsoft Azure**.  

🔗 [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com/edsongom1)  

---

## 📜 Licença  
Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT).  

estou gostando e este é o primeiro desafio .


# 🚀 Criando uma Máquina Virtual (VM) no Azure - Passo a Passo

Este guia explica como criar uma máquina virtual básica no **Microsoft Azure**, ideal para quem está começando a usar a plataforma de nuvem.

---

## 📋 Pré-requisitos

- Conta ativa no [Microsoft Azure](https://portal.azure.com)
- Acesso ao portal do Azure
- Credenciais de login válidas

---

## 🛠 Passo a Passo

1. **Acesse o Portal do Azure**
   - Vá para [https://portal.azure.com](https://portal.azure.com) e faça login.

2. **Encontre o recurso de Máquinas Virtuais**
   - No campo de busca, digite **Máquinas virtuais** e selecione a opção correspondente.

3. **Crie uma nova VM**
   - Clique em **Criar** → **Máquina virtual do Azure**.
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/8a225c37-14d7-4752-954d-95c0a91c2b9a" />

4. **Configure os detalhes básicos**
   - **Nome da VM:** por exemplo, `myVM`
   - **Região:** escolha a mais próxima do seu público/usuário
   - **Imagem:** ex.: *Windows Server 2022 Datacenter*
   - **Tamanho:** escolha a configuração de CPU e memória
   - **Credenciais:** crie um nome de usuário e senha de administrador

5. **Configure as regras de porta de entrada**
   - Habilite portas necessárias, como **RDP (3389)** para acesso remoto no Windows

6. **Ajuste configurações adicionais**
   - Revise abas de discos, redes e outras opções, altere se necessário ou mantenha padrões

7. **Revise e crie**
   - Clique em **Examinar + criar**
   - Após validação, clique em **Criar** para iniciar a implantação

8. **Acesse a VM**
   - Quando a criação for concluída, acesse via portal ou **RDP** usando as credenciais criadas

---

## 📝 Notas Importantes

- 💾 **Salve suas credenciais** para uso futuro.
- 🌎 **Escolha bem a região**, ela afeta latência e custo.
- ⚙️ **Personalize as configurações** conforme sua necessidade (discos, rede, segurança, etc).

---

## 💡 Observação

Este guia é voltado para **VMs Windows**, mas o processo é muito semelhante para **VMs Linux** – basta escolher a imagem do sistema operacional desejado.

---

## 🤝 Contribuições

Se este guia foi útil para você, sinta-se livre para:

- ⭐ Dar uma estrela neste repositório
- 🛠 Abrir um Pull Request com melhorias
- 💬 Enviar sugestões e feedback

---
# 💾 Resumo de Aprendizado: Armazenamento no Azure  

Este é meu resumo do conteúdo de **Armazenamento no Azure**, com base nas aulas e exercícios realizados no módulo.  
Aqui organizei os principais pontos que aprendi, de forma prática e direta, para ajudar na revisão para a **AZ-900**.  

---

## 📌 Introdução  
O armazenamento no Azure é um dos pilares da nuvem, permitindo guardar e acessar dados de forma escalável, segura e altamente disponível.  
É usado tanto para aplicações corporativas quanto para dados pessoais, sempre com foco em **performance, redundância e custo**.  

---

## 🔄 Redundância e Serviços de Armazenamento  

**Redundância** é essencial para manter os dados seguros e disponíveis, mesmo em falhas de hardware ou datacenters.  

- **LRS (Locally Redundant Storage):** 3 cópias no mesmo datacenter.  
- **ZRS (Zone-Redundant Storage):** cópias em zonas diferentes dentro da mesma região. 
no DIO é tratado somentee os dois acima, o conteudo abaixo li no manua oficial microsoft 
- **GRS (Geo-Redundant Storage):** cópias em regiões geograficamente distantes.  
- **RA-GRS (Read-Access Geo-Redundant):** igual ao GRS, mas permite leitura no local secundário.  

**Serviços de Armazenamento:**  
- **Blob Storage:** grandes volumes de dados não estruturados (imagens, vídeos, logs).  
- **File Storage:** compartilhamento de arquivos via SMB (como um servidor de arquivos).  
- **Queue Storage:** mensagens para comunicação entre componentes de sistemas distribuídos.  
- **Table Storage:** armazenamento NoSQL, rápido e simples.  

---

## 🌍 Pontos de Extremidade Públicos e Camadas de Acesso  

Cada serviço de armazenamento possui um **endpoint público**  
(exemplo: `https://nomedaconta.blob.core.windows.net`).  

Podemos restringir acessos por **rede ou identidade** para maior segurança.  

**Camadas de acesso (tiers):**  
- **Hot:** acesso frequente, maior custo de armazenamento, menor custo de leitura.  
- **Cool:** acesso esporádico, custo de armazenamento menor, mas leitura mais cara.  
- **Archive:** longo prazo, custo baixíssimo, mas precisa reidratar antes de ler.  

---

## 🚀 Migrações para o Azure  

Ferramentas que ajudam empresas a migrar dados locais para o Azure:  
- **Azure Migrate →** análise, avaliação e execução da migração.  
- **Data Box →** dispositivo físico enviado pela Microsoft para transferir grandes volumes de dados com segurança.  
- **Storage Migration Service →** migração de servidores de arquivos.  

---

## 📂 Opções de Gerenciamento de Arquivos  

- **Azure Files:** SMB/NFS para compartilhamento de arquivos, ideal para lift-and-shift.  
- **Azure File Sync:** sincroniza arquivos locais com o Azure, mantendo cache no servidor local.  
- **Blob Storage:** usado como repositório central, acessível por APIs, SDKs e Azure Storage Explorer.  

---

## 📝 Revisão Rápida  

- **Redundância:** LRS, ZRS, GRS, RA-GRS.  
- **Serviços:** Blob, Files, Queue, Table.  
- **Camadas:** Hot, Cool, Archive.  
- **Migração:** Azure Migrate, Data Box, File Sync.  
- **Endpoints:** cada recurso tem um endereço público, com controle de segurança.  

---

## ❓ Questionário: Armazenamento do Azure  

O questionário me ajudou a fixar:  
- Diferença entre camadas de acesso.  
- Escolha da redundância correta para cada cenário.  
- Quando usar Blob, Files, Queues e Tables.  
- Opções de migração mais adequadas.  

---

📘 **Este README é meu guia de estudos sobre Armazenamento no Azure.**  
Ele resume os principais pontos para revisão rápida e prática antes da prova da **AZ-900** da [DIO.me](https://www.dio.me).  

