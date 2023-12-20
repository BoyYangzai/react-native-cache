#### use MongoDb to Cache in RN like localStorage/IndexDB api in Web 👋

### Getting Start
```
yarn add react-native-cache-database
```

### Usage
#### Usa Img Cache
Cache img as base64 to Load Image fast 🚀
<br>
Tests: Cache Locally, Load all cached resources **in an instant**
#### For Single
```ts
  const mergedSourceUri = getCacheBySrc(source?.url);
  ...
  <Image source={uri:cacheSourceUri} />

```

#### For Lists
```ts
  const cacheSourceUri = getCacheBySrc(source?.url);

  ...
  render=(item =>
    <Image source={uri:cacheSourceUri} />
  )
```


