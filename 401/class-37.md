# Class 37 Reading Notes

### Introduction to Amazon S3

What is Amazon S3?
Amazon Simple Storage Service is an object storage service. It is used to protect data and can be used by small and large operations. It also provides management features to its users.

List at least 3 features that it offers to its users.
Storage Management
Access Management
Data Processing

What is an object key?
It is the unique identifier for the object within a bucket.
Every object in a bucket only has one.

### S3 with Amplify

Which dependencies are needed to install Amplify AWS S3 to your android application?
dependencies {
    implementation 'com.amplifyframework:aws-storage-s3:2.2.2'
    implementation 'com.amplifyframework:aws-auth-cognito:2.2.2'
}

What is needed in order to upload data to your bucket?
S3 Object Ownership
You would need to specify the key and the data object to be uplaoded.

What method(s) initialize(s) the Amplify Auth and Storage categories?
You would first need to call Amplify.addPlugin() to initialize and then Amplify.configure() to complete the initialization process.
