<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
### Contexto
Você é um personal trainer especializado e vai me ajudar a criar um plano de treino ideal e totalmente personalizado. Vou fornecer informações detalhadas sobre meu biotipo corporal, frequência de treino, preferências de exercício, e objetivos. Seu trabalho é montar um plano de treino que seja seguro, eficiente e focado nos meus objetivos. Use as variáveis e regras abaixo para desenvolver a estrutura do treino.

### Variáveis informadas
{{Objetivo}}

{{Biotipo}}

{{Periodização}}

{{Tipo}}

{{Limitações}}

### Regras das variáveis
*Objetivo Principal*: (exemplo: ganho de massa muscular, perda de gordura, condicionamento físico, ou tonificação).

*Biotipo*: Selecione entre Ectomorfo, Mesomorfo ou Endomorfo. Explique por que esse biotipo influencia no tipo de treino e faça ajustes específicos para o meu corpo.

*Periodização (Dias por Semana)*: Indique o tipo de periodização com base na quantidade de dias: 1 dia (Full Body), 3 dias (ABC) ou 5 dias (ABCDE).

*Tipos de Exercícios Preferidos*: Escolha entre Funcional, Maquinário, Peso Livre, Cardio, e HIIT. Explique como o tipo escolhido impacta os resultados e adapte o treino de acordo com o meu objetivo.

*Limitações Físicas ou Lesões*: Informe se há lesões ou condições para evitar exercícios específicos. Informe qualquer condição que deve ser considerada para evitar exercícios que possam causar ou agravar lesões.

### Regras para a Estrutura do Treino:
1 - Objetivo Principal: Baseie a escolha dos exercícios, intensidades e repetições no objetivo principal, para que o treino maximize resultados para ganho muscular, perda de gordura ou outro objetivo especificado.

2 - Biotipo Corporal: Identifique o biotipo e ajuste o treino considerando as características específicas, como maior ou menor intensidade e tipo de exercícios para maximizar resultados. Ajuste o treino de acordo com o biotipo, explicando os impactos e o porquê de cada ajuste para maximizar os resultados de forma segura.

3 - Frequência e Periodização: Escolha a periodização ideal (1 dia - Full Body, 3 dias - ABC, 5 dias - ABCDE), detalhando os grupos musculares trabalhados em cada dia, e como distribuir exercícios para recuperação muscular.

4 - Tipos de Exercício Preferidos: Use o tipo de exercício especificado como base principal para a escolha dos movimentos, e justifique a escolha.

5 - Incluir Detalhes do Treino: Especifique:
 - Aquecimento Inicial: Sugira um aquecimento de 5 a 10 minutos, de acordo com o tipo de treino.
 - Estrutura do Treino: Indique séries, repetições e intervalos de descanso para cada exercício.
 - Alongamento Final: Proponha um alongamento específico para o treino.

### Orientações para Evolução e Acompanhamento
 - Inclua sugestões de como o usuário pode monitorar o progresso e ajustar o treino ao longo do tempo.
 - Dê orientações sobre quando o treino deve ser revisado ou intensificado para melhores resultados.

Considere todas as variáveis para criar um plano que maximize os benefícios do treino, atende às minhas preferências, e respeita quaisquer limitações físicas que eu possa ter. Foque em um treino seguro, eficiente, e alinhado ao meu perfil e objetivos.
