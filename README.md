# Mistério de Assassinato em SQL

![Ilustração de um detetive olhando para evidências](174092-clue-illustration.png)

Houve um assassinato na Cidade SQL! O Mistério de Assassinato em SQL foi projetado para ser tanto uma lição autodirigida para aprender conceitos e comandos SQL quanto um jogo divertido para usuários experientes de SQL resolverem um crime intrigante.

Se você quiser apenas resolver o mistério, vá para [mystery.knightlab.com](https://mystery.knightlab.com). Se você é novo em SQL, pode querer começar pelo [nosso passo a passo](https://mystery.knightlab.com/walkthrough.html). Ele não ensinará tudo sobre SQL, mas deve ensinar tudo o que você precisa para resolver o mistério.

## O que mais está aqui?

Antes de construirmos a versão baseada na web, projetamos isso para que as pessoas baixassem e resolvessem em seus próprios computadores. Se você estiver interessado nisso, continue lendo.

## O que você precisa para resolver no seu próprio computador

* **sql-murder-mystery.db**: Este arquivo de banco de dados SQLite contém todos os dados com os quais você trabalhará.
* **prompt**: Dependendo do seu nível de experiência com SQL, encontre o prompt no arquivo [prompt_experienced](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_experienced.pdf) ou no arquivo [prompt_beginner](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_beginner.pdf).
* **[reference](https://github.com/NUKnightLab/sql-mysteries/blob/master/reference.pdf)**: Este é um curso rápido sobre conceitos e comandos SQL.
* **um ambiente SQLite de sua escolha**: Para iniciantes, recomendamos usar o [SQLiteStudio](https://sqlitestudio.pl/), que é uma boa interface gráfica para inspecionar seus dados e escrever consultas.

## Começando
* **Para iniciantes em SQL**: comece com a referência, leia o arquivo [prompt_beginner](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_beginner.pdf), depois comece [instalando o SQLiteStudio e carregando o arquivo db](https://github.com/NUKnightLab/sql-mysteries/blob/master/sqlite_studio.pdf). Se você ficar preso em algum ponto, sinta-se à vontade para consultar a referência ou abrir uma [issue no GitHub](https://github.com/NUKnightLab/sql-mysteries/issues) para que possamos saber onde nossas instruções precisam ser melhoradas.

* **Para usuários experientes de SQL**: leia o arquivo [prompt_experienced](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_experienced.pdf), depois baixe o arquivo sql-murder-mystery.db e use um ambiente SQL de sua escolha para resolver o mistério. Você pode usar a referência para refrescar sua memória sobre SQL. Tente completar a atividade toda dentro do seu ambiente SQL (sem anotar notas)!

## Verificando a Solução
Escreva as seguintes consultas no seu ambiente SQL para verificar se você encontrou o assassino certo:

```SQL
INSERT INTO solution VALUES (1, "Insira o nome da pessoa que você encontrou aqui");

SELECT value FROM solution;


Autores
Joon Park
Cathy He
Inspiração
Este mistério de assassinato foi inspirado por um crime na cidade vizinha, Terminal City.

Copyright e Licença
O código original para este projeto é liberado sob a Licença MIT.

O texto original e outros conteúdos são liberados sob Creative Commons CC BY-SA 4.0.

Os componentes web personalizados de consulta SQL usados aqui foram adaptados a partir de código criado e liberado ao domínio público por Zi Chong Kao, criador de Select Star SQL.

Imagem do detetive por rambleron usada sob a licença gratuita do Vecteezy.