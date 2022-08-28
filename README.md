---

<p align="center">
  <img alt="FIAP" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Python_logo_and_wordmark.svg/1920px-Python_logo_and_wordmark.svg.png" title="Admin password alert on Discord web." width="40%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Python" src="https://i.imgur.com/vl3WJ2v.png" width="40%">
</p>

# Imersão Python FIAP 1/3.

[<details><summary>Threat hunting de IP com Python.</summary>](https://github.com/usrbinbrain/fiap-python-02/blob/main/README.md)

  - Conceitos fundamentais mais aplicáveis da linguagem.
  - Interagir com uma API pública.
  - Identificar de forma preventiva endereços IP maliciosos.
  - Enviar alertas para uma plataforma online e acessível 24/7.


</details>

## Origem e história do Python. 📜

<details><summary>...</summary>
	
#### 1 - Guido, o criador.
	
O holandês Guido Van Rossum nasceu na capital da província da Holanda do Norte (Haarlem), dia 31 de janeiro de `1956`, estudou matemática na Universidade de Amsterdã, obtendo seu mestrador em `1982`.
	
As linguagens de programação mais discutidas da época eram o ALGOL, Pascal e Fortran, no final do ano de 1989 Guido tomou uma decisão que permitiria o nascimento da linguagem Python.
	
<p align="center">
  <img alt="Guido Van Rossum (2004)" src="https://upload.wikimedia.org/wikipedia/commons/e/e2/Guido-portrait-2014-drc.jpg" title="Guido Van Rossum (2004)" width="35%">
</p>
	
#### 2 - A criatura, o Python.
	
Em dezembro de `1989`, o matemático/programador holandês `Guido Van Rossum` tinha que implementar a linguagem de programação conhecida como ABC, mas essa linguagem tinha varias limitações, uma delas era não conseguir lidar com exeções de uma sistema operacional chamado amoeba.
	
Após realizar a busca de uma linguagem para substituir o ABC e não encontrar uma linguagem semelhante, Guido decidiu que criaria sua própria linguagem, e que seria mais simples, versátil e sem as limitações do ABC.
	
Buscando criar uma linguagem fácil de aprender, em `1991` Guido lançou o primeiro release da linguagem `Python`, quando desenvolveu a linguagem, ele pensou que precisava de um nome que fosse curto, único e um pouco misterioso, e nomeou o projeto de Python, tendo como referência um programa de TV da BBC (1980) chamado `Fly Circus de Monty Python`.

Como o Python recebeu uma grande aderência por parte dos programadores após seu lançamento, 10 anos depois de sua criação, em 6 de março de `2001` foi criada a organização sem fins lucrativos `Python Software Foundation (PSF)`, que passou a deter os direitos de propriedade intelectual por trás da linguagem e ter o Guido Van Rossum como presidente.
	
No ano `2000` a versão 2.0 do Python foi lançada, trazendo novas funcionalidades que colocava o linguagem em nível de paridade com linguagens tradicionais como **SETL** e **Haskell**.
	
Em `2002` a Free Software Foundation (FSF) criada por Richard Matthew Stallman, premiou Guido com o **Prêmio por Avanços em Software Livre** de 2001.
	
De `2005` a `2012`, Van Rossum trabalhou na Google desenvolvendo exclusivamente a linguagem Python durante metade de sua horas trabalhadas durante o dia, permitindo que a versão 3.0 do Python fosse lançada em dezembro de `2008`.

Em janeiro de `2013` começou a trabalhar para Dropbox, até que em julho de `2018`, ele anunciou que estaria se afastando do cargo de diretor da Python Software Foundation (PSF), Guido e a equipe de desenvolvimento da linguagem Python entraram em discordância sobre um nova atualização (PEP572) que romperia com os padrões de sintaxe da linguagem.
	
No ano de 2020 Guido começou a trabalhar na divisão de desenvolvimento da Microsoft, tendo foco em continuar desenvolvendo o Python e estreitar o espaço entre a Microsoft e o mundo Open Source.

Desde então a linguagem vem se estabelencendo com umas das linguagens de programação mais usada no mundo, esse esquema abaixo representa o relatorio do GitHub das linguagems de programação mais usadas na plataforma, essa perqueisa teve 73 milhões de desenvolvedores avaliados durante 8 anos.
	
<p align="center">
  <img alt="GitHub (2021)" src="https://cdn.programadoresbrasil.com.br/wp-content/uploads/2022/01/linguagens-programacao-2021-github-768x393.png" title="GitHub (2021)" width="70%">
</p>

	
</details>

## Por que o Python ⁉️

<details><summary>...</summary>
	
 - [x] Facilidade em aprender, usar, entender e instalar.

 - [x] É conciso, tem uma lógica e linha de raciocínio bem simples e direta.
 
 - [x] É código aberto, ou seja, aberta a contribuições no desenvolvimento, motivando uma vasta e ativa comunidade.

 - [x] É multiplataforma, você pode criar um único programa com a possibilidade de ser usado em vários sistemas operacionais.

 - [x] É nativo em sistemas operacionais Linux/Unix, possibilitando ampla cobertura de servidores e facilidade no rollback de aplicações.

 - [x] Possui proriedades extensíveis, com mais de 100 mil bibliotecas publicadas, podendo reaproveitar soluções de outros desenvolvedores.

</details>

## Áreas de aplicação do Python. ⚙️

<details><summary>...</summary>
	
### Cibersegurança.

A flexibilidade da linguagem Python a transformou na linguagem ideal para a área de segurança da informação por poder ser utilizada para praticamente qualquer coisa dentro desse segmento. 

Ao longo dos anos, com a grande popularidade da linguagem, foram disponibilizadas muitas ferramentas e bibliotecas prontas para facilitar diversos trabalhos, por exemplo:

 - [x] **Scapy**, usado para para análise de pacotes.
 - [x] **Paimei**, excelente para engenharia reversa.
 - [x] **Volatility**, para extrair artefatos digitais da memória RAM em investigações forenses.

Python é uma das linguagems mais usadas no red team (segurança ofensiva), pois permite criar simulações de ataques de cibercriminosos, análise de malwares, envio e decodificação de pacotes, acesso a servidores, varredura de redes e até mesmo envio massivo de e-mails.

### Ciência de dados.

A ciência de dados é um dos campos de aplicação de Python mais famosos, utilizando as bibliotecas **pandas**, **NumPy**, **SciPy**, **StatsModels**, **scikit-learn** para análises de dados, e a **Plotly** para gerar gráficos com os resultados das analises.

As características do Python o torna um facilitador ao executar essa tarefa, fácil de criar scripts e utilizar suas diversas bibliotecas gratuitas, você poderá analisar, processar e exibir os dados com clareza e eficiência.

### Automação robótica de processos (RPA).

Robotic Process Automation (Automação robótica de processos) é um método aplicado de automação que utiliza de programação para criar uma lógica para realizar algum serviço usual. Ou seja, um programa que realiza um serviço que seria usualmente realizado por um ser humano.

Serviços que antes exigiam atenção de diversas pessoas agora podem ser realizados por um processo que é mais rápido. No setor de TI, por exemplo, a introdução de uma solução de RPA pode resultar em produções mais assertivas, resolução rápida de problemas e processos otimizados

Duas bibliotecas se destacam quando o assunto é o RPA, o **Selenium** e o **Pyautogui**, essas bibliotecas Python permitem desenvolver soluções que podem ser executadas 24 horas por dia e que podem seguir um padrão consistente de qualidade.

### Desenvolvimento web (Back-end).

Por ser uma linguagem livre, o desenvolvedor Back-end em Python pode economizar o tempo, afinal, pode se valer dos módulos compartilhados voluntariamente por outros usuários na internet. 

Alguns sites e aplicativos famosos foram criados em Python ou utilizam essa linguagem na construção, por exemplo: **Instagram**, **Google**, **Spotify**, **Netflix** e **Uber**.

Hoje existem 3 frameworks que dominan o desenvolvimento web no que diz respeito ao uso de Python, o **Django**, **Flask** e **FastAPI**.

</details>
	
## Conceitos iniciais. 📚

<details><summary>...</summary>
	
### Scripts em python.

De maneira direta, scripts são **roteiros** seguidos por sistemas computacionais e trazem dados que são processados e transformados em ações.

Na prática os scripts em python são arquivos de texto com instruções em forma de códigos que são imterpretados de cima para baixo, todos scripts python tem a extensão `.py`.
	
<p align="center">
  <img alt="Scripting" src="https://i.pinimg.com/originals/06/60/ef/0660efe82fa3da42ed56eef013171835.gif" title="Scripting" width="25%">
</p>

Normalmente a primeira linha de um script Python é a shebang, essa linha determina a capacidade do script de ser executado como um executável autônomo sem digitar python de antemão no terminal.
	
Existem 2 tipos de shebang, a portátil e a fixa.
	
A shebang portátil permite que o script seja executado pela versão mais atual do Python que esteja instalada no servidor.

```bash
#!/usr/bin/env python3
```

A shebang fixa funciona, mas como ela informa o caminho absoluto do programa que vai executar o scrit, o script não vai ser executados em sistemas operacionais que tiverem o Python instalado em outro diretório.

```bash
#!/usr/local/bin/python
```

Quando um script Python tem a shebang na primeira linha, esse script pode ser executado da segunte forma no Linux.
	
```bash
./script_python.py
```

Quando o script não tem a shebang, o programa que vai interpretá-lo deve ser informado antes do script no comando Linux.
	
```bash
python3 ./script_python.py
```

### Estruturas basicas de armazenamamento de dados.

No Python, podemos utilizar diversos tipos de estruturas de dados. Estas estruturas resolvem um tipo de problema e podem ser úteis em diversas situações. 

As principais estruturas são as `variáveis`, `listas` e `dicionários` e veremos as diferenças e principais características de cada uma.

#### 1 - Variáveis.

Variáveis em Python são lugares reservados na memória de um dispositivo para o armazenamento de dados que posteriormente vão ser usados na execução de uma solução digital.

Essas variáveis podem ter formatos e tamanhos diferentes, confira alguns tipos:

 - [x] Tipo inteiro (**int**): tipagem composta por algarismos numéricos inteiros.

```python
# Declarando uma variável do tipo inteiro (int).
MINHA_VAR = 1
```

 - [x] Tipo ponto flutuante ou decimal (**float**): tipagem composta por algarismos decimais (frações).

```python
# Declarando uma variável do tipo flutuante (float).
MINHA_VAR = 0.3
```

 - [x] Tipo string (**str**): tipagem composta por caracteres que formam palavras, frases e textos.

```python
# Declarando uma variável do tipo string (str).
MINHA_VAR = 'Gabriel'
```

 - [x] Boolean (**bool**): tipagem composta por lógicas binárias, ou seja, expressões que podem ser classificadas como verdadeiras ou falsas.

```python
# Declarando uma variável do tipo boolean (bool).
MINHA_VAR = False

```

#### 1.1 - Melhores práticas na declaração de variáveis em Python.

Existem padrões estabelecidos no Python para que os programas possam ser mais escaláveis, refatoráveis, compreensíveis e legíveis dentre todos os programadores Python.

Existem dois padrões estabelecidos para declaração de nome de variáveis, o `camel case` e o `snake case`.

Na nomenclatura do padrão **camel case** a variável é declarada com uma letra maiúscula no inicio de cada palavra.

```python
# Nome de variável no padrão camel case.
MinhaVar = 10
```

Na nomenclatura do padrão **snake case** a variável é declarada com todas as palavras separadas por underline.

```python
# Nome de variável no padrão snake case.
minha_var = 10
```

#### 1.2 - Visualizando o valor e o tipo de uma variável.

Para visualizar o valor armazenado em uma variável é usada a função `print()`.

```python
# Declarando o valor da variavel.
minha_var = 10
# Exibindo o valor da variavel.
print(minha_var)
```
[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_variables1)
	
Para identificar o tipo de uma variável usamos a função `type()` em conjunto com a função `print()`.

```python
# Declarando o valor da variavel.
minha_var = 10
# Identificando o tipo da variavel.
print(type(minha_var))
```

[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_type)

#### 2 - Listas.

Uma lista é a estrutura de dados mais básica do Python e armazena os dados em sequência, onde cada elemento possui sua posição na lista, denominada de índice. O primeiro elemento é sempre o índice zero e a cada elemento inserido na lista esse valor é incrementado.

No Python, uma lista pode armazenar qualquer tipo de dado primitivo (string, inteiro, float, etc), para a criação de uma lista no Python, a sintaxe é a seguinte:

```python
# Criação de uma lista vazia
minha_lista = []

# Criação de uma lista de inteiros
minha_lista = [1, 2, 3]

# Criação de uma lista com vários tipos diferentes
minha_lista = [1, "Olá, mundo!", 1.1]
```

Para visualizar o valor completo ou apenas um determinado item de uma lista, observe o exemplo abaixo.
	
```python
# Criação de uma lista com vários tipos diferentes
minha_lista = [1, "Olá, mundo!", 1.1]
	
# Visualizando todos os dados da lista.
print(minha_lista)
	
# Visualizando um determinado dado da lista.
print(minha_lista[1])
```
	
[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_list_duplicates)
	
#### 3 - dicionários.

No Python, os dicionários são coleções de itens desordenados, um elemento dentro de um dicionário possui uma chave atrelada a ele, uma espécie de identificador.

Sendo assim, é muito utilizado quando queremos armazenar dados de forma organizada e que possuem identificação única (como acontece em bancos de dados).

```python
# Declarando um dicionario com chaves numericas.
meu_dicionario = {1: "João", 2: "José"}

# Declarando um dicionario com chaves textuais.
meu_dicionario = {"nome": "João", "sobrenome": "Silva"}
```
	
Para visualizar o valor completo ou apenas um determinado item de um dicionário, observe o exemplo abaixo.
	
```python
# Declarando um dicionario com chaves textuais.
meu_dicionario = {"nome": "João", "sobrenome": "Silva"}
	
# Visualizando todos os dados do dicionário.
print(meu_dicionario)
	
# Visualizando um determinado dado do dicionário.
print(meu_dicionario["sobrenome"])
```

[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_dictionary)
	
### Estruturas de Repetição (ou loops) do Python.

Loops ou estruturas de repetição são blocos básicos de qualquer linguagem de programação e são muito importantes, no python podemos usar o loop `for` e o `while` comforme os exemplos abaixo:

#### 1 - Loop for.

O `for` é utilizado para percorrer ou iterar sobre uma sequência de dados (variáveis, listas e dicionários), executando um conjunto de instruções em cada item.

```python
minha_lista = [1, 2, 3, 4, 5]

for item in minha_lista:
    print(item)
```

[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_for)
	
#### 2 - Loop while.

O while é uma estrutura de repetição utilizada quando queremos que determinado bloco de código seja executado enquanto (do inglês while) determinada condição for satisfeita.

Isso permite que a estrutura de repetição execute até sua condição ser atendida, conforme o exemplo abaixo.

```python
contador = 0

while contador < 10:
    print(f'Valor do contador é {contador}')
    contador += 1
```

[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_while)

### Estruturas de condição do Python.

Estruturas de condição são artifícios das linguagens de programação para determinar qual bloco de código será executado a partir de uma determinada condição.

No Python, assim como em outras linguagens, podemos trabalhar com as estruturas de condição utilizando o `if/else` como veremos abaixo.

#### 1 - Condição if.

O uso do `if` em um programa em Python visa verificar se determinada ação é verdadeira e executar o bloco de código contido em seu escopo.

```python
media = 7

if media > 6.9:
	print("Você foi aprovado!")
```

[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_if2)
	
#### 2 - Condição if/else.

Já o uso o `if/else` fará com que uma das ações sejam executadas, já que se a condição dentro do if não for verdadeira, será executado o código contido no **else**.

O if/else irá testar caso a condição seja verdadeira e executar uma determinada ação ou caso a mesma não seja executar outra.

```python
media = 5

if media > 6.9:
	print("Você foi aprovado!")
else:
    print("Você foi reprovado.")
```

[Exemplo de execução](https://www.w3schools.com/python/trypython.asp?filename=demo_if_else2)
	
</details>

## Obtendo o repositório para execução dos scripts de exemplo. 📝

<details><summary>...</summary>
		
Para realizar o clone (download) desse repositório vamos usar o git, em sistemas Linux baseados em Debian o pacote git pode ser intalado digitando o seginte comando (como root) no seu terminal.

```bash
apt-get uptade && apt-get install git -y
```

Para clonar esse repositório digite o seguinto comando no seu termial.

```bash
git clone https://github.com/usrbinbrain/fiap-python-01.git
```

Adicione a permissão de execução em todos os script de exemplo na pasta `fiap-python-01/script-snippet` digitando o seguinte comando.

```bash
chmod +x fiap-python-01/script-snippet/*.py
```

Edite os valores das variaveis nos scripts de exemplo para obter resultados diferentes.

</details>
	
---

