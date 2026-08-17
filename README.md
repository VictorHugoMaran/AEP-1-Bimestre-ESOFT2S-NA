# PSE em Ação
### Sistema de Planejamento e Acompanhamento de Ações de Saúde na Escola

Projeto acadêmico desenvolvido para a **Atividade Extensionista Prática (AEP)** — 2º semestre de 2026 — dos cursos de **Engenharia de Software** e **Análise e Desenvolvimento de Sistemas** da **Unicesumar**.

Equipe responsável pela proposta: **IntegraPSE**.

---

## 📌 Sobre o projeto

O **Programa Saúde na Escola (PSE)**, instituído pelo Decreto nº 6.286/2007, articula as áreas de Saúde e Educação para promover ações de prevenção e atenção à saúde nas escolas públicas. Na prática, equipes intersetoriais municipais enfrentam dificuldades para localizar ações programadas, verificar o que já foi realizado ou cancelado e consolidar a quantidade de participantes atendidos, pois essas informações costumam estar dispersas em anotações, formulários e planilhas separadas.

Este projeto propõe o planejamento e o desenvolvimento, em **linguagem C**, de uma **aplicação de terminal** que centralize o cadastro, a consulta, a atualização e o acompanhamento de ações coletivas do PSE — sem armazenar dados clínicos ou identificar individualmente os estudantes.

**Questão norteadora:** Como uma aplicação desenvolvida em linguagem C pode auxiliar uma equipe escolar e de saúde a planejar, registrar e acompanhar ações coletivas do Programa Saúde na Escola, apresentando informações claras aos gestores e preservando a privacidade dos estudantes envolvidos?

---

## 👥 Integrantes

| Nome | RA |
|---|---|
| Victor Hugo Maran Kalomenconkovas | 26001189-2 |
| Murilo Bovo Bonvechio | 26011546-2 |
| Daniel Muniz Gallina | 26008793-2 |

**Curso:** Engenharia de Software 
**Série:** ESOFT2S-NA
**Instituição:** Unicesumar
**Ano:** 2026/2

---

## 🎯 Escopo mínimo do sistema

1. **Cadastrar** uma ação do PSE (código, escola, tema, data prevista, público-alvo, responsável, quantidade prevista de participantes e situação inicial).
2. **Listar** todas as ações cadastradas.
3. **Pesquisar** ações por código, escola ou tema.
4. **Atualizar a situação** da ação (planejada, realizada ou cancelada), registrando a quantidade efetiva de participantes quando realizada.
5. **Gerar um resumo geral** com quantidade de ações planejadas, realizadas e canceladas, total de participantes e percentual de participação.
6. **Validar entradas** (códigos repetidos, quantidades negativas, campos obrigatórios vazios, opções inexistentes no menu).

Fora do escopo: registro individualizado de estudantes, diagnósticos, triagens, banco de dados, interface gráfica ou aplicação web.

---

## 🛠️ Tecnologias e restrições técnicas

- **Linguagem:** C
- **Execução:** terminal (linha de comando)
- **Armazenamento:** em memória durante a execução (uso de arquivo é opcional, como melhoria adicional)
- **Estruturas utilizadas:** condicionais, laços de repetição, vetores e funções, com código modularizado (sem concentrar lógica na `main`)

---

## 📂 Estrutura do repositório

```
.
├── docs/
│   ├── AEP_1_Entrega_PSE_em_Acao.docx     # Documento escrito da 1ª entrega
│   ├── fluxograma_geral.png               # Fluxograma do menu principal
│   └── fluxograma_atualizar_situacao.png  # Fluxograma detalhado da operação
├── src/                                   # Código-fonte em C (a ser adicionado na 2ª etapa)
└── README.md
```

---

## 📈 Status do projeto

- [x] **1ª Entrega — Documento Escrito:** contextualização, problema, objetivos, justificativa, fluxogramas, pseudocódigos, requisitos funcionais e não funcionais, planejamento de sprints e reflexão social/ética.
- [ ] **2ª Entrega — Implementação e Apresentação:** código-fonte completo em C, diagrama e descrição de casos de uso, manual do usuário, capturas de tela e vídeo de apresentação (até 7 minutos).

O planejamento completo das sprints, os requisitos detalhados e os fluxogramas estão disponíveis na pasta [`docs/`](./docs).

---

## ⚖️ Limites éticos

O sistema trabalha exclusivamente com **dados fictícios** e informações coletivas sobre as ações do PSE. Não são cadastrados nome, diagnóstico, prontuário ou qualquer dado sensível individual de estudante, e o programa não realiza diagnóstico, triagem médica, prescrição ou recomendação de tratamento.

---

## 📚 Referências

- BRASIL. Decreto nº 6.286, de 5 de dezembro de 2007. Institui o Programa Saúde na Escola – PSE e dá outras providências. *Diário Oficial da União*, Brasília, DF, 6 dez. 2007.
- BRASIL. Ministério da Saúde. O que é o Programa Saúde na Escola (PSE)? Brasília, DF, 2025.
- BRASIL. Ministério da Saúde. Quais são as ações do PSE? Brasília, DF, 2025.
- SOUSA, M. C. de; ESPERIDIÃO, M. A.; MEDINA, M. G. A intersetorialidade no Programa Saúde na Escola: avaliação do processo político-gerencial e das práticas de trabalho. *Ciência & Saúde Coletiva*, Rio de Janeiro, v. 22, n. 6, p. 1781-1790, 2017.

---

*Projeto de caráter estritamente acadêmico, desenvolvido no contexto da AEP 2026/2 da Unicesumar.*
