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
| `latest` | `sha256:4533d23dad8315cf7c1fba54d337b5bed793f3458561efac8b20fe4244d94f9e`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:4533d23dad8315cf7c1fba54d337b5bed793f3458561efac8b20fe4244d94f9e) |  |



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
        "docker-manifest-digest": "sha256:4533d23dad8315cf7c1fba54d337b5bed793f3458561efac8b20fe4244d94f9e"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "dc0d67968647cf4d64f381f2b46583de7883e519",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/jdk",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIHvLyB/RH8ATRT8OUcuq0dmvpogn4un5IrqsPTCadb3mAiAdOk+W/0yuS/WirfS7swWwZdJMMERcfcR3pddztrEDlQ==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI1YmEwZTkyZjExNmVjOWVkMGJmNTZkZmE2MGJlNTRhNzBmNWI2NzFlMDEyOGY3ZTJiZjk3M2YwYTRhYmE3MGYyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUMybFoyNzgwOFR5eENLVml4cUpJZk01MEhldVNFRXRoWU5odlp1dXpmYnFnSWhBTW45QUxqaUVweVFUamozUDY1N2lIRitzSGtvQklrSEFzRzJCcTlHSDdzUiIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUndha05EUVhsMVowRjNTVUpCWjBsVlVHMWFVRFlyZUZSTE1USjVUVWg2YzNWQldVRkdRbE5KYWpCdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1hoTlJFbDRUVlJOTlZkb1kwNU5ha2w0VFVSSmVFMUVTWGxOVkUwMVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZPVTJjMFJtMDJaMnhMWTNsWFFtTmFZbXBZVVZWeWNHTndkM2x3U3psWWRVazVTVEVLUVdGcVdYVXJiMnBPTDNZd1JHVm1LelJsVG1KVWNFeDZjamR2ZFRkTlMyTkNhMlZIZVRZMWIwdE1UUzlNTUhScmRUWlBRMEZyYjNkblowcEhUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlYwZUdOMUNtRnFUalZTYWxRMmJqVnBWbFJXWkZscGFHZGllWGc0ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDFwUldVUldVakJTUVZGSUwwSkdjM2RYV1ZwWVlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5Y0d0aGVUaDFXakpzTUdGSVZtbE1NMlIyWTIxMGJXSkhPVE5qZVRsNVdsZDRiRmxZVG14TWJteG9ZbGQ0UVdOdFZtMWplVGx2Q2xwWFJtdGplVGwwV1Zkc2RVMUVhMGREYVhOSFFWRlJRbWMzT0hkQlVVVkZTekpvTUdSSVFucFBhVGgyWkVjNWNscFhOSFZaVjA0d1lWYzVkV041Tlc0S1lWaFNiMlJYU2pGak1sWjVXVEk1ZFdSSFZuVmtRelZxWWpJd2QwWm5XVXRMZDFsQ1FrRkhSSFo2UVVKQloxRkpZekpPYjFwWFVqRmlSMVYzVG1kWlN3cExkMWxDUWtGSFJIWjZRVUpCZDFGdldrZE5kMXBFV1ROUFZGazBUbXBSTTFreVdUQmFSRmt3V21wTk5FMVhXWGxaYWxFeVRsUm5lbHBIVlROUFJHZDZDbHBVVlhoUFZFRmpRbWR2Y2tKblJVVkJXVTh2VFVGRlJVSkJOVVJqYlZab1pFZFZaMVZ0Vm5OYVYwWjZXbFJCYWtKbmIzSkNaMFZGUVZsUEwwMUJSVVlLUWtKV2FtRkhSbkJpYldReFdWaEthMHhYYkhSWlYyUnNZM2s1Y1ZwSGMzZElVVmxMUzNkWlFrSkJSMFIyZWtGQ1FtZFJVR050Vm0xamVUbHZXbGRHYXdwamVUbDBXVmRzZFUxSlIwdENaMjl5UW1kRlJVRmtXalZCWjFGRFFraDNSV1ZuUWpSQlNGbEJRMGREVXpoRGFGTXZNbWhHTUdSR2NrbzBVMk5TVjJOWkNuSkNXVGwzZW1wVFltVmhPRWxuV1RKaU0wbEJRVUZIUkN0Rk9YcEZaMEZCUWtGTlFWSjZRa1pCYVVWQlowNXhjVWxTT0ZsdWIyeG1UeXRLZDFkTlVYQUthREZaVDJVNE1GbFdSalZvTVdaU09WSnFlR1l2T0c5RFNVVXZaRTAwUW5aaVJURmhjalJSVDFSc09XSlFiREJSVkdGWksya3ZUbkEwWkZaUk4wZFJhQXAxV2xsWFRVRnZSME5EY1VkVFRUUTVRa0ZOUkVFeWEwRk5SMWxEVFZGRVQyeFNUVFJ2VlZKWmFuSjZibVZ1T1haNVNWWnZOV2xoVTBkWE5YYzVZVEoxQ2xaalowZFVVVFZLU0hwRVNHRlBXVzh3WjJkdU1YZEJiRlV4ZDBKVlNrRkRUVkZFTDJ4Mk9XeDRNbFZZVkRGUGVVTjZjM0Y0ZDBSeWEzaE1ZWFZVT1NzS2JtRjJOWFJITWxSallWaENVbVJUWVVkM2VscG5LM2RxYm01ME1qQnBXalI2VnpROUNpMHRMUzB0UlU1RUlFTkZVbFJKUmtsRFFWUkZMUzB0TFMwSyJ9fX19",
          "integratedTime": 1666318300,
          "logIndex": 5532732,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/jdk/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/jdk",
      "githubWorkflowSha": "dc0d67968647cf4d64f381f2b46583de7883e519",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3294225364",
      "sha": "dc0d67968647cf4d64f381f2b46583de7883e519"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [melange](https://github.com/chainguard-dev/melange) and [apko](https://github.com/chainguard-dev/apko).

