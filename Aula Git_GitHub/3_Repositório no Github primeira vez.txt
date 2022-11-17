Repositório no Github primeira vez

* Depois de você ter criado a sua conta na plataforma, você irá em `Criar repositório`

Você vai preencher com as informações do projeto, então dar o nome do repositório, colocar uma breve descrição e crie.

Logo depois vai aparecer essa página um pouco cinza e confusa e com vários comandos (pode até perceber que alguns deles já usamos), mas o que você tem que fazer é bem simples, apenas copie o link que aparecer para você na penúltima linha. 

* Para passar o commit do meu repositório local (da minha máquina) para um repositório na plataforma do Github, usamos o `git remote add origin <link do repositório copiado no github>`

* `origin` é o nome utilizado para referenciar o nosso repositório

Agora já temos o nosso repositório local conectado com o repositório do Github, porém o `commit` que damos na máquina não sobe automaticamente para a plataforma

* Para isso precisaremos empurrar, enviar para lá com o `git push -u origin main`
esse comando é só para primeira vez para fazer a conexão como o github
depois podemos dar um `git push origin main` e já irá funcionar. 

Agora se recarregarmos a página iremos ver o nosso arquivo aqui na plataforma!
