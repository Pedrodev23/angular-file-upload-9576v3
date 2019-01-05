# Angular File Upload

+ compatible with AngularJS v1.x

---

## About

Supports drag-n-drop upload, upload progress, validation filters and a file upload queue. It supports native HTML5 uploads, but degrades to a legacy iframe upload method for older browsers. Works with any server side platform which supports standard HTML form uploads.

When files are selected or dropped into the component, one or more filters are applied. Files which pass all filters are added to the queue. When file is added to the queue, for him is created instance of `{FileItem}` and uploader options are copied into this object. After, items in the queue (FileItems) are ready for uploading.

## Package managers
### Bower [![Bower](https://img.shields.io/bower/v/angular-file-upload.svg)](http://bower.io/search/?q=angular-file-upload)
```
bower install angular-file-upload
```
You could find this module in bower like [_angular file upload_](http://bower.io/search/?q=angular-file-upload).

### NPM [![npm](https://img.shields.io/npm/v/angular-file-upload.svg)](https://www.npmjs.com/package/angular-file-upload)
```
npm install angular-file-upload
```
You could find this module in npm like [_angular file upload_](https://www.npmjs.com/package/angular-file-upload).

### Yarn [![npm](https://img.shields.io/npm/v/angular-file-upload.svg)](https://www.npmjs.com/package/angular-file-upload)
```
yarn add --exact angular-file-upload
```
You could find this module in yarn like [_angular file upload_](https://yarnpkg.com/en/package/angular-file-upload).

### Nuget
```
Install-Package AngularFileUpload
```
You could find this module in Nuget like [_angular file upload_](https://www.nuget.org/packages/AngularFileUpload/).

### Module Dependency

Add `'angularFileUpload'` to your module declaration:

```
var app = angular.module('my-app', [
    'angularFileUpload'
]);
```