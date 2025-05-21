FROM ollama/ollama:latest

# Add the downloaded CA cert
COPY registry-ollama.crt /usr/local/share/ca-certificates/

# Update CA trust store
RUN update-ca-certificates
