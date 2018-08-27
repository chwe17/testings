# What do I need?

1. Official Armbian nightly image (any stable can be switched to nightly from armbian-config)
2. GitHub account credentials

# How to create a test report?

    git clone https://github.com/armbian/testings
    cd testings
    ./createreport.sh

# How they are used?

We are building kernels once per day and these reports are included in this cycle.

Check [here](https://beta.armbian.com/buildlogs/report.html) for current status.

|BOARD|BOOT|VERSION|KERNEL|NETWORK|WIRELESS|HDMI|USB|DVFS|ARMBIANMONITOR|
|-----|----|-------|------|-------|--------|----|---|----|--------------|
|bananapi-default|"yes"|"yes"|"n/a"|"yes"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kQe"|||
|bananapim2ultra-dev|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|"http://ix.io/1kVQ"|||
|bananapim64-next|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|"http://ix.io/1kV6"|||
|bananapi-next|"yes"|"yes"|"n/a"|"yes"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kQc"|||
|cubietruck-default|"yes"|"yes"|"yes"|"yes"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kQ2"|||
|cubietruck-next|"yes"|"yes"|"yes"|"yes"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kPU"|||
|cubox-i-next|:heavy_check_mark:|:heavy_check_mark:|"n/a"|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kVF"|||
|espressobin-default|:heavy_check_mark:|5.59|4.14.67-mvebu64|:heavy_check_mark:|na|na|:heavy_check_mark:|:heavy_check_mark:|http://ix.io/1lia|
|helios4-next|:heavy_check_mark:|5.59.180825|4.14.65-mvebu|:heavy_check_mark:|na|na|:heavy_check_mark:|:heavy_check_mark:|http://ix.io/1lei|
|nanopct3plus-next|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kMg"|||||
|nanopct4-default|:heavy_check_mark:|5.59|4.4.152-rk3399|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|http://ix.io/1lhu|
|nanopiair-next|"n/a"|:heavy_check_mark:|"n/a"|"n/a"|:heavy_check_mark:|"http://ix.io/1kMZ"||||
|nanopik1plus-next|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kMS"||||
|nanopineocore2-next|"yes"|"n/a"|"n/a"|"n/a"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kPF"|||
|orangepilite-default|"yes"|"n/a"|"yes"|"yes"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kQl"|||
|orangepione-next|"yes"|"yes"|"n/a"|"yes"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kQj"|||
|orangepizero-next|:heavy_check_mark:|5.59.180825|4.14.67-sunxi|:heavy_check_mark:|:heavy_check_mark:|NA|:heavy_check_mark:|:heavy_check_mark:|http://ix.io/1lhS|
|orangepizeroplus2-h5-next|"n/a"|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kMz"||||
|orangepizeroplus-next|:heavy_check_mark:|:heavy_check_mark:|"n/a"|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kMJ"||||
|rock64-default|:heavy_check_mark:|5.59|4.4.152-rockchip64|:heavy_check_mark:|na|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|http://ix.io/1lhr|
|udoo-next|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|"http://ix.io/1kMo"||||
