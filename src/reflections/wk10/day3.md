Read Foundations of C# > C# Enum's and answer the following questions
# What is an Enum, and what are some use cases for them?

Enums are value types, which means they contain their own value, can't inherit or be inherited from, and assignment copies the value of one enum to another. They can be used as a n index for a Loop.  Meaning that they can be iterated over.. 

# How can you modify an Enum?

Enums have members that are symbolic names, corresponding to an underlying integral type. Enum base types can be changed and member values can be specified. The System.Enum .NET Framework Class Library type is the base class of enum types. It contains methods that allow you to work with enums in different ways, such as working with a list of names or values, converting from value to name, and converting from name to value. 


# How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)

Where I have needed to perform CRUD operation Get that generates a list of matching dB items I can perform the list as an Enum.. As example:
In Mick's cat theories application The interface that communicates between cat Therories Service and cat theories repository returns an ENUM of CatTheroies whith will return multple theoris....

E.G.

    public IEnumerable<CatTheory> getTheories()
    {
      return _repo.getTheories();
    }




Afternoon project:  Instead of working on the AllSpice project I decided to take the learning from Micks Cat theory and port it into Artist.  

if you will notice Artis now has works model and it is linked to artist with artistId and all of CRUD is implemented.  The intention was to bring aLL sql crud Implementation with interfaces.. So this was filled out with all learning to date up until the weekend.

https://github.com/boriswart/artist
