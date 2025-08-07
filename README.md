# Desafio - Sistema de Layout e Planograma para Farmácias

## 📋 Descrição do Projeto

Este projeto é um desafio dividido em **2 etapas principais** que consiste no desenvolvimento de um sistema web para auxiliar lojistas (farmacêuticos) na escolha do tamanho da área de vendas da loja e visualização de planogramas por categoria de produtos.

## 👥 Composição dos Grupos

- **Mínimo:** 8 pessoas
- **Máximo:** 10 pessoas
- **Divisão:** Uma parte do time ficará responsável pela **Etapa 1** e outra parte pela **Etapa 2**

## 🚀 Entrega

- **Formato:** Site funcional
- **Tecnologia:** Livre escolha do grupo
- **Requisito:** Ambas as etapas devem estar implementadas na entrega final

### 🎤 Apresentação do Sistema

#### **Requisitos da Apresentação:**
- **Sistema Funcional:** Demonstração do sistema em funcionamento completo
- **Justificativa Técnica:** Explicação das tecnologias utilizadas e motivações das escolhas
- **Demonstração Prática:** Apresentação ao vivo do sistema funcionando

#### **Critérios de Avaliação da Apresentação:**
- **⚡ Desempenho:** Velocidade e responsividade do sistema
- **🧭 Qualidade do Fluxo de Navegação:** Intuitividade e facilidade de uso
- **🎨 Qualidade da Interface:** Design, usabilidade e experiência do usuário
- **⚙️ Complexidade de Desenvolvimento:** Sofisticação técnica e funcionalidades implementadas

---

## 🏪 ETAPA 1 - Escolha da Planta e Definição de Categorias

### Objetivo
Permitir que o lojista escolha o tamanho da área de vendas da sua loja e visualize a distribuição dos universos e categorias.

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

*Nota: Os planogramas por categoria estão na pasta `/planogramas`*

#### 3. Exportação de Dados
- **Funcionalidade:** Exportar planograma selecionado
- **Formato:** Pasta compactada (.zip)
- **Conteúdo:** Uma ou mais listas de produtos com suas respectivas informações

### Funcionalidades Adicionais (Diferenciais)

#### 🌐 Navegação 3D
- **Mapa Navegável 3D:** Implementar visualização tridimensional da loja
- **Interatividade:** Permitir que o usuário navegue virtualmente pela loja
- **Interação com Categorias:** Clicar diretamente nas seções da loja para acessar os planogramas

---

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
├── planogramas/             # Planogramas por categoria, separado por tamanhos de loja
│   ├── loja_p/              # Planogramas da loja pequena por categoria
│   ├── loja_m/              # Planogramas da loja média por categoria
│   └── loja_g/              # Planogramas da loja grande por categoria
└── README.md                # Este arquivo
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

#### Universo Beleza
- 🎨 Dermocosméticos e Cosméticos
- ☀️ Proteção Corporal
- 💅 Perfumaria 2
- 💇 Cabelos e Tinturas

#### Universo Higiene
- 🧴 Desodorante
- 💑 Saúde Sexual
- 👨 Cuidado Masculino
- 🦷 Higiene Oral

#### Universo Alimentos Nutricionais e Suplementos
- 💪 Nutrição Adulta
- 🌱 Vida Saudável

#### Universo Saúde
- 💊 MIP (Medicamentos Isentos de Prescrição)

#### Universo Infantil
- 🍼 Puericultura Leve
- 👶 Banho e Troca
- 🥛 Nutrição Infantil

#### Checkout
- 🛒 Alimentos e Geladeira

---

### 🏪 Farmácia M (75m² a 99m²)

#### Universo Beleza
- 🎨 Dermocosméticos e Cosméticos
- ☀️ Proteção Corporal
- 💅 Perfumaria 2
- 💇 Cabelos e Tinturas

#### Universo Higiene
- 🧴 Desodorante
- 💑 Saúde Sexual
- 👨 Cuidado Masculino
- 🦷 Higiene Oral

#### Universo Alimentos Nutricionais e Suplementos
- 💪 Nutrição Adulta
- 🌱 Vida Saudável

#### Universo Saúde
- 💊 MIP (Medicamentos Isentos de Prescrição)

#### Universo Infantil
- 🍼 Puericultura Leve
- 👶 Banho e Troca
- 🥛 Nutrição Infantil

#### Checkout
- 🛒 Alimentos e Geladeira

---

### 🏪 Farmácia G (100m² a 120m²)

#### Universo Beleza
- 🎨 Dermocosmético e Cosmético
- ☀️ Proteção Corporal
- 💇 Cabelo e Tintura
- 💅 Perfumaria 2

#### Universo Higiene
- 🧴 Desodorante Feminino
- 🧴 Desodorante Masculino
- 🦷 Higiene Oral
- 💑 Saúde Sexual
- 👨 Cuidado Masculino

#### Universo Alimentos Nutricionais e Suplementos
- 💪 Nutrição Adulta
- 🌱 Vida Saudável

#### Universo Saúde
- 💊 MIP (Medicamentos Isentos de Prescrição)

#### Universo Infantil
- 🥛 Nutrição Infantil
- 🍼 Puericultura Leve
- 👶 Banho e Troca

#### Checkout
- 🛒 Alimentos e Geladeira

---

*Boa sorte no desafio! 🍀*
