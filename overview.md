h1. Inital flow

```mermaid
    flowchart TD
    A[Reddit Inital Post<a href=//reddit.com/r/ARG/comments/150eswe/found_this_on_a_lamppost_think_someone_is_trying/> ] --> datatroniks[datatroniks.net];
    datatroniks --> THOMAS[T-H-O-M-A-S]
    datatroniks --> VARIOUS_BROWSER_GAMES;
    
    B[datatroniks.net] --> blurtout[blurtout.yooco.org];
    
    blurtout --> F[concorrections.com];
    blurtout --> B;
    blurtout --> mezoscape[mezoscape.com];
    blurtout --> dontswimuphill;
    dontswimuphill --> dontswimuphill_data;
    dontswimuphill_data --> dontswimuphill_household_data;
    members --> players[Members not in Arc];
    blurtout --> blurtout_data;
    
    subgraph character_data;
        subgraph dontswimuphill_household_data;
        direction LR
            dontswimuphill.households --> dontswimuphill.locations
            
            dontswimuphill.locations --> dontswimuphill.locations.White_River_City[White_River_City]
            dontswimuphill.locations --> dontswimuphill.locations.Cicada_Cove[Cicada_Cove]
            dontswimuphill.locations --> dontswimuphill.locations.Oakenvilleburg[Oakenvilleburg]
            dontswimuphill.locations --> dontswimuphill.locations.Spitshire_Grove[Spitshire_Grove]
            dontswimuphill.locations --> dontswimuphill.locations.Santa_Mesa[Santa_Mesa]
            dontswimuphill.locations --> dontswimuphill.locations.New_Lake_Falls[New_Lake_Falls]
            dontswimuphill.locations --> dontswimuphill.locations.Snakecave_Mounds[Snakecave_Mounds]
            dontswimuphill.locations --> dontswimuphill.locations.Estrada_Beach[Estrada_Beach]        
            


            
            dontswimuphill.locations.White_River_City --> tymborlyn.White_River_City & pascal.White_River_City & stone.White_River_City & oliver.White_River_City

                tymborlyn.White_River_City --> Talia_Princemoore & Talia_Princemoore_Staff

                pascal.White_River_City --> Tony_Pascal & Dylan_Pascal

                stone.White_River_City --> Douglass_Stone & Laura_Stone & Brandley_Stone

                oliver.White_River_City --> Rupert_Oliver & Candice_Oliver & Gary_Oliver



            dontswimuphill.locations.Cicada_Cove --> porter.Cicada_Cove
            
                porter.Cicada_Cove --> Rebecca_Porter & Carey_Porter & Papey_Porter

            dontswimuphill.locations.Oakenvilleburg --> 
                carson.Oakenvilleburg --> Tanya_Carson & Aiden_Carson
            
            dontswimuphill.locations.Spitshire_Grove --> hernandez.Spitshire_Grove
                hernandez.Spitshire_Grove --> Donnie_Hernandez & Michelle_Hernandez & Rose_Hernandez
            
            dontswimuphill.locations.Santa_Mesa --> stone.Santa_Mesa & oliver.Santa_Mesa
            
                stone.Santa_Mesa --> Richard_Stone & Gloria_Stone & Max_Stone & Auldon_Stone
                oliver.Santa_Mesa --> Jason_Oliver & Carissa_Oliver



            dontswimuphill.locations.New_Lake_Falls --> stone.New_Lake_Falls
                stone.New_Lake_Falls --> Wanda_Stone
            
            dontswimuphill.locations.Snakecave_Mounds --> south.Snakecave_Mounds
                south.Snakecave_Mounds --> Calvin_South & Connie_South & Tanner_South
            dontswimuphill.locations.Estrada_Beach --> rothstone.Estrada_Beach
                rothstone.Estrada_Beach --> Troy_Rothstone & Lance_Rothstone & Summer_Rothstone & Autumn_Rothstone


            
        
        end




    subgraph blurtout_data;
        blurtout_website --> blurtout.important_media & blurtout.members & blurtout.clues
        blurtout.clues --> cyber_attack_2020
        cyber_attack_2020 --> newspaper.jpg
        blurtout.important_media[Important Media] --> newspaper.jpg
        blurtout.members --> locations
        locations --> White_River_City;
        White_River_City --> artsmart & awestone & botanifanatic & kimmy911 & mysticaldave & westsideriot 

        kimmy911--> Kim_Feinhorn
        kimmy911--> newspaper.jpg
        
        
        artsmart--> Travis_Conrad;
        awestone--> Connor_MacPhain;
        botanifanatic--> Laurie_Kozlowski;


        mysticaldave --> Dave_Larson
        westsideriot --> Rodney_Lewis
    end
end
```
