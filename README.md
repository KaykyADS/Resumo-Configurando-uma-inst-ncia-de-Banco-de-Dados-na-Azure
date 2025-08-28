# Resumo-Configurando-uma-instancia-de-Banco-de-Dados-na-Azure

# Criando uma Instância Gerenciada de SQL do Azure

## 1. Criar a instância pelo Azure
- No portal, selecione **SQL do Azure** e clique em **Criar**.  
- Configure:
  - Tipo: **Instância única**  
  - Assinatura e grupo de recursos  
  - Nome da instância: `mysqlteste`  
  - Região: **West US 2**  
  - Autenticação: **SQL** e **Microsoft Entra**  

---

## 2. Configurando armazenamento
- Série: **Standard**  
- Geração de hardware  
- **4 vCores** e **20 GB** de memória  
- **32 GB** de armazenamento  
- Licenciamento: **Pagamento conforme o uso**  

---

## 3. Configurando Rede
- Tipo de conexão: **Proxy**  
- Ponto de extremidade público: **Desabilitado**  

---

## 4. Restante das configurações
- Em **Segurança** e **Configurações adicionais**, mantive os valores padrão.  
- Finalizei a criação da instância.  

---
