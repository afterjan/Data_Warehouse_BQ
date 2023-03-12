# **Data Warehouse - BigQuery**
Build a data warehouse in BigQuery using repeated columns

## **Problem**
From this public table `data-to-insights.ecommerce.rev_transactions`. Create an efficient query which derives the total transactions per date and country based on the channel grouping!

## **Tech Stack**
BigQuery

## **SET UP**
1. Open google cloud console https://console.cloud.google.com/
2. On your GCP console, go to BigQuery. You can find it on More Products > Analytics > BigQuery, or simply search it at the search bar.
3. On Explorer click ADD DATA > Star a project by name > fill "data-to-insights" > click STAR
4. Expand node data-to-insights > ecommerce > rev_transactions.
   Table rev_transactions consists of 15 features, here is the schema:
   
   <img width="457" alt="Screenshot 2023-03-12 at 16 59 53" src="https://user-images.githubusercontent.com/113230789/224537565-956a7d5e-3064-4708-955e-1bbaa6578296.png">

## **QUERY**
