# Zippo
Get a zip full of a list of file URLs provided. 

POST a list of file URLs to `//zippo.yourdeployment.com?filename=package.zip` like so
```
file1.txt=https://s3.aws.com/file1&
file2.jpg=https://s3.aws.com/pic&
file3.pdf=https://bucket.googlecloud.com/data1&
dir1/more.txt=https://s3.aws.com/something&
```
And a download of the file you expect will start almost immediately.


