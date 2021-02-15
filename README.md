## Go hello-world
### Unix Terminal
#### Anweisungen ohne Editor in 'hello-world.go' schreiben
    cat > hello-world.go << "E0F"
    package main

    import "fmt"

    func main() {
      fmt.Println("hello world")
    }
    E0F
#### 'hello-world.go' laufen lassen
    go run hello-world.go
#### 'hello-world.go' in eine Executable übersetzen
    go build hello-world.go
#### 'hello-world' ausführen
    ./hello-world
