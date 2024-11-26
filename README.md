# Elon Must Survive

**"Elon Must Survive"** és un joc d'acció i supervivència en què l'Elon Musk ha de travessar una carretera plena de cotxes Tesla descontrolats que, a causa d'una IA malvada, intenten atropellarlo. El jugador ha de controlar l'Elon per evitar els vehicles mentre intenta arribar a la fàbrica de Tesla per desactivar la IA.

## Funcionalitats:

### Personatge:
L'Elon Musk és el protagonista, qui es mou per la pantalla utilitzant les tecles de direcció (amunt, avall, esquerra i dreta). El seu objectiu és evitar els cotxes Tesla que circulen a través de diverses carreteres (carrils) i arribar a la part superior de la pantalla per començar un nou nivell. Quan el personatge arriba a la part superior, el joc canvia la pantalla per iniciar un nou nivell.

### Pantalles del joc:
El joc consta de diverses pantalles (nivells), cadascuna amb un fons fix i cotxes que es desplacen per diferents carrils:

1. **Pantalla Inicial (Background)**: Quan comença el joc, es carrega una pantalla inicial amb un fons de carretera. Els cotxes comencen a moure's horitzontalment i el jugador controla l'Elon per evitar-los.
  
2. **Nova Pantalla**: Quan el personatge arriba a la part superior de la pantalla (nivell completat), el fons es canvia a una nova pantalla, mantenint la mateixa mecànica de joc, però augmentant la dificultat. Els cotxes també es reinicien, amb noves velocitats i posicions aleatòries, mantenint l'ambient del joc dinàmic. Això indica que el jugador ha passat a un nou nivell.

3. **Pantalla de Victoria**: Quan el jugador arriba al nivell 15, el joc mostra una pantalla especial de victòria amb la imatge "victoria.jpeg" i un missatge que diu **"Has salvat a l'Elon"**. Aquesta pantalla marca el final del joc, i el jugador pot reiniciar per començar una nova partida.

4. **Pantalla de Game Over**: Si l'Elon Musk és atropellat per un cotxe Tesla, el joc canvia a una pantalla de "Game Over" on el jugador pot reiniciar la partida. En aquesta pantalla també apareix el missatge de "Game Over" i un botó per reiniciar.

### Cotxes Tesla:
Els cotxes Tesla es mouen horitzontalment a través de la pantalla. Els cotxes tenen velocitats aleatòries i es mouen per diferents carrils (100, 200, 300, 400). Quan un cotxe arriba al final de la pantalla, reapareix a l'altre extrem amb una nova posició aleatòria en un carril diferent.

### Puntuació:
La puntuació es basa en el nombre de carreteres superades pel personatge (el nombre de pantalles completades). Cada vegada que l'Elon Musk arriba a la part superior de la pantalla, guanya un punt i comença un nou nivell amb cotxes més ràpids i més difícils d'evitar. La puntuació es mostra a la part superior de la pantalla i s'actualitza constantment.

### Controles:
Els controls del joc permeten moure l'Elon Musk per la pantalla amb les tecles de direcció (fletxes o WASD). A més, l'usuari pot prémer la tecla **Espai** per activar habilitats especials (si estan disponibles). També hi ha una opció per pausar el joc mitjançant la tecla **Esc**.

- **Fletxa amunt/W**: Moure amunt.
- **Fletxa avall/S**: Moure avall.
- **Fletxa dreta/D**: Moure a la dreta.
- **Fletxa esquerra/A**: Moure a l'esquerra.
- **Espai**: Activar habilitats especials (si les tens disponibles).
- **Esc**: Pausar el joc.

## Pantalla de "Game Over" i "Victoria":
- **Pantalla de "Game Over"**: Quan el personatge és atropellat per un cotxe Tesla, es mostra una pantalla de "Game Over" amb la possibilitat de reiniciar el joc.
- **Pantalla de "Victoria"**: Quan el jugador arriba al nivell 15, es mostra una pantalla de victòria amb la imatge "victoria.jpeg" i el missatge **"Has salvat a l'Elon"**. Aquesta pantalla indica el final del joc, i el jugador pot començar una nova partida.

## Desenvolupament:

Aquest joc ha estat desenvolupat amb **Python** i **Pygame**. Assegura't que tens tots els fitxers necessaris a la carpeta `assets` perquè les imatges, fons i altres recursos es carreguin correctament.

## Requisits:

Per jugar a **Elon Must Survive**, necessitaràs tenir instal·lat Python i la llibreria Pygame. Asegura't que tens els fitxers d'imatge adequats a la carpeta `assets` perquè els fons i els cotxes es carreguin correctament.

### Com jugar:

1. Moure's amb les tecles de direcció:
   - **Fletxa amunt/W**: Moure amunt.
   - **Fletxa avall/S**: Moure avall.
   - **Fletxa dreta/D**: Moure a la dreta.
   - **Fletxa esquerra/A**: Moure a l'esquerra.

2. **Esc**: Pausar el joc.

## Desenvolupat per:

- **lluisp7** utilitzant Python i Pygame.
