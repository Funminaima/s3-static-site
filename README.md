1. The first thing i did was creat my S3 bucket nad made sure to block public access.
   ![s3-bucket](/Screenshot%202024-05-09%20at%209.37.31%E2%80%AFPM.png)
2. Created my cloudfront
   ![cloud_font_image](/Screenshot%202024-05-09%20at%209.36.39%E2%80%AFPM.png)
3. Edited it to create origin access control so i can add it to my s3 policy
   ![oac_cloudfront](/Screenshot%202024-05-09%20at%209.39.06%E2%80%AFPM.png)
4. Attach the policy to my s3 in the permission tab - bucket policy
   ![s3_policy](/Screenshot%202024-05-09%20at%209.37.47%E2%80%AFPM.png)
5. Copied the distribution domain name
   ![domain_name](/Screenshot%202024-05-09%20at%209.36.39%E2%80%AFPM.png)
6. Access my website
   ![website_pic](/Screenshot%202024-05-09%20at%209.36.13%E2%80%AFPM.png)
