<script lang="ts">
  import Post from "../components/Post.svelte";

  var post1: string = 'Tak jak w ostatnich latach również w tym roku tuż przed Narodowym Świętem Niepodległości uczniowie i nauczyciele wzięli udział w Akcji “Szkoła do Hymnu”. Symbolicznie o godz. 11.11 wszyscy wspólnie odśpiewali pełną 4-zwrotkową wersję “Mazurka Dąbrowskiego.'

  var post2: string = "Ministerstwo Obrony Narodowej – organizuje 11.11.2022 w Jarocinie „Wojskową Grę Terenową”. Szczegóły na stronie www.mon.gov.pl"

  var post3: string = "4. listopada w Szkole Podstawowej nr 2 w Wągrowcu odbyły Mistrzostwa Powiatu SZS w Szachach Drużynowych. W składzie reprezentacji naszej szkoły wystąpili: Maja Ciesiółka, Michał Kubanek, Szymon Lihs, Radosław Wieczorek, Bartłomiej Cholewiński i Mikołaj Grewling. Tym razem bezpośredni pojedynek z najgroźniejszym rywalem miał miejsce już w pierwszej rundzie (w ubiegłym roku miało to miejsce w ostatniej rundzie). Wynik tego meczu był remisowy 2:2 ze wskazaniem na ZS2, bo zdobyliśmy punkty na pierwszych dwóch szachownicach. Po dziesięciu rundach okazało się, że minimalne straty w małych punktach “zepchnęły” naszych na 2. miejsce. Zacięta walka trwała ponad cztery godziny. Drugie miejsce też dało awans do rozgrywek na szczeblu wojewódzkim. Gratulacje!"

  var post4: string = 'Książki całkowicie za darmo?Tak! Nasza szkoła bowiem po raz kolejny uczestniczy w ogólnopolskiej akcji „Upoluj swojąksiążkę”.By poczytać/posłuchać wystarczy postępować wg instrukcji zamieszczonej na plakacie:-pobrać darmową aplikację Woblink i zeskanować w niej kod QR z plakatu-czytać i słuchać aż 18 książek całkowicie za darmo do 30 listopada br.Plakat znajdziecie na drzwiach Szkolnej Biblioteki, świetlicy oraz przy wejściu do szkoły.Więcej szczegółów o książkach znajdziecie na stronie: https://akcja.czytajpl.pl/Miłego zaczytania'
</script>
<div>
    <Post title="Szkoła do hymnu" description="{post1}" image="sdh.webp"/>

    <Post title="Wojskowa Gra Terenowa" description="{post2}" image="wgt.jpg"/>
  
    <Post title="II miejsce szachistów" description="{post3}" image="ms.webp"/>
  
    <Post title="Książki ZA DARMO" description="{post4}" image="kzd.jpg"/>
</div>
<style>
</style>

