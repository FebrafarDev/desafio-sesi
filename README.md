# Desafio SESI - Sistema de Layout e Planograma para Farmácias

## 📋 Descrição do Projeto

Este projeto é um desafio dividido em **2 etapas principais** que consiste no desenvolvimento de um sistema web para auxiliar lojistas (farmacêuticos) na escolha do layout da loja e visualização de planogramas por categoria de produtos.

## 👥 Composição dos Grupos

- **Mínimo:** 8 pessoas
- **Máximo:** 10 pessoas
- **Divisão:** Uma parte do time ficará responsável pela **Etapa 1** e outra parte pela **Etapa 2**

## 🚀 Entrega

- **Formato:** Site funcional
- **Tecnologia:** Livre escolha do grupo
- **Requisito:** Ambas as etapas devem estar implementadas na entrega final

---

## 🏪 ETAPA 1 - Escolha da Planta e Definição de Categorias

### Objetivo
Permitir que o lojista escolha o tamanho da sua loja e visualize a distribuição dos universos e categorias.

### Requisitos Básicos

#### 1. Seleção do Tamanho da Loja
O sistema deve oferecer **3 opções de planta**:

- **Loja P (Pequena)** - até 60m²
- **Loja M (Média)** - 75m² a 99m²  
- **Loja G (Grande)** - 100m² a 120m²

*Plantas de referência disponíveis em: `/images/loja_p.png`, `/images/loja_m.png`, `/images/loja_g.png`*

#### 2. Exibição dos Universos e Categorias
Após a seleção da planta, o sistema deve:
- Calcular automaticamente a distribuição dos universos
- Exibir visualmente na planta os universos e categorias correspondentes
- Utilizar como referência as distribuições mostradas em:
  - `/images/loja_p_universos.png`
  - `/images/loja_m_universos.png` 
  - `/images/loja_g_universos.png`

### Funcionalidades Adicionais (Diferenciais)
- **Customização da Planta:** Permitir que o lojista modifique a planta para adequá-la exatamente ao layout da sua loja
- **Visualização Criativa:** Implementar formas alternativas e criativas de exibir os universos e categorias

---

## 📊 ETAPA 2 - Visualização e Exportação de Planogramas

### Objetivo
Permitir a seleção interativa de categorias e visualização dos respectivos planogramas, com opção de exportação.

### Requisitos Básicos

#### 1. Seleção Interativa de Categorias
- Interface que permita ao lojista selecionar qualquer categoria dos universos definidos na Etapa 1
- Navegação intuitiva entre as diferentes categorias

#### 2. Visualização de Planogramas
Ao selecionar uma categoria, o sistema deve:
- Exibir o **planograma** correspondente
- Mostrar esquema visual detalhado da disposição dos produtos
- Indicar posicionamento em prateleiras, gôndolas e expositores

> **O que é um Planograma?**  
> É um esquema visual ou desenho técnico que mostra como e onde os produtos devem ser expostos em prateleiras, gôndolas ou expositores dentro de um ponto de venda, como supermercados, farmácias ou lojas de departamento.

*Nota: As imagens dos planogramas por categoria serão adicionadas posteriormente na pasta `/planogramas`*

#### 3. Exportação de Dados
- **Funcionalidade:** Exportar lista de produtos do planograma selecionado
- **Formato:** Excel (.xlsx)
- **Conteúdo:** Lista completa dos produtos com suas respectivas informações

### Funcionalidades Adicionais (Diferenciais)

#### 🌐 Navegação 3D
- **Mapa Navegável 3D:** Implementar visualização tridimensional da loja
- **Interatividade:** Permitir que o usuário navegue virtualmente pela loja
- **Interação com Categorias:** Clicar diretamente nas seções da loja para acessar os planogramas

---

## 🛠️ Tecnologias Sugeridas

- **Frontend:** React, Vue.js, Angular, ou tecnologia de escolha
- **Backend:** Node.js, Python (Django/Flask), PHP, Java, ou similar
- **3D (opcional):** Three.js, Babylon.js, A-Frame
- **Exportação:** Bibliotecas como ExcelJS, Apache POI, etc.
- **Banco de Dados:** MySQL, PostgreSQL, MongoDB, ou similar

## 📁 Estrutura de Arquivos

```
/
├── images/
│   ├── loja_p.png           # Planta da loja pequena
│   ├── loja_m.png           # Planta da loja média  
│   ├── loja_g.png           # Planta da loja grande
│   ├── loja_p_universos.png # Universos da loja pequena
│   ├── loja_m_universos.png # Universos da loja média
│   └── loja_g_universos.png # Universos da loja grande
├── planogramas/             # Planogramas por categoria (a ser populado)
└── README.md               # Este arquivo
```

