## SHRIKE

A directory buster tool that uses brute force combined with a wordlist to search for unlinked content in target directories. These resources may store sensitive information about web applications and operational systems, such as source code, credentials, internal network addressing, etc...

To Compile and Run:
1) Make sure rust is installed (rustc --version)
2) Make sure cargo is installed (cargo --version)
3) Run 'cargo build'
4) Run 'cargo run -- -u <URL> -w <WORDLIST FILE>
