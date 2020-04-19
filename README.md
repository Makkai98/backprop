Megoldás során a csatolt matlab állományokat modosítottam.
1.Kicseréltem a taníto és teszthalmazokat, illetve a hozzájuk tartozó elvárt kimeneteket
az általam írott halmazokra (genbackpropYY.m).
2.Kicseréltem az aktiváló függvényt és deriváltját
3.Beállítottam a szükséges rétegeket és a rétegekben levő neuronok számát
(1. réteg 36 neuron 35 bemenet+bias,2. réteg 12 neuron tapasztalati uton határoztam meg,
hogy hatékonyabb legyen a tanítás, 3. réteg 10 neuron, mert ennyi osztályom van)
4. Kiszámoltam a teszthalmazra a neuronháló kimenetét és összehasonlítom
az elvárt kimenetekkel megjelenítve.
5. Konfúziós matrxi létrehozása és megjelenítése a command ablakba