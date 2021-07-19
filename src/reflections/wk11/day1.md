# Class Notes 7/19
steps: bcw-create dotnet-vue
Add connection string to startup.cs
startup.cs  => IDB Accounts, Cors
   Cors Who are trusted clients localhost:8080, localhost:8081  Cross Origin x x 
   Configuration Cors => app .....
      Add Police with origins whitelist

  Auth ...  as seen before.  JWT Jason Web Table Config Auth using ENV  Connection String, Domain, Audience...
  app Use Default files => wwwrrrot => index.hrml  (gives new client Vue element)

  Note <em>vite</em> Vue Runner runs client really fast...
   client env connections also .. don't forget.

Uppdate Apps ... JSON ...  Local 3000  change to localhost:5001

# Create SQL tables as needed:
 Note that Auth Accounts ID is string!  Ever see string id in sql? No!

 No=>     Auto Increment E.G

CREATE TABLE Accounts(
  id VARCHAR(255) NOT NULL primary key comment 'primary key',
  createdAt DATETIME DEFAULT CURRENT_TIMESTAMP COMMENT 'create time',
  updatedAt DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP COMMENT 'update time',
  name varchar(255) NOT NULL comment 'Users given name',
  email varchar(255) NOT NULL comment 'Auth Email',
  picture varchar(255) NOT NULL comment 'Picture URL'
) default charset utf8 comment '';

Update  setup .sql   reload PAGE ABD Boom! Automaticly Loads account info into Account Table

New Decorator tag [AUTHORIZE] to don't let people past without a bearere token However please not:
Account Id still needs to come from Auth Account still do not trust Id from user.

-----------------------
# Models
Create Models  prop  <tab> prop with { get; set; }
     DateTime CreatedAt  ...
     DateTime UpdatedAt  ...

     food_Place  etc
     public Account Creator  (Dapper populates virtual)

# Interface

IDbItem
create:   public interface IDbItem
{
  int Id    //requires ID
  string Id  // used when IDBItem<string>
  DateTime CreatedAt { get; set; }   //required interface rules.
  DateTime UpdatesAt ......
}

In an interface everythingmust be public....

Implementation:
public class Review; IDbItem   <---  This interface can be implemented 
{

}












