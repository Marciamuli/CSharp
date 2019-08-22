# Csharp

Todos os materiais desenvolvidos para o Curso de **Desenvolvimento de Sistemas** vão aqui.

![Lógica](https://img.shields.io/badge/VisualStudio%20-2015-green)
![CSharp](https://img.shields.io/badge/C-%23-blue)
![Nível](https://img.shields.io/badge/N%C3%ADvel-B%C3%A1sico-green)

## Introdução

![image](https://i.udemycdn.com/course/750x422/1581488_e3e1_2.jpg)

CSharp
Todos os materiais desenvolvidos para o **Curso de Desenvolvimento de Sistemas** vão aqui.

VisualStudio_2015 CSharp Nível

Introdução
image

**C# (CSharp)** é uma linguagem de programação orientada a objetos criada pela Microsoft, faz parte da sua plataforma.Net. 
A companhia baseou **C#** na linguagem **C++ e Java**.

O **C#** (pronuncia-se "C Sharp") é uma linguagem de programação simples, moderna, orientada a objeto e fortemente tipada. 
O **C#** tem suas raízes na família de linguagens C e os programadores em **C**, **C++**, **Java e JavaScript** a reconhecerão imediatamente. Este tour dá uma visão geral dos principais componentes da linguagem. Se quiser explorar a linguagem por meio 
de exemplos interativos, experimente nossos tutoriais de Introdução à linguagem **C#**.

O **C#** é uma linguagem orientada a objeto, mas inclui ainda suporte para programação orientada a componentes. O design de 
software atual depende cada vez mais dos componentes de software na forma de pacotes independentes e autodescritivos de 
funcionalidade. O principal é que esses componentes apresentam um modelo de programação com propriedades, métodos e 
eventos; eles têm atributos que fornecem informações declarativas sobre o componente; e incorporam sua própria documentação.
**C#** fornece construções de linguagem para dar suporte diretamente a esses conceitos, tornando **C#** uma linguagem muito 
natural para criação e uso de componentes de software.

Vários recursos de **C#** auxiliam na construção de aplicativos robustos e duráveis: Coleta de lixo recupera automaticamente a 
memória ocupada por objetos inacessíveis não utilizados. Tratamento de exceção fornece uma abordagem estruturada e extensível
para detecção e recuperação de erros. E o design fortemente tipado da linguagem impossibilita a leitura das variáveis não 
inicializadas, a indexação de matrizes além dos seus limites ou a execução de conversões de tipo não verificadas.

**C#** tem um sistema de tipo unificado. Todos os tipos do **C#**, incluindo tipos primitivos, como int e double, herdam de um 
único tipo de object raiz. Assim, todos os tipos compartilham um conjunto de operações comuns, e valores de qualquer tipo 
podem ser armazenados, transportados e operados de maneira consistente. Além disso, **C#** oferece suporte a tipos de referência 
e tipos de valor definidos pelo usuário, permitindo a alocação dinâmica de objetos, bem como o armazenamento em linha de 
estruturas leves.

Para garantir que os programas e bibliotecas escritos em **C#** possam evoluir ao longo do tempo de uma maneira compatível, 
enfatizou-se muito o controle de versão no design do **C#**. Muitas linguagens de programação prestam pouca atenção a esse 
problema e, como resultado, programas escritos nessas linguagens quebram com mais frequência do que o necessário quando 
versões mais recentes das bibliotecas dependentes são introduzidas. Aspectos do design do **C#** que foram diretamente 
influenciados pelas considerações de controle de versão incluem os modificadores separados virtual e override, as regras 
de resolução de sobrecarga de método e suporte para declarações explícitas de membro de interface.

**HELLO WORLD C#**

```

using System;
class Hello
{
    static void Main()
    {
        Console.WriteLine("Hello, World");
    }
}


```

O programa **"Hello, World"** começa com uma diretiva using que faz referência ao namespace System. Namespaces fornecem um 
meio hierárquico de organizar bibliotecas e programas em **C#**. Os namespaces contêm tipos e outros namespaces — por 
exemplo, o namespace System contém uma quantidade de tipos, como a classe Console referenciada no programa e diversos 
outros namespaces, como IO e Collections. A diretiva using que faz referência a um determinado namespace permite o uso 
não qualificado dos tipos que são membros desse namespace. Devido à diretiva using, o programa pode usar Console. WriteLine
como um atalho para System.Console.WriteLine.

A classe Hello declarada pelo programa "Hello, World" tem um único membro, o método chamado **Main**. O método **Main** é declarado 
com o modificador estático. Embora os métodos de instância possam fazer referência a uma determinada instância de objeto 
delimitador usando a palavra-chave **this**, métodos estáticos operam sem referência a um objeto específico. Por convenção, um 
método estático denominado **Main** serve como ponto de entrada de um programa.

A saída do programa é produzida pelo método **WriteLine** da classe **Console no namespace System**. Essa classe é fornecida pelas 
bibliotecas de classe padrão, que, por padrão, são referenciadas automaticamente pelo compilador.



## **Classe Console**

A classe Console, do **namespace System**, fornece suporte básico para leitura e escrita de caracteres. Os principais métodos
usados para essas funcionalidades são:

```

Write: escreve uma informação específica em tela.
WriteLine: escreve uma informação específica em tela e pula uma linha em seguida.
ReadLine: captura uma linha de texto digitada pelo usuário e retorna seu valor na forma de string.
ReadKey: captura um único caractere digitado pelo usuário. O retorno desse método é um objeto da classe 
         ConsoleKeyInfo, que contém informações sobre a tecla digitada pelo usuário.
Clear: esse método limpa toda a tela do console. Útil para programas que exigem formatação dos resultados. 

```
