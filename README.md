# Bucket_AWS
Create a S3 Bucket with Terraform

#### Getting started - credentials
```bash
  export AWS_ACCESS_KEY_ID=your_key
  export AWS_SECRET_ACCESS_KEY=your_secret
```

#### Init
```hcl
  terraform init
```

#### Create a Plan named plan.out
```hcl
  terraform plan -out=plan.out
```

#### Validate
```hcl
  terraform validate
```

#### Indentation
```hcl
  terraform fmt
```

#### Aplly
```hcl
  terraform apply plan.out
```

#### Destroy
```hcl
  terraform destroy
```