## 🎯 Critérios de Avaliação

- **Funcionalidade:** Implementação completa de ambas as etapas
- **Usabilidade:** Interface intuitiva e fácil de usar
- **Criatividade:** Soluções inovadoras para exibição dos universos
- **Tecnologia:** Uso adequado das tecnologias escolhidas
- **Trabalho em Equipe:** Colaboração efetiva entre as partes do grupo
- **Diferenciais:** Implementação de funcionalidades extras (customização de planta, navegação 3D)

---

## 🚀 Como Começar

1. **Formar o grupo** (8-10 pessoas)
2. **Dividir responsabilidades** entre Etapa 1 e Etapa 2
3. **Escolher as tecnologias** que serão utilizadas
4. **Analisar as imagens** de referência das plantas e universos
5. **Planejar a arquitetura** do sistema
6. **Desenvolver iterativamente** cada etapa
7. **Integrar as funcionalidades** em um site funcional

---

## 📋 Universos e Categorias Disponíveis

### 🏪 Farmácia P (até 60m²)

#### 🎨 **Dermocosméticos e Cosméticos**
- Limpeza
- Tratamento
- Fotoproteção facial
- Hidratação
- Nutricosmético

#### ☀️ **Proteção Corporal**
- Protetor solar corporal
- Pós-sol
- Bronzeador
- Repelente

#### 💄 **Perfumaria 1**
- Maquiagem*
- Acessório de maquiagem
- Pente/escova
- Fixador de cabelo
- Acessório para cabelo*
- Manteiga de cacau
- Perfume/colônia*

#### 💅 **Perfumaria 2**
- Alicate
- Acessório para unha
- Acetona
- Esmalte
- Algodão
- Depilação
- Descolorante

#### 💇 **Cabelos e Tinturas**
- Shampoo
- Condicionador
- Máscara de tratamento
- Óleo finalizador
- Tintura
- Produtos de tratamento para cabelo em geral

#### 👁️ **Cuidado com os Olhos**
- Colírio e lágrima artificial
- Cuidado com a lente de contato
- Solução para lente de contato

#### 🩺 **Outros (Cuidado Complementar)**
- Antitabagismo*
- Cuidado com o ouvido

#### 🌸 **Higiene e Saúde Íntima Feminina**
- Cuidado ginecológico e urinário
- Absorvente
- Lenço umedecido
- Sabonete íntimo

#### 🧴 **Desodorante**
- Feminino e masculino
- Roll-on
- Aerosol
- Creme
- Bastão

#### 🏥 **Cuidado ao Paciente**
- **Primeiros socorros:** Assepsia, Curativo e adesivo, Esparadrapo e bandagem, Gaze, atadura, algodão e utensílios, Soro fisiológico
- **Contusão:** Produto de uso tópico em spray, gel, adesivo e outros
- **Tratamento de pele:** Antifúngico, Cicatrização e queimadura
- **Produtos ortopédicos*:** Meia, joelheira, munhequeira

#### 👴 **Cuidado Adulto**
- Roupa íntima adulta
- Fralda geriátrica
- Aparelho de aferição*

#### 💑 **Saúde Sexual**
- Preservativo
- Lubrificante
- Gel

#### 👨 **Cuidado Masculino**
- Shampoo masculino
- Creme para barbear
- Lâmina de barbear
- Gel capilar
- Talco para os pés

#### 🦷 **Higiene Oral**
- Creme dental
- Enxaguante bucal
- Escova dental
- Fio dental
- Fixador de prótese dentária
- Higienizador de prótese dentária

#### 🛁 **Higiene Geral**
- Sabonete em barra
- Sabonete líquido
- Óleo corporal
- Acessório para banho*

#### 💪 **Nutrição Adulta**
- Complemento alimentar
- Suplemento alimentar
- Fórmula especial adulta

#### 🌱 **Vida Saudável**
- Vitaminas D+ e cálcio
- Colágeno
- Passiflora e melatonina
- Ômega 3
- Nutrição sênior

#### 🍼 **Puericultura Leve**
- Mamadeira
- Chupeta
- Acessório para amamentação

#### 👶 **Banho e Troca**
- Higiene infantil
- Troca (lenço umedecido, talco)
- Cuidado com recém-nascido

#### 💊 **MIP (Medicamentos Isentos de Prescrição)**
- Dor e febre
- Gripe e alergia
- Sistema digestivo
- Vitaminas e minerais

