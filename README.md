# buf.build connect web gRPC (messaging inside an envelope with length and trailer - think stream.on('end')) with protobuf (schema for transport) over HTTP with JSON content type

- [connect getting started](https://connect.build/docs/web/getting-started/)

- to run this:

```
npm config set @buf:registry https://npm.buf.build
npm install @buf/bufbuild_connect-web_bufbuild_eliza
npm i
npm start
```

type in a phrase and hit submit to see what Eliza the therapist has to say
