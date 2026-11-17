# Roteiro de Atividade de Pesquisa (Sala de aula invertida)
**Disciplina**: Estrutura de Dados  
**Tema**: Balanceamento em Árvores AVL  
**Formato**: Trabalho em grupo (máx. 3 alunos)  

## Entregáveis
1. **Apresentação** (10–15 min)  
2. **Três questões de múltipla escolha** com gabarito  
3. **Forma de entrega**: Um único membro do grupo deve submeter os arquivos no trabalho atribuído no **Microsoft Teams**

---

## 1. Objetivos de Aprendizagem
- **Compreender** o que caracteriza uma árvore AVL.  
- **Explicar** como o fator de balanceamento é calculado e mantido.  
- **Descrever** e **demonstrar** as rotações simples e duplas.  
- **Analisar** o custo de inserção, remoção e busca em AVL.  
- **Aplicar** o conhecimento escrevendo questões conceituais bem‑formuladas.  

---

## 2. Organização dos Grupos
### 2.1 Formação 
- Forme um grupo com no  máximo 3 integrantes.  
- Os grupos serão atribuidos no Teams pelo professor

### 2.2 Distribuição de Papéis  (sugestão)
| Papel | Responsabilidades principais |
|-------|------------------------------|
| **Pesquisador‑1** | Aprofundar a teoria (definições, propriedades). |
| **Pesquisador‑2** | Criar diagramas/figuras e reunir exemplos de aplicações. |
| **Editor** | Compilar slides, revisar linguagem e redigir as questões. |

> *Se o grupo tiver apenas 2 pessoas, rotacionem os papéis ao longo do trabalho.*

---

## 3. Linha do Tempo Recomendada
| Passo | Atividade‑chave | Entregável (checkpoint) |
|-------:|-----------------|-------------------------|
| **1** | Pesquisa bibliográfica e divisão de papéis | Lista de fontes + esboço de tópicos |
| **2** | Criação de diagramas e coleta de exemplos visuais | Pasta de recursos visuais organizada |
| **3** | Redação dos slides e das questões | Rascunho dos slides |
| **4** | Revisão cruzada entre grupos (*peer review*) | Feedback recebido ✔️ |
| **5** | Apresentação em aula + entrega final no Teams | Slides PDF + 3 MCQs |

---

## 4. Etapas Detalhadas

### 4.1 Levantamento Teórico
1. **Leitura‑base**: Pesquisa nas referências bibliográficas ou IA Generativa.  
2. **Pontos mínimos a cobrir**  
   - Definição de árvore balanceada e fator de balanceamento.  
   - Como o balanceamento se perde após inserção/remoção.  
   - Rotações: LL, RR, LR, RL — passo a passo.  
   - Prova (ou justificativa) de altura `O(log n)`.  
   - Comparação breve com *Red‑Black Trees* e *Treaps*.  

> **Dica**: use visualizadores online (VisuAlgo, BST‑Visualizer) para gerar GIFs ilustrativos.

### 4.2 Construção da Apresentação
- **Estrutura sugerida (≈10 slides)**  
  1. Motivação: por que balancear árvores?  
  2. Definição & propriedades.  
  3. Cálculo do fator de balanceamento.  
  4‑7. Cada rotação com diagrama "antes/depois".  
  8. Complexidade e prova de altura.  
  9. Exemplos de uso em aplicações reais.  
  10. Conclusões + temas para estudo futuro.  

> **Boas práticas**  
> - Use fonte ≥ 18 pt para legibilidade.  
> - Prefira diagramas coloridos e animações sutis.  
> - Reserve cerca de 1 min por slide.

### 4.3 Elaboração das Questões de Múltipla Escolha
1. **Cobertura**: cada questão deve focar em **um** conceito (ex.: fator de balanceamento, rotações, complexidade).  
2. **Formato**: 4 alternativas; 1 ou mais corretas; forneça o gabarito ao final.  
3. **Qualidade**  
   - Evite "todas as alternativas acima".  
   - Explique (em nota separada para o professor) por que cada alternativa está certa ou errada.  

---

## 5. Recursos Recomendados

