Dalam Rust, kita dapat merubah tipe data dari suatu variable yang sudah kita nyatakan secara explicit tipe datanya dengan menggunakan kata kunci "as"


```
fn merubah_tipedata() {
    let x: f32 = 0.4;
    let b: f64 = x as f64;
    print!("{}", b);
}
```
