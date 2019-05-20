<p>Natasja Damsbjerg<p>
<p>Programmering<p>
<p>Årsprøve<p>

<ul>
<a href="https://natasjadamsbjerg.github.io/Programmering-B-aarsproeve/">https://natasjadamsbjerg.github.io/Programmering-B-aarsproeve/</a>
</ul>

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
<li><a href="https://www.boredapi.com/api/activity">Dette link føre til en API der generere aktiviteter</a></li>
<li><a href="https://github.com/15Dkatz/official_joke_api">Dette link føre til en API der generere jokes</a></li>
<li><a href="https://github.com/thm/uinames">Dette link føre til en API der generere navne</a></li>
</ul></li>
</ul>

<ul>
<li>(jQuery ajax response) fylder handlebar-skabelonen med JSON.</li>
</ul>

<ul>
<li>(Materialize.css) viser aktiviteter i et "card component" layout</li>
</ul> 

Jeg bruger:

Javascript-biblioteket jQuery, som her bruges til at indhente dataen fra de to eksterne API'er.

Handlebars.js til at "putte" dataen ind i nogle templates.

Materialize.css til at skabe layoutet på min app hvor dataen vises til sidst.

Derefter kan du se en lille app med 4 forskellige sider. Den første side giver en ideer, hvis man keder sig.
Den anden side er bare linket til forskellige API'er. Den trejde sider er en name generator, der giver tilfældige navne ud fra forskellieg parametre. Den fjerede side er en joke generator, der kommer med tilfældige jokes. 
 
      
