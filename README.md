# Dio-RDF-NotookLM
Projeto DIO - NotbookLM criação de um notbook para estudo sobre Web Semantica - Foco em construção Criação de ontôlogias  e vocabularios.

# 🌐 Estudos em Web Semântica: RDFS e SKOS

Este repositório contém resumos, modelos e exercícios práticos de preparação para provas (P1) voltados para os fundamentos da Web Semântica, especificamente utilizando **RDF Schema (RDFS)** e **SKOS (Simple Knowledge Organization System)**.

---

## 📖 Sobre o Material

O conteúdo aqui documentado foi sintetizado a partir de exercícios práticos e provas passadas. Ele aborda os princípios de criação de vocabulários, estruturação de conhecimento, inferência de dados e representação de instâncias em formato de grafos.

🔗 **Link para o Caderno de Estudos Original (NotebookLM):** 

[# 🌐 Estudos em Web Semântica: RDFS e SKOS

Este repositório contém resumos, modelos e exercícios práticos de preparação para provas (P1) voltados para os fundamentos da Web Semântica, especificamente utilizando **RDF Schema (RDFS)** e **SKOS (Simple Knowledge Organization System)**.

---

## 📖 Sobre o Material

O conteúdo aqui documentado foi sintetizado a partir de exercícios práticos e provas passadas. Ele aborda os princípios de criação de vocabulários, estruturação de conhecimento, inferência de dados e representação de instâncias em formato de grafos.

🔗 **Link para o Caderno de Estudos Original (NotebookLM):** 
[(https://notebooklm.google.com/notebook/07630c21-cdd2-484d-9817-7710c2b86601)]

---

## 🎯 Principais Tópicos Abordados

### 1. RDF Schema (RDFS) e Modelagem de Vocabulários
A base da web de dados e como estruturar ontologias e vocabulários:
* **Recursos:** O conceito central da web semântica e a importância dos URIs dereferenciáveis (que retornam dados úteis ao serem acessados) [1-3].
* **Hierarquia de Classes:** Definição de classes e suas subclasses utilizando `rdfs:Class` e `rdfs:subClassOf` (ex: `Estudante` é subclasse de `Pessoa`) [1, 4].
* **Propriedades e Restrições:** Uso de `rdfs:domain` (quem realiza a ação/sujeito) e `rdfs:range` (o alvo da ação ou tipo de dado/objeto) [5, 6].
* **Hierarquia de Propriedades:** Uso de `rdfs:subPropertyOf` (ex: `leciona` como subpropriedade de `colaboraCom`) [6].
* **Inferência de Dados:** Como as máquinas utilizam RDFS para deduzir novas informações. Exemplo: se alguém "leciona", e o domínio de "leciona" é "Professor", infere-se que essa pessoa é um Professor [5, 7].
* **Representação Gráfica:** Instanciação de dados utilizando elipses para URIs (recursos) e retângulos para literais (textos, números) [8, 9].

### 2. SKOS (Simple Knowledge Organization System)
Construção de Tesauros e vocabulários controlados para organização do conhecimento:
* **Conceitos:** Declaração de recursos como `skos:Concept` [10].
* **Taxonomia:** Relacionamentos hierárquicos utilizando `skos:broader` (Termo Genérico - TG) e `skos:narrower` (Termo Específico - TE) [11, 12].
* **Relacionamentos:** Uso de `skos:related` para termos que possuem relação não hierárquica [10, 11].
* **Rótulos e Descrições:**
  * `skos:prefLabel`: Rótulo preferencial do termo [10, 11].
  * `skos:altLabel`: Rótulos alternativos ou sinônimos [10, 11].
  * `skos:definition`: Definição formal do conceito [10, 11].
  * `skos:scopeNote`: Nota de escopo limitando o uso do termo [10, 11].

---

## 💻 Tecnologias e Sintaxes Utilizadas
* **Turtle (.ttl):** Sintaxe simplificada utilizada predominantemente para SKOS e inferências [8, 10, 11].
* **RDF/XML:** Sintaxe em XML para a escrita rigorosa de vocabulários RDFS [1-3].

---

## 🚀 Como utilizar este repositório para estudar
1. **Entenda os Namespaces:** Familiarize-se com a declaração de prefixos (`rdf:`, `rdfs:`, `skos:`) [13, 14].
2. **Pratique a Inferência:** Analise grafos e propriedades (ex: `teaches` e `gives-lecture`) para deduzir novas triplas [5].
3. **Escreva Vocabulários:** Traduza modelos conceituais UML e requisitos em linguagem natural para RDF/XML ou Turtle [5, 15].
4. **Crie Tesauros:** Mapeie taxonomias hierárquicas aplicando o padrão S]

---

## 🎯 Principais Tópicos Abordados

### 1. RDF Schema (RDFS) e Modelagem de Vocabulários
A base da web de dados e como estruturar ontologias e vocabulários:
* **Recursos:** O conceito central da web semântica e a importância dos URIs dereferenciáveis (que retornam dados úteis ao serem acessados) [1-3].
* **Hierarquia de Classes:** Definição de classes e suas subclasses utilizando `rdfs:Class` e `rdfs:subClassOf` (ex: `Estudante` é subclasse de `Pessoa`) [1, 4].
* **Propriedades e Restrições:** Uso de `rdfs:domain` (quem realiza a ação/sujeito) e `rdfs:range` (o alvo da ação ou tipo de dado/objeto) [5, 6].
* **Hierarquia de Propriedades:** Uso de `rdfs:subPropertyOf` (ex: `leciona` como subpropriedade de `colaboraCom`) [6].
* **Inferência de Dados:** Como as máquinas utilizam RDFS para deduzir novas informações. Exemplo: se alguém "leciona", e o domínio de "leciona" é "Professor", infere-se que essa pessoa é um Professor [5, 7].
* **Representação Gráfica:** Instanciação de dados utilizando elipses para URIs (recursos) e retângulos para literais (textos, números) [8, 9].

### 2. SKOS (Simple Knowledge Organization System)
Construção de Tesauros e vocabulários controlados para organização do conhecimento:
* **Conceitos:** Declaração de recursos como `skos:Concept` [10].
* **Taxonomia:** Relacionamentos hierárquicos utilizando `skos:broader` (Termo Genérico - TG) e `skos:narrower` (Termo Específico - TE) [11, 12].
* **Relacionamentos:** Uso de `skos:related` para termos que possuem relação não hierárquica [10, 11].
* **Rótulos e Descrições:**
  * `skos:prefLabel`: Rótulo preferencial do termo [10, 11].
  * `skos:altLabel`: Rótulos alternativos ou sinônimos [10, 11].
  * `skos:definition`: Definição formal do conceito [10, 11].
  * `skos:scopeNote`: Nota de escopo limitando o uso do termo [10, 11].

---

## 💻 Tecnologias e Sintaxes Utilizadas
* **Turtle (.ttl):** Sintaxe simplificada utilizada predominantemente para SKOS e inferências [8, 10, 11].
* **RDF/XML:** Sintaxe em XML para a escrita rigorosa de vocabulários RDFS [1-3].

---

## 🚀 Como utilizar este repositório para estudar
1. **Entenda os Namespaces:** Familiarize-se com a declaração de prefixos (`rdf:`, `rdfs:`, `skos:`) [13, 14].
2. **Pratique a Inferência:** Analise grafos e propriedades (ex: `teaches` e `gives-lecture`) para deduzir novas triplas [5].
3. **Escreva Vocabulários:** Traduza modelos conceituais UML e requisitos em linguagem natural para RDF/XML ou Turtle [5, 15].
4. **Crie Tesauros:** Mapeie taxonomias hierárquicas aplicando o padrão S
