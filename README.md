# SIR-SIS-models-on-BA-ER-graphs
Analiza dynamiki modelów SIR i SIS w zależności od cech sieci BA i grafu ER

**Model SIS**:
$$ \frac{dS(t)}{dt} = \-beta S(t) I(t) + \gamma I(t) $$ $$ \frac{dI(t)}{dt} = \beta S(t) I(t) - \gamma I(t) $$

**Model SIR**:
$$ \frac{dS(t)}{dt} = \-beta S(t) I(t) $$ $$ \frac{dI(t)}{dt} = \beta S(t) I(t) - \gamma I(t) $$ $$ \frac{dR(t)}{dt} = \gamma I(t) $$

Gdzie: <em>S (Susceptible)</em> - osoby zdrowe, które są podatne na zarażenie, <em>I (Infected)</em> – osoby zarażone oraz <em>R (Recovered)</em> – osoby ozdrowiałe, które nie mogą ponownie być zarażone

**Graf Erdosa-Renyi**:


**Sieć Barabasiego-Albert**:
