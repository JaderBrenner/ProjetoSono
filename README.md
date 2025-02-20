#### Insights sobre padrões de sono e hábitos diários

![imagem](imagens/sono_pexels.jpg)

O Sleep Health and Lifestyle Dataset fornece insights detalhados sobre os padrões de sono, hábitos diários e fatores de estilo de vida dos indivíduos. Este conjunto de dados sintéticos compreende 400 linhas e 13 colunas , cobrindo métricas essenciais como duração do sono, qualidade do sono, níveis de atividade física, estresse, categoria de IMC, saúde cardiovascular e presença de distúrbios do sono.

## Organização do projeto

```
├── .gitignore          <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml        <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE             <- Licença de código aberto (MIT)
├── README.md           <- README principal para desenvolvedores que usam este projeto.
|
├── dados               <- Arquivos de dados para o projeto.
|
├── notebooks           <- Jupyter Notebooks
│
|   └──src              <- Código-fonte para uso neste projeto.
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      ├── config.py    <- Configurações básicas do projeto
|
├── referencias         <- Dicionários de dados, manuais e todos os outros materiais explicativos.
|
├── imagens             <- Imagens utilizadas no projeto
```

## Configuração do ambiente

1. Faça o clone do repositório que será criado a partir deste modelo.

    ```bash
    git clone ENDERECO_DO_REPOSITORIO
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o gerenciador de ambientes de sua preferência.

      ```bash
      conda env export > ambiente.yml
      ```

## Um pouco mais sobre a base

[Clique aqui](referencias/01_dicionario_de_dados.md) para ver sobre o dicionário de dados 
