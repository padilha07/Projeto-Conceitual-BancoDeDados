# 🏦 Modelo Conceitual de Banco de Dados - Sistema de Propriedade e Bancos

## 📌 Descrição do Projeto  
Este projeto representa o **Modelo Entidade-Relacionamento (MER)** para um sistema de **gerenciamento de propriedades e bancos**.  
O sistema envolve **pessoas, empresas, bancos e a relação de propriedade entre eles**.

## 🎯 Objetivos do Sistema  
✅ Registrar informações de **pessoas e empresas**.  
✅ Relacionar **pessoas e empresas a propriedades**.  
✅ Gerenciar a relação entre **bancos e clientes**.  
✅ Armazenar **endereços e nomes de entidades**.  

## 📊 Modelo Conceitual  
Abaixo está o **diagrama entidade-relacionamento (DER)** do sistema:

## 🔗 Estrutura do Banco de Dados  
O banco de dados segue um **modelo relacional**, garantindo integridade e organização.

### **📌 Entidades e Relacionamentos**
1. **Person (Pessoa)**  
   - Possui atributos: `CPF`, `Nome`, `Endereço`.  
   - Relacionada ao **Owner** (Proprietário) através da entidade **U**.  

2. **Company (Empresa)**  
   - Possui atributos: `Cname` (Nome da Empresa), `Caddress` (Endereço).  
   - Relacionada ao **Owner** (Proprietário) através da entidade **U**.  

3. **Bank (Banco)**  
   - Possui atributos: `Bname` (Nome do Banco), `Baddress` (Endereço).  
   - Relacionado à entidade **U**.  

4. **U (Relacionamento Intermediário)**  
   - Conecta **Person, Company e Bank** à entidade **Owner**.  

5. **Owner (Proprietário)**  
   - Determina a propriedade entre os participantes do sistema.  
![Diagrama Conceitual](img/ModeloEntidadeRelacionamentoBanco.drawio.png)
