# Survey em IA e Segurança: Técnicas de Preservação de Privacidade

## Tema

**Privacidade e Inteligência Artificial**

Este trabalho apresenta uma revisão sistemática sobre técnicas de preservação de privacidade em sistemas de IA, abordando:
- Federated Learning (aprendizado distribuído)
- Differential Privacy (privacidade diferencial)
- Machine Unlearning (desaprendizado de máquina)
- Synthetic Data Generation (geração de dados sintéticos)

## Integrantes

- DAVI IURY LOPES SOUZA, 554054
- LUCAS PINHEIRO DA COSTA, 553311
- LUIZA ESTHER MARTINS PESSOA, 555516
- RAFAEL PORTO CARVALHO, 555707
- THEO ARAUJO MAGALHAES, 555910

**Instituição:** Universidade Federal do Ceará

## Instruções para o Avaliador

### Estrutura do Repositório

```
Survey-on-Privacy-and-AI/
├── survey.tex              # Artigo principal (LaTeX)
├── survey.pdf              # Artigo compilado (PDF)
├── refs.bib                # Referências bibliográficas
├── refs/                   # PDFs dos artigos consultados
├── llncs.cls               # Template Springer LNCS
├── splncs04.bst            # Estilo bibliográfico
└── README.txt              # Este arquivo
```

### Como Compilar o Artigo

**Opção 1 - Visualizar PDF:**
O arquivo `survey.pdf` já está compilado e pronto para leitura.

**Opção 2 - Recompilar (se necessário):**
```bash
pdflatex survey.tex
bibtex survey
pdflatex survey.tex
pdflatex survey.tex
```

**Opção 3 - Usar Overleaf:**
Importe o projeto completo no Overleaf para compilação automática.

### Metodologia de Revisão Sistemática

**Bases consultadas:**
- Google Scholar (principal)
- IEEE Xplore
- ACM Digital Library
- arXiv
- Springer

**Critérios de seleção:**
1. Artigos com alto número de citações (>100 citações preferencialmente)
2. Publicações em conferências/periódicos de alto impacto (IEEE, ACM, Springer)
3. Análise de abstract e relevância para o tema
4. Rastreamento de referências citadas pelos trabalhos principais
5. Priorização de surveys e trabalhos seminais

**Processo de triagem:**
- Busca inicial: ~50 artigos identificados
- Após análise de abstract e local de publicação: 25 artigos pré-selecionados
- Leitura completa e análise de relevância: 16 artigos finais incluídos no survey

### Principais Referências Utilizadas

1. **Zhang et al. (2021)** - "A survey on federated learning" (Knowledge-Based Systems)
2. **McMahan et al. (2017)** - "Communication-Efficient Learning of Deep Networks from Decentralized Data" (FedAvg)
3. **Bonawitz et al. (2017)** - "Practical Secure Aggregation for Privacy-Preserving Machine Learning" (CCS)
4. **Goyal & Mahmoud (2024)** - "A Systematic Review of Synthetic Data Generation Techniques Using Generative AI" (Electronics)
5. **Nadăş et al. (2025)** - "Synthetic Data Generation Using Large Language Models" (IEEE Access)
6. **Hardy et al. (2017)** - "Private federated learning on vertically partitioned data" (arXiv)
7. **Liang et al. (2020)** - "Think Locally, Act Globally: Federated Learning with Local and Global Representations" (arXiv)

Lista completa disponível em `refs.bib` (21 referências).

### Estrutura do Artigo

O artigo segue o formato Springer LNCS e contém:

1. **Introdução** - Contextualização do problema e apresentação das quatro técnicas
   - Contextualização - Descrição detalhada de cada técnica
   - Metodologia de Revisão Sistemática
2. **Caracterização Ferramental** - Análise detalhada das técnicas:
   - Machine Unlearning
   - Differential Privacy
   - Federated Learning (com taxonomia completa)
3. **Geração de Dados Sintéticos** - GANs, VAEs, LLMs e sinergia com outras técnicas
4. **Conclusão** - Síntese, desafios e direções futuras
5. **Bibliografia** - 16 referências

### Apresentação em Vídeo

**Link do vídeo (YouTube não listado):**
[NÃO ESQUECER DE COLOCAR O VIDEO AQUI E NO TXT]

**Duração:** [XX minutos]

**Conteúdo abordado:**
- Problema e motivação
- Taxonomia das técnicas de privacidade
- Comparação entre métodos (Federated Learning, Differential Privacy, Machine Unlearning)
- Geração de dados sintéticos e aplicações
- Limitações, desafios e tendências futuras

### Uso de Ferramentas de IA

**Declaração de uso:**
Ferramentas de IA foram utilizadas como apoio no desenvolvimento deste trabalho:

- **Amazon Q Developer:** Auxílio na organização do repositório, estruturação do README e revisão de formatação LaTeX
- **ChatGPT/Claude:** Suporte na revisão gramatical, organização de ideias e refinamento de texto
- **GitHub Copilot:** Assistência na escrita de código LaTeX e formatação de referências

**Nota importante:** Todo o conteúdo técnico, análise crítica, seleção de referências e argumentação são de autoria dos integrantes do grupo. As ferramentas de IA foram utilizadas exclusivamente como apoio editorial e organizacional.
