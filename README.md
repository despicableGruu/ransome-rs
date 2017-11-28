## CrypticCipher

This program encrypts files and directories. It's designed for educational exploration of security concepts.

**Setup:**

Two components are required: a PHP server and a Go application.

**PHP Server:**

1.  Place the `server` directory on your web server.

**Go Application:**

1.  Ensure Go is installed.
2.  Compile using the following commands:

    **Windows (32-bit):**

    ```bash
    GOOS=windows GOARCH=386 go build encrypt.go
    GOOS=windows GOARCH=386 go build decrypt.go 
    ```

    **Other Systems:**

    Consult the [cross-compilation guide](https://www.digitalocean.com/community/tutorials/how-to-build-go-executables-for-multiple-platforms-on-ubuntu-16-04).

**Structure:**

The program utilizes an asynchronous communication model between components.


[Diagram](https://github.com/despicableGruu/ransome-rs/blob/master/architecture.png)