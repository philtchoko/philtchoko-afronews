# Where Do People Get News That They Trust About Politics and Inner-Group Conflict?
  
  
  
  This study explores how information networks influence media consumption, political perceptions, and intergroup dynamics, with a specific focus on rural and urban communities in Africa.
Using data from the Afrobarometer dataset, the research identifies key differences in media consumption patterns. Urban respondents are more likely to engage with social media, while rural 
respondents rely more on newspapers and discussions with family and friends. These differences highlight the role of settlement type in shaping how people access and interpret information. 
Drawing on concepts like Carlson’s "distorted democracy" and Rogers’ theory of media marginalization, the study reveals how socially transmitted information reinforces in-group and out-group 
biases. The findings emphasize the need for media literacy programs and equitable access to reliable information, particularly in rural areas where information networks may play a larger role. 
The study concludes by calling for further analysis of sociological factors, such as GDP, democracy, and political affiliation, to better understand how media consumption shapes political 
behavior and social cohesion.



## Data

  Afrobarometer Dataset:

      A dataset from a survey containing African attitudes, experiences, and aspirations.

      Merged(All countries) Round 8 Data of Afrobarometer:  https://www.afrobarometer.org/wp-content/uploads/2025/07/R8_Merge-Codebook_28May24.final_.pdf
      
  Data Collection:

      Gathered important independent variables:

        country -> Country of respondent 
        settlement_type -> "Do you come from a Rural or Urban area?" Values: 1, 2, 3 (Rural, Urban, Semi-Urban)
        age -> Age of respondent Values: 18-70
        gender -> Gender of respondent Values: 1 or 2( Male, Female)
        

      Dependent variables:

        friends_fam -> "When you get together with your friends or family, would you say you discuss political matters:" 
        Values: 0-2, 8, 9, -1 (Never, Occasionally, Frequently,     Refused, Don't Know, Missing)
        newspaper -> "How often do you get news from the following sources: print newspapers?" 
        Values: 0-4, 8, 9, -1(Never, Less than once a month, A few times a month, a few times a week, Everyday, Refused, Don't Know, Missing)
        social_media ->  "How often do you get news from the following sources: social media such as Facebook, Twitter, WhatsApp, or others?" 
        Values: 0-4, 8, 9, -1(Never, Less than once a month, A few times a month, a few times a week, Everyday, Refused, Don't Know, Missing)
        television -> "How often do you get news from the following sources: television?" 
        Values: 0-4, 8, 9, -1(Never, Less than once a month, A few times a month, a few times a week, Everyday, Refused, Don't Know, Missing)
        integration -> "Which of the following statements is closest to your view? Choose Statement 1 or Statement 2. 
        Statement 1: Communities are stronger when they are made up of people from different ethnic groups, races, or religions. 
        Statement 2: Communities are stronger when they are made up of people who are similar to each other, that is, people from the same ethnic group, race, or religion.
        Values: 1-5, 8, 9, -1 
        Value Labels: 1=Agree very strongly with Statement 1, 2=Agree with Statement 1, 3=Agree with Statement 2, 4=Agree very strongly with Statement 2, 
        5=Agree with neither, 8=Refused, 9=Don’t know, -1= Missing. 
        
        
  Data Cleaning

       - Created a dataframe containing the independent and dependent variables -> trust_df(how much trust do people of varying identities place in different news forms?)
       - Created a dataframe containing uniquely 
       - Replaced "Semi-Urban" with "Urban"
       - Changed the scale for newspaper, social_media, and television to match that of friends_fam. 
       ("Every day" -> Frequently, "A few times a week" and "A few times a month" -> "Occasionally", "Less than once a month" -> "Never")
       - Changed the scale for integration from "Agree very strongly with Statement 1, 2=Agree with Statement 1" to "Diverse" and "Similar"
       
        


## Results

   Heatmaps
   

   <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/a2c362f0-fe9b-461c-9d59-7109e0e199dd" />



   <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/ff2d51c2-131c-49b4-ae16-502f9720a387" />



  Graphs

  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/80cc13c8-4f9d-468e-af9d-e76037ec78a0" />


  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/f23588a5-4c2f-48cf-b36a-d21b5c9ef363" />


  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/cd71f998-f655-4bce-81f0-1f41ebeb44ac" />


  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/d222d03d-bc87-4e73-8771-261b4d644315" />


  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/15563447-8397-49b4-a442-5633b3356540" />


  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/f9afdfca-da88-44b6-b49a-79e28d89f133" />


  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/5d342480-3a90-4e5d-9874-1c46afe1e868" />


  <img width="1400" height="865" alt="image" src="https://github.com/user-attachments/assets/f725f93f-f45b-4496-8de9-2ce6d78e6d2d" />



  



## References
