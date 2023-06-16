# TRANSDER-BACKEND
this repo contain 3 wacky directories, 
- The main api account creation and auth and getting accounts based on the recommendation profile, I need to decide on whether I want to write it in Java, C# or Typescript (FastAPI)
- The service that creates the recommendation profile, this will be written in like rust or c++ maybe even Go if im desperate. the goal is for it to be fast, seeing that I need to muck around with SGD matrix factorization it will need to be much speeds.
- the database used for accounts and messaging and stuff
lord knows home I am going to handle everything. I dont know how I am going to make the database work with recommendation profiles and stuff. POSTGRES may come in clutch in this case with the JSONB type. profile tags and questions may also be a play and store those answers on a table and query them to see similarities between others.





 