# graalvm-stack
Custom GraalVM Distribution for use in Direktspeed Projects

## Update 15.04.2021 
https://github.com/graalvm/graalvm-ce-dev-builds/releases now has a java16 build!


## Installation
i think in lib/node_modules/bin should be nothing but who knows
``` 
export GRAALVM_HOME=~/.graalvm
export NPM_HOME=$GRAALVM_HOME/languages/js
export JAVA_HOME=$GRAALVM_HOME
export PATH=$GRAALVM_HOME/bin:$GRAALVM_HOME/languages/js/bin:$NODE_HOME/lib/node_modules/bin
mkdir $GRAALVM_HOME && cd $GRAALVM_HOME
curl -s -L https://github.com/graalvm/graalvm-ce-dev-builds/releases/download/21.0.0-dev-20201204_0332/graalvm-ce-java11-linux-amd64-dev.tar.gz | tar zxf - --strip 1 -C $GRAALVM_HOME
npm set prefix $NPM_HOME
``` 
