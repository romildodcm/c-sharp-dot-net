# Anotações

**Comentários**
```
// de uma linha

/*
Multiplas
Linhas
*/
```

**print**

Classe + método que insere uma quebra de linha '\n' ao final `Console.WriteLine("hello");`, se não quiser, só usar o método `Write("Hello);`, **sempre usar o  ponto e vírgula `;` após as instruções/comandos**.

**Método**

- Após um método sempre terão os parênteses `()`, com ou sem parâmetros. Exemplos:

```
WriteLine()
Write()
```

**.NET**

- Ecossistema para desenvolvimento de aplicativos
-  C# e F#
-  "O compilador do .NET salva o código de IL em um arquivo chamado assembly do .NET"
- "O runtime do .NET é um ambiente de execução para o seu assembly do .NET compilado."
- Além disso pode "usar o compilador do C# que está instalado com o SDK do .NET para criar um assembly com seu código C#."
- o SDK do .NET já traz um conjunto de bibliotecas, mas bibliotecas de terceiros podem ser instaladas com gerenciadores de pacotes como o NuGet.
-  tabela com modelo de aplicativos e estruturas do .NET utilizadas https://docs.microsoft.com/pt-br/learn/modules/dotnet-introduction/2-what-is-dotnet#what-are-the-major-app-models

<div class="table-scroll-wrapper has-inner-focus" tabindex="0" role="group" aria-label="Dados roláveis horizontalmente"><table class="table"><caption class="visually-hidden">Principais modelos de aplicativos?</caption>
<thead>
<tr>
<th>Modelo de aplicativo</th>
<th>Estrutura</th>
<th>Observações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Web</td>
<td>ASP.NET Core</td>
<td>A estrutura para a criação da lógica do lado do servidor.</td>
</tr>
<tr>
<td>Web</td>
<td>ASP.NET Core MVC</td>
<td>A estrutura para a criação da lógica do lado do servidor para páginas da Web ou APIs Web.</td>
</tr>
<tr>
<td>Web</td>
<td>Razor Pages do ASP.NET Core</td>
<td>A estrutura para a criação de HTML gerado pelo servidor.</td>
</tr>
<tr>
<td>Cliente Web</td>
<td>Blazor</td>
<td>O Blazor é uma parte do ASP.NET Core. Os dois modos dele permitem a manipulação de DOM (Modelo de Objeto do Documento) por meio de soquetes como um veículo de comunicação para a execução de código do lado do servidor ou como uma implementação do WebAssembly para a execução do C# compilado no navegador.</td>
</tr>
<tr>
<td>Desktop</td>
<td>WinForms</td>
<td>Uma estrutura para criar aplicativos no estilo "acinzentado" do Windows.</td>
</tr>
<tr>
<td>Desktop</td>
<td>Windows Presentation Foundation (WPF)</td>
<td>Uma estrutura para criar aplicativos da área de trabalho dinâmicos em conformidade com diferentes fatores forma. O WPF permite que os elementos da forma realizem movimentos, esmaecimentos, deslizamentos e outros efeitos com a ajuda de uma biblioteca de animações avançada.</td>
</tr>
<tr>
<td>Móvel</td>
<td>Xamarin</td>
<td>Permite que os desenvolvedores do .NET criem aplicativos para dispositivos iOS e Android.</td>
</tr>
</tbody>
</table></div>

**Modelos de aplicativos**
 O modelo de aplicativo escolhido pode ser um aplicativo Web, de área de trabalho ou móvel ou um processo em segundo plano, por exemplo.

**Pacotes externos/dependências**

- Instalar pacotes pela CLI do .NET Core com o comando `dotnet add package <name of package>`.
- pacotes instalados são listados na seção dependencies do arquivo ``.csproj``.
- Limpar/remover dependências `dotnet remove package <name of dependency>`.
- [Criar um projeto .NET de exemplo](https://docs.microsoft.com/pt-br/learn/modules/dotnet-dependencies/3-exercise-dependency#create-a-sample-net-project)
- 

