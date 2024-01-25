<pre> IMAA2024 Matematikk for ingeniørfag 2 D Vår 2024, Ålesund. </pre>

# Main Title
# Math subject 1

## Quick links
1. [Funksjoner med flere variabler](#funksjoner-med-flere-variabler)
2. [Partiell derivasjon](#partiell-derivasjon)
3. [Derivasjon og partiell derivasjon](#derivasjon-og-partiell-derivasjon)
4. [PDE - Partielle differensialligninger](#pde---partielle-differensialligninger)
5. [Diskret matematikk](#diskret-matematikk)


## Funksjoner med flere variabler

### Quick links

## Partiell derivasjon  

### Quick links
1. [Hvordan partiell derivere](#hvordan-partiell-derivere)
2. [Eksempler](#eksempler) 
3. [Når kan vi partiell derivere](#når-kan-vi-partiell-derivere)
4. [Gradient og retningsderivert](#gradient-og-retningsderivert)
5. [Tolkning til gradienten](#tolkning-til-gradienten)



### Hvordan partiell derivere
Når vi har en funksjon med flere variabler, f(x,y) = y^2 + x^2 +2*x.
Kan vi derivere med hensyn på x eller y.

### Gradient og retningsderivert

Gradienten er en vektor som peker i retningen til størst økning i funksjonen. Den er ortogonal til nivåkurvene. Den er også ortogonal til tangenten til nivåkurvene.

Finn gradienten og den retningsderiverte til f(x,y) = x^2 + y^2 i punktet (-1,1) i retningen til vektoren n = 1/sqrt(2)[1,1] (|[1,1]| = sqrt(2) ).

&#x2207; f(x,y) = [&#8706;f/&#8706;x (x,y), &#8706;f/&#8706;y (x,y)] = [2x, 2y]\

&#x2207;f(-1,1) = [-2, 2]\

&#8706;f/&#8706;n (x) = D_n f(x) = &#x2207;f(x) * n
&#8706;f/&#8706;(n) (-1,1) = &#x2207;f(-1,1)*n = [-2, 2] * 1/sqrt(2)[1,1] = -2/sqrt(2) + 2/sqrt(2) = 0


#### Tolkning til gradienten

Gradienten inneholder de retningsderiverte i retning til enhetsvektorene.\
&#8706;f/&#8706;x (x) er den retningsderviverte i x-retning.\

Gradienten er ortogonal til nivåkurvene. Det vil si den forteller oss hvilken retning vi må gå for å øke funksjonen mest mulig (eller minke). 

#### Eksempel

f(x,y) = 3/4*y^2 + 1/12*y^3 - 1/32*y^4 - x^2.\
Start i (1,2) = x.\

a) Hva er stigningstallet til f i retning v = [3, 1]\

&#8706;f / &#8706;x = -2x\
&#8706;f / &#8706;y = 3/2*y + 1/4*y^2 - 1/8*y^3\
&#x2207;f(1,2) = [ &#8706;f/&#8706;x (1,2) , &#8706;f/&#8706;y (1,2) ] 
= [-2, 3+1-1] 
= [-2, 3]\

For å beregne D_u f trenger vi en trening u med |u| = 1. v = [3,1] har |v| = sqrt(3^2+1^2) = sqrt(10)\
u = 1/sqrt(10) * [3,1]\

D_u f(1,2) = &#x2207;f(1,2)*u = [-2, 3] * 1/sqrt(10) * [3,1] = 1/sqrt(10) * (-2*3 + 3*1) = -3*sqrt(10)/10

tan(alpha) = -3*sqrt(10)/10
a = tan^-1(-3*sqrt(10)/10) = 43.5 grader   

b) I hvilken retning minker f fortest mulig?


### Eksempler 

f(x,y) = y^2 + x^2 +2*x.\
f(x,y) derivert med hensyn på x = 2*x + 2. Dette er stigningen i x-retning (n-vektor = [1, 0] (egentlig kolonnevektor også))\
f(x,y) derivert med hensyn på y = 2*y. Dette er stigningen i y-retning (n-vektor = [0, 1] (egentlig kolonnevektor også))\

### Når kan vi partiell derivere

Det er ikke alltid den partiell deriverte eksisterer. TODO jeg vet ikke helt når dette er, men vertfall når funksjonen ikke er kontinuerlig.

## Derivasjon og partiell derivasjon

## PDE - Partielle differensialligninger

## Diskret matematikk
aowduhawihd

## Regne ut den retningsderiverte

1. Finn gradienten til funksjonen.
2. Finn lengden til vektoren
3. blablabla, skal sjå i OneNote so ej ikkje skriv noke feil.

