###  Backend
- Za svaki servis, po jedan deployment
- Jedna replika, user-service = ime deployment-a = ime servisa
- ClusterIP za servise

- Redis: deployment sa jednom replikom, ima svoj servis, ClusterIP
- Baza podataka: PGO

- ako hocemo da komuniciraju servisi, obracaju se servisu, pa se obracaju deployment-u
- 

###  Frontend
- HTTP Route -> ??? -> Deployment 


