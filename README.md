
# Laboratório Linux

## Sobre o Projeto

Projeto prático desenvolvido durante meus estudos de Ciência da Computação para praticar Linux e utilização do terminal.
O laboratório simula a estrutura de arquivos de uma instituição de ensino, permitindo praticar navegação entre diretórios, organização de arquivos, filtragem de informações e análise de dados por meio de comandos Linux.

## Objetivos

- Praticar navegação entre diretórios no Linux.
- Praticar a criação, organização e manipulação de arquivos e diretórios.
- Praticar filtros e consultas de informações pelo terminal.
- Praticar a combinação de comandos utilizando pipelines.
- Desenvolver raciocínio lógico na resolução de tarefas no terminal.
- Desenvolver familiaridade com o terminal Linux.

## Estrutura do Projeto

```text 
colegio-novo-rumo/
|-- Administrativo/
|-- Alunos/
|-- Professores/
|-- dados/
|-- relatorios/
|-- TI/
|-- treino_atividade/
|-- treino_extra/
|-- treino_revisao/
|-- treino_revisao_2/
`-- README.md
```

## Principais comandos praticados

- `pwd` - Exibe o diretório atual.
- `ls` - Lista arquivos e diretórios.
- `cd` - Permite navegar entre diretórios.
- `mkdir` - Cria diretórios.
- `touch` - Cria arquivos vazios.
- `cp`  - Copia arquivos e diretórios.
- `mv` - Move ou renomeia arquivos e diretórios.
- `cat` - Exibe o conteúdo de arquivos.
- `head` - Exibe as primeiras linhas de um arquivo.
- `tail` - Exibe as últimas linhas de um arquivo.
- `grep` - Filtra linhas de acordo com um texto ou padrão.
- `sort` - Ordena informações.
- `uniq` - Identifica ou agrupa linhas repetidas.
- `cut` - Extrai campos ou partes de uma linha.
- `wc` - Conta linhas, palavras e caracteres.
- `find` - Localiza arquivos e diretórios.

## Exemplos de comandos

### Navegação

```bash
cd treino_extra
cd arquivos
cd ..
cd ../..
```

### Visualização de arquivos

```bash
cat treino_extra/arquivos/usuarios.txt
```

### Filtragem de informações

```bash
grep "Bloqueado" treino_extra/arquivos/usuarios.txt
```

### Filtragem com contagem

```bash
grep "Ativo" treino_extra/arquivos/usuarios.txt | wc -l
```

### Seleção de campos e agrupamento

```bash
cut -d ";" -f 2 treino_extra/arquivos/usuarios.txt | sort | uniq -c
```

Nesse exemplo, o segundo campo de cada linha é selecionado, os resultados são ordenados e as ocorrências são contabilizadas.

## Exemplos de dados

O arquivo `usuarios.txt` utiliza o formato:

```text
nome;tipo;status
```

Exemplo:

```text
ana;Professora;Ativo
bruno;Aluno;Ativo
diego;Aluno;Bloqueado
```

## Conhecimentos desenvolvidos

Durante o desenvolvimento deste laboratório, foram praticados conceitos como:
 
- Estrutura hierárquica de diretórios.
- Caminhos relativos.
- Navegação no sistema de arquivos.
- Manipulação de arquivos e diretórios.
- Filtragem de dados.
- Processamento de texto no terminal.
- Uso de pipelines com `|`.
- Combinação de comandos Linux para análise de informações.
- Busca de arquivos e diretórios com `find`.

## Tecnologias

- Linux
- Ubuntu
- WSL (Windows Subsystem for Linux)
- Shell / Terminal
- Git
- GitHub

## Status do projeto
 
Em desenvolvimento.
 
O projeto será atualizado conforme novos conhecimentos de Linux, Shell Script, Git e GitHub forem estudados.

## Objetivo profissional
 
Este projeto faz parte do meu processo de formação em Ciência da Computação e tem como objetivo demonstrar minha evolução prática em Linux e ferramentas utilizadas na área de Tecnologia da Informação.

## Próximos passos

- Continuar os estudos de Linux.
- Aprofundar os conhecimentos em Git e GitHub.
- Iniciar os estudos de Shell Script.

