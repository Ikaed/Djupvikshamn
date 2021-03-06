<!DOCTYPE html>
<html lang="sv">
   <head>
      <title>Startsida - Djupvikshamn</title>
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Style+Script&display=swap" rel="stylesheet">
      <link rel="stylesheet" href="css/normalize.css" />
      <link rel="stylesheet" href="css/main.css" />
      <script src="/js/main.js" type="module"></script>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=2" />
      <meta name="description" content="A webpage about the port of Djupvik in Gotland, Sweden">
      <link rel="icon" type="image/png" href="images/favicon-32x32.png" sizes="32x32" />
   </head>
   <body>
      <header>
         <!--Avsedd för att centrera logotypen och titeln för webbsidan vid mobil-->
         <div class="headerwrapper">
            <div id="logobrand">
               <picture>
                  <source media="(min-width: 1281px)" srcset="images/logo.svg"/>
                  <source media="(min-width: 769px)" srcset="images/logo_medium.svg"/>
                  <img src="images/logo_small.svg" alt="Bild på en GPS-pin och inuti hålet en krok">
               </picture>
               <h1>Djupviks hamn</h1>
            </div>
         </div>
      </header>
      <nav>
         <ul>
            <li><a href="#" id="activePage">Startsida</a></li>
            <li><a href="../html/guest.html">Gästplats</a></li>
            <li><a href="../html/history.html">Historia</a></li>
            <li><a href="../html/member.html">Medlemsplats</a></li>
            <li><a href="../html/tourist.html">Turistmål</a></li>
            <li><a href=#contactinfo>Kontakt</a></li>
            <li><a href="../html/english.html">English</a></li>
         </ul>
      </nav>
      <main>
         <section class="frontpagecards">
            <!--En varning dyker upp vid validering på denna och andra sidor om saknad heading men det är bara en rekommendation, så därför saknas det en heading här eftersom layouten blir felaktig annars-->
            <article class="information">
               <h2>Övergripande information om hamnen</h2>
               <p>
                  Djupviks hamn ligger på Gotlands västkust nästan rakt öster om Lilla Karlsö. Hamnen är otroligt vackert belägen i anslutning till ett gammalt Gotländskt fiskeläge bestående av fiskebodar från sent 1800-tal. Husen är grupperade i tre rader, mellan dem ligger gistgarden där man torkar nät och närmast stranden ligger båthusen. Från fiskeläget har man fri utsikt mot de båda Karlsöarna.
               </p>
               <p>Ansvaret för hamnen och fiskeläget har Djupviks hamnförening, som är en ideell förening som aktivt verkar för att bibehålla och utveckla Djupvik som fiskehamn och som fritidsbåtshamn för de många närboende och sommarboende.
               </p>
               <p>Föreningen driver en glasskiosk och kaffeservering på sommartid i ett gammalt båthus vid hamnen. Ett par hundra meter ovanför hamnen ligger Djupviks Hotell, ett hotell med restaurang och bra standard.
               </p>
               <p>Det finns även toaletter i hamnen varav en som är tillgänglighetsanpassad för rullstolar och rollatorer. 
               </p>
               <picture>
                  <source media="(min-width: 1281px)" srcset="/images/Djupvik.jpg"/>
                  <source media="(min-width: 769px)" srcset="/images/Djupvik_medium.jpg"/>
                  <!--För att få bilder responsiva så räcker det med att ta bort height och width från html-elementet img och sedan i stilmallen skriva in på img att max-width är 100%-->
                  <img src='/images/Djupvik_small.jpg' alt='En bild på Djupviks hamn'/>
               </picture>
            </article>
            <article>
               <h2>Senaste nytt: Hamnjobb</h2>
               <h3 class="date"><time>2019-04-06</time></h3>
               <p>Lördagen den 6 april samlades ett antal av föreningens medlemmar för arbete i hamnen. Kiosken, kajerna och stranden städades. Kajer lagades och gräs brändes. Diverse fix på många håll. Vädret var bra och korven god. Det som återstår inför säsongen är att ta bort släke från stranden, att sätta upp ramp vid kiosken och att fylla kiosken med varor.</p>
            </article>
            <article>
               <h2>Succé för hamnens dag! </h2>
               <h3><time>2018-07-16</time></h3>
               <figure>
                  <picture>
                     <source media="(min-width: 1281px)" srcset="images/HamnensDag.jpg"/>
                     <source media="(min-width: 769px)" srcset="images/HamnensDag_medium.jpg"/>
                     <!--Skulle det vara en enhet som är mindre än 769 pixlar eller om det är en webbläsare som inte stödjer <picture> och src så visas bilden nedan-->
                     <img src="images/HamnensDag_small.jpg" alt="En bild på en människosamling under Hamnens dag">
                  </picture>
                  <figcaption>Foto: Björn Hjernquist</figcaption>
               </figure>
               <p>Lördagen den 16 juli arrangerade föreningen Djupviks hamn i Eksta ”Hamnens dag” i Djupvik. Vårt arbete har med åren alltmer också inriktats på att alla besökare, även de som kommer landvägen skall trivas i det vackra hamnområdet. Nu bjöds det in till ”Hamnens dag”. På plats fanns sjöfartsverkets SAR-helikopter, Sjöräddningens båt Hwitstjärna, släckningsbil från räddningstjänsten i Klintehamn, russ från Gannarve och ett antal loppisförsäljare. Aktiviteten lockade ett stort antal besökare.
               </p>
               <p>Uppskattningsvis 1000 besökare sökte sig under dagen till Djupvik. Intresset var stort för de besökande organisationerna som informerade och alla fick möjlighet att titta och ställa frågor. Barnen fick rida, de bjöds på bulle och dricka och många prövade lyckan i fiskdammen. Det fanns möjlighet att handla kaffe, korv, dricka och glass. Många dröjde sig kvar i hamnområdet och trivdes i det inledningsvis lite blåsiga men vackra vädret.
               </p>
            </article>
         </section>
      </main>
      <footer>
         <div class="footerwrapper">
            <address>
               <p>Hamnfogde Bo Lautin
                  <br>
                  0707-920310
                  <br>
                  Djupviks hamnförening
                  <br>
                  c/o Ekholm
                  <br>
                  Eksta Hägur 170
                  <br>
                  623 54 Klintehamn 
               </p>
               <p id="copyright">© Copyright of Djupvikshamn.se 2021. Alla rättigheter förbehållna. <a href="mailto:info@djupvikshamn.se">info@djupvikshamn.se</a></p>
            </address>
            <div id="quicklinks">
               <h2>Snabblänkar</h2>
               <ul>
                  <li><a href="../html/guest.html">Gästplats</a></li>
                  <li><a href="../html/history.html">Historia</a></li>
                  <li><a href="../html/member.html">Medlemsplats</a></li>
                  <li><a href="../html/tourist.html">Turistmål</a></li>
               </ul>
            </div>
         </div>
         <aside id="contactinfo">
            <h2>Kontaktformulär</h2>
            <form action=# method=post>
               <fieldset>
                  <legend>Fyll i ärendet:</legend>
                  <p>
                     <label for="Heading">Rubrik*:</label>
                     <input type="text" maxlength="20" id="Heading" name="heading" size="17" required><br>
                     <label for="Message">Meddelande*:</label>
                     <!--Textruta att skriva i-->
                     <textarea rows="5" maxlength="256" cols="30" name="message" id="Message" required>
                      </textarea>
                  </p>
               </fieldset>
            </form>
            <form action=# method=post>
               <fieldset>
                  <legend>Ärende*:</legend>
                  <p>
                     <label for="concernform">
                        <select id="concernform" name="concern" required>
                           <option value="" disabled selected>Vad gäller ditt ärende?</option>
                           <option value="boat">Båtplats</option>
                           <option value="member">Medlem</option>
                           <option value="other">Övrigt</option>
                        </select>
                     </label>
                  </p>
               </fieldset>
            </form>
            <fieldset>
               <legend>Kontaktsätt*:</legend>
               <form action=# method=post>
                  <p>
                     <!--Rullista-->
                     <label for="contactform">
                        <select id="contactform" name="contact" required>
                           <option value="" disabled selected>Hur vill du bli kontaktad?</option>
                           <option value="mail">E-mail</option>
                           <option value="phone">Telefon</option>
                           <option value="nothing">Ingen kontakt</option>
                        </select>
                     </label>
                  </p>
               </form>
            </fieldset>
            <fieldset>
               <legend>Fyll i dina kontaktuppgifter:</legend>
               <form action=# method=post>
                  <p>
                     <label for="Email">E-mail:</label>
                     <input type="text" maxlength="30" id="Email" name="email" size="17" /><br>
                     <label for="PhoneNumberEmail">Telefon:</label>
                     <input type="text" maxlength="12" id="PhoneNumberEmail" name="phonenumberemail" size="17" /><br>
                  </p>
               </form>
            </fieldset>
            <br>
            <div>
               <p>
                  <!--Knapp-->
                  <input type="submit" value="Skicka >>"/>
                  <input type="reset" value="Återställ" />
               </p>
            </div>
         </aside>
      </footer>
      <button id="upButton" title="Uppåt">▲</button>
   </body>
</html>
