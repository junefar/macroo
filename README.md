# macroo

```toml
[dependencies]
macroo = {path="../macroo"}
macroo_derive = {path="../macroo/macroo_derive"}

```

```rust
use macrooo::HelloMacro;
use macrooo_derive::HelloMacro;


#[derive(HelloMacro)]
struct MM;

fn main(){
    MM::hello_macro();
}

//Hello， in my macro，my name is MM
```