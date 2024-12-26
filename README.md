Il y a 4 types de relations fondamentales en Programmation Orientée Objet (POO) :

1--L'Héritage (relation "est un")

2--La Composition (relation "est une partie de")
-----------------------------------------------------------------------------
<?php
    echo "Hello, World!"

    class Facture {
    private $client [];

    public function construct(Client $client []) {
        $this->client = $client;
    }
}

  class Client {
    private $nom;

    public function construct($nom) {
        $this->nom = $nom;
    }
}

 $client = new Client('sara');
  $client2 = new Client('sara');

 $client3 = new Client('sara');
 
 $list = [$client, $client2, $client3]:

 $Facture = new Facture($list);
?>
--------------------------------------------------------------------------------------------------
3--L'Association (relation "utilise")

4--L'Agrégation (relation "contient")

Ces relations sont essentielles pour structurer le code orienté objet et définir comment les différentes classes interagissent entre elles. 
