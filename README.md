Olá, bom dia.

Este é meu repositório do treinamento AZ-900 azure na DIO.me

Estou em migração para Dados e meu foco em Azure, este é meu 3 bootcamp na Dio.
estou muito confiante , já aprendi a definição de Cloud
Nuvem e classificações de nuvens
A nuvem pode ser classificada em:
•	Nuvem Pública: infraestrutura fornecida por terceiros (ex.: Microsoft Azure), acessível a múltiplos clientes em modelo multi-tenant.
•	Nuvem Privada: infraestrutura dedicada, usada exclusivamente por uma organização, podendo ser local (on-premises) ou hospedada em data center externo.
•	Nuvem Híbrida: combinação entre nuvem pública e privada, permitindo maior flexibilidade e integração.

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
