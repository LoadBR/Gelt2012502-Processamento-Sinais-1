# Gelt2012502-Processamento-Sinais-1
Códigos, dados e resultados das aulas práticas de Processamento de Sinais I - GELE7317

## Aula Prática 1 — Sinais e Sistemas

A primeira atividade prática aborda conceitos fundamentais de sinais e sistemas, incluindo geração e reprodução de sinais senoidais, chirps, análise no domínio do tempo e da frequência, resposta ao impulso e convolução.

### Atividades desenvolvidas

- Geração de sinais senoidais de 500 Hz, 5 kHz e 10 kHz;
- Geração de chirps linear, quadrático e logarítmico;
- Análise temporal e espectral do sinal `handel.wav`;
- Estudo conceitual da medição da resposta ao impulso de uma sala;
- Análise dos sinais `h_banheiro.wav` e `sinal_taca.wav`;
- Aplicação de convolução entre sinais de áudio e a resposta ao impulso do banheiro;
- Comparação dos sinais originais e processados;
- Geração de gráficos e arquivos de áudio resultantes.

## Estrutura do repositório

Gelt2012502-Processamento-Sinais-1
│
├── README.md
├── .gitignore
├── requirements.txt
│
└── Aula-01/
    ├── README.md
    │
    ├── Codigo/
    │   └── AP1_Sinais_e_Sistemas.ipynb
    │
    ├── Dados/
    │   ├── handel.wav
    │   ├── h_banheiro.wav
    │   └── sinal_taca.wav
    │
    ├── Resultados/
    │   ├── figuras geradas durante os experimentos
    │   └── sinais de áudio processados
    │
    └── Relatorio/
        └── relatório final da Aula Prática 1

## Ferramentas utilizadas

O desenvolvimento da atividade foi realizado principalmente em Python, utilizando o Google Colab como ambiente de execução.

Principais bibliotecas utilizadas:

NumPy;
SciPy;
Matplotlib;
IPython.


## Execução

O notebook principal da Aula Prática 1 está localizado em:
- Aula-01/Codigo/AP1_Sinais_e_Sistemas.ipynb

O arquivo pode ser aberto diretamente no Google Colab ou executado em um ambiente Jupyter com as dependências necessárias instaladas.
Os arquivos de entrada utilizados pelos experimentos estão localizados em:
- Aula-01/Dados/

Os gráficos e sinais gerados durante o processamento são armazenados em:
- Aula-01/Resultados/

Os gráficos e sinais gerados durante o processamento são armazenados em:
-  Aula-01/Resultados/

## Reprodutibilidade

As dependências utilizadas no projeto são documentadas no arquivo:
- requirements.txt

Em um ambiente Python compatível, elas poderão ser instaladas com:
- pip install -r requirements.txt

## Relatório

O relatório final da Aula Prática 1 será disponibilizado em:
- Aula-01/Relatorio/
O documento apresenta a metodologia utilizada, os principais resultados obtidos, a discussão dos experimentos e as conclusões da atividade.
