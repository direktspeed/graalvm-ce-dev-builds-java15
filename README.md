# graalvm-stack
Custom GraalVM Distribution for use in Direktspeed Projects


## Installation

``` 
mkdir  ~/.graalvm && cd ~/.graalvm
curl -s https://github.com/graalvm/graalvm-ce-builds/releases/download/vm-20.3.0/graalvm-ce-java11-linux-amd64-20.3.0.tar.gz | tar Jxf --strip 1 -C ~/.graalvm
GRAALVM_HOME=~/.graalvm
JAVA_HOME=~/.graalvm
PATH=~/.graalvm/bin:~/.graalvm/languages/js/bin:~/.graalvm/languages/js/lib/node_modules/bin
npm set prefix ~/.graalvm/languages/js/lib/node_modules
``` 
