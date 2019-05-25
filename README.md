# Installation:
*#Install rustup tool*  
`brew install rustup-init`  
 
*#Run rustup to install rust and a package manager tool:  **rustc**, **rustup** and **cargo***  
 `rustup-init`  

*#Update rustup*  
`rustup update`  

# Basic Components:

*#Install code linter*  
`rustup component add clippy`  
  Usage: `cargo clippy`  

# Pitfalls and solutions:

ERROR:  
*# Error adding new packages via cargo*  
`Unable to update registry https://github.com/rust-lang/crates.io-index
Caused by:
  no authentication available`  

SOLUTION:  
*# Add new ssh agent*  
``eval `ssh-agent -s```  

`ssh-add`
