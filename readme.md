### Alpine Guide
`docker build -t alpinedemo:vigine - < Alpine.Dockerfile`
`docker images | grep "alpinedemo"`
`docker run -it --rm alpinedemo:vigine`

### Scratch Guide
`docker build --tag hello .`
`docker images | grep "hello"`
`docker run --rm hello`

### Compile the c file
gcc -static hello_ssl.c -o hello_ssl_static
./hello_ssl_static
ldd hello_ssl