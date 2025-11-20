# EBS Encryption

- Encrypted EBS volumes provide the following
  - Data at rest is encrypted inside the volume
  - All the data in flight moving between the instance and the volume is encrypted
  - All snapshots are encrypted
  - All volumes are created from the snapshot
- Encryption and decryption are handled transparently
- Encryption has minimal impact on latency
- EBS encryption leverages KMS keys (AES-256)
- Copying an unencrypted snapshot allows encryption
- Snapshots of encrypted volumes are encrypted
  