# ![icon](icon/EP_icon_32x32.png) Export

> A CoverBuilder Plugin

A tool to export multiple PDFs and JPGs.


## Package Extension

The folder [`staging`](./staging) is used to package extensions for Adobe Exchange.

Use `npm run bundle` to bundle the code to staging. Then you can create the packaged `zxp` file:

	bash com.brunoherfst.export.sh

If you want to be able to double click the files set the files permission to executable:

    chmod +x com.brunoherfst.export.sh

Just make sure your OS is opening this file now with Terminal.app and not your favorite code editor.

> Note: You will need an internet connction for the time-stamp.
