# gcp-test-sa
to test GCP CI/CD

## Run on cloud shell
gcloud builds submit --tag gcr.io/msds-2022/test-app --project=msds-2022 <br>
gcloud run deploy test-app --image gcr.io/msds-2022/test-app --platform managed --project=msds-2022 --allow-unauthenticated --region us-west1 <br>