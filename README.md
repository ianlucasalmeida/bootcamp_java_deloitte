# Bootcamp Java Deloitte

# CRUD de Clientes - Java Puro (Bootcamp Deloitte)

Este é um projeto de sistema de cadastro de clientes (CRUD) desenvolvido em Java Puro (Java SE) rodando no terminal. O projeto utiliza `ArrayList` para gerenciar os dados em memória, focando nos conceitos de Programação Orientada a Objetos e controle de fluxo.

## 📁 Estrutura do Projeto

O projeto segue a padronização de pacotes do Java (`com.deloitte.cadastro`):

```text
.
├── README.md
└── src
    └── com
        └── deloitte
            └── cadastro
                ├── Cliente.java
                └── Main.java
```

## 🚀 Como executar o projeto (Terminal Linux/Mac/Windows)

Para compilar e rodar o projeto corretamente sem erros de pacote (`Incorrect Package`), siga os passos abaixo no seu terminal.

**1. Abra o terminal na raiz do projeto e acesse a pasta `src`:**
```bash
cd src
```

**2. Compile os arquivos Java:**
Este comando irá gerar os arquivos `.class` compilados dentro da mesma estrutura de pastas.
```bash
javac com/deloitte/cadastro/*.java
```

**3. Execute o programa principal:**
No Java, você deve chamar o arquivo usando o nome completo do pacote a partir da pasta `src`.
```bash
java com.deloitte.cadastro.Main
```

## 💻 Como executar via VS Code

Se preferir rodar direto pela interface do VS Code:
1. Certifique-se de ter o **Extension Pack for Java** instalado.
2. Abra o arquivo `Main.java`.
3. Verifique se a primeira linha contém exatamente `package com.deloitte.cadastro;`.
4. Clique no botão **"Run"** (ou "Executar") que aparece logo acima do método `public static void main`.

## 🔄 Como versionar e enviar o código (Git)

Para salvar suas alterações e enviá-las para o repositório remoto no GitHub, certifique-se de estar na raiz do projeto e execute:

```bash
# 1. Adiciona todos os arquivos modificados e novos (incluindo este README)
git add .

# 2. Cria um commit com uma mensagem clara sobre a atualização
git commit -m "docs: atualiza README com instrucoes de execucao e comandos git"

# 3. Envia o código para a branch main no GitHub
git push origin main
```
*(Nota: Caso ocorra um erro de "Internal Server Error 500" durante o push, aguarde alguns instantes e tente o comando de push novamente, pois isso geralmente indica instabilidade temporária no GitHub).*

## 🛠️ Tecnologias Utilizadas

* Java SE (JDK 8 ou superior)
* Scanner (Entrada de dados)
* ArrayList (Armazenamento em memória)