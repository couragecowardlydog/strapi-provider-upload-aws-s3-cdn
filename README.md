# Strapi : Upload Provider

Upload provider for strapi , with S3 and CDN

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install provider.

```bash
npm install strapi-provider-upload-aws-s3-cdn
```

## Usage

```javascript
module.exports = ({ env }) => ({
    upload: {
      provider: 'aws-s3-cdn',
      providerOptions: {
        region: <aws-region> ,
        params: {
          Bucket: <bucketName> ,
        },
        cdn: <cdn url>
      },
    },
  });

```


## License
[MIT](https://choosealicense.com/licenses/mit/)
