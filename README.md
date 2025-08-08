# 📊 Dashboard de Salários na Área de Dados

Um aplicativo interativo desenvolvido em **Streamlit** para análise de salários na área de dados, criado durante a *Imersão de Dados* da [Alura](https://www.alura.com.br/).  
O projeto permite explorar tendências salariais por ano, senioridade, tipo de contrato, tamanho da empresa e localização, utilizando gráficos dinâmicos e KPIs.

---

## 📋 Índice
1. [Introdução](#introdução)  
2. [Funcionalidades](#funcionalidades)  
3. [Instalação](#instalação)  
4. [Uso](#uso)  
5. [Dependências](#dependências)  
6. [Configuração](#configuração)  
7. [Exemplos de Análises](#exemplos-de-análises)  
8. [Problemas Comuns](#problemas-comuns)  
9. [Contribuidores](#contribuidores)  
10. [Licença](#licença)  

---

## 📖 Introdução
O **Dashboard de Salários na Área de Dados** foi criado para oferecer uma visão clara e interativa sobre os salários no setor de dados nos últimos anos.  
O objetivo é ajudar profissionais e empresas a entenderem o cenário global de remuneração na área de dados.

O dataset utilizado contém informações como:
- Ano
- Cargo
- Senioridade
- Tipo de contrato
- Tamanho da empresa
- Localização
- Salário anual (USD)

---

## 🚀 Funcionalidades

✅ **Filtros Interativos** — ajuste ano, senioridade, tipo de contrato e tamanho da empresa.  
✅ **KPIs em Destaque** — salário médio, salário máximo, total de registros e cargo mais frequente.  
✅ **Gráficos Dinâmicos**:  
- 📈 *Top 10 cargos por salário médio*  
- 📊 *Distribuição de salários anuais*  
- 🥧 *Proporção dos tipos de trabalho (remoto, híbrido, presencial)*  
- 🌍 *Mapa de salários médios de Cientistas de Dados por país*  
✅ **Tabela de Dados Filtrada** para análise detalhada.  

---

## 🛠 Instalação

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Crie um ambiente virtual**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶ Uso

Execute o aplicativo Streamlit:
```bash
streamlit run app.py
```
O dashboard abrirá no seu navegador (por padrão em `http://localhost:8501`).

💡 *Dica:* Você pode hospedar no **Streamlit Cloud** para acessar online.

---

## 📦 Dependências
- [pandas==2.2.3](https://pandas.pydata.org/) — Manipulação de dados  
- [streamlit==1.44.1](https://streamlit.io/) — Interface web interativa  
- [plotly==5.24.1](https://plotly.com/python/) — Visualizações dinâmicas  

---

## ⚙ Configuração
O app carrega dados de:
```
https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv
```
🔗 É necessário ter conexão à internet para funcionar.

---

## 📊 Exemplos de Análises

**1. Salário médio por cargo**  
![Top 10 Cargos](https://via.placeholder.com/800x400.png?text=Top+10+Cargos+por+Sal%C3%A1rio)

**2. Distribuição de salários anuais**  
![Distribuição Salarial](https://via.placeholder.com/800x400.png?text=Distribui%C3%A7%C3%A3o+Salarial)

**3. Proporção de tipos de trabalho**  
![Proporção Trabalho](https://via.placeholder.com/800x400.png?text=Tipos+de+Trabalho)

**4. Mapa de salários de Cientistas de Dados**  
![Mapa Global](https://via.placeholder.com/800x400.png?text=Mapa+de+Sal%C3%A1rios)

---

## 🐞 Problemas Comuns

| Problema | Causa | Solução |
|----------|-------|---------|
| Gráficos em branco | Filtros sem correspondência no dataset | Ajuste os filtros |
| Erro ao carregar dados | Sem conexão com a internet | Verifique sua rede |
| Versões incompatíveis | Dependências desatualizadas | Use `pip install -r requirements.txt` |

---

## 👥 Contribuidores
Projeto desenvolvido durante a **Imersão de Dados** da [Alura](https://www.alura.com.br/) por:
- **[Seu Nome]**

---

## 📄 Licença
Este projeto está licenciado sob a **MIT License** — use, modifique e compartilhe livremente.

---
💙 *Se este projeto te ajudou, deixe uma ⭐ no repositório!*
