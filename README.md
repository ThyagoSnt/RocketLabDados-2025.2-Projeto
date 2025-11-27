<h1 align="center">🚀 Rocket Lab 2025: Case V-Credit 🚀</h1>


<h4 align="center">Solução de Engenharia de Dados e Business Intelligence desenvolvida pela DataFreaks para o desafio de transformação digital da V-Credit.</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge" alt="Status Concluído">
  <img src="https://img.shields.io/badge/Versão-1.0.0-blue?style=for-the-badge" alt="Versão 1.0">
  <img src="https://img.shields.io/badge/Databricks-Community-orange?style=for-the-badge" alt="Databricks">
</p>

<br />

## 🏢 Sobre o Case V-Credit

A **V-Credit** é uma instituição financeira com 30 anos de mercado, enfrentando desafios com a digitalização de seus canais de atendimento. O aumento no volume de interações digitais (App, Chatbot, URA) gerou fragmentação de dados, altos custos operacionais e dificuldade em medir a satisfação do cliente.

**O Desafio:**
Estruturar uma base de dados confiável e unificada para permitir análises estratégicas que reduzam custos e melhorem a experiência do cliente (CX).

<br />

## 🎯 Nossa Solução

Desenvolvemos uma solução completa "end-to-end", dividida em duas frentes principais:

### 🛠️ 1. Engenharia de Dados (Arquitetura Medalhão)
Implementamos um pipeline de dados robusto no **Databricks**, seguindo as melhores práticas de Lakehouse:

* **Camada Bronze:** Ingestão dos dados brutos (CSV/Excel) sem tratamento.
* **Camada Silver:** Limpeza, deduplicação, tratamento de tipos e padronização (Ex: categorização de motivos e canais).
* **Camada Gold:** Tabelas agregadas e modelos dimensionais (Star Schema) prontos para análise de negócio.

### 📊 2. Inteligência de Negócio (Business Analytics)
Utilizamos os dados tratados para gerar insights acionáveis focados em:
* **Redução de Custos:** Identificação de gargalos no Nível 2 de atendimento.
* **Eficiência de Canais:** Análise comparativa entre URA, Chatbot e Atendimento Humano.
* **Jornada do Cliente:** Mapeamento de ofensores de satisfação (NPS/CSAT).

<br />

## 💻 Stack Tecnológico

<p align="center">
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

<br />

## 📂 Estrutura do Projeto

```bash
├── 📁 database/              # Bases de dados originais 
├── 📁 notebooks/          # Códigos PySpark/SQL
│   ├── land_to_bronze.ipynb
│   ├── bronze_to_silver.ipynb
│   └── silver_to_gold.ipynb
├── 📁 diagrams/          # Arquivos de visualização
└── README.md
```
<br />




## 👨‍💻 Membros da Equipe

Conheça os **DataFreaks** - nossa equipe de desenvolvedores:

<table align="center">
<tr>
    <td align="center" width="150px">
        <a href="https://github.com/ThyagoSnt">
            <img src="https://github.com/ThyagoSnt.png" width="115px" style="border-radius: 50%;" alt="Thyago Santos"/>
            <br />
            <sub><b>Thyago Santos</b></sub>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://github.com/SardinhaK">
            <img src="https://github.com/SardinhaK.png" width="115px" style="border-radius: 50%;" alt="Péricles Sardinha"/>
            <br />
            <sub><b>Péricles Sardinha</b></sub>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://github.com/Breno-Lira">
            <img src="https://github.com/Breno-Lira.png" width="115px" style="border-radius: 50%;" alt="Breno Lira"/>
            <br />
            <sub><b>Breno Lira</b></sub>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://github.com/markfranca">
            <img src="https://github.com/markfranca.png" width="115px" style="border-radius: 50%;" alt="Marcus França"/>
            <br />
            <sub><b>Marcus França</b></sub>    
        </a>
    </td>
        <td align="center" width="150px">
        <a href="https://github.com/jpbezerra">
            <img src="https://github.com/jpbezerra.png" width="115px" style="border-radius: 50%;" alt="João Bezerra"/>
            <br />
            <sub><b>João Bezerra</b></sub>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://github.com/felipecisneiros">
            <img src="https://github.com/felipecisneiros.png" width="115px" style="border-radius: 50%;" alt="Felipe Cisneiros"/>
            <br />
            <sub><b>Felipe Cisneiros</b></sub>
        </a>
    </td>
</tr>
</table>

<br />

## 🌟 Nossos Valores

Como **DataFreaks**, acreditamos em:

- 💡 **Inovação**: Sempre buscando soluções criativas e tecnologias emergentes
- 🤝 **Colaboração**: Trabalho em equipe e compartilhamento de conhecimento
- 🎯 **Excelência**: Comprometimento com a qualidade em cada linha de código
- 🚀 **Crescimento**: Aprendizado contínuo e desenvolvimento pessoal/profissional
- 🌍 **Impacto**: Criar soluções que fazem diferença na vida das pessoas

<br />

---

<p align="center">
    <br />
    <em>RocketLab 5.0 - Visagio</em>
</p>