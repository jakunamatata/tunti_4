The classic example, with the ReturnStatement:

return 
  "something";
// is transformed to
return;
  "something";


Esimerkistä huomataan, että ASI täyttää automaattisesti puolipisteitä
rivien loppuun. Tällöin kannattaa olla tarkkana miten koodi on kirjoitettu
sillä ASI saattaa saada koodin rikki.
