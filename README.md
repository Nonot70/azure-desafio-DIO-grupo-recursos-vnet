# 🚀 Desafio – Construindo Arquiteturas no Azure: Grupo de Recursos e Rede Virtual  

Este repositório faz parte do meu aprendizado no **Bootcamp Microsoft Azure AZ-900**, promovido pela DIO em parceria com a Microsoft.  
O objetivo deste desafio é consolidar os conceitos de **organização e infraestrutura na nuvem**, criando um **Grupo de Recursos** e uma **Rede Virtual (VNET)** no portal do Azure.  

---

## 🎯 Objetivos do Desafio  

- Criar um **Grupo de Recursos** para organizar os recursos de forma lógica.  
- Provisionar uma **Rede Virtual (VNET)** dentro desse grupo, simulando a criação de uma camada de rede.  
- Explorar as principais funcionalidades de gerenciamento e boas práticas no uso do Azure.  

---

## 🛠️ Passo a Passo  

### 🔹 Criando o Grupo de Recursos  

1. No portal do Azure, acesse **Grupos de Recursos**.  
2. Clique em **Criar** e preencha:  
   - **Assinatura**: utilize a assinatura padrão.  
   - **Nome do grupo de recursos**: `RG-AZ900-LAB`.  
   - **Região**: selecione a mais próxima de você ou a que se encaixa no cenário (ex.: *Brazil South*).  
3. (Opcional) Adicione **tags** para identificar projetos, responsáveis ou centros de custo.  
4. Clique em **Revisar + Criar** e depois em **Criar**.  

🔎 **Explorando recursos do Grupo de Recursos:**  
- **Log de atividades** → histórico de ações realizadas.  
- **Controle de acesso (IAM)** → gerenciar permissões de usuários.  
- **Visualizador de recursos** → exibe graficamente os relacionamentos.  
- **Marcações (tags)** → ajudam no controle de custos e organização.  

---

### 🔹 Criando a Rede Virtual (VNET)  

1. No portal, pesquise por **Rede Virtual** e clique em **Criar**.  
2. Preencha as informações:  
   - **Assinatura**: mantenha a padrão.  
   - **Grupo de recursos**: selecione o criado anteriormente (`RG-AZ900-LAB`).  
   - **Nome da rede virtual**: `VNET-AZ900`.  
   - **Região**: escolha a mesma do grupo ou outra, conforme necessidade (ex.: *Brazil South*).  
3. Configure as opções de **endereçamento IP** (mantendo as sugestões padrão para este laboratório).  
4. Clique em **Revisar + Criar** e finalize com **Criar**.  

---

## 💡 Observações Importantes  

- O **Grupo de Recursos** funciona como uma "pasta lógica" onde você organiza serviços relacionados.  
- Uma **VNET** é essencial para criar a comunicação entre recursos dentro do Azure, como máquinas virtuais, bancos de dados e aplicações.  
- É possível criar recursos em regiões diferentes do grupo, o que traz **flexibilidade** em cenários reais.  
- O uso de **tags** é altamente recomendado em ambientes corporativos para **monitorar custos, segurança e governança**.  

---

## 📚 O que Aprendi  

- A importância da **organização lógica** no Azure através de grupos de recursos.  
- Como **redes virtuais** são a base para a comunicação entre serviços.  
- A flexibilidade de escolher diferentes regiões para recursos e grupos.  
- Boas práticas de governança com **IAM e tags**.  

---

## 🏁 Conclusão  

Este desafio reforçou conceitos fundamentais de infraestrutura em nuvem.  
A criação de **Grupos de Recursos** e **Redes Virtuais** é a porta de entrada para entender como arquiteturas em nuvem são estruturadas no Azure.  

📌 **Próximos passos**: explorar **sub-redes**, **máquinas virtuais** e **segurança de rede** dentro da VNET criada.  
