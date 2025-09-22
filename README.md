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

---
No DIO neste treinamento é tratado somentee os dois acima, o conteudo abaixo li no manua oficial microsoft 
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

# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure  

Este README é um resumo prático sobre **como configurar recursos e dimensionamentos em Máquinas Virtuais (VMs) no Azure**.  
O objetivo é revisar os principais conceitos cobrados na **AZ-900**, de forma direta e organizada.  

---

## 📌 Introdução  

As Máquinas Virtuais (VMs) no Azure permitem rodar sistemas operacionais e aplicações de forma escalável na nuvem.  
Você pode ajustar recursos de acordo com a **necessidade de performance, custo e disponibilidade**.  

---

## 🖥️ Recursos de uma VM no Azure  

Ao criar uma VM, você pode configurar:  

- **Região** 🌍 → Define em qual datacenter sua VM ficará hospedada.  
- **Tamanho da VM** 📏 → Combinação de CPU, memória e capacidade de rede.  
- **Armazenamento** 💾 → Discos do SO e discos de dados (Standard HDD, Standard SSD ou Premium SSD).  
- **Rede** 🌐 → Conexões via IP público, VNet e regras de firewall.  
- **Sistema Operacional** 🖥️ → Windows, Linux ou imagens personalizadas.  

---

## ⚡ Dimensionamento de VMs  

O dimensionamento permite ajustar as VMs para melhor uso de recursos.  

### 🔹 Tipos de Dimensionamento  
- **Vertical (Scale Up/Down):**  
  Aumentar ou reduzir recursos (ex: trocar de uma VM B1s para D2s_v3).  

- **Horizontal (Scale Out/In):**  
  Adicionar ou remover instâncias de VM automaticamente com **Virtual Machine Scale Sets (VMSS)**.  

---

## 📊 Séries de VMs  

Cada série foi projetada para cenários específicos:  

- **B-Series:** Econômicas, workloads leves, dev/teste.  
- **D-Series:** Balanceadas, boas para aplicações de uso geral.  
- **E-Series:** Otimizadas para memória, bancos de dados.  
- **F-Series:** Otimizadas para CPU, processamento intenso.  
- **N-Series:** Projetadas para GPU, machine learning e gráficos avançados.  

---

## 🛠️ Opções de Alta Disponibilidade  

- **Availability Sets:** Distribui VMs em domínios de falha e atualização dentro de um datacenter.  
- **Availability Zones:** VMs em zonas físicas distintas dentro da mesma região.  
- **VM Scale Sets:** Gerenciamento automático de várias VMs para carga variável.  

---

## 💡 Boas Práticas  

- Escolher série/tamanho de VM de acordo com o workload.  
- Usar **Azure Advisor** para recomendações de custo e performance.  
- Configurar **autoescala** para cargas variáveis.  
- Monitorar com **Azure Monitor e Log Analytics**.  
- Sempre considerar **alta disponibilidade** em produção.  

---

## 📝 Revisão Rápida  

- **Recursos configuráveis:** Região, tamanho, SO, disco, rede.  
- **Dimensionamento:** Vertical (scale up/down) e Horizontal (scale sets).  
- **Séries:** B (econômicas), D (geral), E (memória), F (CPU), N (GPU).  
- **Disponibilidade:** Availability Sets, Zones, Scale Sets.  

---
## 💡 Segurança e Identidade na Microsoft Azure

A segurança baseada em identidade é o núcleo da proteção na nuvem Microsoft Azure. O Azure Entra ID (antigo Azure AD) é o serviço que gerencia usuários, grupos, dispositivos e aplicativos, oferecendo:

Autenticação e Autorização – Controle de logins e permissões.

MFA e SSO – Autenticação multifator e login único para apps.

Gestão de Dispositivos e Aplicativos – Integração segura com apps internos e SaaS.

A segurança é reforçada por:

Acesso Condicional – Políticas dinâmicas de login baseadas em risco.

Identity Protection – Detecção de logins suspeitos e resposta automatizada.

Governança de Identidade – Revisões de acesso, pacotes de permissões e PIM (acesso administrativo just-in-time).

Outras camadas incluem RBAC (controle de acesso por função), Key Vault (proteção de segredos) e Defender for Cloud (monitoramento de vulnerabilidades).

Boas práticas: ativar MFA, usar princípio de privilégio mínimo, monitorar eventos e automatizar provisionamento/desprovisionamento de acessos.

Em resumo, Segurança e Identidade na Azure fornecem uma base confiável para proteger recursos na nuvem, garantindo que apenas os usuários corretos tenham acesso aos dados corretos, no momento certo.

