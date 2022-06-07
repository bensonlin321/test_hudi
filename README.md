# test_hudi

https://drive.google.com/drive/folders/1083vNjjuclSBYl7prt6078lWEuEUnXNb?usp=sharing

docker run -p 9000:9000 -p 9001:9001 -v /Users/bensonlin/Project/S3_Play/data:/data -e "MINIO_ROOT_USER=benson" -e "MINIO_ROOT_PASSWORD=a12345678" -e "MINIO_SITE_REGION=us-east-1" --rm  minio/minio server /data --console-address ":9001"



