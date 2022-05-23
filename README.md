# Night Shift

A peaceful night at the museum is interrupted when a stray dog (clearly not an appreciator of the arts) starts destroying everything he sees!
As the security guard for the night, it's your job to keep everything in its place.

## Screenshots:

![ns_splash](https://user-images.githubusercontent.com/68665056/169908922-ee4b4373-0f14-43ea-942c-d2166d405a89.png)

![night shift gameplay_Moment](https://user-images.githubusercontent.com/68665056/169912035-6b0ed8cc-5ec0-4f4c-947f-acdee4eeb510.jpg)

![night shift gameplay_Moment2](https://user-images.githubusercontent.com/68665056/169912053-abdeeb43-e138-4d60-b737-0483ab5d6b0a.jpg)

---

## SPRINT 1 (25/02)

1. Cachorro seleciona objeto para interagir
	1. [X] Objetos: Plano, cubos para interação e placeholder para o cachorro
	2. [ ] Cada cubo é um ponto de interesse.
	3. [ ] Escolha aleatória entre pontos de interesse
2. Cachorro se move pelo mapa (https://www.youtube.com/watch?v=atCOd4o7tG4)
	1. [ ] Pathfinding até ponto de interesse (!! Parte mais importante)
	2. [ ] Precisamos que o cachorro OU encoste no objeto OU esteja a uma distância que queremos
3. Cachorro interage com objeto
	1. [ ] A partir do ponto 2 do último tópico, precisamos setar uma propriedade no cubo
	   (false->true ou vice-versa) e setar um timer (temporário) para que essa propriedade volte ao estado
	   original.
	2. [ ] Voltamos ao primeiro ponto da Sprint, e temos um loop infinito.
