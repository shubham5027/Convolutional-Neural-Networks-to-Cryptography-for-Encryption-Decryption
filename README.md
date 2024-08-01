
---

# Neural Cryptography: Encryption and Decryption Using Convolutional Neural Networks

## Project Summary

With the advent of Artificial Intelligence and Internet of Things (IoT) devices, the demand for more innovative methods of preserving cybersecurity is growing. The prospect of utilizing neural networks (convolutional neural networks) for cryptography is relatively new. Recent attempts have aimed to use neural networks for cryptanalysis with varying results. This project explores how neural networks can be used and tuned for cryptographic operations, including encryption, decryption, signing, and verification.

By encompassing the CIA (Confidentiality, Integrity, and Availability) triad, this project demonstrates an efficient neural cryptography algorithm (NCA) through tuning and implementation via socket communication. NCA is dynamically self-configurable, resulting in a robust yet inconsistent algorithm, although low error rates can be achieved multiple times with neural networks.

The project also includes the development of a signature/verification capability based on the hidden states of the neural networks, which has not been accomplished before. The presented code serves as a foundation for further research and improvements to neural cryptography. Once fully developed, the cipher will autonomously restore the confidentiality of the system when compromised. There are numerous opportunities for NCA, including secure communication between autonomous IoT devices and its potential use in Artificial Intelligence due to its dynamically self-configurable nature and efficient functioning in massively parallel processing environments.

## Running the Code

To run this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/shubham5027/Convolutional-Neural-Networks-to-Cryptography-for-Encryption-Decryption/tree/main.git
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook to see the implementation and results:
    ```bash
    jupyter notebook Encrypt-Decrypt.ipynb
    ```

## Performance Results

### Encryption and Decryption Timing

#### Neural Cryptography Algorithm (NCA)
- **Scenario 1**
  - Time taken for Alice to Encrypt the Plain Text: 0.019057750701904297 seconds
  - Time taken for Bob to Decrypt the Cipher Text: 0.016915321350097656 seconds

- **Scenario 2**
  - Time taken for Alice to Encrypt the Plain Text: 0.022756576538085938 seconds
  - Time taken for Bob to Decrypt the Cipher Text: 0.015015840530395508 seconds

- **Scenario 3**
  - Time taken for Alice to Encrypt the Plain Text: 0.023770809173583984 seconds
  - Time taken for Bob to Decrypt the Cipher Text: 0.010978460311889648 seconds

#### Fernet (SHA256)
- **Scenario 1**
  - Time taken for Fernet to Encrypt the Plain Text: 0.0006625652313232422 seconds
  - Time taken for Fernet to Decrypt the Cipher Text: 0.00032639503479003906 seconds

- **Scenario 2**
  - Time taken for Fernet to Encrypt the Plain Text: 0.0011723041534423828 seconds
  - Time taken for Fernet to Decrypt the Cipher Text: 0.0004074573516845703 seconds

- **Scenario 3**
  - Time taken for Fernet to Encrypt the Plain Text: 0.0004811286926269531 seconds
  - Time taken for Fernet to Decrypt the Cipher Text: 0.0001995563507080078 seconds

### Signing and Verification Timing

#### Neural Cryptography Algorithm (NCA)
- **Scenario 1**
  - Time taken for Alice to Sign the Plain Text: 0.015861988067626953 seconds

- **Scenario 2**
  - Time taken for Alice to Sign the Plain Text: 0.01784682273864746 seconds

#### Fernet (SHA256)
- **Scenario 1**
  - Time taken for Fernet to Sign the Plain Text: 0.0002117156982421875 seconds

- **Scenario 2**
  - Time taken for Fernet to Sign the Plain Text: 0.0001609325408935547 seconds

## References

- Abadi, M & Andersen, D. Learning to Protect Communications with Adversarial Neural Cryptography. October 24 2016. Google Brain.
- Adversarial Neural Cryptography in Theano. [Adversarial Neural Cryptography in Theano](https://nlml.github.io/neural-networks/adversarialneural-cryptography/)
- Adversarial Neural Cryptography in TensorFlow. [Adversarial Neural Cryptography in TensorFlow](https://github.com/ankeshanand/neuralcryptography-tensorflow)
- Fernet (symmetric encryption). [Fernet Documentation](https://cryptography.io/en/latest/fernet/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

This README provides a comprehensive overview of the project, including its purpose, installation instructions, usage, performance results, and references. Feel free to adjust any sections as needed.
