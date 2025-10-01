```mermaid

erDiagram
   direction TB

   Coach ||--o{ Player : manages
   Coach {
      string name
      string team
   }

   Player ||--o{ Round : plays
   Player {
      string name
      float scoringAverage
      int handicap
   }

   Round ||--o{ Statistics : generates
   Player ||--o{ Statistics : has
   Decade ||--o{ Statistics : records

   Round {
      int roundScore
      date datePlayed
      string course
   }
   
   Statistics {
      float fairwayPercentage
      float GIRPercentage
      float puttsPerRound
      float bogeyRate
   }

   Decade {
      int roundID
      float score
      float fairways
      float GIRs
      float putts
   }
