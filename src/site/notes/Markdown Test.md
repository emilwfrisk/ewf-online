---
{"dg-publish":true,"permalink":"/markdown-test/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":false,"dgShowInlineTitle":false}
---

Dags att testa lite markdown format...

~~~
Vi gillar kodblock. Väldigt mycket.
~~~

Är du extra **viktig?** Eller bara *snedvriden?* Kanske ~~genomdragen?~~

# Fotnoter
Inte helt säker på att jag förstår, men om vi har lite text och behöver en källa så ska man använd hatt/tak-knappen, inne i  hakparenteser. [^1] 

Man kan skriva infon direkt under, men markdown lägger fotnoten längst ner på sidan automatiskt. Går även bra att göra bignotes, lite oklart vad de gör.[^bignote]

Går såklart bra att göra en fotnot^[Hejsan så hemskt mycket] inline också.

[^1]: Här kan vi skriva vad vår källa faktiskt är...
[^bignote]: Okej vad är en bra förklaring här då, vad är ens en bignote..

# Citat
Görs med > större än tecknet.
> Jag är inte bara bäst, jag är ödmjuk också.
> \- Emil

> Human beings face ever more complex and urgent problems, and their effectiveness in dealing with these problems is a matter that is critical to the stability and continued progress of society. \- Doug Engelbart, 1961

# Block

> [!Quote]
> Hej jag är ett block. Väldigt tjusigt faktiskt. Titeln avgör färg, finns keywords. Typ "Bug".

> [!Bug]
> Hej 

> [!Question]

# Kod
## Inline
`Hej jag är i backticks, undrar var den knappen finns på tangentbordet...
`Aha, shift +dubbeltryck på knappent ill vänster om backspace...`

## Kodblock
tre backticks eller squigglies 
~~~cs
static void Main()
{
	string name = "John";
	Console.WriteLine("Hello" + name);
}
~~~
