# onedrive-link
Generate direct download links for OneDrive

Enter `npx onedrive-link` followed by your OneDrive sharing link. The tool will spit out a direct download link that can be used with `curl`, `wget`, or any other tool that expects a "direct" download link.

```
npx onedrive-link https://1drv.ms/u/s!AkfaA...
```

Based on https://docs.microsoft.com/en-us/graph/api/shares-get?view=graph-rest-1.0&tabs=http#encoding-sharing-urls.

This tool is tiny and has no dependencies - and could probably just be a bash or ps1 script. But this is quick and doesn't require any installation.

## License
MIT
