# 🎭 Mapas Culturais - Extração e Tratamento de Dados

Este repositório foi criado para organizar e facilitar a análise de dados dos **agentes culturais** extraídos da plataforma [Mapas Culturais](https://mapas.cultura.gov.br/). Ele contém scripts de **extração**, **higienização**, **organização** e **visualização** de dados, além de planilhas auxiliares para padronização.

---

 <div align="center">
  <a href="https://mapas.cultura.gov.br/" target="_blank">
    <img src="https://github.com/dsilvaphy/Mapas-Culturais-Gov/blob/main/Mapa_da_Cultura.png" alt="printmapas" width="850" height="460">
  </a>  
 </div>
 
---

## 🚀 Funcionalidades

1. **Extração de Dados**
   - Obtenha informações detalhadas dos agentes culturais usando a **API Mapas Culturais**.
2. **Higienização e Padronização**
   - Prepare os dados para análises, corrigindo inconsistências e duplicidades.
3. **Organização de Áreas de Atuação**
   - Gere uma planilha com múltiplas áreas de atuação por agente.
4. **Exportação Filtrada**
   - Crie planilhas segmentadas por estado, cidade ou área de atuação.
5. **Visualização**
   - Analise as estatísticas com dashboards criados no Power BI.

---

## 🗂️ Estrutura do Repositório

### 📜 **Scripts**
| Arquivo                          | Descrição                                                                                  |
|----------------------------------|--------------------------------------------------------------------------------------------|
| `API_mapas_culturais.ipynb`      | Extrai os dados dos agentes culturais utilizando a **API Mapas Culturais**.                |
| `Tratamento_base_API.ipynb`      | Realiza a **higienização** e prepara a base para importação em um banco de dados SQL.      |
| `Organização_áreas_de_atuacao.ipynb` | Gera uma planilha com as colunas **id** e **área de atuação**, permitindo múltiplas áreas por agente. |
| `Criar_Excel_Grupo-Subgrupo.ipynb` | Exporta planilhas filtradas por **área de atuação**, **cidade** ou **estado**.             |

---

### 📊 **Dashboards**
| Arquivo                | Descrição                                                                               |
|------------------------|-----------------------------------------------------------------------------------------|
| `Dashboard PNAB.pbix`  | Dashboard criado no **Power BI** para visualização de estatísticas dos agentes culturais e editais da PNAB. |
| `Dashboard PNAB.pdf`   | Versão **PDF** do dashboard para fácil visualização.                                    |

---


 <div align="center">
  <a href="https://github.com/dsilvaphy/Mapas-Culturais-Gov/blob/main/Dashboard%20PNAB.pdf" target="_blank">
    <img src="https://github.com/dsilvaphy/Mapas-Culturais-Gov/blob/main/dashboard.png" alt="dashboard" width="850" height="450">
  </a>  
 </div>

 ---
 
### 📄 **Planilhas Auxiliares**
| Arquivo           | Descrição                                                                                  |
|-------------------|--------------------------------------------------------------------------------------------|
| `estados.xlsx`    | Planilha padronizada com nomes de estados. Útil para higienização de bases e outras análises. |
| `municipios.xlsx` | Planilha padronizada com nomes de municípios. Corrige erros de grafia em bases de dados.    |

---

## 🔧 Como Usar

1. **Baixe os Arquivos**
   - Faça o download de todos os arquivos do repositório e salve em um único diretório.
2. **Execute os Notebooks**
   - Siga esta ordem de execução:
     1. `API_mapas_culturais.ipynb` - Extração dos dados.
     2. `Tratamento_base_API.ipynb` - Higienização da base.
     3. `Organização_áreas_de_atuacao.ipynb` - Organização de áreas de atuação.
     4. `Criar_Excel_Grupo-Subgrupo.ipynb` - Exportação filtrada.
3. **Visualização**
   - Abra o arquivo `Dashboard PNAB.pbix` no Power BI para explorar as estatísticas ou visualize a versão em PDF.

---


## 🛠️ Tecnologias Utilizadas
- **Python**: Extração, tratamento e organização de dados.
- **Power BI**: Criação de dashboards interativos.
- **Excel**: Auxílio na padronização e exportação de dados.

---

Sinta-se à vontade para contribuir ou adaptar este repositório! 😊

## Licença

Este projeto está licenciado sob a **Creative Commons Attribution-NonCommercial 4.0 International License**. Não é permitido usar o código para fins comerciais.

Veja a licença completa [CC BY-NC 4.0](/creativecommons.org/licenses/by-nc/4.0/deed.pt-br).
