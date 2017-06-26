# taxcal
ervice/index.js Deploy this in AWS lambda & tie it up with an API gateway. You can consome the service without the API but that would then mean installing the relevant AWS SDKs based on the device used.

index.html This is static. But you can host it in an S3 butcket and set a route using route53 to create a proper website with a DNS name.

The whole deployment process including provisioning of relevant resources including permissions can be automated with additional effort.
