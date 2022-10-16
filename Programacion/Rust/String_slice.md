# String slice

tags: #Apuntes #Progracion #Rust

Un *string slice* es una referencia a una parte de un *String*.  

## Ejemplo

~~~Rust
fn main() {
    let s = String::from("hello world");

    let hello = &s[0..5];
    let world = &s[6..11];
}
~~~