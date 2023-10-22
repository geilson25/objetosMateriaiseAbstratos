# Projeto de Modelagem de Objetos em JavaScript

Este é um projeto de exemplo que demonstra a modelagem de objetos em JavaScript com foco em dois objetos materiais e dois objetos abstratos relacionados ao cotidiano do aprendizado. O objetivo deste projeto é ilustrar como os objetos podem ser definidos e como suas características e ações podem ser representadas na programação orientada a objetos (POO).

## Objetos Materiais

### Livro

O objeto `Livro` representa um livro físico e possui os seguintes atributos e ações:

- **Atributos**:
  - `titulo` (string) - Título do livro.
  - `autor` (string) - Nome do autor.
  - `numeroDePaginas` (number) - Número de páginas do livro.
  - `anoPublicacao` (number) - Ano de publicação.
  - `genero` (string) - Gênero do livro.
  - `estaEmprestado` (boolean) - Indica se o livro está emprestado.
  - `dataDeEmprestimo` (Date) - Data de empréstimo.
  - `dataDeDevolucao` (Date) - Data prevista de devolução.
  - `nota` (number) - Nota atribuída ao livro.

- **Métodos**:
  - `emprestar()` - Registra o empréstimo do livro.
  - `devolver()` - Registra a devolução do livro.
  - `calcularAvaliacaoMedia()` - Calcula a avaliação média do livro com base nas notas recebidas.
  - `obterDetalhes()` - Retorna os detalhes do livro (título, autor, etc.).
  - `verificarDisponibilidade()` - Verifica se o livro está disponível para empréstimo.
  - `atualizarNota()` - Permite aos leitores atualizarem a nota do livro.
  - `prolongarEmprestimo()` - Estende o período de empréstimo.
  - `verificarAtraso()` - Verifica se o livro está atrasado na devolução.
  - `obterDiasRestantes()` - Retorna o número de dias restantes para a devolução.

### Lápis

O objeto `Lápis` representa um lápis físico e possui os seguintes atributos e ações:

- **Atributos**:
  - `cor` (string) - Cor do lápis.
  - `comprimento` (number) - Comprimento do lápis em centímetros.
  - `pontaAfida` (boolean) - Indica se a ponta do lápis está afiada.
  - `marca` (string) - Marca do lápis.
  - `material` (string) - Material do qual é feito o lápis.
  - `temBorracha` (boolean) - Indica se o lápis possui borracha acoplada.
  - `tamanhoDaBorracha` (number) - Tamanho da borracha em centímetros.
  - `preço` (number) - Preço do lápis.
  - `quantidade` (number) - Quantidade de lápis disponíveis.

- **Métodos**:
  - `afiarPonta()` - Afia a ponta do lápis.
  - `escrever(texto)` - Escreve o texto com o lápis.
  - `apagar()` - Apaga o texto com a borracha (se disponível).
  - `verificarDisponibilidade()` - Verifica se há lápis disponíveis.
  - `comprar()` - Compra mais lápis.
  - `verificarBorracha()` - Verifica se o lápis possui uma borracha.
  - `verificarPonta()` - Verifica se a ponta do lápis está afiada.
  - `amolarBorracha()` - Amola a borracha do lápis.
  - `calcularPrecoTotal()` - Calcula o preço total com base na quantidade.

## Objetos Abstratos

### Aluno

O objeto `Aluno` representa um aluno e possui os seguintes atributos e ações:

- **Atributos**:
  - `nome` (string) - Nome do aluno.
  - `matricula` (string) - Número de matrícula.
  - `curso` (string) - Nome do curso.
  - `idade` (number) - Idade do aluno.
  - `notas` (array de números) - Notas do aluno em diferentes disciplinas.
  - `frequencia` (number) - Percentagem de frequência nas aulas.
  - `status` (string) - Status do aluno (ativo, trancado, formado, etc.).
  - `email` (string) - Endereço de e-mail do aluno.
  - `historicoAcademico` (array de objetos) - Histórico acadêmico com detalhes das disciplinas cursadas.

- **Métodos**:
  - `calcularMedia()` - Calcula a média das notas do aluno.
  - `verificarAprovacao()` - Verifica se o aluno foi aprovado com base nas notas e frequência.
  - `matricularDisciplina(disciplina)` - Registra a matrícula em uma disciplina.
  - `trancarCurso()` - Tranca a matrícula no curso.
  - `solicitarDiploma()` - Inicia o processo de solicitação de diploma.
  - `enviarEmail(mensagem)` - Envia um e-mail para o aluno.
  - `atualizarDadosPessoais(dados)` - Atualiza os dados pessoais do aluno.
  - `obterHistorico()` - Retorna o histórico acadêmico do aluno.
  - `participarAula(disciplina)` - Registra a participação do aluno em uma aula.

### Calculadora

O objeto `Calculadora` representa uma calculadora e possui os seguintes atributos e ações:

- **Atributos**:
  - `marca` (string) - Marca da calculadora.
  - `modelo` (string) - Modelo da calculadora.
  - `alimentacao` (string) - Tipo de alimentação (bateria, solar, etc.).
  - `display` (string) - Conteúdo atual do display.
  - `memoria` (number) - Valor armazenado na memória.
  - `modoOperacao` (string) - Modo de operação atual (adição, subtração, etc.).
  - `historicoOperacoes` (array) - Registro das operações realizadas.
  - `ligada` (boolean) - Indica se a calculadora está ligada.
  - `tamanhoTela` (string) - Tamanho da tela
