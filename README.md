# aws-cloud9-nativefier

This is a simple wrapper script for [https://github.com/jiahaog/nativefier](nativefier), which essentially wraps an existing webpage in an electron runner. It wraps the url to the [https://console.aws.amazon.com/cloud9/home](AWS Cloud9 Console dashboard), and thus the AWS Cloud9 IDE. 

# Usage

You unleash the powers of alt-tab for AWS Cloud9 by running:

    npm install && npm run build
  
This will generate a nativefier app in ./dist which you can drag into your Applications folder (on Mac).
Mac users may want to download the [https://github.com/mvhenten/aws-cloud9-nativefier/releases](compiled binary here).
 
 ## DISCLAIMER
I work for the AWS Cloud9 Team at Amazon, but this is in no way part of our offical product release. This package only contains a single line bash script that runs natvefier.
