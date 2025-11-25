# ⚡ Calculadora de Economia - Associação Ibiapaba Solar

![Ibiapaba Solar](logo.png)

## 🌟 Sobre o Projeto

Calculadora online desenvolvida para a **Associação Ibiapaba Solar** que permite aos usuários simularem economia real na conta de energia através do sistema de compensação de energia solar compartilhada.

**🔗 Site Online:** [https://ibiapabasolar.netlify.app](https://ibiapabasolar.netlify.app)

## 🎯 Funcionalidades

### 💰 Cálculos Precisos
- **Simulação realista** baseada no Estatuto Social da associação
- **Fórmula do Artigo 21º**: `Valor = [(Cmc - Cgd) × 0,8]`
- **Tarifas atualizadas** do mercado cativo e geração distribuída
- **Cálculo automático** de CIP e custos de disponibilidade

### 📱 Experiência do Usuário
- **Interface responsiva** para mobile e desktop
- **Duas opções de entrada**: valor da fatura ou consumo em kWh
- **Resultados detalhados** com comparação lado a lado
- **Design moderno** com degradê verde e animações suaves

### 🔗 Integração com WhatsApp
- **Botão direto** para contato comercial
- **Mensagem automática** com dados da simulação
- **Lead qualificado** com informações completas

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Design moderno com Glassmorphism
- **JavaScript** - Cálculos e interatividade
- **GitHub Pages** - Hospedagem gratuita
- **Netlify** - Deploy contínuo

## 📊 Como Funcionam os Cálculos

### 🧮 Fórmula Base
```javascript
Valor Contribuição = [(Cmc - Cgd) × 0,8]

Onde:
- Cmc = (Consumo × 0,9727) + 140,06
- Cgd = [(Consumo × 0,9727) - (Créditos × 0,7392)] + 140,06
