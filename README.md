# 📝 Lista de Tarefas em Python

Um gerenciador de tarefas simples e interativo desenvolvido em Python, com interface de linha de comando (CLI).

## 🎯 Funcionalidades

- ✅ **Adicionar Tarefas**: Crie novas tarefas com nome, prioridade e categoria
- 📋 **Listar Tarefas**: Visualize todas as tarefas cadastradas
- ✔️ **Marcar como Concluída**: Altere o status de tarefas para "Concluída"
- 🗑️ **Excluir Tarefas**: Remova tarefas da lista
- 🔍 **Filtrar Tarefas**: Filtre tarefas por prioridade ou categoria

## 🚀 Como Usar

### Pré-requisitos
- Python 3.10+ (devido ao uso de `match/case`)

### Executar o Programa

```bash
python projeto.py
```

### Menu Interativo

Ao executar, você verá as seguintes opções:

```
============================
    ESCOLHA UMA OPÇÃO:
1 - ADICIONAR NOVA TAREFA
2 - VER TAREFAS ADICIONADAS
3 - MARCAR COMO CONCLUÍDO
4 - EXCLUIR TAREFA
5 - FILTRAR TAREFA
0 - SAIR
============================
```

## 📌 Estrutura das Tarefas

Cada tarefa possui os seguintes atributos:

| Atributo  | Descrição | Exemplo |
|-----------|-----------|---------|
| Nome      | Nome da tarefa | "Estudar Python" |
| Prioridade | Nível de prioridade | Alta, Média ou Baixa |
| Categoria | Categoria da tarefa | "Estudos", "Trabalho" |
| Status    | Status atual | "Pendente" ou "Concluída" |

## 💡 Exemplos de Uso

### 1. Adicionar uma Tarefa
```
Escolha: 1
Digite o nome da tarefa: Estudar Python
Digite a prioridade da tarefa(Alta,Média,Baixa): Alta
Digite a categoria da tarefa: Estudos
Estudar Python adicionado com sucesso
```

### 2. Listar Tarefas
```
Escolha: 2

======= LISTA DE TAREFAS =======
Tarefa 1:
    Nome      : Estudar Python
    Prioridade: Alta
    Categoria : Estudos
    Status    : Pendente
================================
```

### 3. Filtrar por Prioridade
```
Escolha: 5
Como deseja filtrar?
1- Por Prioridade
2- Por Categoria
ESCOLHA: 1
Digite a prioridade (Alta, Média, Baixa): Alta
```

## 📂 Estrutura do Projeto

```
lista_de_tarefas_py/
├── projeto.py          # Arquivo principal com toda a lógica
└── README.md           # Este arquivo
```

## 🔧 Funções Principais

| Função | Descrição |
|--------|-----------|
| `adicionar_tarefas()` | Adiciona uma nova tarefa à lista |
| `listar_tarefas()` | Exibe todas as tarefas cadastradas |
| `concluir_tarefas()` | Marca uma tarefa como concluída |
| `excluir_tarefas()` | Remove uma tarefa da lista |
| `filtrar_tarefas()` | Filtra tarefas por prioridade ou categoria |

## ⚙️ Características Técnicas

- **Armazenamento**: Tarefas armazenadas em memória (lista de dicionários)
- **Busca**: Case-insensitive (maiúsculas/minúsculas não importam)
- **Estrutura de Controle**: Utiliza `match/case` (Python 3.10+)
- **Validação**: Verificação de existência de tarefas antes de operações

## 🎓 Conceitos Aprendidos

Este projeto demonstra conceitos fundamentais de Python:
- ✓ Estruturas de dados (listas e dicionários)
- ✓ Funções e modularização
- ✓ Laços de repetição (for, while)
- ✓ Estruturas condicionais (if/elif/else, match/case)
- ✓ Interface de linha de comando (CLI)
- ✓ Manipulação de strings
- ✓ Tratamento de entrada/saída

## 📝 Licença

Este projeto é de código aberto e pode ser utilizado livremente.

---

**Desenvolvido por:** [rodrigomonte07](https://github.com/rodrigomonte07)