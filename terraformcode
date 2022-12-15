provider "aws" {
    profile = "myaws"
    region = "us-east-2"
}

resource "aws_s3_bucket" "b" {
    bucket = "geddada12"
    acl = "private"

    tags = {
        Name = "My Bucket"
        Environment = "Dev"
    }
}
