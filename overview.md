h1. Inital flow

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
    
    
    members --> membersInArc[Members in Arc];
    members --> players[Members not in Arc];
    
    
    
    membersInArc --> artsmart;
    membersInArc --> awestone;
    
    membersInArc --> botanifanatic;
    subgraph membersInArc;
        subgraph botanifanatic
            botanifanatic.full_name--> Laurie_Kozlowski
        end

        subgraph kimmy911
            kimmy911.full_name--> Kim_Feinhorn
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




    membersInArc --> kimmy911
    membersInArc --> mysticaldave
    membersInArc --> westsideriot


```
