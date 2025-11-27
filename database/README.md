# RocketLabDados-2025.2-Projeto
Para encontrar os dados utilizados no projeto você pode acessar o drive: https://drive.google.com/drive/folders/1tvAXukhhDZKG1IC9w-nNZnKniPAuYRUu
e baixar a pasta 'dados_brutos' para importa-los no ambiente do Databricks.

Caso nescessário você pode extrai-los utilizando o 'extract.sh' como mostrado abaixo:
## Extração de dados para csv:

Adicione a essa pasta em seu diretório o conteudo de dentro da pasta 'Base de Dados' presente no drive.

### Estrutura de pastas

```text
RocketLabDados-2025.2-Projeto/
└── database
    ├── Chamados_Hora.csv
    ├── dump.sql
    ├── extract.sh
    └── tables
        ├── base_atendentes.csv
        ├── base_motivos.csv
        ├── canais.csv
        ├── chamados.csv
        ├── Chamados_Hora.csv
        ├── clientes.csv
        ├── custos.csv
        └── pesquisa_satisfacao.csv
```

- `dump.sql`: arquivo de dump do banco PostgreSQL.
- `extract.sh`: script responsável por restaurar o dump e exportar as tabelas para CSV.
- `tables/`: pasta com os arquivos `.csv` gerados a partir das tabelas do banco.

### Como executar a extração

1. Certifique-se de que você está dentro da pasta `database`:

```bash
cd RocketLabDados-2025.2-Projeto/database
```

2. Dê permissão de execução ao script (apenas na primeira vez):

```bash
chmod +x extract.sh
```

3. Execute o script:

```bash
./extract.sh
```

O script irá:

- Verificar se o arquivo `dump.sql` existe na pasta atual;
- Instalar o PostgreSQL (caso ainda não esteja instalado);
- Dropar (se existir) e recriar o banco `basedados`;
- Restaurar o conteúdo do `dump.sql` no banco;
- Exportar todas as tabelas do schema `public` para CSV;
- Copiar os arquivos `.csv` gerados para a pasta `tables/`.

Após a execução, os arquivos CSV estarão disponíveis em:

```text
RocketLabDados-2025.2-Projeto/database/tables
```