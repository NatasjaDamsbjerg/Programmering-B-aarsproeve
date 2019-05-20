<p>Natasja Damsbjerg<p>
<p>Programmering<p>
<p>Årsprøve<p>

<a href="https://natasjadamsbjerg.github.io/Programmering-B-aarsproeve/">https://natasjadamsbjerg.github.io/Programmering-B-aarsproeve/</a>

Denne app er bygget op af forskellige scripts, som er importeret til min app.
"Names and jokes" er navnet på denne lille app, der gør brug af to eksterne Javascript libraries, en css boilerplate og tre API'er. 

Sådan virker siden:

<ul>
<li>Siden loader og henter .js og .css ressourser fra cdn.</li>
</ul>

<ul>
<li>Handlebars.js opsætter en skabelon for random activity.</li>
</ul>

<ul>
<li>(jQuery document ready event listener) viser div id="page one", og skjuler de andre sider.</li>
</ul>

<ul>
<li>(jQuery) $.ajax henter data fra:
<ul>
<li><a href="https://www.boredapi.com/api/activity">En API der generere aktiviteter</a></li>
<li><a href="https://github.com/15Dkatz/official_joke_api">En API der generere jokes</a></li>
<li><a href="https://github.com/thm/uinames">En API der generere navne</a></li>
</ul></li>
</ul>

<ul>
<li>(jQuery ajax response) fylder handlebar-skabelonen med JSON.</li>
</ul>

<ul>
<li>(Materialize.css) viser aktiviteter i et "card component" layout</li>
</ul> 

Derefter kan du se en lille app med 4 forskellige sider. Den første side giver en ideer, hvis man keder sig.
Den anden side er bare linket til forskellige API'er. Den trejde sider er en name generator, der giver tilfældige navne ud fra forskellieg parametre. Den fjerede side er en joke generator, der kommer med tilfældige jokes. 

Jeg bruger:

Javascript-biblioteket jQuery:
<ul>
<li>Bruges i denne app til at indhente dataen fra to eksterne API'er</li>
</ul>

Handlebars.js:
<ul>
<li>Bruges til at anvende HTML struktur til API'ers JSON resultat. ALtså "putte" dataen ind i nogle templates</li>
</ul>

Materialize.css:
<ul>
<li>Bruges til at skabe layoutet på min app, så dataen vises på en pæn måde til sidst</li>
</ul>

 
      
