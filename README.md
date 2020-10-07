## go mod
[Reference Article](https://medium.com/mindorks/create-projects-independent-of-gopath-using-go-modules-802260cdfb51#:~:text=It%20is%20used%20by%20the,contains%20source%20code%20and%20binaries.&text=With%20the%20latest%20release%20of,improves%20package%20management%20a%20lot)

Step 1:  
```go mod init <folderName>/github.com/{your_username}/{repo_name}```

e.g.  
```go mod init LearnGoMod```

Step 2:  
```go build``` 

Step 3:   
```go run main.go```

