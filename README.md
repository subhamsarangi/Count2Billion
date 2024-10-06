## Installation Instructions

1. **C++**: Install `g++`
   ```bash
   sudo apt install g++
   ```

2. **Rust**: Install Rust using rustup
   ```bash
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   source $HOME/.cargo/env
   ```

3. **Go**: Install Go
   ```bash
   sudo apt install golang-go
   ```

4. **Java**: Install OpenJDK
   ```bash
   sudo apt install default-jdk
   ```

5. **Python**: Python is typically pre-installed. If not:
   ```bash
   sudo apt install python3
   ```

6. **Elixir**: Install Elixir
   ```bash
   sudo apt install elixir
   ```

7. **TypeScript**: Install Node.js and npm, then TypeScript
   ```bash
   sudo apt install nodejs npm
   npm install -g typescript
   ```

8. **PHP**: Install PHP
   ```bash
   sudo apt install php
   ```

## Checking
```bash
g++ --version
rustc --version
go version
java -version
python3 --version
elixir --version
node --version
php --version
```


## Running instructions

### C++
```bash
g++ cpp_count_to_billion.cpp -o cpp_count_to_billion
./cpp_count_to_billion
```
- takes   0m1.923s

### Rust
```bash
rustc rs_count_to_billion.rs -o rs_count_to_billion
./rs_count_to_billion
```
- takes 0m3.161s

### Go
```bash
go build go_count_to_billion.go -o go_count_to_billion
./go_count_to_billion
```
-takes 0m0.341s

### Java
```bash
javac java_count_to_billion.java
java java_count_to_billion
```
- takes 0m0.365s

### Python
```bash
python3 py_count_to_billion.py
```
- takes 0m25.234s

### Elixir
```bash
elixir exs_count_to_billion.exs
```
- takes 0m11.725s

### Typescript
```bash
node ts_count_to_billion.js
```
- takes 0m0.883s

### Php
```bash
php php_count_to_billion.php
```
- takes 0m3.787s