# azblob-download-artifact
Hyperskill GitHub Action | Azure blob download artifact

```yaml
- uses: hyperskill/azblob-download-artifact@v1.0.1
  with:
    connection_string: ${{ secrets.AZURE_STORAGE_CONNECTION_STRING }}
    name: frontend-dist
    path: dist
```

For uploading, use https://github.com/marketplace/actions/azure-blob-upload-artifacts
