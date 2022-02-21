![your-UML-diagram](//www.plantuml.com/plantuml/png/ZOzDYW8n48NtESLRpZ3J5yYgBp238BYFfaW7aWhaHq7nPkwyc4dRtTWBmLtn5U_dzIchc8jtuk1KIlWZBdGHwBZaCqL8_8z79P4CfMmf4aFkGt2ak6B5XZmvJHaI2_vfJlVRrpVgNPNHJj9A98x1wYfTyK6bOLChd4BKaDiSBHlyujc3bQTPYBUMxQ6ubLd3ReRuFEN52gFNRWembCV9RN5xB9l5LVJ4kdZt0000)
class Menue{
 -nutzer : Nutzer
 -regestieren :boolean
 -angemeldet : boolean
 + Menü() 
 +regristieren() : void
 -regristieren(hashPassword :String , nutzername) : void  
 +regristieren() : void 
 +anmelden() : void 
 -anmelden (hashPassword :String , nutzername) : void
 +anmelden () : Void 
 +getangemldet() : boolean
