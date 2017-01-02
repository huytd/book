# Ebook: Ngôn ngữ lập trình Rust
[![Build Status](https://travis-ci.org/rust-vietnam/book.svg?branch=master)](https://travis-ci.org/rust-vietnam/book)

## Lời tựa

Bạn muốn tìm hiểu về Rust nhưng không biết bắt đầu từ đâu! Quyển sách này là điểm khởi đầu tốt nhất, quyển sách sẽ giới
thiệu với các bạn những kiến thức cơ bản trong Rust, từ đơn giản cho đến phức tạp. Những kiến thức trong đây
được trình bày hết sức đơn giản, dể hiểu, rất thích hợp cho những bạn đang bắt đầu tìm hiểu về Rust.

Rust Vietnam không trực tiếp viết ra quyển sách, nhưng Rust Vietnam sẽ thực hiện việc Việt hoá quyển sách này,
để giúp các bạn có cách tiếp cận tốt nhất đối với Rust.

## Các nội dung đã được Việt hoá

- [Giới thiệu](https://rust-vietnam.github.io/book/ch01-00-introduction.html)
    - [Installation](https://rust-vietnam.github.io/book/ch01-01-installation.html)
    - [Hello, World!](https://rust-vietnam.github.io/book/ch01-02-hello-world.html)

- ~~Guessing Game Tutorial~~

- ~~Common Programming Concepts~~
    - ~~Variables and Mutability~~
    - ~~Data Types~~
    - ~~How Functions Work~~
    - ~~Comments~~
    - ~~Control Flow~~

- ~~Understanding Ownership~~
    - ~~What is Ownership?~~
    - ~~References & Borrowing~~
    - ~~Slices~~

- ~~Structs~~
    - ~~Method Syntax~~

- ~~Enums~~
    - ~~Option~~
    - ~~Match~~
    - ~~`if let`~~

## Basic Rust Literacy

- ~~Modules~~
    - ~~`mod` and the Filesystem~~
    - ~~Controlling Visibility with `pub`~~
    - ~~Importing Names with `use`~~

- ~~Fundamental Collections~~
    - [Vectors](https://rust-vietnam.github.io/book/ch08-01-vectors.md)
    - ~~Strings~~
    - ~~Hash Maps~~

- ~~Error Handling~~
    - ~~Unrecoverable Errors with `panic!`~~
    - ~~Recoverable Errors with `Result`~~
    - ~~To `panic!` or Not To `panic!`~~

- ~~Generics~~
    - ~~Syntax~~
    - ~~Traits~~
    - ~~Lifetime syntax~~

- ~~Testing~~
    - ~~Writing tests~~
    - ~~Running tests~~
    - ~~Test Organization~~

- ~~I/O~~
    - ~~`Read` & `Write`~~
    - ~~`std::fs`~~
    - ~~`std::path`~~
    - ~~`std::env`~~


## Thinking in Rust

- ~~Composition~~
    - ~~Instead of Inheritance~~
    - ~~Trait Objects?~~

- ~~Creating a Library~~
    - ~~Cargo~~
    - ~~Crates.io~~
    - ~~Organizing your Public API~~
    - ~~Documentation~~
    - ~~Workspaces and Multiple Related Crates~~

- ~~Closures~~

- ~~Zero-cost Abstractions~~
    - ~~Iterators as a Case Study~~

- ~~Smart Pointers~~
    - ~~`Box<T>`~~
    - ~~`Rc<T>`~~
    - ~~`Cell`~~
    - ~~`RefCell`~~
    - ~~Interior Mutability~~

- ~~Concurrency~~
    - ~~Threads~~
    - ~~`Send` & `Sync`~~
    - ~~`Arc<T>`~~
    - ~~`Mutex<T>`~~
    - ~~`Channels`~~

## Advanced Topics

- ~~Patterns~~

- ~~More Lifetimes~~

- ~~Unsafe Rust~~
    - ~~Raw Pointers~~
    - ~~`transmute`~~

- ~~Foreign Function Interface~~
    - ~~Conditional Compilation~~
    - ~~Bindings to C~~
    - ~~Using Rust from Other Languages~~
    - ~~`static`~~

- ~~Advanced Type System Features~~
    - ~~Associated Types~~
    - ~~Trait Objects~~
    - ~~UFCS~~
    - ~~Coherence~~

- ~~Macros~~
    - ~~Writing Your Own Macros~~

- ~~Nightly Rust~~
    - ~~Nightly Features~~
    - ~~How to Find Out About Nightly Features~~

- ~~Appendix~~
    - ~~Keywords~~
    - ~~Operators~~
    - ~~Derivable Traits~~

## Contributing guidelines

Chúng tôi sẽ rất vui nếu bạn giúp chúng tôi Việt hoá một chapter hay là sửa một lỗi nhỏ về ngữ pháp, bất kỳ lỗi nào
bạn tìm thấy thì đừng ngại tạo một [Pull request](https://github.com/rust-vietnam/book/pulls). Để có thể xem được
phiên bản ebook offline thì bạn cần làm các bước sau:

1. Clone project: `$ git clone https://github.com/rust-vietnam/book`
2. Vì ebook này được xâu dựng bằng [mdBook](https://github.com/azerupi/mdBook), nên cần install: `$ cargo instal mdbook`
3. Serve project : `mdbook serve`
4. Tiến hành Việt hoá hoặc tìm lỗi.
5. Tiến hành build ebook: `$ mdbook build`. Mặc định sau khi build thì content sẽ nằm trong folder `book`
6. Review lại một lần nửa: `$ open -a "Firefox" book/index.html # OS X` hoặc `$ open -a "Google Chrome" book/index.html # OS X`.
Nếu bạn dùng `Window` bạn có thể mở folder `book` và duple click vào file `index.html` để xem nội dung ebook.
7. Tạo PR.

Ngay sau khi bạn tạo PR chúng tôi đã xây dựng 1 người giúp việc `CI` để tự động kiểm tra lại bạn có sai sót nhỏ gì không ?
Đưng lo lắng bạn có thể xem lại công việc của người giúp việc [CI](https://travis-ci.org/rust-vietnam/book) đã thực hiện.
Bạn sẽ thấy status hiện tại của CI, nếu green, xin chúc mừng chúng tôi sẽ review lại và sẽ accept PR của bạn, việc này sẽ mất
từ 2-3 tiếng. Ngay sau khi merge thì PR của bạn sẽ xuất hiện trên trang chủ [Ebook: Ngôn ngữ lập trình Rust](https://rust-vietnam.github.io/book/).