# 💰 Otimização de Custos no Microsoft Azure e Uso das Calculadoras

A **otimização de custos no Azure** é um dos pilares de uma boa estratégia de nuvem. Planejar corretamente garante que você pague apenas pelo que realmente utiliza e evita surpresas na fatura.

## 🚀 Práticas de Otimização de Custos

- **Dimensionamento Correto (Right-Sizing):** Ajuste de VMs, bancos de dados e serviços para o tamanho ideal de uso.
- **Instâncias Reservadas e Savings Plans:** Reduzem custos de cargas previsíveis ao contratar 1 ou 3 anos de uso antecipadamente.
- **Spot Instances:** Usar VMs com preço reduzido para workloads tolerantes a interrupção.
- **Monitoramento de Custos:** Utilizar **Azure Cost Management + Billing** para acompanhar gastos em tempo real.
- **Desligamento Automático:** Programar VMs de teste/dev para desligarem fora do horário comercial.

---

## 🧮 Calculadoras do Azure

A Microsoft disponibiliza **duas ferramentas diferentes** para planejamento financeiro:

### 🔢 1. Calculadora de Custo do Azure (Pricing Calculator)

🔗 [Acesse aqui](https://azure.microsoft.com/pricing/calculator/)

- Ideal para quem está **planejando novos projetos** na nuvem.
- Permite **selecionar recursos** (VMs, banco de dados, redes, etc.), escolher **região**, **quantidade** e **tempo de uso**.
- Gera **estimativa de custo mensal**, ajudando a prever quanto você pagará mês a mês.

---

### 📊 2. Calculadora de TCO (Total Cost of Ownership)

🔗 [Acesse aqui](https://azure.microsoft.com/pricing/tco-calculator/)

- Ideal para quem quer **comparar ambiente local vs. nuvem**.
- Analisa custos de hardware, energia, rede, pessoal e manutenção que você tem hoje no on-premises.
- Mostra **economia potencial** com a migração para Azure ao longo de 1, 3 ou 5 anos.

---

## 🆚 Quando Usar Cada Uma

| Cenário | Ferramenta Recomendada |
|--------|----------------------|
| Você tem um ambiente **on-premises** e quer avaliar se vale a pena migrar | **Calculadora de TCO** |
| Você já decidiu ir para a nuvem e quer saber quanto gastará **mensalmente** | **Calculadora de Custos (Pricing Calculator)** |

---

## 📌 Exemplo Prático

Imagine que você tem **10 VMs locais** rodando em seu datacenter. Você pode:

1. Inserir essas VMs na **Calculadora de TCO** para ver quanto economizaria na nuvem em 3 anos.
2. Usar a **Pricing Calculator** para escolher o tipo de VM no Azure, adicionar disco, rede, backup e obter uma **estimativa mensal detalhada**.

---

> 💡 **Dica:** Combine as duas calculadoras para criar um **business case completo** — mostre a economia no longo prazo com o TCO e o custo mensal com a Calculadora de Preço.
>
> # 🔐 Gerenciando Políticas de Acesso no Azure e Portal de Confiança da Microsoft  

Este guia apresenta os conceitos, ferramentas e boas práticas para **gerenciar políticas de acesso no Azure**, utilizar o **Portal de Confiança da Microsoft** e garantir **conformidade regulatória** no ambiente de nuvem.  

---

## 📌 Introdução  

Gerenciar políticas de acesso no Azure é um passo essencial para garantir **segurança**, **governança** e **conformidade** na nuvem.  
O **Azure Entra ID** (antigo Azure Active Directory) é o ponto central para administrar identidades e controlar quem tem acesso a quais recursos.  

Além disso, a Microsoft disponibiliza o **[Portal de Confiança da Microsoft](https://servicetrust.microsoft.com/)**, que fornece informações detalhadas sobre **compliance**, **auditorias**, **certificações** e boas práticas de segurança utilizadas na nuvem da Microsoft.  

---

## 🛡️ Gerenciamento de Políticas de Acesso  

### 🔑 Tipos de Políticas no Azure  
| Tipo de Política | Descrição | Onde Configurar |
|------------------|-----------|-----------------|
| **Políticas de Acesso Condicional** | Controlam o acesso com base em condições (localização, dispositivo, risco de login). | [Acesso Condicional no Entra ID](https://learn.microsoft.com/azure/active-directory/conditional-access/overview) |
| **Políticas de Expiração de Senha** | Definem periodicidade de troca de senha e complexidade mínima. | Entra ID → Segurança → Autenticação |
| **Políticas de MFA (Autenticação Multifator)** | Requer autenticação em duas etapas para usuários e administradores. | Entra ID → Segurança → MFA |
| **RBAC (Controle de Acesso Baseado em Função)** | Concede permissões específicas para grupos e usuários com base em funções. | [RBAC no Azure](https://learn.microsoft.com/azure/role-based-access-control/overview) |

---

## 🔎 Portal de Confiança da Microsoft  

O **[Microsoft Service Trust Portal](https://servicetrust.microsoft.com/)** é um repositório central para:  

- 📜 **Documentação de Compliance:** ISO, SOC, GDPR, LGPD e outras certificações.  
- 🔍 **Relatórios de Auditoria:** Provas de conformidade e avaliações independentes.  
- 📊 **Guias de Boas Práticas:** Configurações recomendadas para segurança e governança.  
- 🛡️ **Whitepapers de Segurança:** Estudos detalhados sobre proteção de dados e continuidade de negócios.  

---

## ✅ Conformidade e Monitoramento  

No **Azure**, você pode monitorar a conformidade utilizando:  

- **[Microsoft Purview Compliance Manager](https://learn.microsoft.com/microsoft-365/compliance/compliance-manager-overview):** Avaliação de riscos e score de compliance.  
- **[Defender for Cloud](https://learn.microsoft.com/azure/defender-for-cloud/):** Recomendação de melhorias de segurança e postura.  
- **[Azure Policy](https://learn.microsoft.com/azure/governance/policy/overview):** Criação de regras para garantir que todos os recursos sigam os padrões definidos.  

---

## 💡 Caso Real – Empresa de Finanças Migrando para Azure  

> **Cenário:**  
> Uma fintech precisava garantir que apenas funcionários autorizados pudessem acessar dados financeiros sensíveis de qualquer lugar do mundo.  

**Solução aplicada:**  
- Implementação de **Acesso Condicional** exigindo **MFA** para todos os acessos externos.  
- Definição de política que bloqueia logins vindos de países onde a empresa não opera.  
- Uso do **Azure Policy** para obrigar que todas as máquinas virtuais tenham criptografia habilitada.  
- Auditoria contínua com o **Compliance Manager** para manter aderência às exigências da LGPD.  

**Resultado:**  
- 🔒 Redução de 90% em tentativas de acesso não autorizado.  
- 📈 Conformidade com ISO 27001 e PCI-DSS em auditoria externa.  
- 💰 Evitou riscos regulatórios que poderiam gerar multas milionárias.  

---

## 📚 Recursos Úteis  

- 🔗 [Portal de Confiança da Microsoft](https://servicetrust.microsoft.com/)  
- 📖 [Documentação do Acesso Condicional](https://learn.microsoft.com/azure/active-directory/conditional-access/overview)  
- 🛡️ [Visão Geral do Azure Policy](https://learn.microsoft.com/azure/governance/policy/overview)  
- ✅ [Compliance Manager – Microsoft Purview](https://learn.microsoft.com/microsoft-365/compliance/compliance-manager-overview)  

---

## 📌 Conclusão  

Gerenciar políticas de acesso e usar o Portal de Confiança é fundamental para manter a **segurança**, **conformidade regulatória** e **governança corporativa** no Azure.  
Seguindo boas práticas, como MFA, RBAC e políticas de compliance, é possível reduzir riscos e melhorar a postura de segurança da sua organização.

---
# Azure: Ferramentas de Implantação, Governança e Conformidade

## 1. Ferramentas de Implantação na Azure
A **Microsoft Azure** oferece diversas ferramentas para implantar, configurar e gerenciar recursos de forma **consistente, escalável e segura**.  

### 🔹 1.1 Portal do Azure
- Interface gráfica baseada em navegador.  
- Ideal para iniciantes e tarefas administrativas rápidas.  
- Dashboards personalizáveis e monitoramento em tempo real.  

### 🔹 1.2 Azure CLI
- Ferramenta **multiplataforma** em linha de comando.  
- Sintaxe baseada em `az <comando>`.  
- Permite **automação** e integração com **scripts** e **DevOps**.  

### 🔹 1.3 Azure PowerShell
- Focado em administradores Windows.  
- Oferece **cmdlets** para automação e orquestração.  
- Integra-se ao Active Directory.  

### 🔹 1.4 Modelos ARM (Azure Resource Manager)
- Arquivos **JSON** para provisionamento declarativo.  
- Suporte a **Infraestrutura como Código (IaC)**.  
- Consistência, versionamento e repetibilidade.  

### 🔹 1.5 Bicep
- Linguagem declarativa simplificada.  
- Sintaxe mais limpa que ARM Templates.  
- Facilita criação, manutenção e reutilização de templates.  

### 🔹 1.6 Azure DevOps e GitHub Actions
- Suporte a **CI/CD (Integração Contínua e Entrega Contínua)**.  
- Automação de testes, versionamento e deploy.  

---

## 2. Primeiros Passos em Governança e Conformidade
Governança e conformidade são essenciais para garantir que os recursos na nuvem sigam regras corporativas, legais e de segurança.  

### 🔹 2.1 Azure Policy
- Criação e aplicação de **políticas** para recursos.  
- Exemplos:  
  - Restringir uso de regiões.  
  - Exigir **tags** em recursos.  
  - Forçar uso de VMs aprovadas.  

### 🔹 2.2 Azure Blueprints
- Conjuntos de **modelos de governança**.  
- Integram políticas, permissões e grupos de recursos.  
- Garantem consistência entre ambientes (Dev, Homolog, Prod).  

### 🔹 2.3 Role-Based Access Control (RBAC)
- Controle de acesso baseado em funções.  
- Aplica o princípio do **menor privilégio**.  
- Permite delegar acesso granular.  

### 🔹 2.4 Microsoft Purview (Governança de Dados)
- Classificação e rastreamento de **dados sensíveis**.  
- Ajuda a cumprir **LGPD** e **GDPR**.  
- Facilita auditorias e relatórios.  

### 🔹 2.5 Azure Security Center e Compliance Manager
- **Defender for Cloud (ex-Security Center):** monitora postura de segurança e detecta ameaças.  
- **Compliance Manager:** fornece relatórios e auditorias para conformidade regulatória.  

---

## 3. Rede e Conectividade na Azure
Além da implantação de recursos de computação e dados, a **rede (Networking)** é parte essencial da governança e conformidade.  

### 🔹 3.1 Virtual Network (VNet)
- Permite criar redes virtuais privadas na Azure.  
- Segrega e organiza recursos (VMs, bancos de dados, apps).  
- Suporte a **sub-redes, firewalls e roteamento personalizado**.  

### 🔹 3.2 Network Security Groups (NSG)
- Controlam o tráfego de entrada e saída em sub-redes ou interfaces de rede.  
- Regras configuráveis para **segurança de acesso**.  

### 🔹 3.3 Azure Firewall
- Firewall gerenciado e escalável.  
- Políticas centralizadas de segurança de rede.  

### 🔹 3.4 Azure ExpressRoute e VPN Gateway
- **ExpressRoute**: conexão dedicada e privada entre datacenters on-premises e a Azure.  
- **VPN Gateway**: conexões criptografadas via internet.  

### 🔹 3.5 Governança de Rede
- **Azure Policy + VNet**: restringir criação de recursos fora da rede corporativa.  
- **Monitoramento com Network Watcher**: análise de tráfego, logs e conformidade.  

---

## 4. Conclusão
- Ferramentas de **implantação** (Portal, CLI, PowerShell, ARM, Bicep, DevOps) permitem **provisionamento eficiente**.  
- Soluções de **governança** (Policy, Blueprints, RBAC, Purview, Compliance) garantem **segurança e conformidade**.  
- Serviços de **rede (VNet, NSG, Firewall, ExpressRoute, VPN)** asseguram **conectividade segura e governança de tráfego**.  

Assim, é possível construir ambientes na Azure que sejam **robustos, escaláveis, seguros e aderentes às normas corporativas e legais**.  

---
# 📊 Monitoramento Inteligente com o Azure

O **Monitoramento Inteligente** dentro da **Microsoft Azure** é um dos pilares da governança e da operação em nuvem.  
Ele garante que os serviços, aplicações e recursos de infraestrutura sejam acompanhados de forma proativa, utilizando **métricas, logs e recomendações** para manter:

- ✅ Disponibilidade  
- ⚡ Desempenho  
- 🔒 Segurança  
- 💰 Otimização de custos  

---

## 🚀 Ferramentas de Implantação do Azure

Para que o monitoramento seja efetivo, é necessário implantar os recursos seguindo boas práticas. O Azure oferece ferramentas que ajudam na **automação** e na **padronização** da configuração de monitoramento:

- **Azure Resource Manager (ARM Templates)** → implantação de ambientes já preparados com métricas e diagnósticos habilitados.  
- **Azure CLI / PowerShell** → automação de implantação com scripts que incluem parâmetros de monitoramento.  
- **Terraform / Bicep** → infraestrutura como código, garantindo monitoramento integrado em cada recurso.  
- **Azure Policy** → aplicação de políticas que forçam a coleta de métricas e logs em todos os serviços.  

---

## 🔎 Serviços de Monitoramento do Azure

O Azure disponibiliza um **ecossistema robusto** para monitorar recursos, aplicações e usuários:

- **Azure Monitor** → serviço central de monitoramento, coleta métricas e logs de praticamente todos os recursos.  
- **Application Insights** → monitoramento de aplicações, performance, dependências e rastreamento de falhas.  
- **Azure Service Health** → visibilidade de incidentes e manutenção programada da própria plataforma Azure.  
- **Azure Advisor** → recomendações automáticas de desempenho, segurança e custo.  
- **Azure Security Center (Defender for Cloud)** → insights de segurança e conformidade.  

---

## 👀 Visão dos Serviços de Monitoramento

O monitoramento no Azure é estruturado em camadas complementares:

- **Infraestrutura** → VMs, redes, discos e bancos de dados.  
- **Aplicações** → APIs, tempo de resposta, erros e dependências externas.  
- **Plataforma** → incidentes globais ou regionais da Azure.  
- **Segurança e Custos** → compliance, governança e otimização de gastos.  

---

## 📈 Métricas e Logs

- **Métricas** → dados numéricos em tempo real (CPU, latência de rede, requisições/segundo).  
- **Logs** → registros detalhados de eventos (logins, falhas, alterações em recursos).  

🔗 Todos esses dados podem ser enviados ao **Log Analytics Workspace**, consultados com **Kusto Query Language (KQL)**.  

---

## 🖥️ Azure Monitor

O **Azure Monitor** é o núcleo do monitoramento da nuvem Microsoft. Ele fornece:

- Coleta unificada de métricas e logs  
- Painéis no **Azure Dashboard** e integração com **Power BI**  
- **Alertas automatizados** (e-mail, SMS, Teams ou Webhooks)  
- Integração com **Machine Learning** para detecção de anomalias  

---

## ⚙️ Ferramentas dentro do Azure Monitor

### 🔹 Insights
- **Application Insights** → performance, dependências, telemetria e diagnóstico avançado.  
- **VM Insights** → utilização, processos e estado das máquinas virtuais.  
- **Container Insights** → monitoramento de clusters Kubernetes (AKS).  

### 🔹 Service Health
- Incidentes da própria Azure, manutenções planejadas e avisos de saúde.  
- **Exemplo prático:** Se um datacenter no Brasil estiver em manutenção, o Service Health emite alerta para os clientes afetados.  

### 🔹 Alertas
- Configurados para métricas ou logs específicos (ex.: CPU acima de 80%).  
- Podem disparar **ações automáticas**, como escala horizontal de VMs.  

### 🔹 Advisor
- Recomendações em **Custo, Segurança, Desempenho e Alta Disponibilidade**.  
- **Exemplo:** detectar que uma VM está sobredimensionada e sugerir downgrade para reduzir custos.  

---

## 🌐 Importância do Azure Monitor

A utilização do Azure Monitor é estratégica porque:

- 🔄 Garante **disponibilidade e resiliência** dos serviços.  
- 🛡️ Oferece **segurança proativa**, detectando riscos em tempo real.  
- 💸 Apoia a **otimização de custos**, evitando recursos subutilizados.  
- 🎯 Melhora a **experiência do usuário final** com análises de performance.  

---

## ✅ Validação dos Serviços de Monitoramento

Checklist para validar se o monitoramento está habilitado corretamente:

- [ ] Diagnósticos ativados em cada recurso (VMs, bancos, redes).  
- [ ] Dados fluindo para o **Log Analytics Workspace**.  
- [ ] Testes de alertas configurados (ex.: gerar carga em uma VM).  
- [ ] Dashboards e relatórios com métricas críticas visíveis.  
- [ ] Recomendações do **Advisor** e do **Defender for Cloud** aplicadas.  

---

## 📌 Conclusão

👉 O **Monitoramento Inteligente com o Azure** é a soma de:

- **Azure Monitor**  
- **Application Insights**  
- **Service Health**  
- **Azure Advisor**  

Esses serviços, quando usados em conjunto, entregam **segurança, performance e economia**, com base em **métricas, logs detalhados e recomendações automatizadas**.  



📘 **Este README é um guia de estudos sobre Configuração e Dimensionamento de VMs no Azure.**  
Ele resume os pontos-chave para revisão rápida e prática antes da prova da **AZ-900**.

