# vaccination-portal
A from scratch project about Vaccination portal to register vaccine and get vaccinated


# Data Models

Vaccine
{
  ID: UUID
  Type: String,
  CountryOfOrigin: String,
  ValidAge: String,
}

Person
{
  Name: String,
  DOB:String,
  ID: String,
  Verified:String
  DosageNumber:String
}

Register
{
Person_ID, Vaccine, DateAndTime
}

MedernaVaccine type of Vaccine
{
  Availble:number,
  Consumed: number,
}
PfizerVaccine type of Vaccine
{
  Availble:number,
  Consumed: number,
}
CoviSheild type of Vaccine
{
  Availble:number,
  Consumed: number,
}


# Rest Design

Put Vaccine 
METHOD POST - /rest/v1/vaccineportal/vaccine
         BODY : 
          
                
