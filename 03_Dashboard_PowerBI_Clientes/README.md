# 📊 Projeto 3 – Dashboard de Clientes (Power BI)

Este é o terceiro projeto da minha trilha prática, seguindo os dois anteriores (levantamento de requisitos e plano de testes).  
Aqui eu transformei uma base simples de clientes e compras em um dashboard visual feito no Power BI.

O objetivo foi criar algo direto, organizado e fácil de interpretar.

---

## 🎯 Objetivos do Projeto

- Criar uma base fictícia em Excel/Sheets
- Modelar os dados no Power BI
- Criar indicadores principais (cards)
- Montar gráficos simples e claros
- Organizar o dashboard de forma visual
- Exportar tudo em PDF para apresentação
- Documentar no GitHub

---

## 🧱 Estrutura dos Dados

### **Tabela Clientes**
- `id_cliente`  
- `nome_cliente`  
- `data_cadastro`  
- `cidade`  
- `estado`  
- `status_cliente`  

### **Tabela Compras**
- `id_compra`  
- `id_cliente`  
- `data_compra`  
- `valor_compra`  

### 🔗 Relacionamento utilizado

```
Clientes (id_cliente) 1 → N Compras (id_cliente)
```

---

## 📊 Visuais Criados

### **Indicadores (cards)**
- 👥 Total de clientes  
- 🛒 Total de compras  
- 💰 Média de valor gasto  

### **Gráficos**
- 📈 Cadastros por mês (colunas)  
- 📉 Clientes por cidade (barras)  

O foco foi criar um painel simples, objetivo e fácil de entender.

---

## 🛠️ Tecnologias Utilizadas
- Power BI Desktop  
- Excel / Google Sheets  
- GitHub  

---

## 📁 Estrutura do Repositório

```
03_Dashboard_PowerBI_Clientes/
├── dados/
│   └── base_clientes_compras.xlsx
├── dashboard/
│   └── dashboard_clientes.pbix
├── docs/
│   └── Dashboard_Clientes_Projeto3.pdf
├── imagens/
│   └── dashboard_clientes_tela.png
└── README.md
```

---

## ▶️ Como abrir o projeto

1. Baixe o arquivo `.pbix`  
2. Abra no **Power BI Desktop**  
3. Se necessário, ajuste o caminho da planilha na pasta `dados/`  
4. Atualize os dados para visualizar o dashboard  

---

## 🔗 Conexão com os Projetos Anteriores

- No **Projeto 1**, fiz o levantamento e estrutura básica do sistema de cadastro  
- No **Projeto 2**, criei os cenários de teste  
- No **Projeto 3**, utilizei uma base fictícia inspirada nos dados anteriores para gerar indicadores no Power BI  

---

## 📸 Resultado Final

O dashboard apresenta:
- Evolução mensal de cadastros  
- Distribuição de clientes por cidade  
- Indicadores gerais (total de clientes, total de compras e média de gasto)  

---

✔ Projeto concluído.
