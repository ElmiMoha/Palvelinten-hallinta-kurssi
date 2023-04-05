X) 

   # Create a Web Page Using Github
   
   - Luo uusi reprositori, johon pitää lisää README file ja valita         lisensiksi GNU GeneralPublic License version 3.
   - Uusi tiedosto pitää luoda reprositioon nimeltään MarkDown(.md)        joka automaattisesti luo tiedostoista nettisivun.
   - Mitä .md tekee: 
      yksi "#" luo h1 otsikon
      Teksi kirjoitetaan normaalisti
      kaksi "##" tekee h2 otsikon
      koodit lyödään neljällä välilyönnillä
      
   # Salt Vagrant - automatically provision one master and two slaves
   
   - Asenna Vagrant ja Virtualbox
   - Valmiiksi tehdystä Vagrantfilesta luodaan kolme konetta( MASTER, t001 ja t002).
   - Ajetaan orjat(t001 ja t002) MASTER koneelta ja siihen yhdistetään        <vagrant ssh tmaster>
   - Muutoksia tehdään idempotenti komennolla tarvittaessa
   - Lopuksi tuhotaan kaikki kolmea konetta
   
   # Asenna Debian 11 Vagrantilla.
   
       Loin aluksi Vagrant-test kansion, johon loin Vagranfilen. 
       mkdir C:\users\Vagrant-test\vagrantfile\.
       Seuraavaksi otin yhteyttä koneeseen käyttämällä komentoja 
   
       <vagrant up>
       <vagrant ssh>
   
![image](https://user-images.githubusercontent.com/129681045/230184566-6ea30473-f011-4347-a3f5-518d3abf3642.png)
   
   
   # Asenna kolmen koneen verkko
   
       Poistin ensimmäisenä tekemäni kone ja käytin komentoja 
       <exit> josta poistuin koneesta ja sen jälkeen tuhosin koneen komennolla <vagrant destroy>.
   
       Tämän jälkeen avasin kansiosta Vagrantfilen ja menin Notepadin kautta kirjoittamassa siihen mallitiedostosta kopioimani tekstin, jossa luotiin kolmeaa konetta. Tämän jälkeen tallensin tiedoston ja komennolla <Vagrant up> käynnistin koneet tai ainakin yritin. Sain seuraavanlaisen vastauksen. 
   
![image](https://user-images.githubusercontent.com/129681045/230185304-43ca8b47-9f30-4673-aa79-4221a56196e0.png)
   
   Olen tässä yrittänyt luovuttamatta ja tiedon etsinnällä päässyt tähän saakka. Olen tällä hetkellä jännyyn jumiin tähän kohtaan. 
   
   
   # Lähteet
   
   1) Karvinen 2023: Create a Web Page Using Github
   2) Karvinen 2023: Salt Vagrant - automatically provision one master and two slaves
