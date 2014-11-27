####DICA: Github

Como esse material é baseado em um workshop, eu peço para meus alunos subirem os exerciícios no [Github](http://github.com) e alguns ainda não estão familiarizados então vamos lá.

Primeiramente instale o git na sua máquina:

- [MacOs]()
- [Linux]()
- [Windows]()

Depois disso crie uma conta no Github e vamos adicionar uma chave para você poder acessar sua conta via ssh.

Lendo a documentação [Generating SSH keys](https://help.github.com/articles/generating-ssh-keys/) vemos como criamos uma chave ssh no terminal e depois adicionamos na nossa conta no Github.

Depois de feito isso vamos criar nosso repositório git onde estão nosso arquivos:

```
cd /meus-exercicios
git init
```

Vamos criar o repositório no Github, na página inicial.

![](https://cldup.com/gaixfYqF7R.png)

![](https://cldup.com/XlhjpfR_gm.png)

![](https://cldup.com/zp9Fa7XNfu.png)

Pronto agora você deve copiar essa parte:

```
git remote add origin git@github.com:suissa/dica-be-mean.git
```

Volte para o terminal e vamos adicionar os arquivos para comitá-los:

```
git add .
git commit -m 'Subindo os exercícios'
git remote add origin git@github.com:suissa/dica-be-mean.git
git push origin master
```

E está lá quando você der refresh na página do repositório já verá seus arquivos, fácil não?