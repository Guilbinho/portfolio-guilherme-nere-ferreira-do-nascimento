# 📚 Dicionário de Dados Interativo — Trimix Sorveteria

## 📝 Descrição do Projeto
Este projeto consiste em um **dicionário de dados interativo** do banco de dados da **Trimix Sorveteria**, uma rede de 4 lojas com atendimento de balcão. O dicionário documenta as **19 tabelas** do sistema de gestão operacional e vendas (vendas, caixa, estoque por loja, transferências, estornos, segurança por perfil, auditoria e LGPD).

Desenvolvido como parte da disciplina de **Modelagem de Banco de Dados** (UNICID), com orientação do Prof. Dr. Diego Marques de Carvalho, como atividade do **Grupo 07**. O dicionário complementa o projeto de modelagem da Trimix, que reúne requisitos, DER e scripts SQL.

Para cada coluna, o site mostra:

| Informação | O que explica |
| :--- | :--- |
| **Atributo** | Nome da coluna |
| **Descrição / Regra de Negócio** | Para que serve a coluna e as regras (RN) ligadas a ela |
| **Tipo e Tamanho** | Tipo de dado no MySQL (`INT(11)`, `VARCHAR(100)`, `DECIMAL(10,2)` etc.) |
| **Constraints** | Chaves primárias e estrangeiras, campos únicos, `NOT NULL` e valores padrão |
| **Privacidade (LGPD/GDPR)** | Classificação do dado: `[DPS]` dado pessoal sensível, `[DP]` dado pessoal ou `[N/A]` |
| **Linhagem** | De onde o dado vem e para onde ele segue |
| **Controle de Acesso (RBAC)** | Quais perfis (atendente, gerente, administrador) podem ler ou alterar |

### ✨ Funcionalidades do site
* **Busca** por nome de tabela ou de coluna.
* **Menu lateral** com atalho para cada uma das 19 tabelas.
* **Tema claro/escuro** com um clique.
* **Visualizador do DER** (Diagrama Entidade-Relacionamento) com zoom e arrastar.
* **Download da Especificação de Requisitos e Regras de Negócio** em PDF.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** HTML5, CSS3 e JavaScript
* **Bibliotecas:** [Panzoom](https://github.com/timmywil/panzoom) 4.5.1 (zoom e movimento do DER), carregada por CDN
* **Banco de dados documentado:** MySQL 8.0, engine InnoDB
* **Ferramentas:** VSCode e GitHub Pages <!-- confirme as ferramentas que você usou -->
* **Modelo de IA:** [Nome do modelo, ex: Gemini / ChatGPT / Claude] <!-- preencha -->

## 📁 Estrutura de arquivos
```
/
├── index.html      # estrutura da página
├── style.css       # estilos e tema claro/escuro
├── script.js       # dados das tabelas, busca, menu e DER
├── assets/
│   └── der.png     # diagrama entidade-relacionamento
└── docs/
    └── Especificacao_Requisitos_Regras_Negocio_BD.pdf
```

## 📊 Resultados e Aprendizados
* **Documentação de banco:** aprendi o que um dicionário de dados precisa conter para que outra pessoa entenda o banco sem consultar o código.
* **Tipos e constraints:** praticei a descrição de chaves primárias e estrangeiras, campos únicos e valores obrigatórios.
* **LGPD na modelagem:** classifiquei as colunas como dado pessoal, pessoal sensível ou não aplicável, e vi como isso afeta a anonimização e o controle de acesso.
* **Controle de acesso (RBAC):** relacionei cada tabela aos perfis de atendente, gerente e administrador.
* **Dados em JavaScript:** o conteúdo do dicionário fica em uma estrutura de dados no `script.js`, e a página é montada a partir dela, o que facilita corrigir ou incluir colunas.
* **Trabalho em grupo:** o documento foi dividido entre responsáveis pelas regras de negócio (Data Owners) e pela qualidade técnica do dicionário (Data Stewards), e a lista completa está na página inicial do site. Minha função foi a de Data Steward.

## 🧠 Declaração de Uso Ético da IA
Este projeto utilizou inteligência artificial ([Nome do Modelo, ex: ChatGPT / GitHub Copilot / Claude]) estritamente como ferramenta de suporte tecnológico para [Finalidade, ex: estruturação do HTML e do JavaScript da página interativa]. Todo o código gerado foi revisado, testado e compreendido por mim, garantindo a minha responsabilidade integral sobre a autoria final, integridade e funcionamento da aplicação.

## 💻 Deploy do projeto
[Clique para acessar](https://guilbinho.github.io/dicionario-dados-trimix/)

---
[Voltar ao início](https://github.com/Guilbinho/NOME-DO-REPO-PORTFOLIO)
