# aws-sdk-js-v3-rds-signer-cjs

> An [AWS IAM database authentication](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.IAMDBAuth.html) token signer for RDS, implementing `RDS.Signer` for AWS SDK for JS v3

## Installing

```sh
npm install --save aws-sdk-js-v3-rds-signer-cjs
```

This is a light fork of [aws-sdk-js-v3-rds-signer](https://www.npmjs.com/package/aws-sdk-js-v3-rds-signer). That package only provides an esm module and no support for cjs. Unfortunately there are still many usecases that require a commonjs module, so this fork provides that. When/if AWS finally releases their official module, this will be deprecated.
