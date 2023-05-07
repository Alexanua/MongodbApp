# MongoDB Applikation


## Moduler
+ mongodb-driver-sync
+ org.Json

## Kod
+ [X] Modell: Person
    + [X] name (get/set)
    + [X] ålder (get/set)
    + [X] Adress (get/set)
    + [X]  constructor ( Alla variable)
    + [x] @Override constructor toString ()



+ Anställd extends Person
    +[X] private anställningsNummer
    + [X] anställningsNummer (get/set)
    + [X] constructor ( Alla variable)
    + [X] @Override constructor toString ()


+ Kund extends Person
    + [X] private kundNummer
    + [X] kundNummer(get/set)
    +[X] constructor ( Alla variable)



+ Faced:mongoDBFaced
 +  [X] import com.mongodb.client.*;
 + [X] import org.bson.Document;
 +  [X] import com.mongodb.ConnectionString;
 +[X] import com.mongodb.MongoClientSettings;
 + [X] import com.mongodb.client.MongoClient;
 + [X]  import com.mongodb.client.MongoDatabase;
 + [X] import com.mongodb.client.model.Filters;
 +[X]  import com.mongodb.client.model.Updates;

+ [X] private final MongoCollection<Document> kundCollection
+ [X] private final MongoCollection<Document> anställdCollection
+ [X] MongoDBFacade()
    + CRUD för Kund
        +  [X] createKund (Kund kund)
        + [X] readKund (String kundnummer)
      
        + [X] DeleteKund (index)
        + [X] UpdateKund (index, new values)
  
    + CRUD för Anställd
      + [X] createAnställd (Anställd anställd)
      +[X]  readAnställd (String anställningsnummer)

      + [X] DeleteAnställd (index)
      + [X] UpdateAnställd (index, new values)


