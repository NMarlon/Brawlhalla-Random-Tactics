# Brawlhalla Random Acts
 Um mostrador de movimentos e táticas aletoriamente do Brawlhalla (ou outros jogos)
 
 Esse programa foi feito para facilitar meu desenvolvimento com o jogo Brawlhalla, eu estava muito previsível nos movimentos, então pra quebrar meu hábito de sempre fazer as mesmas coisas, eu comecei o Random Tatics do Brawlhalla em Python. Assim eu interrompo o movimento que estou fazendo pra tentar encontrar uma forma de encaixar o movimento novo durante a luta e assim me tornar menos previsível pelo oponente.
 
(**VEJA O PROGRAMA FUNCIONANDO AQUI nesse link: https://replit.com/@MarlonRViana/Brawlhallarandomtatics?v=1 .**)

# INSTRUÇÕES

1. Baixe e Instale o Python em: https://www.python.org/downloads/
2. Abra o arquivo: brawlhalla_random.py desse Git  
PRONTO!

Você também pode editar as variáveis:

- *num_caracteres_max* = inteiro #Ajusta o número de caracteres à mostrar por palavra 
- **ataques,combinadores,tecnica** = array de strings #Listas com os ataques, suas combinações e táticas. *Fique à vontade* para acrescentar ou deletar componentes de qualquer um dessas listas
  - Z, X e C são teclas do teclado, você pode substituí-las pelos oficiais Sig (Signature / Heavy attack), Light (Light attack), Rec (Recovery). 
    -  Veja no Reddit sobre os nomes oficiais: https://www.reddit.com/r/Brawlhalla/comments/a82bdz/what_do_nsig_etc_mean/
  -  -> (), V (seta baixo), J (Jump/Pulo), " " (neutro)  são combinadores, você pode substituí-los no início do arquivo brawlhalla_random.py pelos oficiais: N (Neutral), S (Side), D (Down).
  -  Tecnica são apenas táticas individuais que EU uso, 
    - Atk (atacar): focar em ataque
    - Def (Defensiva): tomar a defensiva, evitar levar dano
    - Trp (Trap): Ficar parado e esperar ou esquivar o ataque do oponente para só então contra-atacá-lo

- show = array de booleano  #Oculta alguma das listas
- mostrar_divisor = boleano #Oculta a linha divisora
- contador_max = inteiro #O número componentes por linha
- tempo_por_linha = inteiro #O tempo entre cada linha

- pular_linhas_num = inteiro  #Quantas linhas vai pular (opcional)
- pular_linhas_escritas = inteiro #Quantas vão ser escritas (somente se pular linhas)




Veja também informações no meu blog: https://marlonrviana.blogspot.com/2021/05/brawlhalla-game-programa-para-treino.html

# BUGS
1. Se houver quebra de linha não intencional como: 

![image](https://user-images.githubusercontent.com/43282318/119597386-4b9a4b80-bdb7-11eb-99bb-4e37e7ce8094.png) 

diminua: contador_max=5 para algo menor 

# FALE CONOSCO
 Você entrar em contato comigo no e-mail:
 marlonrviana@gmail.com
 pelos comentários desse Git.

