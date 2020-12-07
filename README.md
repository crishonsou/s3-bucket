# s3-bucket
Terraform module to create S3 Buckets

module "bucket_name" {

  source       = "github.com/crishonsou/s3-bucket"

  name         = "companyname-bucketname"

  user_enabled = false

}
