# jdk

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/tuananh/jdk/actions/workflows/release.yaml/badge.svg)](https://github.com/tuananh/jdk/actions/workflows/release.yaml)

WORK IN PROGRESS

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/jdk:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `openjdk-jre-17` `openjdk-jre-17-20221109` `openjdk-jre-17.0` `openjdk-jre-17.0.5` `openjdk-jre-17.0.5.8` `openjdk-jre-17.0.5.8-r0` | `sha256:35f2836f1afa57fa1064e481d2e10e14c756b98a7a54a37cfdf138ebc564342b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:35f2836f1afa57fa1064e481d2e10e14c756b98a7a54a37cfdf138ebc564342b) | `amd64` |
| `openjdk-jre-11` `openjdk-jre-11-20221109` `openjdk-jre-11.0` `openjdk-jre-11.0.17` `openjdk-jre-11.0.17.8` `openjdk-jre-11.0.17.8-r0` | `sha256:3805ce10c4eae441ff9a27542dd182477256bc18f537698e5551a18684b5b411`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:3805ce10c4eae441ff9a27542dd182477256bc18f537698e5551a18684b5b411) | `amd64` |
| `openjdk-11` `openjdk-11-20221109` `openjdk-11.0` `openjdk-11.0.17` `openjdk-11.0.17.8` `openjdk-11.0.17.8-r0` | `sha256:01ab33f239cb9bab311ba4fe63b1f85864de6dd6d0b3119ea7d5ec638a1e4e5a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:01ab33f239cb9bab311ba4fe63b1f85864de6dd6d0b3119ea7d5ec638a1e4e5a) | `amd64` |
| `latest` `openjdk-17` `openjdk-17-20221109` `openjdk-17.0` `openjdk-17.0.5` `openjdk-17.0.5.8` `openjdk-17.0.5.8-r0` | `sha256:ad0036b87381b5a8a91f92be081b5b1a0027f88f52f87664a82b1820c29fe564`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ad0036b87381b5a8a91f92be081b5b1a0027f88f52f87664a82b1820c29fe564) | `amd64` |



## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/jdk:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/jdk:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/jdk"
      },
      "image": {
        "docker-manifest-digest": "sha256:ad0036b87381b5a8a91f92be081b5b1a0027f88f52f87664a82b1820c29fe564"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "21beac0be1210b2457f892b689ccbbf5a996972c",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQCNg/gHJL19yArtcl8cg2JrJb9n2VAGuILRmTNGKAayZgIhAMfR4a6FZCtYEkNFoIqliI1Y17oAJQ2UnoV6L+eoNQVm",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI3Mjg2MWY0YTc1NzczMzgyMjI0ZjExYjI1MDYwZTgyNzRhODcxMTUwZTcwZjhkZGQ3NmZiMGU2YmFmMDJjMjYzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJRGpDNHBLT3FaYkE5OS81MUVnYnZCZGVtbVpHSXg4THJ3U1RzZXRlZ0puSUFpRUExMHFGblVweXJid0IyQUlxcmxDalhESFdkb2hlOFJWVWlzelhnK0lUTExBPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjBha05EUVhwNVowRjNTVUpCWjBsVlRrRlJWblF3TVc5MmFpOXBSRzAxUld4YVpYRm5ORzVSUVRGUmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRWTmFrbDNUWHBCZVZkb1kwNU5ha2w0VFZSQk5VMXFTWGhOZWtGNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYyWjFjM2EwTXlTVmxaWW1GdVlsSnZObXgxZFUweVVVNXplRE53ZUVFMlNWbHpMM1lLYWxWYWJIQkVWMFo1VUZaamMyczNUV2hTY2xjMlEzTlpTSEZWYzBFNE1tWnRRalZDVVVrMU1UVlJVV292WTNSa2FXRlBRMEZzYzNkblowcFlUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZLWlM5SUNsZHdTR2R4T1d4dE1sbzFXWGhOTDFJMFRqQk9RVXh2ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRGWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSUldOSVZucGhSRUV5UW1kdmNncENaMFZGUVZsUEwwMUJSVVJDUTJkNVRWZEtiRmxYVFhkWmJWVjRUV3BGZDFscVNUQk9WR1J0VDBScmVWbHFXVFJQVjA1cVdXMUtiVTVYUlRWUFZGazFDazU2U21wTlEzZEhRMmx6UjBGUlVVSm5OemgzUVZGUlJVaHBOVzVoV0ZKdlpGZEpkbVF5T1hsaE1scHpZak5rZWt3elNteGlSMVpvWXpKVmRXVlhSblFLWWtSQmJVSm5iM0pDWjBWRlFWbFBMMDFCUlVaQ1FtaHFZVWRHY0dKdFpERlpXRXByVEZkc2RGbFhaR3hqZVRsd1lsZEdibHBZVFhkSVVWbExTM2RaUWdwQ1FVZEVkbnBCUWtKblVWQmpiVlp0WTNrNWIxcFhSbXRqZVRsMFdWZHNkVTFKUjBwQ1oyOXlRbWRGUlVGa1dqVkJaMUZEUWtoelJXVlJRak5CU0ZWQkNqTlVNSGRoYzJKSVJWUktha2RTTkdOdFYyTXpRWEZLUzFoeWFtVlFTek12YURSd2VXZERPSEEzYnpSQlFVRkhSVmh0YzBZeWQwRkJRa0ZOUVZKcVFrVUtRV2xDUW1oeVdqbERWQ3Q1T0RSWU5qVk9SV05USzJSR1ltdHpMMjk1WVZSWFIwb3dXRzFYYTI5V2VIbHVaMGxuU1RaUk1HTTJUemhFTjJkM2IwdFhNd3BsUVd4VlNuTjJhR2RrZVdoQlQyMXliMk5OYkVKdk5FMWlTWE4zUTJkWlNVdHZXa2w2YWpCRlFYZE5SR0ZCUVhkYVVVbDRRVTlNTlVaaU9WaDFOVWN5Q25waWRsaFpOR2N4TWtJM1ZucHRla0ZqYm5kSVFVOTBSMDVCWmpsU0wyMDFjRVJ2WVM4NVRUVkxaMHB5Wm1WTlJqazJXVFZLUVVsM1dXRXlNekI1U0dZS1RGTXpiRU5sYTJ4bFpYbDJWazh6ZHpGbFN6ZFBjbmR6S3pOd1MyOVVZM1pHUVVGS1ZuSlJNazlTWTJWclJHVlBjRWt4V0dacWJFRUtMUzB0TFMxRlRrUWdRMFZTVkVsR1NVTkJWRVV0TFMwdExRbz0ifX19fQ==",
          "integratedTime": 1668031389,
          "logIndex": 6799132,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "21beac0be1210b2457f892b689ccbbf5a996972c",
      "githubWorkflowTrigger": "push",
      "run_attempt": "2",
      "run_id": "3432132972",
      "sha": "21beac0be1210b2457f892b689ccbbf5a996972c"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [melange](https://github.com/chainguard-dev/melange) and [apko](https://github.com/chainguard-dev/apko).

