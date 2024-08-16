---
title: Terraform error encounters
date: 2024-08-15 02:00:00 +1000
categories: [Terraform]
tags: [terraform-errors]     # TAG names should always be lowercase
description: These are the contents I encountered while learning terraform in automating aws cloud and the fixes i applied.
image:
  path: /assets/img/terraform/mockup.png
  alt: preview-image-of-the-post
pin: true
---

<!--size for preview image 1200 x 630 -->

# A good template for a Blog

## Title

### Subtitle

![Desktop View](/assets/img/sample/mockup.png){: width="700" height="400"}

## B

### B.b

![Image - Description](/assets/img/sample/mockup.png){: w="700" h="400" .shadow}
_Caption of the image, with shadow_

This is `inline code part`. Thank you!

`/path/to/a/file.extend`{: .filepath}

```shell
 Error: creating S3 Bucket (my-tf-test-bucket): operation error S3: CreateBucket, https response error StatusCode: 409, RequestID: 95ZM6Y4N8B82W4JH, HostID: HrxADlTzHBVIYrNQHyR0ry/OcAFSqru0VgACkRODR/LFuhJt5gaQD7L65kVlCYR7kAovgnefv0xiR9zRA3Xibw==, BucketAlreadyExists: 
 
   with aws_s3_bucket.tf_state,
   on main.tf line 27, in resource "aws_s3_bucket" "tf_state":
   27: resource "aws_s3_bucket" "tf_state" {
```
