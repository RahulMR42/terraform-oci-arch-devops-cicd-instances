### Sample Terraform.tfvars

```java

# Authentication
tenancy_ocid         = "ocid1.tenancy.oc1..xxxx"
user_ocid            = "ocid1.user.oc1..xxx"
fingerprint          = "xxx"
private_key_path     = "xxx"

# Region
region = "xxxx"

# Compartment
compartment_ocid = "ocid1.compartment.oc1..xxxx" #CICD Compartment

# OCI User and Authtoken
oci_user_name       = "xxxxx"
# For a federated user (single sign-on with an identity provider), enter the username in the following format: TenancyName/Federation/UserName.
# For example, if you use OCI's identity provider, your login would be, Acme/oracleidentitycloudservice/alice.jones@acme.com.
#If you are using OCI's direct sign-in, enter the username in the following format: TenancyName/YourUserName. For example, Acme/alice_jones. Your password is the auth token you created previously.

oci_user_authtoken = "xxxx"
```