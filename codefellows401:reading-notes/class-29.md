# Reading Notes


## Code 401 - Advanced Software Development

## Overview of reading notes

The reading delve into data storage using Amazon S3.

### What is Amazon S3?

Amazon S3 is a storage service that provides secure storage for different types of data in the cloud.

### List at least 3 features that it offers to its users.

1. Storage Classes: different storage classes for use cases
2. Data management
3. IAM access control

### What is an object key?

An object key is a identifier assigned to each object that is stored in Amazon S3.


### Which dependencies are needed to install Amplify AWS S3 to your ndroid application?

* com.amplifyframework:aws-storage-s3
* com.amplifyframework:aws-auth-cognito

### What is needed in order to upload data to your bucket?

In order to upload data to your bucket, you need the specified key and data object using the Amplify.Storage.uploadFile method.

### what method(s) initialize(s) the Amplify Auth and Storage categories?

The Amplify Auth and storage categories are initialized by using Amplify.addPlugin() and Amplify.configure().

## Things I want to know more about

* just general stuff about each of these concepts. No real questions.