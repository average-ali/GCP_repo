## SQL workflow to transform and wrangle movielens raw data, so that the resulting tables fit the Cloud Retail BigQuery schema.
Produced datasets are used in Cloud Retail to train search and recommendation models.

catalog_creation.sqlx: Create products table that serves as the catalog on which Cloud Retail Search model will be trained.

ue_.sqlx files: All files generate different user events table. The tables will be used to train Recommendations AI models in Cloud Retail.
