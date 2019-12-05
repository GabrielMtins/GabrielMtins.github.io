# Variáveis

A variável é um local na memória ram em que podemos armazenar dados, como números e caracteres.  
Há vários tipos de variáveis em C:  
int - variável que armazena números inteiros  
float - varíável que armazena números decimais  
double - variável que armazena números decimais  
char - variável que armazena um caractere  
Para criar variáveis é bem simples:
Em nosso código digitamos:
<code> TipoDeVariavel nomeDaVariavel </code>
Exemplos:  
<pre> <code> 
int x;
double mono;
char c1;
</pre> </code>
Vale a pena lembrar que há algumas restrições para nomeações de variáveis:  
1. Nomes de variáveis não podem conter letras, números e underline (_)
2. Nomes de variáveis não podem começar com números
3. Elas não podem ter nome com palavras especiais usadas em C (como main, int, etc)  

## Trabalhando com variáveis

Podemos atribuir diversos valores a variáveis, e usamos isso atráves do operador "=". Exemplos:
<pre> <code> 
int x;  
x = 2;  
int y = 3;  
</pre> </code>
Como podemos ver, criamos uma variável x, e demos um valor a ela depois, dizendo que ela é igual a 2. 
Também podemos declarar valores a variáveis logo quando elas são declaradas, como pode ser visto na 
última linha do código
