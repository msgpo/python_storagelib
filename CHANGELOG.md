# 0.3

* added `has_object_matching()` to check an object with multiple key/value pairs

# 0.2

* more flexible requirements for requests
* removed some debug prints
* don't fail if `AWS_PROFILE` environ is present
* added `s3_test_url` script to test an URL
* added `delete_object()` shortcut

# 0.1

* Initial version featuring:
 * URL parsing
 * Visual transfer progress hook
 * wasabi detection
 * configured S3 resource (`.resource`)
 * configured S3 client (`.client`)
 * requests auth module (`.aws_auth`)
 * credentials check (list bucket, read, write)
 * configured generic service (`iam` for ex.)
 * direct bucket names
 * direct bucket access
 * test bucket existence
 * bucket creation
 * test object exitence
 * direct object head access
 * direct object stats access
 * test object with etag exitence
 * test object with meta existence
 * set policy on bucket (allow external downloads)
 * set wasabi auto delete on bucket (retention)
 * set wasabi auto delete on object (retention extension)
 * delete bucket (with wasabi force)
 * wasabi rename bucket
 * wasabi object rename (with prefix)
 * set wasabi compliance
 * direct object download
 * object download url
 * validate file etag (mono and multipart)

