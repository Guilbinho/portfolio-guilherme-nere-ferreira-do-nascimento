# 🧮 Calculadora de IMC

## 📝 Descrição do Projeto
Este projeto consiste em uma calculadora de **Índice de Massa Corporal (IMC)** que roda direto no navegador. A pessoa informa o peso (em kg) e a altura (em metros), clica em **CALCULAR** e recebe o valor do IMC com a respectiva classificação.

Desenvolvido como parte da disciplina de **Desenvolvimento Front-End Para Web (2026.2)**, o objetivo da atividade era praticar JavaScript em uma página HTML: ler dados de um formulário, validar a entrada, fazer o cálculo e mostrar o resultado na tela.

### ⚙️ Como funciona
O IMC é calculado pela fórmula:

```
IMC = peso / (altura × altura)
```

O resultado é mostrado com 2 casas decimais e classificado assim:

| IMC | Classificação |
| :--- | :--- |
| Abaixo de 18,5 | Baixo peso |
| 18,5 a 24,99 | Peso normal |
| 25 a 29,99 | Sobrepeso |
| 30 a 34,99 | Obesidade grau I |
| 35 a 39,99 | Obesidade grau II |
| 40 ou mais | Obesidade grau III (mórbida) |

Se algum campo estiver vazio ou com valor zero/negativo, a página exibe **"Entrada Inválida"**.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** HTML5 e JavaScript
* **Ferramentas:** VSCode <!-- confirme a ferramenta que você usou -->
* **Modelo de IA:** [Nome do modelo, ex: Gemini / ChatGPT] <!-- preencha -->

## 📊 Resultados e Aprendizados
* **Leitura de dados:** aprendi a pegar o valor digitado nos campos com `document.getElementById(...).value`.
* **Funções e eventos:** liguei o botão à função `calcularIMC()` usando o evento `onclick`.
* **Validação de entrada:** usei `isNaN` e comparações para impedir cálculo com campos vazios ou valores inválidos.
* **Estruturas condicionais:** usei `if / else if / else` para classificar o resultado em faixas.
* **Formatação de números:** usei `toFixed(2)` para mostrar o IMC com duas casas decimais.
* **Atualização da página:** escrevi o resultado na tela com `innerHTML`, sem recarregar a página.

## 🧠 Declaração de Uso Ético da IA
Este projeto utilizou inteligência artificial ([Nome do Modelo, ex: ChatGPT / GitHub Copilot]) estritamente como ferramenta de suporte tecnológico para [Finalidade, ex: revisão da lógica de validação e depuração de funções em JavaScript]. Todo o código gerado foi revisado, testado e compreendido por mim, garantindo a minha responsabilidade integral sobre a autoria final, integridade e funcionamento da aplicação.

## 💻 Deploy do projeto
[Clique para acessar](https://guilbinho.github.io/NOME-DO-REPO/AT3-Calculadora-IMC/)

---
[Voltar ao início](https://github.com/Guilbinho/NOME-DO-REPO)

