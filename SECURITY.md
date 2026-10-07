# Security Policy

This repository is a reference implementation of the BHDR regression kernel. It is research code, not a certified cryptographic product.

## Reporting

Report a vulnerability privately through GitHub: open the **Security** tab of this repository and choose **Report a vulnerability**. Please do not open a public issue.

Please include the affected version or commit, a minimal reproduction if you have one, and the expected and observed behaviour.

## Scope

In scope: incorrect results from the kernel, unsafe handling of inputs, and plaintext leakage beyond the trust model described in the README.

Out of scope: weaknesses in the underlying CKKS library or in parameters you chose.
