# This source code is limited to exchange and study, where it involves legal issues and I have nothing to do with it

# Version
This is a development version
- Fiat currency transaction, currency transaction

---
- ## [简体中文](README.md)
---

# Donate:
#### Your donation is our biggest motivation for open source
- BTC/USDT (Bitcoin/USDT): 1Dwwqhw9pV9iSSQwuJc8nAygda7XfahaoW
- ETH/USDT (Ethereum/USDT): 0x4f1ea0f10aa99f608f31f70b4d3119f6928693ed
- LTC (Litecoin): LXr4TMtDhCSpdAo98vg2sbvX3UXDVPQvMa


# Front-end development specification
1. The page is named using the camel case method, such as Exchange.vue, WithdrawRecord.vue, the name is English words, and the function of the module must be correctly described
2. It is forbidden to use pinyin for variable naming, especially pinyin abbreviations
3. When there are many pages, folders should be used for classification, such as routing and international management can use the require provided by webpack to implement subcontracting, which is convenient for maintenance;
4. There should be as few data variables as possible in the module, and sub-objects should be used for management when there are more


> A Vue.js project
# be careful
1. The node version must be greater than 8.0, and the corresponding npm version needs to be used. If an error occurs during the installation of dependencies or third-party packages, you can use npm proxy or switch mirroring
2. Because this is a separate version based on a complete version, it may involve leveraged trading and the interface of ieo management. Due to the coupling between pages, it is necessary to track errors and annotate the error-reporting interface;
3. Nginx needs to be configured to enable gzip compression, which can greatly improve the loading speed of the home page and prevent the phenomenon of white screen;
4. Compression-webpack-plugin This plug-in version needs attention. The function of this plug-in is to compress js and css resources in .gz format. Due to the corresponding webpack version, the compression-webpack-plugin plug-in version needs to be reduced. See details package.json file

# Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## Join us
    In order to facilitate everyone to communicate and learn, please join the QQ exchange group:
    *Blockchain exchange technical knowledge exchange group [QQ group: 735446452]

## Update log
2018.7.27
1. Personal assets, handling fees, transaction amount, etc. are cut to 8 decimal places;

2018.7.21
1. Fix the bug of garbled code on some pages of Alipay and WeChat in account settings;

2018.7.20
1. Fix the bug that the currency trading area and the commission record will display scientific counting;

2018.7.18
1. Fix the problem that the value of RMB in currency conversion is incorrect;
2. Optimize the status of the upper left selection area after selecting a trading pair for currency trading;
3. The scientific counting of transaction mining and currency holding dividend pages is converted into numbers;
4. Paging function on the currency holding dividend page;
5. My order for fiat currency transactions adds a contact number;

2018.7.17
1. Fix the BUG of withdrawal record page on the withdrawal page and optimize the screening function;
2. Homepage feature content optimization;

2018.7.16
1. The currency transaction removes the restriction of displaying the price to 2 decimal places;
2. Fix the bug that the currency conversion page converts the RMB value error;
3. On the withdrawal page, the drop-down box of the withdrawal address allows users to manually input;
4. Fix the bug that there is no data in the currency column of the withdrawal record form on the withdrawal page;
5. Fix the BUG that has data but is not displayed on the currency selection page in the withdrawal record form.
6. Modification of legal currency transaction style
7: Add WeChat customer service picture
8: chat content icon replacement
9: Modification of pen lifting accuracy

2018.7.13
1. Increase the paging function for the promotion of friends and my commission;
2. The accuracy of buyPrice is adjusted to 8, in order to solve the error of "quantity error" when entering decimal point value when buying in fiat currency;
3. Style modification; and the QR code is online;

2018.7.12
1. Fix the bug that the value of the legal currency transaction input and the sold quantity cannot be submitted for purchase;
2. Modified the style of the announcement page, and added a revolving light to the homepage announcement;

2018.7.11
1. Replace the banner picture with 1-6;
2. Field modification, buying and selling, and style modification;

2018.7.10
1. Replace the real name with *;

2018.7.9
1. Real-name authentication uploads more than 2M to refuse to submit pictures;

2018.7.8
1. Banner indicator bottom 3px=>20px;
2. Remove the super partner connection;
3. Prompt for failure to upload pictures for real-name authentication;
4. The real-name certification audit failed prompt;
5. Replace 126 with banner map;
6. Fix the bug that the black scroll bar appears in the poptip component on the withdrawal page.

2018.7.7
1. Fix the bug that there are only 3 Chinese titles on the first page of the announcement list page;
2. Fix the problem that js reports an error when the homepage line chart interface returns [];
3. Chinese and English linkage on myextension page;
4. Financial Center=》Remove the nodata error message of holding currency dividend;
5. Remove the QR code from the homepage app download temporarily;
6. The bug that the word does not display after the registration button is clicked.