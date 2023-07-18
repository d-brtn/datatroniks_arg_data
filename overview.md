# Draft of information so far

```mermaid
    flowchart TD
    A[Reddit Inital Post<a href=//reddit.com/r/ARG/comments/150eswe/found_this_on_a_lamppost_think_someone_is_trying/> ] --> B[datatroniks.net];
    B[datatroniks.net] --> C[T-H-O-M-A-S]
    B[datatroniks.net] --> D[VARIOUS BROWSER GAMES];
    
    B[datatroniks.net] --> blurtout[blurtout.yooco.org];
    
    blurtout --> F[concorrections.com];
    blurtout --> B;
    blurtout --> G[mezoscape.com];
    blurtout --> members['/members'];
    blurtout --> blurtout.majortopics[Major Topics]
    
    
    subgraph BlurtOut;
        blurtout.majortopics --> blurtout.majortopics.2020_cyber_attack
    
        members --> membersInArc[Members in Arc];
        members --> players[Members not in Arc];
        
        
        
        membersInArc --> artsmart;
        membersInArc --> awestone;
        
        membersInArc --> botanifanatic;
        subgraph membersInArc;
        direction LR

            subgraph botanifanatic
                botanifanatic.full_name--> Laurie_Kozlowski
            end

            subgraph kimmy911
                kimmy911.full_name--> Kim_Feinhorn
                kimmy911.media --> cyber_attack_2020.newspaper.jpg
            end

            subgraph mysticaldave
                mysticaldave.full_name--> Dave_Larson
            end

            subgraph westsideriot
                westsideriot.full_name--> Rodney_Lewis
            end

            subgraph awestone
                awestone.full_name--> Connor_MacPhain
            end

            subgraph artsmart
                artsmart.full_name-->  Travis_Conrad
            end
        end
    end



    membersInArc --> kimmy911
    membersInArc --> mysticaldave
    membersInArc --> westsideriot


```
