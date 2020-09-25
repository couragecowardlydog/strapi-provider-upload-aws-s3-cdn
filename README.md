# Strapi : Upload Provider

Foobar is a Python library for dealing with word pluralization.

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
        region: <> ,
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
