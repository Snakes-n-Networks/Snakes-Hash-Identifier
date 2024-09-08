# Snakes Hash Identifier

Snakes Hash Identifier is a software tool designed to identify different types of hashes used to encrypt data, especially passwords. This tool supports a wide variety of encryption formats, making it a versatile choice for security professionals, developers, and anyone dealing with encrypted data.

## Features

- **Wide Range of Supported Hashes**: The tool can identify numerous hash formats, including common ones like MD5, SHA-1, and SHA-256, as well as less common ones like GOST R 34.11-94 and Whirlpool.
- **User-Centric Efficiency**: Some encryption algorithms may not be distinguishable unless decrypted. The tool's efficiency can be influenced by the user's understanding and criteria.

## Supported Hash Formats

Snakes Hash Identifier can identify the following encryption formats:

- **Checksum Algorithms**: 
  - ADLER-32
  - CRC-32, CRC-32B, CRC-16, CRC-16-CCITT
  - FCS-16
  - XOR-32

- **Unix-based Hashes**:
  - DES(Unix)
  - MD5(Unix)
  - MD5(APR)

- **Common Hashing Algorithms**:
  - MD2, MD4, MD5
  - NTLM
  - RipeMD-128, RipeMD-160, RipeMD-256, RipeMD-320
  - SHA-1, SHA-224, SHA-256, SHA-384, SHA-512
  - Whirlpool

- **Complex Hashes**:
  - GHash-32-3, GHash-32-5
  - Haval-128, Haval-160, Haval-192, Haval-224, Haval-256
  - SNEFRU-128, SNEFRU-256
  - Tiger-128, Tiger-160, Tiger-192
  - GOST R 34.11-94

- **Password Hashes**:
  - MySQL, MySQL5 - SHA-1(SHA-1($pass)), MySQL 160bit - SHA-1(SHA-1($pass))
  - MD5(phpBB3), MD5(Wordpress), MD5(Half), MD5(Middle)
  - SHA-1(MaNGOS)
  - MD5(HMAC(Wordpress))
  - SAM - (LM_hash:NT_hash)
  - RAdmin v2.x
  - Lineage II C4
  - Domain Cached Credentials
  - Joomla (md5($pass.$salt))
  - Django (SHA-1, SHA-256, SHA-384)

- **Other Formats**:
  - And more…

## Usage

Simply input the hash, and the tool will identify the most likely algorithm used to create it. Note that the tool may not differentiate between certain algorithms unless additional information or decryption is provided.

## Installation

To install Snakes Hash Identifier, clone the repository and run the following command:

```bash
git clone <https://github.com/Snakes-n-Networks/Snakes-Hash-Identifier.git>
```
```bash
cd snakes-hash-identifier
```
```bash
python3 snakes-hash-identifier.py
```
## Contributing

Contributions are welcome! Please open an issue to discuss what you would like to contribute.

## License

This project is licensed under the Mozilla Public License Version 2.0
 - see the LICENSE file for details.

Contact

For more information or questions, feel free to reach out at [SnakesNnetworks@gmail.com].