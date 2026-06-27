<H1>Tesi di Laurea Triennale</H1>
In questo repository è possibile visionare il progetto svolto nell'ambito del lavoro di Tesi per il corso di Laurea Triennale in Informatica presso l'Università degli studi di Napoli Federico II. L'applicativo è stato progettato e implementato nell'ambito del Tirocinio Curricolare svolto presso Alten Italia S.p.A., multinazionale che opera nell'ambito della consulenza ICT.

<br><br>
<h1>Descrizione Progetto</h1>
Tool di supporto alla programmazione di Liquibase per la gestione delle evoluzioni su DB relazionale in ambito di applicativi Java-like.
Il tool è basato su tecnologie java web. Il suo obiettivo è generare script Liquibase XML per operazioni sul DB da lanciare in fase di deployment su Jenkins per tenere aggiornato anche il DB oltre al codice, quando si rilascia una nuova versione di un’applicazione.
Liquibase è una libreria open source indipendente dal database per tracciare, gestire e applicare le modifiche allo schema del database.
<br><br>
Ogni script XML dovrà contenere:
<ul>
	<li>Una Restrinction del caso in cui deve entrare in funzione la INSERT e l’UPDATE;</li>
	<li>la query, INSERT, UPDATE o quant’altro per aggiornare i dati su DB;</li>
	<li>la rollback in cui far tornare allo stato di prima la tabella o il DB in generale.</li>
</ul>
Tramite un’infrastruttura web di menù è possibile scegliere l'operazioni da fare, ovvero tipo di script da generare. Quindi, tale menù consentirà di stabilire il tipo di script da generare (creazione di tabelle, aggiornamento di struttura di tabelle, inserimento di dati su DB in base a determinate restrizioni etc.).
<br><br>
Una serie di maschere consentirà, dopo un’analisi di tabelle a DB di generare gli script Liquibase per l’aggiornamento degli ambienti di sviluppo, collaudo e produzione.
<br><br>
L’architettura si basa sul pattern MVC, si struttura quindi in:
<ul>
	<li>Controller;</li>
	<li>Service: dove risiede la business logic e i DTO;</li>
	<li>Stato di persistenza.</li>
</ul>
Gli script generati sarano disponibili anche nella view in una text box. A tale scopo si fa uso di codice javascript ajax che farà comparire in modo asincrono il risultato (lo script da poter essere copiato ed incollato) nella pagina web. In oltre, è possibile effettuare il download di un file XML contenente lo script.
<br><br>
I dbms supportati al momento son MySql e Oracle.
<br><br>
Le tecnologie utilizzate sono:
<ul>
	<li>Java 8;</li>
	<li>Spring Framework;</li>
	<li>Hibernate (tecnologia di persistenza);</li>
	<li>Javascript e AJAX;</li>
	<li>XML;</li>
	<li>HTML;</li>
	<li>CSS e Bootstrap Framework;</li>
	<li>MySQL / Oracle;</li>
	<li>Tomcat;</li>
	<li>Liquibase.</li>
</ul>

Il testing è stato effettuato con jUnit e Mockito, seguendo la metodologia SECT per il testing Black Box e Branch Coverage per il testing White Box.

# Scarica e Leggi la Tesi 
Il progetto in questione è stato svolto nell'ambito di un tirocinio presso Alten Italia S.p.A. in collaborazione con l'Università degli studi di Napoli Federico II.
<br><br>

Il tirocinio e il Progetto erano parte integrante del lavoro di stesura di Tesi  necessaria per conseguire il titolo accademico. Per tanto, in allegato è possibile accedere e visualizzare la Tesi di Laurea Triennale di cui questo progetto fa parte.

 
<br><br>
<h3><i>Puoi leggere qui la <a href="https://drive.google.com/file/d/1q-7YKrnldXI-SRMjaBw5asE6Wo-0DHRC/view?usp=sharing">Tesi di Laurea</a></i></h3>