### 5.1 Livros
- **CORMEN, T. H. et al.** *Introduction to Algorithms*. 3ª ed. MIT Press, 2009. Capítulo 13.  
- **WEISS, M. A.** *Data Structures and Algorithm Analysis in C++*. 4ª ed. Pearson, 2013.  
- **GOODRICH, M. T.; TAMASSIA, R.; MOUNT, D. M.** *Data Structures and Algorithms in C++*. 2ª ed. Wiley, 2011.  
- **DROZDEK, A.** *Estrutura de Dados e Algoritmos em C++*. Cengage Learning, 2016.

### 5.2 Artigos & Tutoriais Online
- **GeeksforGeeks**: "AVL Tree | Set 1 (Insertion)" e "AVL Tree | Set 2 (Deletion)"  
  → https://www.geeksforgeeks.org/avl-tree-set-1-insertion/  
- **Programiz**: "AVL Tree"  
  → https://www.programiz.com/dsa/avl-tree  
- **Brilliant.org**: Módulo interativo sobre árvores AVL  
  → https://brilliant.org/wiki/avl-tree/  
- **CP-Algorithms**: "Treap"  
  → https://cp-algorithms.com/data_structures/treap.html (para comparação)

### 5.3 Vídeos Educacionais
- **Abdul Bari** (YouTube): "AVL Trees & Rotations"  
- **William Fiset** (YouTube): "AVL Tree insertion and rotations"  
- **MIT OpenCourseWare**: 6.006 Introduction to Algorithms (Lecture sobre BST/AVL)

### 5.4 Ferramentas Interativas
- **VisuAlgo**: Visualizador de estruturas de dados (BST/AVL)  
  → https://visualgo.net/en/bst  
- **USF Data Structure Visualizations**: AVL Tree  
  → https://www.cs.usfca.edu/~galles/visualization/AVLtree.html  
- **Algorithm Visualizer**: Árvores AVL  
  → https://algorithm-visualizer.org/  

### 5.5 Ferramentas para Criação de Diagramas
- **draw.io** (app.diagrams.net) — editor gratuito de diagramas  
- **Excalidraw** — desenhos colaborativos online  
- **Canva** — templates para apresentações visuais  
- **Mermaid** — diagramas como código (integra com Markdown)

### 5.6 Implementações de Referência em C++
- **CP-Algorithms**: Implementação completa de AVL em C++  
  → https://cp-algorithms.com/  
- **GitHub**: Busque por "AVL tree C++ implementation" para exemplos práticos  
- **LeetCode/HackerRank**: Problemas envolvendo árvores balanceadas

---

## 6. Dicas Pedagógicas para o Grupo
| Desafio Comum | Estratégia Sugerida |
|---------------|---------------------|
| Memorizar as quatro rotações | Crie flashcards ou diagramas comparativos (LL / RR / LR / RL). |
| Entender por que a altura é `O(log n)` | Refaça a justificativa passo a passo e discuta no grupo. |
| Preparar boas perguntas | Teste‑as com colegas de outro grupo; refine se houver confusões. |
| Visualizar as rotações | Use os simuladores online durante a preparação dos slides. |

---

## 7. Entrega Final

### 7.1 Arquivos a Submeter
- **Slides**: PowerPoint (.pptx), PDF).  
- **Arquivo "Questoes.pdf"**:  
  - 3 questões numeradas.  
  - Alternativas A–D.  
  - Gabarito ao final com justificativas breves.  

### 7.2 Checklist antes de Submeter
- [ ] Fator de balanceamento definido claramente.  
- [ ] Todos os tipos de rotação ilustrados com diagramas.  
- [ ] Questões revisadas (ortografia, coerência e alternativas plausíveis).  
- [ ] Referências citadas no último slide .  
- [ ] Apenas um membro do grupo fez a submissão no Teams.  
- [ ] Todos os integrantes do grupo confirmaram a versão final.

---


**Boa pesquisa e ótimos estudos!**  
*Lembre-se: o aprendizado em grupo potencializa a compreensão de estruturas de dados complexas. Aproveitem para trocar ideias e construir conhecimento colaborativamente!*
