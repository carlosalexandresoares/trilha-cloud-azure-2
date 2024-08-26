# trilha-cloud-azure-2
 desafio da dio

# Guia para Criar Máquinas Virtuais no Microsoft Azure

Este guia oferece um passo a passo claro para criar máquinas virtuais (VMs) no portal do Microsoft Azure.

## Sumário
- [Requisitos Necessários](#requisitos-necessários)
- [Guia de Criação de Máquinas Virtuais](#guia-de-criação-de-máquinas-virtuais)
  1. [Acessar o Portal do Azure](#acessar-o-portal-do-azure)
  2. [Navegar até "Máquinas Virtuais"]( #navegar-até-máquinas-virtuais)
  3. [Criar uma Nova Máquina Virtual](#criar-uma-nova-máquina-virtual)
  4. [Configurar a Máquina Virtual](#configurar-a-máquina-virtual)
  5. [Revisar e Criar](#revisar-e-criar)
- [Dicas Adicionais](#dicas-adicionais)
- [Recursos Úteis](#recursos-úteis)

## Requisitos Necessários
- Conta ativa no Microsoft Azure.
- Acesso ao portal do Azure em [portal.azure.com](https://portal.azure.com).
- Permissões necessárias para criar recursos no Azure.

## Guia de Criação de Máquinas Virtuais

### Acessar o Portal do Azure
- Abra seu navegador e vá até [portal.azure.com](https://portal.azure.com).
- Faça login com suas credenciais da conta Microsoft Azure.

### Navegar até "Máquinas Virtuais"
- No painel à esquerda do portal, clique em "Máquinas Virtuais".
- Você será direcionado para a página de gerenciamento de máquinas virtuais.

### Criar uma Nova Máquina Virtual
- Na página "Máquinas Virtuais", clique em "Adicionar" ou "Criar máquina virtual".
- Você será levado à página de configuração da nova VM.

### Configurar a Máquina Virtual
1. **Informações Básicas:**
   - **Assinatura:** Selecione a assinatura do Azure que será utilizada.
   - **Grupo de Recursos:** Escolha um grupo de recursos existente ou crie um novo.
   - **Nome da VM:** Insira um nome para a máquina virtual.
   - **Região:** Escolha a região onde a VM será hospedada.
   - **Opções de Disponibilidade:** Configure conforme suas necessidades (ex: Conjunto de Disponibilidade ou Zona de Disponibilidade).

2. **Imagem e Tamanho:**
   - **Imagem:** Selecione o sistema operacional e a imagem da VM (ex: Windows Server, Ubuntu, etc.).
   - **Tamanho da VM:** Escolha o tamanho da VM conforme a necessidade de recursos (CPU, memória).

3. **Configurações de Administração:**
   - **Nome de Usuário:** Insira o nome de usuário do administrador.
   - **Autenticação:** Escolha entre senha ou chave pública SSH (recomendado para Linux).

4. **Discos:**
   - Configure o tipo e tamanho dos discos (disco do sistema operacional e discos de dados adicionais, se necessário).

5. **Rede:**
   - Configure a rede virtual, sub-rede e outras opções de rede, como IP público e grupos de segurança de rede (NSG).

6. **Gerenciamento, Monitoramento e Outras Configurações:**
   - Configure opções adicionais como diagnósticos de inicialização, monitoramento, identidade gerenciada, etc.

### Revisar e Criar
- Após configurar todas as opções, clique em "Revisar e criar".
- Revise todas as configurações na tela de revisão.
- Se tudo estiver correto, clique em "Criar".
- Aguarde enquanto a VM é provisionada e implantada. Esse processo pode levar alguns minutos.

## Dicas Adicionais
- Utilize a funcionalidade de modelos do Azure para reutilizar configurações de VMs em novas implantações.
- Verifique a compatibilidade de software e os requisitos de rede antes de escolher uma imagem de VM.
- Use tags para organizar e gerenciar melhor os recursos no Azure.
