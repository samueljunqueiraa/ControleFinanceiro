# 💰 Controle Financeiro

Sistema de gestão financeira pessoal desenvolvido em **Java** utilizando o gerenciador de dependências **Gradle**. O projeto foca em organizar receitas e despesas com uma arquitetura clara e escalável.

---

## 📋 Funcionalidades
* **Gestão de Transações**: Registro de entradas e saídas financeiras.
* **Persistência de Dados**: Estrutura preparada para integração com bancos de dados como PostgreSQL.
* **Cálculos Automáticos**: Processamento de saldos e fluxos de caixa.

---

## 🛠️ Tecnologias e Ferramentas
* **Linguagem**: Java.
* **Build Tool**: Gradle.
* **IDE**: IntelliJ IDEA (configurações inclusas via `.idea`).

---

## 📁 Estrutura do Projeto

```
ControleFinanceiro/
├── app/                        # Código fonte da aplicação
├── gradle/                     # Configurações do wrapper Gradle
├── .gitignore                  # Arquivos ignorados pelo Git
├── build.gradle                # Scripts de build e dependências
├── gradlew                     # Executável Gradle para Linux/Mac
├── gradlew.bat                 # Executável Gradle para Windows
└── settings.gradle             # Definições do projeto Gradle
```

## 🏗️ Arquitetura e Padrões
O projeto segue princípios de Engenharia de Software para garantir código limpo e manutenção facilitada, alinhado ao objetivo de se tornar um desenvolvedor Java Senior:

SOLID: Divisão de responsabilidades entre classes de serviço e modelos.

Modularização: Uso do Gradle para gerenciar o ciclo de vida da aplicação.

## 📥 Como Executar
Pré-requisitos
Java JDK 17 ou superior.

Gradle (opcional, pois o projeto inclui o wrapper).
```
# Clone o repositório
git clone [https://github.com/samueljunqueiraa/ControleFinanceiro.git](https://github.com/samueljunqueiraa/ControleFinanceiro.git)

# Entre na pasta
cd ControleFinanceiro

# Execute o projeto via Gradle
./gradlew run
```

## 🐾 Projeto desenvolvido para consolidar conhecimentos em Back-end Java e Gestão Financeira. EOF
