# Manuale d'Uso

<div>   
<button type="button" class="collapsible active">+ Creazione account</button>
<div class="content" style="display: none;" markdown="1">

- Registrarsi a [GitHub](https://github.com)
- Mandare una mail a [rubentura@proton.me](mailto:rubentura@proton.me) indicando il nome utente, e richiedendo accesso alla pagina relativa alla propria sala (nel caso in cui la pagina non esista ancora, provvederò io alla sua creazione)
- Attendere la conferma, per poi accedere a [GitHub](https://github.com), controllare le notifiche nell'apposito bottone in alto a destra, ed accettare l'invito a collaborare
<div>   
<button type="button" class="collapsible active">+ Screenshots</button>
<div class="content" style="display: none;" markdown="1">

![](/assets/img/gif1.png)
![](/assets/img/gif2.png)
![](/assets/img/gif3.png)
</div>
</div>
</div>
</div>

<div>   
<button type="button" class="collapsible active">+ Modifica pagina</button>
<div class="content" style="display: none;" markdown="1">

Una volta aggiungi come collaboratori alla pagina di sala, potete finalmente modificare ed aggiungere informazioni a vostro piacimento.

1. Aprire la pagina https://github.com/infosaam/nome-sala
2. Cliccare sull'icona di modifica a destra di `README.md`
![](/assets/img/edit.png)
3. Modificare a piacimento (NB: C'è una sezione, alla fine del file, racchiusa fra le parole `script`. Non va assolutamente modificata, e va lasciata alla fine. Inserite tutto ciò che volete **prima** di tale sezione.)
4. Salvare cliccando sul bottone verde **Commit changes** in fondo alla pagina
![](/assets/img/commit.png)
</div>
</div>

<div>   
<button type="button" class="collapsible active">+ Informazioni utili</button>
<div class="content" style="display: none;" markdown="1">

Queste pagine sfruttano una sintassi relativamente comprensibile, in modo da permettere anche ad utenti non necessariamente esperti di potersi gestire in autonomia la propria pagina. Ecco alcune informazioni utili:

Innanzitutto, per rendere la pagina più facilmente navigabile, ogni sezione è espandibile con un semplice click. Come si inserisce una nuova sezione? Semplice! 
Il template è questo:

```html
<div>   
<button type="button" class="collapsible active">+ TITOLO SEZIONE</button>
<div class="content" style="display: none;" markdown="1">

ROBE ROBE INFORMAZIONI GHISA
</div>
</div>
```
Potete tranquillamente ignorare tutte le scritte che non capite, e sostituire il titolo della sezione, e il contenuto stesso.

Per quanto riguarda la formattazione:
- Elenchi puntati: basta iniziare la riga con il trattino (-), e lasciare uno spazio
- Elenchi numerati: basta iniziare la riga con il numero seguito da un punto (1.), e lasciare uno spazio
- Grassetto: inserire la parola fra doppi asterischi (`**PAROLONA**`)
- Link: inserire la scritta che va mostrata a schermo fra parentesi quadre, e il link da seguire fra parentesi tonde, senza spazi fra i blocchi de parentesi (`[testo](https://www.ghisa.com)`)
</div>
</div>

<div>   
<button type="button" class="collapsible active">+ Video tutorial</button>
<div class="content" style="display: none;" markdown="1">

## Tutorial generico
{% include youtube.html id="6OrE5Q6-oXw" %}

## Tutorial immagini
{% include youtube.html id="8iBo5ZGpm14" %}
</div>
</div>

<script type="text/javascript">

    function loadCSS(filename){ 

       var file = document.createElement("link");
       file.setAttribute("rel", "stylesheet");
       file.setAttribute("type", "text/css");
       file.setAttribute("href", filename);
       document.head.appendChild(file);
    }

    //just call a function to load your CSS
    //this path should be relative your HTML location
    loadCSS("collapse.css");

    var coll = document.getElementsByClassName("collapsible");
    var i;

    for (i = 0; i < coll.length; i++) {
      coll[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var content = this.nextElementSibling;
        if (content.style.display === "block") {
          content.style.display = "none";
        } else {
          content.style.display = "block";
        }
      });
    }

</script>
