Como funciona: O programa terminal feito em kotlin

Estudo de caso escolhido: **Caça ao Tesouro Pirata**.

O tesouro fica escondido em uma posição aleatória de um mapa de 0 a 20 (X e Y). O jogador comanda um navio, digita coordenadas para navegar e tenta chegar a até 1 milha do tesouro antes que as provisões ou a tripulação acabem.

- Matemática: a distância até o destino e até o tesouro é calculada com o Teorema de Pitágoras.
- Operadores relacionais: o clima do dia (mar calmo, vento forte ou tempestade) é definido comparando a força do vento e muda o custo da viagem.
- Null safety: partes do mapa estão rasgadas (null) e entradas vazias ou inválidas são tratadas com `?.`, `?:` e `toIntOrNull()`.
- Menu em laço `while`: 1 navegar, 2 ler o mapa, 3 desistir.
