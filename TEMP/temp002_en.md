
Kintone UI Component - v0 maintenance stop & migration to v1
https://bozuman.cybozu.com/k/36902/show#record=548

---
title: "End of Support Notice: Kintone UI Component v0"
description: "Kintone UI Component v0 will reach end of support on December 31, 2023."
date: "2023-02-16T00:00:00Z"
hasToc: false
category: "サイト情報"
type: "single"
layout: "news"
---

Thank you for using "Cybozu developer network".  
Kintone UI Component v0 will reach end of support on December 31, 2023.
After this date, we will no longer provide updates including security fixes for this version.
Customers currently using Kintone UI Component v0 need to migrate to Kintone UI Component v1, in order to continue to receive updates.

### Summary{#details}

<!-- textlint-disable no-doubled-joshi -->

With the release of Kintone UI Component v1 (hereinafter referred to as v1) in March 2021, we discontinued the development of new features for [Kintone UI Component v0](https://kintone-labs.github.io/kintone-ui-component/latest/) (hereinafter referred to as v0).
When v0 reach end of support, applications that run on top of this version will continue to run. V0 will still be available for download from GitHub and installation in npm, but no fixes will be made. Additionally, Kintone update may cause Kintone to stop working or break the layout.

<!-- textlint-enable -->

#### How to check your version {#confirm-v0}

Run the following command in your terminal. When you are using v0, it will return `true`.

<!-- eslint-disable -->
```js
!!kintoneUIComponent;
```

### Migration to Kintone UI Component v1{#migration}

If you are using v0 for customization, we recommend that you migrate to [kintone UI Component v1](https://kintone-ui-component.netlify.app/en/) for a more stable version.

V1 includes features that are not available in v0, such as accessibility support and mobile components.  
We are also adding features responding to [Kintone Front-End Architecture](https://blog.kintone.com/company-news/september-2022-product-update).  
Additionally, if you run into any issue and need technical support, you can [contact us](https://jp.cybozu.help/k/en/trouble_shooting/developer/developer_qa.html).  
[GitHub Issue](https://github.com/kintone-labs/kintone-ui-component/issues) also accepts questions and feature requests.

To migrate to v1, you need to modify the source code of the customization.  
For more details, see [A commentary on the difference between v0 and v1](https://kintone-ui-component.netlify.app/docs/en/guides/comparison-v0-v1).

### Feature Difference {#feature-difference}

There are some features in v0 that are not supported anymore in v1. See the documents below for more information:

* [kintone UI Component v1](https://kintone-ui-component.netlify.app/en/)
* [kintone UI Component v0](https://kintone-labs.github.io/kintone-ui-component/latest/)

### Reference {#reference}

//TODO: I don't think we need this part since we have all the related links above. We can add related v0 guides from .devßß. ex:
- [Create Plug-in Setting Pages with Kintone UI Component (v0)](https://kintone.dev/en/plugins/plug-in-tool-guides/create-plug-in-setting-pages-with-kintone-ui-component-v0/)  
- [Create Form Components with Kintone UI Component (v0)](https://kintone.dev/en/tutorials/tool-guides/create-form-components-with-kintone-ui-component-v0/)


