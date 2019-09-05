FROM kencho214/ansible:1.0.0

# Install IBM Cloud CLI
RUN curl -fsSL https://clis.cloud.ibm.com/install/linux | sh

# Install IBM Cloud CLI Plugins
RUN ibmcloud plugin install cloud-object-storage && \
  ibmcloud plugin install container-registry && \
  ibmcloud plugin install container-service

CMD ["/bin/bash"]
