# Avaliação Final – Interação Humano-Computador (IHC)

## Identificação do Estudante

- **Nome:** Lucas Bretas Prata de Pinho Tavares
- **Matrícula:** 22400039
- **Curso:** Ciência da Computação
- **Polo:** CEUB / Brasília-DF
- **Data de Entrega:** 17/06/2026

## Descrição Geral

Este repositório reúne as atividades desenvolvidas durante a disciplina de Interação Humano-Computador (IHC), contemplando os desafios das Unidades de Aprendizagem UA1, UA2, UA3 e UA4. Todo o conteúdo das respostas foi consolidado em um único arquivo de entrega, conforme orientação prévia.

---

## UA1 – Introdução à IHC e seus benefícios

### Objetivo

O objetivo desta atividade foi analisar uma interface com problemas de usabilidade, focando na eliminação da ambiguidade em ações críticas e na melhoria da previsibilidade do sistema.

### Solução Desenvolvida

O problema principal identificado na interface foi a ambiguidade dos botões "Avançar" e "Retornar", que geravam incerteza sobre qual ação confirmava a exclusão ou a interrompia. A solução proposta foi trocar os rótulos para indicar claramente a ação, como "Excluir" e "Cancelar". Além disso, sugeriu-se o uso de uma hierarquia visual com cores diferentes, como vermelho para a ação de exclusão, para demonstrar a intenção de cada botão. Essas correções tornam o fluxo previsível e retiram o medo do usuário ao manipular dados sensíveis da folha de pagamento.

### Arquivos Entregues

- Desafios UA's.pdf

---

## UA2 – Interface, interação e Affordance

### Objetivo

O objetivo foi definir o tipo de interface mais acessível e o equipamento necessário para garantir a autonomia de um usuário com limitações físicas (deficiência visual).

### Solução Desenvolvida

Foi definido que a interface mais adequada para o caso é a de fala, pois dispensa o uso de elementos gráficos e torna a interação sonora e acessível. Para garantir o funcionamento, recomendou-se que o equipamento base incorpore leitores de tela com dispositivos de áudio. Isso permite que o usuário cego escute o que está na tela e saiba quais objetos está manuseando (botões, formulários, menus), garantindo total autonomia.

### Arquivos Entregues

- Desafios UA's.pdf

---

## UA3 – Storyboarding e prototipação de interfaces

### Objetivo

O objetivo foi aplicar técnicas de design para compreender, idealizar e prototipar soluções que auxiliem na locomoção de pessoas com deficiência visual em ambientes externos.

### Solução Desenvolvida

A solução seguiu um processo criativo dividido em etapas. Primeiro, utilizou-se storytelling, picture cards e jornada do usuário para compreender as necessidades de Ricardo, um usuário cego e entusiasta da tecnologia que já utiliza smartphones e smartwatches. Na ideação, storyboards foram usados para propor soluções como óculos inteligentes com leitura em áudio, aplicativo em relógio com respostas táteis ou bengala com sensores. Por fim, antes da codificação, previu-se a criação de protótipos de baixa fidelidade para testar interações sonoras e mecânicas e validar a eficácia com o usuário na prática.

### Arquivos Entregues

- Desafios UA's.pdf

---

## UA4 – TypeScript

### Objetivo

O objetivo foi implementar, através de código orientado a objetos, classes para gerenciar produtos e vendas, testando o relacionamento e o cálculo de valores entre as instâncias.

### Funcionalidades Implementadas

- **Criação da Classe Produto:** Implementação com os atributos tipados `nome`, `descricao`, `valorComercial`, `fabricante` e `emEstoque`.
- **Criação da Classe Venda:** Implementação de uma classe recebendo um array de produtos no construtor.
- **Cálculo de Total:** Implementação do método `calcularTotal()` para somar o valor comercial de todos os itens inseridos na venda.
- **Instanciação e Teste:** Criação de objetos reais, como um "Monitor Gamer Samsung Odyssey G40" e uma "Camisa Oficial Cruzeiro", inserção na classe Venda e impressão do valor total no console.

### Tecnologias Utilizadas

- TypeScript
- Node.js

### Como Executar o Projeto

#### Pré-requisitos

- Node.js instalado
- npm ou yarn

#### Instalação

```bash
npm install

### Execução

```bash
node dist/index.js
```

### Compilação

```bash
tsc
```

### Arquivos Entregues

- Desafios UA's.pdf

---

## 💡 Considerações Finais

O desenvolvimento dos desafios proporcionou um entendimento prático sobre como conceber soluções focadas na usabilidade e na acessibilidade. Pude aprender desde a correção de falhas visuais e de navegação até a aplicação de técnicas imersivas como storyboarding e prototipação sonora para usuários cegos. Além disso, a etapa prática com TypeScript solidificou o conceito de como as regras de negócio idealizadas na fase de IHC são, de fato, transpostas para o código.

---

## ✍️ Declaração de Autoria

Declaro que este trabalho foi desenvolvido por mim, respeitando as normas acadêmicas e de integridade estabelecidas pela instituição.

**Nome do Estudante:** Lucas Bretas Prata de Pinho Tavares  
**Data:** 15/06/2026
