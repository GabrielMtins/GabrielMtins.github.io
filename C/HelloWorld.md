# Hello World
Nesse primeiro tutorial, estaremos discutindo um programa que todo programador novato faz ao conhecer uma linguagem  
<pre> <code>
#include &lt;stdio.h&gt;  
  
int main(){  
    printf("Hello World");  
}  
</code> </pre>
Vamos analisar o código linha a linha e ver o que ele significa  

<pre> <code> #include &lt;stdio.h&gt;  </code> </pre>

Nessa linha, estaremos "incluindo" uma biblioteca (que é o que está entre os < e >. Essa biblioteca significa "Standard Input and Output", ou seja, será a nossa principal maneira de se comunicar com o usuário que está usando nosso programa  

<pre> <code> int main(){  </code> </pre>

Como podemos ver, iniciamos algo chamado "main", que significa principal. É no "main" que todo nosso programa será rodado, por isso, é a parte principal do programa. Abrimos os conchetes e tudo que escrevermos dentro desses conchetes será executado ao compilar nosso programa.

<pre> <code> printf("Hello World"); </code> </pre>
Aqui iremos printar algo no console, que será o nosso output (que foi incluido com a biblioteca stdio.h), e nossa principal maneira de se comunicar com nossos usuários.  
Digitamos printf e logo abrimos parênteses, para indicar o que nós queremos imprimir. Como vamos imprimir um texto, abra as aspas ("") e digite o texto que deseja dentro das aspas (Nesse caso, "hello world").  
Além disso, percebemos que devemos deixar um ponto em vírgula no final de uma linha em C.  

<pre> <code> }  </code> </pre>

Essa chave final será utilizada para representar que nosso main acaba aqui.  
Feito isso, basta compilar. Abra o terminal e digite o seguinte comando:

<pre> <code> gcc main.c -o main </code> </pre>
(Em sistemas MacOS ou Linux)  
<pre> <code> gcc main.c -o main.exe </code> </pre>
(Em sistemas Windows)  

Esse comando irá compilar nosso programa. Para rodar ele basta digitar:

<pre> <code> ./main  </code> </pre>
(Em sistemas linux ou MacOS)
<pre> <code> main.exe  </code> </pre>
(No Windows)  
Assim você receberá uma mensagem de "Olá Mundo" no console!!
