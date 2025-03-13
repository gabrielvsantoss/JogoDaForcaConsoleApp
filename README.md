#Jogo da Forca

![](https://imgur.com/RyW9d6R)

#Funcionalidades:
- **Interação com o usuario:** Permite o usuario de tentar acertar uma palavra sorteada pelo sistema.
- **Contagem de erros:** Consegue contar os erros do usuario.
- **Sistema de Vitória ou Derrota:** Consegue descobrir se o usario acertou a palavra ou passou dos 5 erros permitidos.


#Como usar
1. Clone o repositório ou baixe o código fonte.
2. Abra o terminal ou o prompt de comando e navegue até a pasta raiz
3. Utilize o comando abaixo para restaurar as dependências do projeto.


```
dotnet restore
```

4. Em seguida, complete uma solução utilizando o comando:
```
dotnet build --configuration Release
```

5. Para executar o projeto compilado em tempo real:
```
dotnet run --- project JogoDaForca.ConsoleApp
````

6. Para executar o arquivo compilado, navegue até a pasta ./JogoDaForca.ConsoleApp/bin/Release/net8.0/e execute o arquivo:
````
JogoDaForca.ConsoleApp.exe
````

#Requisitos
- .NET SDK para construção e execução do projeto.