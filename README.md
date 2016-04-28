# StackenLayout

## Lite bakgrund
Idag (April 2016) körs Stackens hemsida med hjälp av ett långsamt PHP-hack som 
några Stacken medlemmar har hackat ihop för några år sedan. För att modernisera 
Stackens hemsida på lång sikt så kommer hemsidan att migreras till en 
markdown-baserad lösning.

## Vad är detta repo för något?
Den lösning som är aktuell i dagsläget är
[hugo](https://github.com/spf13/hugo) vilket är en generator som spottar ur sig
statiska websidor och är skriven i Golang. Detta repo ska lagra det tema 
som stackens nya hemsida ska ha.

## Vad som ska göras
Mycket saker måste göras. Jag kladdade ihop ett förslag på hur hemsidan kan se
ut. Om folk tycker att det är OK, så ska [dokumentationen till Hugos template
system](https://gohugo.io/templates/overview/) läsas och användas för att
skriva temat. Om inga hinder uppstår (vilket det kommer att göra) kan sedan 
migrering påbörjas.

Det som också behöver lösas är hur denna hugo-lösning och de äldre websidorna ska
fungera tillsammans.

## Om du vill delta i detta projekt
Hör av dig till medik (medik at stacken.kth.se) eller forka och gör en push
request om du vill hjälpa till. Det som är uppe i repon 'just nu' är ett förslag
på hur webbsidan kan se ut. Har du förslag på hur det kan förbättras? Tveka
inte att höra av dig!
