{
    "Version": "2012-10-17",
    "Statement": [
    {
        "Sid": "MRAP-policy"
        "Effect": "Allow",
        "Principal": "arn:aws:iam::123456789012:role/app-role",
        "Action": "s3:GetObject",
        "Resource": "arn:aws:s3::123456789012:accesspoint/mfzwi23gnjvgw.mrap/object/*",
    }]
}