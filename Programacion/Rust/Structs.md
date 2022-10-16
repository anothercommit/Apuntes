# Structs

En Rust los datos de una **struct** se llaman *fields*.

Using struct update syntax, we can achieve the same effect with less code, as shown in Listing 5-7. The syntax .. specifies that the remaining fields not explicitly set should have the same value as the fields in the given instance.


~~~ Rust
fn main() {

    let user2 = User {
        email: String::from("another@example.com"),
        ..user1
    };
}
~~~