FROM java:8-jdk

ENV SBT_VERSION 1.2.8
RUN wget https://github.com/sbt/sbt/releases/download/v${SBT_VERSION}/sbt-${SBT_VERSION}.tgz ; \
    tar -xzf sbt-${SBT_VERSION}.tgz ; \
    rm -rf sbt-${SBT_VERSION}.tgz ; \
    mv sbt /opt ; \
    ln -sf /opt/sbt/bin/sbt /usr/bin/



