# Curso de GIT e Versionamento 

## Primeiros passos no código
* Usar git init
* Usar git add . (assim ele adiciona a pasta git invisível)

## Como conectar ao meu repositório remoto
* Usar git remote add origin (link)


## Salvando alterações
* O CNTRL - S primeiro
* Usar git add (nome do arquivo)
* Usar git commit -m "Sua mensagem"

### Enviando para o repositório remoto (GitHub)
* Usando git remote vemos tudo o que temos em relação aos remotos 
* git push origin main 



## Compartilhar entre amigos o código:

* Se eu quiser verificar antes pelo git se desejo que o que meu amigo editou venha para meu código:
 git fetch -> git diff origin/master (mostra a diferença do meu código pro do repositório)
 * Quando seu amigo utilizando o mesmo repositório github atualizar algo no código utilize:
 git pull

# Branch
## São ramificações do código, podendo um amigo trabalhar em uma parte do código e você em outra, até que em certo ponto nós possamos unir nossos códigos.
* Como criar uma nova branch:
git branch (nome da branch)

* Como saber quais branchs tenho no meu código:
git log --oneline --decorate

* Como IR para alguma branch:
git checkout (nome da branch)
* Agora vocês podem trabalhar em projetos diferentes, sem afetar o código um do outro.

### E como juntar com a outra?
git merge (nome da branch que quer juntar com a sua)

