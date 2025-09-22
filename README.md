# banco-de-dados-DIO-AZ900

# Laboratório Azure SQL - Curso AZ-900 (DIO)

Este repositório contém minhas anotações e prática realizadas durante o laboratório do curso **AZ-900 Microsoft Azure Fundamentals** pela DIO.  
O objetivo é aplicar conceitos da computação em nuvem e registrar a experiência de criação de um **Banco de Dados SQL no Azure**.

---

## Objetivos do Desafio
- Praticar a criação e configuração de uma instância SQL no Azure.  
- Documentar o processo técnico de forma clara.  
- Utilizar o GitHub como repositório de anotações e material de apoio.  

---

## Resumos e Anotações

### Tipos de Serviço de Nuvem
- **IaaS (Infraestrutura como Serviço)**  
  Trabalha com uma infraestrutura já existente, mas o usuário gerencia toda a parte lógica, como **sistema operacional, softwares e configurações**.  
  Exemplo: **Azure Virtual Machines**.  

- **PaaS (Plataforma como Serviço)**  
  Já disponibiliza a infraestrutura e aplicativos necessários para desenvolvimento. O foco do usuário é **a aplicação e o código**, sem se preocupar com o sistema operacional ou middleware.  
  Exemplo: **Azure App Service**.  

- **SaaS (Software como Serviço)**  
  O usuário apenas consome o **aplicativo final**, sem precisar gerenciar infraestrutura ou plataforma.  
  Exemplos: **Microsoft 365, Netflix**.  

---

### Modelo de Responsabilidade Compartilhada
No Azure (e em outros provedores de nuvem), a **responsabilidade pela segurança e gestão** é dividida entre o **cliente** e o **provedor de nuvem**.  

- **Cliente (usuário/empresa):**  
  É responsável pelos **dados, acesso de usuários, configurações e políticas de segurança internas**.  
  Exemplo: proteger senhas, gerenciar permissões e definir firewalls.  

- **Provedor de Nuvem (Microsoft):**  
  É responsável pela **infraestrutura física, rede, datacenter, hardware, energia e redundância**.  

Em resumo: o cliente gerencia **o que ele controla na nuvem**, enquanto a Microsoft garante que a nuvem em si esteja disponível, estável e segura.  

---

## Passo a Passo (Laboratório SQL no Azure)
1. Acessar o [portal do Azure](https://portal.azure.com).  
2. Criar um novo recurso → **Banco de Dados SQL**.  
3. Definir grupo de recursos, nome do servidor e credenciais de administrador.  
4. Escolher plano de performance (DTUs ou vCores).  
5. Configurar regras de firewall para acesso externo.  
6. Conectar-se via Azure Data Studio ou SQL Server Management Studio.  

---

## Dicas
- Sempre revisar o **pricing tier** para evitar custos altos.  
- Organizar recursos em **resource groups** facilita gestão e exclusão.  
- Utilizar **tags** para identificar projetos, ambiente (dev/test/prod).  

---

## Evidências
(Imagens armazenadas em `/images` com prints das etapas principais)  

---

## Recursos Úteis
- [Documentação oficial - Azure SQL](https://learn.microsoft.com/azure/azure-sql/)  
- [Portal do Azure](https://portal.azure.com/)  
