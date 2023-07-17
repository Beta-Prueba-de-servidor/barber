# barber
-------------------------------------------------
     ->#[master]->#[pro]-> encoding erro <--#[fix]
                          <-[build]
---------------------------------------------------
                 ->#[build]<-[dev]
-----------------------------------------------------                 
                 ->#[dev] <-[back]
                          <-[front]
                          -/docker-compose
------------------------------------------------------                          
               ->#[/back/]-|-/src/
                           |-/Dockerfile
                 
               ->#[/front/]-|-/src/app/pages.js
                            |        /common/components/
                            |               /styles/globals.css
                            |       /home/pages.js
                            |-/Dockerfile
