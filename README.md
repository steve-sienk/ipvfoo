## IPvGreen

### Overview
IPvGreen is a Chrome extension that provides insight into the sustainability of websites that rely on Amazon's AWS.

It is based on the [IPvFoo extension](https://github.com/pmarks-net/ipvfoo).

### Which AWS servers are sustainable?
As of October 2019, AWS has 5 regions that are advertised as sustainable, they are:
- US West: `us-west-1`
- EU Frankfurt: `eu-central-1`
- EU Ireleand: `eu-west-1`
- US GovCloud: `us-gov-west-1`
- CA Montreal: `ca-central-1`

### Installation

#### Chrome Plugin Installation

[IPvGreen v1.01](https://chrome.google.com/webstore/detail/ipvgreen/japapgcichafkoenponokhilebeejbch) is in the Chrome webstore!

#### Developer Installation
To install the extension from source code, choose `Load unpacked` (Developer mode required) from Chrome's extensions menu and point to the /src directory. 

### Screenshots

##### Example of an AWS server sustainable server
![IPvGreen1](/screenshot.png)
Part of this site was provided sustainably by Amazon Canada's `ca-central-1` AWS server.

##### Example of an AWS server that isn't publically  sustainability
![IPvGreen2](/screenshot2.png)

#### Further reading and thanks
This project was part of Pivotal Hackday 2019.
Thanks to @denise for this bit of info.
"@denise: AWS has only five regions today that are publicly stated to be carbon-neutral: us-west, EU (Frankfurt), EU (Ireland), US GovCloud, and Montreal. 
https://docs.google.com/document/d/1eCCb3rgqtQxcRwLdTr0P_hCK_drIZrm1Dpb4dlPeG6M/edit
"