#### 👶 **Fraldas Infantis**
- Todos os tamanhos e segmentos
- Elástico e fecho

#### 🥛 **Nutrição Infantil**
- Fórmula
- Snack
- Composto lácteo, etc.

#### 🛒 **Alimentos e Geladeira**
- **Checkout:** Chocolate, Bala e chiclete, Barra de cereal
- **Geladeira:** Refrigerante, Água, Água de coco, Isotônico, Whey Protein, Suplemento líquido

#### 🎯 **Área Promocional**
- Cestão
- Ponta de gôndola
- Display de balcão

---

### 🏪 Farmácia M (75m² a 99m²)

#### 🎨 **Dermocosmético e Cosmético**
- Limpeza
- Tratamento
- Fotoproteção facial
- Hidratação
- Nutricosmético

#### 💄 **Perfumaria 1**
- Maquiagem*
- Acessório de maquiagem*
- Pente/escova
- Fixador de cabelo
- Acessório para cabelo*
- Manteiga de cacau
- Perfume/colônia*

#### 💇 **Cabelo e Tintura**
- Shampoo
- Condicionador
- Máscara de tratamento
- Óleo finalizador
- Tintura
- Produtos de tratamento para cabelo em geral

#### ☀️ **Proteção Corporal**
- Protetor solar corporal
- Pós-sol
- Bronzeador
- Repelente

#### 💅 **Perfumaria 2**
- Alicate
- Acessório para unha
- Acetona
- Esmalte
- Algodão
- Depilação
- Descolorante

#### 🦷 **Higiene Oral**
- Creme dental
- Enxaguante bucal
- Escova dental
- Fio dental
- Fixador de prótese dentária
- Higienizador de prótese dentária

#### 👁️ **Cuidado Complementar**
- **Cuidado com os olhos:** Colírio e lágrima artificial, Cuidado com a lente de contato, Solução para lente de contato
- **Outros:** Antitabagismo*, Cuidado com o ouvido, Aparelho de aferição*

#### 🌸 **Higiene e Saúde Íntima Feminina**
- Cuidado ginecológico e urinário
- Absorvente (interno e externo)
- Lenço umedecido
- Sabonete íntimo

#### 👨 **Cuidado Masculino**
- Shampoo masculino
- Creme para barbear
- Lâmina de barbear
- Gel capilar
- Talco para os pés

#### 💑 **Saúde Sexual**
- Preservativo
- Lubrificante
- Gel

#### 🧴 **Desodorante**
- Feminino e masculino
- Roll-on
- Aerosol
- Creme
- Bastão

#### 🛁 **Higiene Geral**
- Sabonete em barra
- Sabonete líquido
- Óleo corporal
- Acessório para banho*

#### 🏥 **Cuidado ao Paciente**
- **Primeiros socorros:** Assepsia, Curativo e adesivo, Esparadrapo e bandagem, Gaze, atadura, algodão e utensílios, Soro fisiológico
- **Contusão:** Produto de uso tópico
- **Tratamento de pele:** Antifúngico, Cicatrização e queimadura
- **Produtos ortopédicos*:** Meia, joelheira, munhequeira

#### 🥛 **Nutrição Infantil**
- Fórmula, snack, composto lácteo, etc.

#### 🍼 **Puericultura Leve**
- Mamadeira
- Chupeta
- Acessório para amamentação

#### 👴 **Cuidado Adulto**
- Roupa íntima adulta
- Fralda geriátrica

#### 🥗 **Saudabilidade**
- Barra de proteína
- Adoçante, mel, chá, snack saudável

#### 💪 **Nutrição Adulta**
- Complemento alimentar
- Suplemento alimentar
- Fórmula especial adulta

#### 🌱 **Vida Saudável (Público 60+)**
- Vitaminas D+ e cálcio
- Colágeno
- Passiflora e melatonina
- Ômega 3
- Nutrição senior

#### 💊 **MIP (Medicamentos Isentos de Prescrição)**
- Dor e febre, gripe e alergia, sistema digestivo, vitaminas e minerais

#### 👶 **Banho e Troca**
- Higiene infantil
- Troca (lenços umedecidos, talco)
- Cuidado com recém-nascido

#### 👶 **Fraldas Infantis**
- Todos os tamanhos e segmentos
- Elástico e fecho

#### 🛒 **Alimentos e Geladeira**
- **Checkout:** Chocolate, Bala e chiclete, Barra de cereal
- **Geladeira*:** Refrigerante, Água, Água de coco, Isotônico, Whey Protein, Suplemento líquido

