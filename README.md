# Sala di Cesena

<div>   
<button type="button" class="collapsible active">+ Orario lezioni</button>
<div class="content" style="display: none;" markdown="1">

- Martedì: ore 20.30 - 23.00
- Giovedì: ore 20.45 - 23.00
</div>
</div>

<div>   
<button type="button" class="collapsible active">+ Informazioni di pagamento</button>
<div class="content" style="display: none;" markdown="1">

![](/assets/img/costi.jpg)
- 55 € di iscrizione, valida per tutto l'anno
- 40 € mensili, 35 € nel caso in cui saldiate almeno 3 mesi con lo stesso pagamento

Per quanto riguarda le modalità di pagamento, il bonifico rimane la modalità preferita, ma in caso vi venga più comodo si accettano anche contanti (da pagare a Ruben Tura).

IBAN: IT09X0306967684510749162049

Intestatario: ASD Romagna Malatestiana

Causale: Nome Cognome Sala + Cosa si paga (ad esempio Mario Rossi Cesena Ott-Dic)

**Ricordatevi di inviare la ricevuta del bonifico all'indirizzo mail [asd-romagnamalatestiana@achillemarozzo.it](mailto:asd-romagnamalatestiana@achillemarozzo.it)**
</div>
</div>

<div>   
<button type="button" class="collapsible active">+ Prossimi eventi</button>
<div class="content" style="display: none;" markdown="1">

- Sabato 22 Ottobre 2022: **Sparring Day dai nostri amici di Hema Ravenna!** Informazioni sull'[evento facebook](https://fb.me/e/1Vk5zS6bi).
- Domenica 23 Ottobre 2022: **Mensile di Due Mani di Marozzo ad Imola!** Esercizi la mattina, a cura di Andrea Reggi, e sparring al pomeriggio.
- **Qualifiche Nord / Sud**: coming soon...
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
