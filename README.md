# Acessibilidade-e-Dislexia-Parte-I-Aula-72


## Sobre o projeto

Página simples de blog com dicas para criar senhas seguras, com foco em uma leitura mais clara e acessível.


## criar a base do html "!" pra cliar a estrutura do html 


## codigo: html "O que poderíamos mudar para facilitar a leitura?"

<main>
    <article>
      <h1>Como criar uma senha segura</h1>

      <p>
        Uma senha segura ajuda a proteger suas contas na internet.
        Evite usar informações fáceis de adivinhar, como seu nome
        ou sua data de nascimento.
      </p>

      <h2>Dicas para criar uma senha</h2>

      <ul>
        <li>Use uma senha longa.</li>
        <li>Misture letras, números e símbolos.</li>
        <li>Não use a mesma senha em todos os sites.</li>
      </ul>

      <p>
        Se possível, use um gerenciador de senhas para guardar
        suas senhas com segurança.
      </p>
    </article>
  </main>


## conectar o css com o html: "na linha 07 do html" 

<link rel="stylesheet" href="style.css">


## codigo: "design style.css"




body {
  font-family: Arial, sans-serif;
  font-size: 18px;
  line-height: 1.7;
  color: #222;
  background-color: #f4f6f8;
}

main {
  max-width: 680px;
  margin: 40px auto;
  padding: 24px;
}

article {
  background-color: white;
  padding: 28px;
  border-radius: 8px;
}

h1,
h2 {
  line-height: 1.3;
}

p {
  margin-bottom: 18px;
}

li {
  margin-bottom: 10px;
}


## [ Como abri o projeto html e css ]

## Como executar o projeto

1. Abra este repositório no GitHub Codespaces.
2. No VS Code, abra o terminal em **Terminal → New Terminal**. *Clique em continuar trabalhando no github e selecione a vs mais basica*

![imagem representativa](./assent/captura%20de%20tela%20de%202026-10-06%2008-20-15.png)


3. **Depois que abri a nova página** Execute o comando:

   
   python3 -m http.server 8000


## [ Explicação  do  Programa ]

1-Organizar com HTML: “Usei título, subtítulo, parágrafos e uma lista para separar as ideias.”

2-Escolher uma fonte legível: “Usei Arial, uma fonte sem serifa e comum nos computadores.”

3-Aumentar o tamanho do texto: “Deixei o texto com 18px para ficar mais confortável de ler.”

4-Ajustar o espaço entre linhas: “O line-height: 1.7 evita que as linhas fiquem muito juntas.”

5-Limitar a largura: “O max-width evita que cada linha fique comprida demais.”

6-Comparar antes e depois: peça à turma para dizer o que ficou mais fácil de encontrar e ler.