#### 🎯 **Área Promocional**
- Cestão
- Ponta de gôndola
- Display de balcão

---

### 🏪 Farmácia G (100m² a 120m²)

#### 🎨 **Dermocosmético e Cosmético**
- Limpeza
- Tratamento
- Fotoproteção facial
- Hidratação
- Nutricosmético

#### ☀️ **Proteção Corporal**
- Protetor solar corporal
- Pós-sol
- Bronzeador
- Repelente

#### 💄 **Perfumaria 1**
- Maquiagem*
- Acessório de maquiagem*
- Pente/escova
- Fixador de cabelo
- Acessório para cabelo*
- Manteiga de cacau
- Perfume/colônia*

#### 💇 **Cabelo e Tintura**
- Shampoo
- Condicionador
- Máscaras de tratamento
- Óleo finalizador
- Tintura
- Produtos de tratamento para cabelo em geral

#### 🌸 **Higiene e Saúde Íntima Feminina**
- Cuidado ginecológico e urinário
- Absorvente (interno e externo)
- Lenço umedecido
- Sabonete íntimo

#### 💅 **Perfumaria 2**
- Alicate
- Acessório para unha
- Acetona
- Esmalte
- Algodão
- Depilação
- Descolorante

#### 🧴 **Desodorante Feminino**
- Roll-on
- Aerosol
- Creme
- Bastão

#### 🧴 **Desodorante Masculino**
- Roll-on
- Aerosol
- Creme
- Bastão

#### 🦷 **Higiene Oral**
- Creme dental
- Enxaguante bucal
- Escova dental
- Fio dental
- Fixador de prótese dentária
- Higienizador de prótese dentária

#### 💑 **Saúde Sexual**
- Preservativo
- Lubrificante
- Gel

#### 🛁 **Higiene Geral**
- Sabonete em barra
- Sabonete líquido
- Óleo corporal
- Acessório para banho*

#### 🏥 **Cuidado ao Paciente**
- **Primeiro socorro:** Assepsia, Curativo e adesivo, Esparadrapo e bandagem, Gaze, atadura, algodão e utensílios, Soro fisiológico
- **Contusão:** Produto de uso tópico em spray, gel, adesivo e outros
- **Tratamento de pele:** Antifúngico, Cicatrização e queimadura
- **Produtos ortopédicos*:** Meia, joelheira, munhequeira

#### 👨 **Cuidado Masculino**
- Shampoo masculino
- Creme para barbear e Lâmina de barbear
- Gel capilar
- Talco para os pés

#### 🥗 **Saudabilidade**
- Barra de proteína
- Adoçante, mel, chá, snack saudável

#### 👁️ **Cuidado Complementar**
- **Cuidado com os olhos:** Colírio e lágrima artificial, Cuidado com a lente de contato, Solução para lente de contato
- **Outros:** Antitabagismo*, Cuidado com o ouvido, Aparelho de aferição*

#### 👴 **Cuidado Adulto**
- Roupa íntima adulta (elástico e fecho)
- Fralda geriátrica

#### 💪 **Nutrição Adulta**
- Complemento alimentar
- Suplemento alimentar
- Fórmula especial adulta

#### 🌱 **Vida Saudável**
- Vitaminas D+ e cálcio
- Colágeno
- Passiflora e melatonina
- Ômega 3
- Nutrição sênior

#### 🥛 **Nutrição Infantil**
- Fórmula, snack, composto lácteo, etc.

#### 🍼 **Puericultura Leve**
- Mamadeira
- Chupeta
- Acessório para amamentação

#### 🍽️ **Puericultura Pesada***
- Prato
- Talher
- Babador

#### 💊 **MIP (Medicamentos Isentos de Prescrição)**
- Dor e febre, gripe e alergia, sistema digestivo, vitaminas e minerais

#### 👶 **Banho e Troca**
- **Higiene infantil:** Shampoo, condicionador, sabonete, pós-banho
- **Troca:** Lenço umedecido, talco
- **Cuidado com recém-nascido**

#### 👶 **Fralda Infantil**
- Todos os tamanhos e segmentos
- Elástico e fecho

#### 🛒 **Alimentos e Geladeira**
- **Em frente ao balcão:** Chocolate, Bala e chiclete, Barra de cereal
- **Geladeira*:** Refrigerante, Água, Água de coco, Isotônico, Whey Protein, Suplemento líquido

#### 🎯 **Área Promocional**
- Cestão
- Ponta de gôndola
- Display de balcão

---

*Boa sorte no desafio! 🍀*
