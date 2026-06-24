# Aula Prática Git

## Objetivo
Praticar:
- Criação de branches
- Commits
- Pull Requests

## Atividade

Cada aluno deve:
1. Criar uma branch com seu nome
2. Criar um arquivo .txt com seu nome
3. Fazer commit
4. Abrir um Pull Request bem documentado

---
### 1. Clonar o repositório
`git clone URL_DO_REPOSITORIO`

`cd aula-pratica-git`

### 2. Criar branch (PADRÃO OBRIGATÓRIO)
### Exemplo:
**kaua/minha-atividade**

### 3. Criar a branch
`git checkout -b kaua/minha-atividade`
ou
`git branch kaua/minha-atividade`

### 4. Criar o arquivo TXT
`echo "Nome: Kauã" > kaua.txt`

`echo "Curso: (opcional)" >> kaua.txt`

`echo "Mensagem: Estou aprendendo Git!" >> kaua.txt`

**Verificar o conteúdo:**
`cat kaua.txt`

### 5. Commit
`git add .`

`git commit -m "feat: adiciona arquivo kaua.txt"`

### 6. Enviar para o GitHub
`git push origin nome-da-sua-branch`

## Modelo obrigatório de PR
### O que foi feito?
Criei um arquivo TXT com meu nome.

### Por que foi feito?
Para praticar o fluxo de Git (branch, commit e PR).

### Como foi feito?
- Criei uma branch com meu nome
- Criei o arquivo kaua.txt
- Adicionei minhas informações
- Fiz commit e push

### Como testar?
Verificar se o arquivo kaua.txt foi criado corretamente no repositório.
