# ElevateCraft Static App

## Capability

ElevateCraft Static App is a serverless cloud platform designed to store all your data securely and efficiently. It leverages the power of Azure Static Web Apps to provide a seamless and scalable solution for your data storage needs.

## Security

Security is a top priority for ElevateCraft Static App. We implement various security measures to ensure your data is protected at all times. This includes encryption, access controls, and regular security audits.

## Generating an SSL/TLS Certificate

To secure your app with SSL/TLS, follow these steps:

1. **Generate a private key and a certificate signing request (CSR):**
   ```sh
   openssl req -new -newkey rsa:2048 -nodes -keyout yourdomain.key -out yourdomain.csr
   ```

2. **Submit the CSR to a Certificate Authority (CA):**
   Choose a trusted CA and follow their instructions to submit your CSR and obtain an SSL/TLS certificate.

3. **Install the SSL/TLS certificate:**
   Once you receive the certificate from the CA, install it on your web server. The installation process may vary depending on your server software.

4. **Configure your web server to use the SSL/TLS certificate:**
   Update your server configuration to use the newly installed certificate. Refer to your server's documentation for specific instructions.

## Further Reading

For more information on SSL/TLS certificates, you can refer to the following resource:
[SSL/TLS Certificates Explained](https://www.ssl.com/faqs/what-is-an-ssl-tls-certificate/)
