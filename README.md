# Análise de Saúde, Mobilidade e Educação

Este repositório contém uma análise de dados que correlaciona informações sobre casos de dengue, alunos e mobilidade urbana (uso de ônibus).

## Conteúdo

- `Analise_Saude_Mobilidade_Educacao.ipynb`: Notebook Jupyter com a análise completa.
- `Bases de Alunos3.csv/`: Diretório contendo os arquivos CSV usados na análise.
- `Bases de Onibus3.csv/`: Diretório contendo os arquivos CSV usados na análise.

## Estrutura do Projeto

1. **Importação de bibliotecas e leitura dos dados:**
   - Pandas é usado para manipulação de dados.
   - Os arquivos CSV são carregados em DataFrames.

2. **Exploração dos dados:**
   - Exibição de informações básicas dos DataFrames com `.info()`.

3. **Filtragem dos dados:**
   - Extração de listas de nomes dos alunos e usuários de ônibus.
   - Filtragem dos casos de dengue para identificar alunos e usuários de ônibus afetados.

4. **Geração de Diagrama de Venn:**
   - Uso das bibliotecas Matplotlib e Matplotlib-Venn para criar um diagrama que mostra a interseção entre os grupos.

## Dependências

- Python 3.x
- Pandas
- Matplotlib
- Matplotlib-Venn
```
## Como Usar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. **Instale as dependências:**

   ```bash
   pip install pandas matplotlib matplotlib-venn
   ```

3. **Execute o notebook:**
   - Abra o `Analise_Saude_Mobilidade_Educacao.ipynb` com o Jupyter Notebook ou Google Colab.
   - Siga as instruções no notebook para executar as células de código.

## Dados

Os dados usados nesta análise estão localizados no diretório `Bases de Dados`:
- `Base de Dengue3.csv`: Dados de casos de dengue.
- `Base de Alunos3.csv`: Dados de alunos.
- `Base de Onibus3.csv`: Dados de uso de ônibus.

## Contribuição

Sinta-se à vontade para contribuir com este projeto! Faça um fork do repositório, crie uma branch para suas alterações e abra um pull request.

## Licença

Este projeto é licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações, entre em contato através de [seu-email@dominio.com](mailto:seu-email@dominio.com).

Este arquivo README fornece uma visão geral clara do projeto, incluindo sua estrutura, dependências, instruções de uso e informações de contato. Certifique-se de substituir os placeholders (como URLs e endereço de e-mail) com as informações relevantes do seu projeto.
