# Wi-Not-Stop Website

### All Files are statically updated

#deploy

1. npm install
2. gulp clean
3. gulp build
4. install aws cli to easily push to s3 bucket
5. PRODUCTION: aws s3 sync dist/ s3://www.wineenergyheatingandairconditioning.com --acl public-read
