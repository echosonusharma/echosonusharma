```rs
fn main() {
    println!("Hi, I'm Sonu.");

    let mut languages: Vec<&str> = Vec::new();

    languages.push("JS/TS");
    languages.push("Go");

    println!("I can code in {}.", languages.join(", "))
}
```