# Instruccions

> **Important**: LLegeix detingudament aquestes instruccions **abans** de començar.

Tens accés a aquest document perquè t'has clonat el repositori git on s'hi troba.


### Desenvolupament en LOCAL

> Heu de fer tota l'activitat en **LOCAL**, és a dir, en el vostre entorn de desenvolupament. **NO modifiqueu cap fitxer directament a github**, a menys que de forma explícita i clara així s'indiqui a l'exercici.

Com a norma general, **un cop acabada la feina en local i fets els commits, sincronitzareu el repo local amb el repo remot de github fent _git push_**.


### Directori de treball

Has de crear-te el directori següent, que anomenarem **directori de treball**, dins del qual faràs tots els exercicis **excepte els de Visual Studio Code**:

```~/DAW/M051/uf1```

Els exercicis de Visual Studio Code es faran al directori ```~/workspaces```.

**Compte!!**: NO has de fer els exercicis dins del directori d'inici. El directori d'inici s'explica a continuació.


### Directori d'inici

Dins del directori de treball hauràs d'haver-te **clonat** el repositori git on es troba aquest enunciat, de manera que se't crearà un nou directori, que anomenarem **directori d'inici**:

```~/DAW/M051/uf1/aa-m5-uf1-username```

On _username_ és el vostre nom d'usuari de github.

**Atenció**: Ves amb compte ja que els següents exercicis els hauràs de fer **fora** d'aquest repositori, en el **repositori de treball**. 


### Nom i Cognoms de l'alumne

> Sempre que s'indiqui ```Nom Cognoms``` s'haurà de substituir pel nom i cognom/s de l'alumne/a.

Sempre s'haurà d'incloure Nom i Cognoms (almenys el primer cognom) com a mínim **a tots els commits**.


### Branca main

> Cada vegada que inicialitzis un nou repositori git, i **un cop fet el primer commit**, hauràs de reanomenar la branca per defecte _master_ per _main_ amb la següent comanda git (des de la branca _master_):

```bash
git branch -M main
```

**Nota**: Aquesta comanda no et funcionarà si no has fet com a mínim 1 commit abans.


### Edició de documents markdown

Per a crear i editar els documents **markdown** dels exercicis, ets lliure de fer servir l'editor que vulguis, per exemple el _nano_ o el _vi_ en el terminal. Així i tot:

> Per a editar documents _markdown_ es recomana usar **Jupyter Lab**, ja que disposa d'un editor gràfic de fitxers markdown (el trobareu a baix, a _Other > Markdown File_), i a més, us ofereix un previsualitzador (per a poder veure com queda a mesura que aneu fent modificacions).

Per a accedir al previsualitzador markdown, heu de clicar damunt del fitxer (a l'explorador de fitxers) amb el botó secundari del ratolí, i seleccionar _Open With > Markdown Preview_.

### Lliurament

Al final de cada nivell tens les instruccions per a **preparar** aquell nivell per al lliurament que faràs al final. És a dir:

- Al final de cada nivell hauràs de seguir les instruccions indicades al final de l'enunciat del nivell (preparació del nivell per al lliurament).

- Quan hagis preparat tots els nivells que vulguis lliurar, **i no abans**, hauràs de fer el lliurament de la següent manera:

1. Entra al directori d'inici.
2. Fes un git commit (fent git add primer si cal) amb el missatge següent:

**"Nom Cognom: activitat acabada"**

3. Fes un git push. 

Per fer un _git push_ necessites tenir definit el _remote_:

Tingues en compte que, en el directori d'inici, ja tens els _remotes_ definits, no cal que els defineixis tu. Això és així perquè el directori d'inici no és un repositori git que hagis inicialitzat tu amb ```git init``` sinó que és un repositori git que tu t'has clonat. **Els repositoris git clonats ja tenen els _remotes_ definits**.