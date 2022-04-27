# twitter_bert
terve. muutama huomio tähän koska en ole jaksanut kummemmin kommentoida noita tiedostoja :D

requirements.txt -tiedostosta löytyy tarvittavat paketit. Niitä on aika iso läjä, kannattanee tehdä virtual environment
tätä puuhastelua varten. Jos venv ei ole tuttu konsepti, täältä löytyy dokumentaatio: https://docs.python.org/3/tutorial/venv.html
paketit voi asentaa terminaalissa tällä: 
$ pip install -r requirements.txt

Tärkeimmät tiedostot on finetune_testing.ipynb ja load_saved_model.ipynb. finetune_testing:istä löytyy mallin lataus,
koulutus (huom. hidas operaatio), ja tallennus, sekä muutama linkki mistä ne setit on revitty. load_saved_model:issa
mallia on testailtu yksittäisen tekstinpätkän labelointiin.

valmiita malleja ei löydy tästä reposta (liian isoja filuja), vaan ne pitää itse ladata ja kouluttaa lokaalisti.
