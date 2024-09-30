erDiagram
    Client }|..|{ Insurable-Property   : has
    Client {FirstName Jonny
    Nickname The_Fiddler}
    Client ||..o{ Quote_Request: initiates
    Client ||..o{ Agent : "Contacts"
    Client ||..o{ Quote : receives
    Client ||..o{ Bet : Accepts
    Insurance-Policy ||--|{Bet :Not_Covered
    Devil }|..|{ Bet : Makes
    Devil {NOT Cool
    Known_For Soul_Theft}
    Bet {Stakes Soul
    Prize Golden_Fiddle
    Winner Jonny
    Loser Devil
    }
    Agent ||--|{ Quote : provides
    Agent { Insurance-Company Employee}
    Quote ||--|{ Insurable-Property : includes
    Agent ||--|{ Insurance-Policy : writes
    Insurance-Company ||--|{ Insurance-Policy : provides
    Insurance-Company {DBA Georgia_Peach_Inc}
    Insurable-Property ||--o{ Insurance-Policy : "covered in"
    Insurable-Property {Instrument Fiddle
    Accessory Bow 
    Accessory Fiddle_Case}
    Insurance-Policy {Excluded_Hazard Bets_With_Devil
    Property_Not_Covered Jonny_Soul}
	
	end 
	
	_**This is intended to be a fun way to illustrate the insurance quote to policy process while incorporating firsthand professional knowledge and music. The Diagram is representative of a client(Johnny) who is seeking to insure his property, a fiddle. He decided to insure his fiddle after accepting a Bet with the Devil. Johnny contacts and Agent who provides Johnny with a Quote for insurance and writes the Policy. The Policy is issued by the insurance company( The Georgia_Peach_Inc) but has certain exclusions; namely "Bets_With_Devil" are not covered.**_  