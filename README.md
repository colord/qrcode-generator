# QR Code Generator

![qrcode-ui](https://user-images.githubusercontent.com/10601293/214124585-d9ac7106-4a40-4133-acce-4198ebaf488e.gif)

## Lessons Learned
- Using the Clipboard API in Javascript, you can easily ask the user's permission to paste the contents of the clipboard into an input element
- Data URLS can be downloaded using the download attribute from the anchor element
- Short circuit evaluation can be used instead of ternary operator. This is useful when you're checking for the existence of the qrcode -- to prevent null data being passed into the qrcode generator function
