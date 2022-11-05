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
| `latest` | `sha256:2fc589367f725da8378a3cbfeab6a967baee929fdf6c7c234f6c10ed406232a6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:2fc589367f725da8378a3cbfeab6a967baee929fdf6c7c234f6c10ed406232a6) |  |



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
        "docker-manifest-digest": "sha256:2fc589367f725da8378a3cbfeab6a967baee929fdf6c7c234f6c10ed406232a6"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "9c8a411300f622b11e4a3ec8ba27a0b90d05acfd",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/jdk",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIBiLbvIA7i1J9MThfkR11FbjNk88TYGG8zjjukV7O12iAiBdCaIfJMMvOGf6zqK9Udv8i4L3au27usQv48baK6hxlg==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIzMzk5YWMyNzdhYzE4MDY3MzRiOTlhMTYzMTI3YmQxNDU4ZjIzMTg5MjRiOTZlYjNiZWJlYzQ0YmY0NTRhNzgzIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQlJNY2RUUm1GT1pocGlKUjhwdVVXMjc0bWdTNnFwSTUwL3dpRmxnQ0hzNEFpRUFpc21NWXZEa2hiUC84VURiRUVNLzJDR1NwYk5UVFNXVWRMOE5GdmV1M1ZrPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUndha05EUVhsMVowRjNTVUpCWjBsVlQwTnNNMGhYY1VWQ1ltWm5NV0pyUTNKUVExVjVlbWxhVDNnMGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVUVRCTlJFbDNUVlJOTkZkb1kwNU5ha2w0VFZSQk1FMUVTWGhOVkUwMFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ4ZEZKQmRtcE5NbVpFVVZSallVRkNhMFZXYWpsc2VYaHlWVnBtU0VKVFJ6Uk5MM1lLYWtaalZreEhUelI2VDJocFdtbE1XRFZsT0U1RFVVSk1kVE4xVFVSUlJVVlhXRTU0UVZjNU1Va3pjSGhaYmtvM1RFdFBRMEZyYjNkblowcEhUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZVTlhWc0NtbFRaSFJFTVRJelUydFFTRmRvUTI1RGFXbHBiWGh6ZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDFwUldVUldVakJTUVZGSUwwSkdjM2RYV1ZwWVlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5Y0d0aGVUaDFXakpzTUdGSVZtbE1NMlIyWTIxMGJXSkhPVE5qZVRsNVdsZDRiRmxZVG14TWJteG9ZbGQ0UVdOdFZtMWplVGx2Q2xwWFJtdGplVGwwV1Zkc2RVMUVhMGREYVhOSFFWRlJRbWMzT0hkQlVVVkZTekpvTUdSSVFucFBhVGgyWkVjNWNscFhOSFZaVjA0d1lWYzVkV041Tlc0S1lWaFNiMlJYU2pGak1sWjVXVEk1ZFdSSFZuVmtRelZxWWpJd2QwWm5XVXRMZDFsQ1FrRkhSSFo2UVVKQloxRkpZekpPYjFwWFVqRmlSMVYzVG1kWlN3cExkMWxDUWtGSFJIWjZRVUpCZDFGdlQxZE5ORmxVVVhoTlZFMTNUVWRaTWsxcVNtbE5WRVpzVGtkRmVscFhUVFJaYlVWNVRqSkZkMWxxYTNkYVJFRXhDbGxYVG0xYVJFRmpRbWR2Y2tKblJVVkJXVTh2VFVGRlJVSkJOVVJqYlZab1pFZFZaMVZ0Vm5OYVYwWjZXbFJCYWtKbmIzSkNaMFZGUVZsUEwwMUJSVVlLUWtKV2FtRkhSbkJpYldReFdWaEthMHhYYkhSWlYyUnNZM2s1Y1ZwSGMzZElVVmxMUzNkWlFrSkJSMFIyZWtGQ1FtZFJVR050Vm0xamVUbHZXbGRHYXdwamVUbDBXVmRzZFUxSlIwdENaMjl5UW1kRlJVRmtXalZCWjFGRFFraDNSV1ZuUWpSQlNGbEJNMVF3ZDJGellraEZWRXBxUjFJMFkyMVhZek5CY1VwTENsaHlhbVZRU3pNdmFEUndlV2RET0hBM2J6UkJRVUZIUlZGR09WQk5aMEZCUWtGTlFWSjZRa1pCYVVGemFqSXdUWEVyZVZsUE5rRkZlRGx2UVhST1RrRUtSM0JLU0doVWVtNUthM0U0YlRsb2RqRm5TV2hGUVVsb1FVMVhTR015UVdGSGNXTkpieTlvZVVwNkswaDJPVlJETWk5RFVYbHZVRkI0T1V4QmJIUlhlUXBRTWxGMVRVRnZSME5EY1VkVFRUUTVRa0ZOUkVFeWEwRk5SMWxEVFZGRE1EUnBTMjVyTjA1SWFGSjFTVTVuTUZkWFdFaGFZamxuSzFSS2FERXJURUZoQ21oRlpDOVpVMHhHVjI5TVpXeE1kRFpaU0RkWlUydHRUVTUzWVZoVmVIZERUVkZEY1drMWJscDZRbWxCUWxwSFVUVmlabWg1V1NzeVluQjRXWGd3YkZJS1ZXUlZjRkJETVVsbk1sUXpkMnBuZFZvMGNIQkJVblJDV2paTVVuUnZZazEwYlc4OUNpMHRMUzB0UlU1RUlFTkZVbFJKUmtsRFFWUkZMUzB0TFMwSyJ9fX19",
          "integratedTime": 1667527300,
          "logIndex": 6461037,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/jdk/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/jdk",
      "githubWorkflowSha": "9c8a411300f622b11e4a3ec8ba27a0b90d05acfd",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3390671667",
      "sha": "9c8a411300f622b11e4a3ec8ba27a0b90d05acfd"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [melange](https://github.com/chainguard-dev/melange) and [apko](https://github.com/chainguard-dev/apko).

