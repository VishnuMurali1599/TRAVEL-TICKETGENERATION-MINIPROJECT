# TravelTicketGeneration_MiniProject


    Again i am with one more mini project:
        
        This is especially for people staying in banglore.
        
        I hope for atleast once we all would have travelled in BMTC(Bangalore Metropolitan Transport
        Corporation), one of the most busiest corperation in Banglore having around 6000+ buses 
        operating.
        When i was travelling i would been wondering how this ticket will generated.
        Finally i crearted a small program were we can generate ticket with fully explained and Programmed
        with the hellpl of Python.
        
        
    Lets Now Get in to Programming Part:
        The tickets are generated based on Stages.
        When a Bus starts operating from Intial Point to final Point, some of the main stops 
        are generated as Stages. The stops inbetween two stages are consider as sub-stops
        
        Ticket Printing Explanation with example:
         1. Consider A has starting point and E has final point.
        
         2. Now assume that there are 5 stages b/w these two point.
            
         3. Stage A = Starting point
               SubStop=A1,A2,A3
            Stage B = intermediate point
               Substop=B1,B2,B3
            stage C = intermediate point
               Substop=C1,C2,C3
            stage D = intermediate point
               Substop=D1,D2,D3
            Stage E = Final point
            
         4.Now the Ticket price will be genrated b/w two stages and substops will be covered in b/w
           these two stages
            
         5.IF a person want to travel from Stage A to Stage D all intermediate stages(B,C) will also 
           be covered,or from Stage A to C ,(stage B )will also be covered including substops.
            
            
    
