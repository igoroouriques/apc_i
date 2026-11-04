<div align="center">

# 🧠 APC I · Algoritmos e Programação de Computadores I

**Meus exercícios de lógica de programação, escritos em portugol no VisuAlg.**

![VisuAlg](https://img.shields.io/badge/VisuAlg-3.0-198754?style=for-the-badge)
![Portugol](https://img.shields.io/badge/Linguagem-Portugol-1572B6?style=for-the-badge)
![Univille](https://img.shields.io/badge/Univille-Joinville-198754?style=for-the-badge)

*Projeto acadêmico da **Univille, em Joinville (SC)**, com a professora **Sabrina Boing Moreira**.*

</div>

---

## 📖 Sobre o projeto

Este repositório reúne os algoritmos que fiz na disciplina de **Algoritmos e Programação de Computadores I**. Cada arquivo é um exercício que pratica um conceito da lógica de programação, como entrada e saída de dados, decisões, repetições, acumuladores, funções e modularização.

Os programas são curtos e diretos, pensados para estudar a lógica antes de partir para uma linguagem como Java, Python ou C.

## 👩‍🏫 Disciplina

| | |
| --- | --- |
| **Instituição** | Univille · Joinville (SC) |
| **Curso** | Engenharia de Software |
| **Disciplina** | Algoritmos e Programação de Computadores I |
| **Professora** | Sabrina Boing Moreira |
| **Aluno** | Igor de Oliveira Ouriques |

## 📚 Exercícios

| Arquivo | Tema |
| --- | --- |
| `Primeiro Programa.visualg` | Estrutura básica de um algoritmo e saída de dados |
| `Interação.visualg` | Interação com o usuário: entrada e saída de dados |
| `Operações Lógicas.visualg` | Operadores lógicos (`e`, `ou`, `nao`) |
| `Verifica Chuva.visualg` | Estruturas de decisão |
| `Menu Lanchonete.visualg` | Menu de opções com `escolha ... caso` |
| `Exemplo do Para.visualg` | Laço de repetição `para` |
| `Acumulador.visualg` | Variáveis acumuladoras |
| `Acumulador Tentativa minha.visualg` | Minha versão do exercício do acumulador |
| `Funções Caracteres (1).visualg` | Funções para manipular textos |
| `Script_Função.visualg` | Criação e uso de funções |
| `modularização.alg` | Divisão do programa em módulos |

### Exemplo: `Menu Lanchonete.visualg`

```pascal
algoritmo "MenuLanchonete"
var
   opcao: inteiro
inicio
   escreval("1 - Hambúrguer | 2 - Pizza | 3 - Salada")
   leia(opcao)
   escolha opcao
      caso 1
         escreval("Preparando Hambúrguer...")
      caso 2
         escreval("Assando Pizza...")
      caso 3
         escreval("Cortando Salada...")
   fimescolha
fimalgoritmo
```

## 🛠️ Ferramentas

| Item | Uso |
| --- | --- |
| **VisuAlg 3** | Editor e interpretador de portugol |
| **Portugol** | Pseudolinguagem em português para aprender lógica |
| **Git e GitHub** | Versionamento e publicação dos exercícios |

## 🚀 Como rodar

Os arquivos `.visualg` e `.alg` **não abrem direto no navegador**: eles rodam no **VisuAlg**, um programa gratuito.

1. **Instale o VisuAlg 3** pelo site oficial: [visualg3.com.br](https://visualg3.com.br). Ele é feito para Windows. No Linux e no macOS, dá para usar com o Wine.
2. **Baixe o repositório:** na página do projeto, clique em **Code → Download ZIP** e extraia a pasta. Se preferir, clone com Git:

   ```bash
   git clone https://github.com/igoroouriques/apc_i.git
   ```

3. **Abra o VisuAlg** e vá em **Arquivo → Abrir**. Escolha o exercício que quer testar.
4. **Execute** com a tecla **F9**, ou clique no botão de executar.
5. Se o programa pedir algum dado (`leia`), digite o valor na janela de execução e tecle **Enter**.

> 💡 **Dica:** para testar o menu da lanchonete, rode o `Menu Lanchonete.visualg` e digite `1`, `2` ou `3`.

## 📁 Estrutura

```
apc_i/
├── Primeiro Programa.visualg
├── Interação.visualg
├── Operações Lógicas.visualg
├── Verifica Chuva.visualg
├── Menu Lanchonete.visualg
├── Exemplo do Para.visualg
├── Acumulador.visualg
├── Acumulador Tentativa minha.visualg
├── Funções Caracteres (1).visualg
├── Script_Função.visualg
├── modularização.alg
└── README.md
```

## 🎯 O que foi praticado

- Declaração de variáveis e tipos de dados
- Entrada (`leia`) e saída (`escreva` e `escreval`) de dados
- Operadores aritméticos, relacionais e lógicos
- Estruturas de decisão e seleção múltipla (`escolha ... caso`)
- Estruturas de repetição (`para`)
- Acumuladores
- Funções e modularização do código

## 👤 Autor

**Igor de Oliveira Ouriques**
Estudante de Engenharia de Software · Univille, Joinville (SC)

[![GitHub](https://img.shields.io/badge/GitHub-igoroouriques-181717?style=flat-square&logo=github)](https://github.com/igoroouriques)
[![Instagram](https://img.shields.io/badge/Instagram-igoroouriques-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/igoroouriques)

---

<div align="center">

Exercícios acadêmicos, feitos para estudo.
Agradecimento à professora **Sabrina Boing Moreira** pelas aulas e pela orientação. 💚

</div>
