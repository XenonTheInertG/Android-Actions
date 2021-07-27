# sGSIbot

Don't run the package directly in this warehouse, please fork this warehouse to run the package and then go to your own GitHub and run again!
Don't build directly in this warehouse, please fork this warehouse first, and then go to your own warehouse to build!

## Instructions:

1. Fork this warehouse
2. Edit SGSI_Build.yml:
     ROM_URL: link for your download
     ZIP_NAME: The name of the package downloaded for you
     OS_TYPE: The type of rom you want to run
     BUILD_TYPE: The type you need to build (ab|a-only)
     REPACK_NAME: The name of the package you need to pack
3. After modification, click Start commit -> Actions tab -> Star -> SGSI-Build

 
## Output result
If upload rom to Release download, please modify yml upload_action-gh-release:'false' ->'true'
After each successful build, the mountain will remove the automatically uploaded version, otherwise the upload will fail next time.
Download the results in [Release](../../releases)

If you upload rom to WeTransfer to download, modify upload_WeTransfer of yml:'false' ->'true'
After uploading the download link, pay attention to the output result Download Link:‌‌
