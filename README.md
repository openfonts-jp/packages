# packages

> OpenFonts.jp のフォント情報

## Usage

- `files/` にフォント情報があります
  - フォント情報の仕様は https://github.com/openfonts-jp/schemas を参照してください
- フォント情報をもとに，CircleCI 経由でフォントがサーバへアップロードされます
- フォント情報は https://github.com/openfonts-jp/registration-form で送信します

## Environments

|Env|Note|
|:--|:--|
|`OPENFONTS_PACKAGE_JSON_SCHEMA_URL`|`https://schemas.openfonts.jp/package/v01/schema.json`|
|`GCLOUD_SERVICE_KEY`|See https://circleci.com/docs/2.0/google-auth/|
|`BUCKET_ROOT_URL`|`gs://your-bucket`|
