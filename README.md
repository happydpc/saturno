## Saturno

An implementation of Peter Shirley's [Ray Tracing in One Weekend][rtiow_book].
The rendering library has bindings for Web Assembly so it can render client or
server-side.

### Build and Run Server
```
cd backend &&
./build.sh
```

### Run Ray Tracer Tests
```
cd ./rendering &&
cargo test --release
```


![Book Cover](https://raw.githubusercontent.com/alvarosan/saturno/master/rendering/book_cover.png)
![Diffuse Normals](https://raw.githubusercontent.com/alvarosan/saturno/master/rendering/render_diffuse_ms100_2000x1000.png)



[rtiow_book]:<https://www.realtimerendering.com/raytracing/Ray%20Tracing%20in%20a%20Weekend.pdf>
