# Exercício: Explorando Evolução de Código com GitEvo

## 1. Repositório selecionado
https://github.com/scikit-learn/scikit-learn

## 2. Gráfico selecionado
![Evolução de Código scikit-learn](prodXtest.png)

## 3. Explicação

### Análise Temporal e Comportamento das Curvas
Ao analisar o gráfico **Production and test files** (gerado pelo GitEvo entre 2021 e 2026), observa-se uma evolução altamente estável e incremental da base de código do projeto:
* **Ficheiros de Produção (production file):** Apresentam um crescimento gradual e constante, subindo de cerca de 620 ficheiros em 2021 para aproximadamente 730 ficheiros em 2026.
* **Ficheiros de Teste (test file):** Mantêm um crescimento igualmente linear e suave, evoluindo de cerca de 220 ficheiros em 2021 para perto de 260 ficheiros em 2026.

### Boas Práticas e Padrões Observados
* **Proporcionalidade e Manutenibilidade:** A curva de ficheiros de teste acompanha em sincronismo o crescimento da base de produção. A proporção mantém-se aproximadamente constante (~1 ficheiro de teste para cada 2.8 a 3 ficheiros de produção), o que demonstra uma cultura madura de *Garantia de Qualidade* (QA) e integração contínua (CI).
* **Ausência de Débito Técnico Abrupto:** As curvas não apresentam picos descontrolados nem quedas acentuadas, o que reflete um ciclo de desenvolvimento consistente, sem refatorações destrutivas ou introdução massiva de código sem cobertura.

### Grandes Alterações no Gráfico
* **Período de Platô (2022–2025):** Entre 2022 e 2025, nota-se uma estabilização no número de ficheiros de produção (estancado em torno dos 660–680 ficheiros). Isso aponta para uma fase de consolidação da arquitetura, onde a equipa focou na melhoria e expansão dos ficheiros existentes em vez de criar novos módulos.
* **Retoma do Crescimento (2025–2026):** Entre 2025 e 2026 observa-se uma nova inclinação positiva no número de ficheiros de produção, acompanhada proporcionalmente pelos ficheiros de testes, assinalando a expansão de novas funcionalidades no projeto.
