FROM jenkins/jenkins

ADD plugins.txt /usr/share/jenkins/ref/plugins.txt

RUN echo 2.0 > /usr/share/jenkins/ref/jenkins.install.UpgradeWizard.state
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt
