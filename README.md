{
 {
"AWSTemplateFormatVersion": "2010-09-09",
   "Resources": {
      "IAM": {
  "Type" : "AWS::IAM:: Policy",
  "Properties" : {
    "Groups": [ String, ...],
    "PolicyDocument" : Json,
    "PolicyName" : String,
    "Roles" : [String, ...],
    "Users" : [String, ...]
    }
 }
}
