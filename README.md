# IA na Prática: Supervisionado, Não Supervisionado e Reforço

Este repositório contém as implementações práticas discutidas no artigo: **"Aprendizado supervisionado, não supervisionado e por reforço"** escrito por Gisele Oliveira. O objetivo é demonstrar como diferentes abordagens de Inteligência Artificial processam dados e tomam decisões.

## Como Executar no Google Colab
A maneira mais fácil de testar os projetos é através do **Google Colab**, que executa tudo diretamente no seu navegador, sem precisar instalar nada no seu computador.

1. **Acesse o arquivo:** Clique em um dos notebooks acima (ex: `Aprendizado_reforco.ipynb`).
2. **Abra no Colab:** No topo da página do arquivo, clique no botão **"Open in Colab"**.
3. **Execute:** No menu superior do Colab, selecione **Ambiente de execução > Executar tudo**.

---

## Projetos Incluídos

### 1. Aprendizado Supervisionado 
* **O que faz:** Treina um modelo com imagens rotuladas para que ele aprenda a reconhecer padrões visuais e classificar novas imagens como "gato" ou "cachorro".
* **Conceito:** O aprendizado ocorre através de dados que já possuem a resposta correta, chamados de rótulos.
* **Destaque Técnico:** Utiliza redes neurais convolucionais e ajuste de parâmetros para redução do erro ao longo do tempo.

### 2. Aprendizado Não Supervisionado 
* **O que faz:** Organiza uma lista de textos em grupos por similaridade, mesmo sem saber previamente sobre quais temas eles tratam.

* **Conceito:** O modelo identifica estruturas ocultas e padrões de organização interna sem rótulos definidos ou noção explícita de certo ou errado.
* **Destaque Técnico:** Utiliza o algoritmo KMeans e vetorização TF-IDF para medir a similaridade entre os dados.

### 3. Aprendizado por Reforço 
* **O que faz:** Um agente aprende a tomar decisões em um ambiente simulado através de tentativas e erros, recebendo feedback na forma de recompensas ou penalidades.

* **Conceito:** O foco é a tomada de decisão sequencial e a observação das consequências das ações ao longo do tempo para maximizar os resultados.
* **Destaque Técnico:** Implementa a estratégia epsilon-greedy para equilibrar a exploração de novas opções e o aproveitamento de escolhas conhecidas.

---

## Resumo das Diferenças

| Abordagem | Entrada de Dados | Objetivo Principal | Exemplo no Projeto |
| :--- | :--- | :--- | :--- |
| **Supervisionado** | Dados com respostas (rótulos) | Classificar ou prever resultados | Identificação de Gatos/Cães |
| **Não Supervisionado** | Dados sem respostas prévias | Agrupar e encontrar padrões | Agrupamento de Textos |
| **Por Reforço** | Interação e Feedback | Aprender a melhor estratégia | Simulador de Decisões |

---

## Artigo Completo
Para conferir a análise teórica completa e entender como essas tecnologias impactam as áreas social e educacional, leia o artigo original no Medium:

🔗 [**Aprendizado supervisionado, não supervisionado e por reforço - Gisele Oliveira**](https://medium.com/@giseleoliveirabr/aprendizado-supervisionado-n%C3%A3o-supervisionado-e-por-refor%C3%A7o-c19775f15b91)
