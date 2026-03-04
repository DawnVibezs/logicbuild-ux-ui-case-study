# 🏗️ LogicBuild: UX/UI Case Study

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Role](https://img.shields.io/badge/Role-UX%2FUI_Designer-blue)
![Focus](https://img.shields.io/badge/Focus-Acessibilidade_%26_WCAG-orange)

**LogicBuild** é um aplicativo educacional projetado para ensinar lógica de programação (Back-End) para profissionais das áreas de Arquitetura e Engenharia Civil. O projeto utiliza **metáforas visuais da construção civil** e rígidas **diretrizes de acessibilidade (WCAG)** para reduzir a curva de aprendizado e mitigar deficiências situacionais e permanentes.

---

## 🛑 O Problema
A transição de carreira da Engenharia/Arquitetura para a área de Tecnologia esbarra em um obstáculo cognitivo: **a abstração do código**. 
Profissionais acostumados com projetos visuais, palpáveis e estruturais (CAD, Revit) sentem grande frustração ao encarar a "tela preta" do terminal de programação. Além disso, a rotina de dupla jornada gera escassez de tempo e fadiga visual extrema.

## 💡 A Solução: Concreto para o Abstrato
Criar uma interface que traduza linhas lógicas de código em estruturas visuais imediatas. Através do modo **Dual View**, a interface ancora o novo conhecimento (Back-End) em um modelo mental que o usuário já domina (Construção Civil).

> *"Uma classe em Java é a forma de uma viga; instanciar um objeto é concretar essa viga."*

---

## 🎨 Destaques de UX/UI e Acessibilidade (WCAG)

O design foi centrado em resolver dores reais mapeadas na pesquisa de personas:

* **🌑 Dark Mode Nativo (Fadiga Visual):** Uso da paleta *Dark Navy* para mitigar a fadiga ocular de usuários que estudam à noite pelo celular, atingindo taxa de contraste nível AA (WCAG 1.4.3).
* **👁️ Independência de Cor (Daltonismo):** Feedback de sucesso e erro nunca dependem exclusivamente da cor. O par verde/vermelho foi substituído/apoiado por ícones estruturais (✔️ Check, 🔒 Cadeado) e hachuras técnicas (WCAG 1.4.1).
* **👆 Operabilidade Motora (Lei de Fitts):** Botões em formato de "bloco de concreto" posicionados na zona de alcance natural do polegar, com Touch Targets superiores a 48x48 pixels, ideal para uso mobile em movimento (transporte público).

---

## 🔬 Teste de Usabilidade e Iteração

O protótipo foi validado com usuários reais (Engenheiros e Arquitetos) aplicando o protocolo *Think Aloud*. A pesquisa revelou pontos cruciais que geraram a **Iteração 2** do produto:

1. **Refinamento de UX Writing:** O rótulo original *"Enviar para Aprovação"* gerou hesitação (medo de disparar um e-mail/processo externo). Foi iterado para **"Construir Estrutura (Rodar Código)"**, alinhando a ação de TI com a ação da Engenharia.
2. **Affordances e Microinterações:** Os usuários tentaram dar zoom no desenho técnico (memória muscular de CAD). Foram adicionados ícones de lupa (+ e -) e suporte a gestos de *pinch-to-zoom*, respeitando o modelo mental da área.

### 🖼️ Evolução do Protótipo (Versão Final)

![IMG-20260303-WA0118](https://github.com/user-attachments/assets/2de90af2-74b1-4250-bac2-a14d686a7785)

---

## 🚀 Próximos Passos (Visão de Produto)
* **Onboarding Dinâmico:** Testar se usuários *fora* da construção civil conseguem adotar as metáforas após um tutorial curto.
* **Gamificação:** Implementar recompensas na forma de "materiais de construção" para manter a constância nos estudos diários.
* **Acessibilidade Avançada:** Compatibilidade total com leitores de tela para deficiência visual severa.

---
*Projeto desenvolvido como Experiência Prática e avaliado com nota de excelência no quesito de aplicação de métricas de usabilidade e Design Centrado no Usuário.*
