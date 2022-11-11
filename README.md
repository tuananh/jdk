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
| `openjdk-11` `openjdk-11-20221110` `openjdk-11.0` `openjdk-11.0.17` `openjdk-11.0.17.8` `openjdk-11.0.17.8-r0` | `sha256:9fa1477171b186efdaa27345de2397bc3e8cfd5eee9b08b5c3dd08ec4bc54281`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:9fa1477171b186efdaa27345de2397bc3e8cfd5eee9b08b5c3dd08ec4bc54281) | `amd64` |
| `openjdk-17-20221109` | `sha256:ad0036b87381b5a8a91f92be081b5b1a0027f88f52f87664a82b1820c29fe564`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ad0036b87381b5a8a91f92be081b5b1a0027f88f52f87664a82b1820c29fe564) | `amd64` |
| `latest` `openjdk-17` `openjdk-17-20221110` `openjdk-17.0` `openjdk-17.0.5` `openjdk-17.0.5.8` `openjdk-17.0.5.8-r0` | `sha256:66a1fe47c510762ad8c0e9abedd54c6b19eafd7741817598e4f67d988fb59566`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:66a1fe47c510762ad8c0e9abedd54c6b19eafd7741817598e4f67d988fb59566) | `amd64` |
| `openjdk-jre-17-20221109` | `sha256:35f2836f1afa57fa1064e481d2e10e14c756b98a7a54a37cfdf138ebc564342b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:35f2836f1afa57fa1064e481d2e10e14c756b98a7a54a37cfdf138ebc564342b) | `amd64` |
| `openjdk-jre-11-20221109` | `sha256:3805ce10c4eae441ff9a27542dd182477256bc18f537698e5551a18684b5b411`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:3805ce10c4eae441ff9a27542dd182477256bc18f537698e5551a18684b5b411) | `amd64` |
| `openjdk-jre-17` `openjdk-jre-17-20221110` `openjdk-jre-17.0` `openjdk-jre-17.0.5` `openjdk-jre-17.0.5.8` `openjdk-jre-17.0.5.8-r0` | `sha256:3d2094ad4733cb2c5b828f2185e0391d3f8dacc82d1620a3a364aef14658cd90`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:3d2094ad4733cb2c5b828f2185e0391d3f8dacc82d1620a3a364aef14658cd90) | `amd64` |
| `openjdk-jre-11` `openjdk-jre-11-20221110` `openjdk-jre-11.0` `openjdk-jre-11.0.17` `openjdk-jre-11.0.17.8` `openjdk-jre-11.0.17.8-r0` | `sha256:04fcbc390c8b4a3d28d6d52fd2feab3bcfb4ebf520a0e7aeb80ab8332927d3ce`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:04fcbc390c8b4a3d28d6d52fd2feab3bcfb4ebf520a0e7aeb80ab8332927d3ce) | `amd64` |
| `openjdk-11-20221109` | `sha256:01ab33f239cb9bab311ba4fe63b1f85864de6dd6d0b3119ea7d5ec638a1e4e5a`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:01ab33f239cb9bab311ba4fe63b1f85864de6dd6d0b3119ea7d5ec638a1e4e5a) | `amd64` |



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
        "docker-manifest-digest": "sha256:66a1fe47c510762ad8c0e9abedd54c6b19eafd7741817598e4f67d988fb59566"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "7b946d77172d85c953e099c48c494bdc90f0ce8a",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIA/vnp8DqquCEuSPxcEo4hlXAupe/EguVpoabnVFYWa5AiA87OkhVT54+fbdPyF/QEzAVaU8uEisnydu7kkNdjFQ+A==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIwNTBjOWMxOGNlZmYxNGNhNjk3YjZhZjVkZmE4NWZlMTJkODNmZDc5OTE4MWQ3ZGU3NmVlMWU2N2U5NzYzMTYwIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUNneG9yeWZDVkd4eEtwZWtzdHB6QVYvbEM0ZmtITlptT0gwYmQ2OXJ3RGNRSWdFTnY4NWRJam96d0Z5Zk5IdVJReWRjaHZCMU11RWw4djY5R1BOZ2JheC93PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjBla05EUVhveVowRjNTVUpCWjBsVlpURk1RbHBsYkU5bWRVOUdkR3d6ZVRsd1NuRnVkMVV3UkZobmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUlhkTlZHTXhUMVJOTWxkb1kwNU5ha2w0VFZSRmQwMVVaM2RQVkUweVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZoUkNzclIzTTFlVnAzZHpkYWFuSnhkVGh1UTNwU2RreE9VRFo0WWtwVk0wOVpSellLY1VOaU1qUlFOWEJDTm5SQlJrUndTR1IwTmxwdVNrVlFWM1ZqZW1GcFkxcDRTamRKZHpsUmFXVm1LMnRSYTNVNGJuRlBRMEZzZDNkblowcFpUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZCU0hSc0NsbzRWV2sxTUdSMEt6a3pSVmh1YzJveVdGTlRRakV3ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRGWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSUldOSVZucGhSRUV5UW1kdmNncENaMFZGUVZsUEwwMUJSVVJDUTJjeldXcHJNRTV0VVROT2VrVXpUVzFSTkU1WFRUVk9WRTVzVFVSck5WbDZVVFJaZWxFMVRrZEthMWw2YTNkYWFrSnFDbHBVYUdoTlEzZEhRMmx6UjBGUlVVSm5OemgzUVZGUlJVaHBOVzVoV0ZKdlpGZEpkbVF5T1hsaE1scHpZak5rZWt3elNteGlSMVpvWXpKVmRXVlhSblFLWWtSQmJVSm5iM0pDWjBWRlFWbFBMMDFCUlVaQ1FtaHFZVWRHY0dKdFpERlpXRXByVEZkc2RGbFhaR3hqZVRsd1lsZEdibHBZVFhkSVVWbExTM2RaUWdwQ1FVZEVkbnBCUWtKblVWQmpiVlp0WTNrNWIxcFhSbXRqZVRsMFdWZHNkVTFKUjB0Q1oyOXlRbWRGUlVGa1dqVkJaMUZEUWtoM1JXVm5RalJCU0ZsQkNqTlVNSGRoYzJKSVJWUktha2RTTkdOdFYyTXpRWEZLUzFoeWFtVlFTek12YURSd2VXZERPSEEzYnpSQlFVRkhSVmx5UzBObFFVRkJRa0ZOUVZKNlFrWUtRV2xGUVRodUwwbFdWMkZaU1VsSFlWRnJPRU4yYlU1VFUyRkJWVXRYUVV0NVFUSnFjbmh5WVdoaE1VZE9WRzlEU1VWME1WSnRNMVpsYzI0MWRXcE9XZ3ByYzNwemN6WXlaV2cwU0RGbWFVRnRiM05WZWtwQmJHNHpaSGxoVFVGdlIwTkRjVWRUVFRRNVFrRk5SRUV5WjBGTlIxVkRUVkZFT0VONlUyUmtibnBPQ2todk5FcFFZM1JWSzJkcFlVdFJSMDFhTDNBck5qRnpUR1pZV1dKcVUxcHZSVll6TkhNMlRsQnpNR0ZQVDNKQmIzbEJPVWRvYlhORFRVVklhMjVrZEZBS1YxbFplRmx1Y2pGbk0zQkxOVnB3WVhWSVdVRnFjbUZMVWtNdmJuaEdjbk12YUV4Q1prOHhReTkzUkVRMmJHOVVSVWhLWjJGUlUwRXZRVDA5Q2kwdExTMHRSVTVFSUVORlVsUkpSa2xEUVZSRkxTMHRMUzBLIn19fX0=",
          "integratedTime": 1668103181,
          "logIndex": 6835531,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "7b946d77172d85c953e099c48c494bdc90f0ce8a",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3439220404",
      "sha": "7b946d77172d85c953e099c48c494bdc90f0ce8a"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [melange](https://github.com/chainguard-dev/melange) and [apko](https://github.com/chainguard-dev/apko).

