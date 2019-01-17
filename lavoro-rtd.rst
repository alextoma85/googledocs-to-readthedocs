
.. _h7d4d73362b291793a962411315d6b:

Il lavoro da fare su Read the Docs
##################################

Questa rappresenta la fase finale del lavoro ed è molto semplice come operazioni da effettuare. Una volta completato il lavoro di compilazione su Github, bisogna andare su \ |LINK1|\  e (dopo aver creato il relativo account) importare il progetto, già creato, da Github.

Nella finestra, su “URL del Deposito Codice”, bisogna scrivere l’URL del progetto che avete creato su Github, e quindi scegliere il nome del progetto, ad esempio:

“\ |STYLE0|\ ”

e lasciare “Tipo del Deposito Codice” selezionato su “Git”.

A quel punto verrà messo in collegamento il vostro progetto di \ |STYLE1|\  con il progetto su \ |STYLE2|\ . 

Una primissima azione da compiere è andare su “Amministrazione” e settare la lingua italiana. Questo consentirà a Read the Docs di aggiungere al titolo del vostro progetto la desinenza ``/it/latest``. Il documento è in italiano quindi prende la desinenza ``/it``. Questa impostazione permetterà alle note colorate che avete creato su Google doc di avere un titolo italiano (“Nota” al posto di “Note”, “Avvertimento” al posto di “Warning”, “Attenzione” al posto di “Attention” ecc.).

Esempio: come-creare-guida.readthedocs.io/it/latest

A questo punto il progetto di Github è compilato su Read the Docs.

Considerato che avevamo scelto come titolo del nostro progetto su Read the Docs: “\ |STYLE3|\ ”, l”URL compilato da Read the Docs per vedere il nostro progetto sarà: 

| ``linee-guida-open-data-comune-vattelapesca.readthedocs.io``

.. _h684482d484317635c64347543807d51:

Messaggi di ‘passing’ e ‘failing’ sul pannello di controllo di Read the Docs
****************************************************************************


.. admonition:: Avviso di passing

    \ |STYLE4|\ 
    
    Se non ci sono errori commessi durante le procedure spiegate fino ad ora, tutto andrà a buon fine, e Read the Docs darà il messaggio in colore verde di «\ |STYLE5|\ » al nostro progetto, significa che il nostro progetto è - quindi - online. La compilazione (build) su Read the Docs avviene con successo e ogni modifica che effettuiamo sul file del Google doc, viene commissionato a Github e compilato in tempo reale su Read the Docs, apparendo immediatamente sulle pagine HTML. La “build” su Read the Docs viene eseguita correttamente.


.. admonition:: Avviso di failing

    \ |STYLE6|\ 
    
    Se sono stati commessi errori nella procedura finora illustrata, Read the Docs alla sezione “i miei progetti”, darà un messaggio in colore rosso di «\ |STYLE7|\ ». In questo caso c’è qualche problema da qualche parte e bisogna ripercorrere tutti i passaggi fatti da quando si è iniziato a lavorare a partire dai file su Google doc fino a quanto eseguito sul sito di Read the Docs. 
    La compilazione su Read the Docs ha incontrato qualche problema, e quando si presenta questo caso la prima cosa da fare è andare nel file ``conf.py`` - dentro il repository del progetto su Github - e verificare le istruzioni date dentro questo file. Generalmente se si presenta un problema nella compilazione di Read the Docs, il problema sta dentro questo file. Una volta individuato e risolto il problema, Read the Docs comincerà automaticamente a compilare le istruzione del file ``conf.py`` di Github e dara il bollino verde di «passed» (cioè la compilazione è effettuata con successo).

Abbiamo completato tutte le procedure e ci possiamo godere il nostro documento nella nuova modalità di pubblicazione e visualizzazione con lo stile Read the Docs o con il design Docs Italia.

[Questa pagina è \ |LINK2|\  del tutorial “\ |LINK3|\ ” (a cura di Pablo Persico, Andrea Borruso e Ciro Spataro) ed ulteriormente arricchita].

|

.. _h31771703d4c464c26683c015a1:

Web Analytics
*************

E’ possibile agganciare strumenti di web analytics ai progetti online di read the docs. Se si usa, ad esempio Google Analytics, una volta creato il progetto specifico su \ |LINK4|\ , si ottenuto il codice. Il codice va inserito nel progetto specifico nel pannello di Amministrazione di read the docs, seguendo questo percorso:

Amministrazione / Impostazioni avanzate, e andando in fondo alla pagina fino alla voce ``Codice Analytics``, quindi cliccare il testo ‘salva’.

--------

  


|REPLACE1|


.. bottom of content


.. |STYLE0| replace:: **linee guida open data comune vattelapesca**

.. |STYLE1| replace:: **Github**

.. |STYLE2| replace:: **Red the Docs**

.. |STYLE3| replace:: **linee guida open data comune vattelapesca**

.. |STYLE4| replace:: **Procedura andata a buon fine: «passing»**

.. |STYLE5| replace:: **passing**

.. |STYLE6| replace:: **Procedura con Errore: «failing»**

.. |STYLE7| replace:: **failed**


.. |REPLACE1| raw:: html

    <script id="dsq-count-scr" src="//guida-readthedocs.disqus.com/count.js" async></script>
    
    <div id="disqus_thread"></div>
    <script>
    
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
    /*
    
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://guida-readthedocs.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

.. |LINK1| raw:: html

    <a href="http://readthedocs.io/" target="_blank">http://readthedocs.io</a>

.. |LINK2| raw:: html

    <a href="http://come-creare-guida.readthedocs.io/it/latest/_docs/capitolo2.html" target="_blank">ripresa da quella</a>

.. |LINK3| raw:: html

    <a href="http://come-creare-guida.readthedocs.io/it/latest/index.html" target="_blank">Tutorial pubblicazione Read the Docs su DocsItalia</a>

.. |LINK4| raw:: html

    <a href="https://analytics.google.com/analytics/web" target="_blank">Google Analytics</a>

