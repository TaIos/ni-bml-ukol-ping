Monitoring odezvy pingu (20b)
============================


**Produkt**: jupyter notebook (příp. skript), který posílá pingy na vhodně vybraný server. Stanovíte si rozumnou mez round-trip-time (RTT) pro odpověď, kdy bude považována za úspěch (X=1), pokud pong překročí tuto mez nebo nedorazí vůbec, počítáte neúspěch (X=0). Cílem je sekvenčně modelovat pravděpodobnost úspěšné odezvy p(X=1). Skript by měl obsahovat parametr, který určí, kolik pingů se pošle jednorázově. Při jednom modelujete Bernoulliho rozdělením, při více pingách binomickým. Apriorno je beta. Vykresluje se vývoj bodového odhadu pravděpodobnosti +/- 3 směrodatné odchylky (odmocniny z variance).

**STAV**: rozpracováno
