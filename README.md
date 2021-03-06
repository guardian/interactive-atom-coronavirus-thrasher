# interactive-atom-thrasher-template

**You will need<br>**
 * [Node.js](http://nodejs.org/)<br>
 * [Homebrew](https://brew.sh/)

## Installation
Clone this repo

**Note:** New thrashers should live within their own branch

 Install project dependencies with
 
```
npm install
```


## Usage

### Creating your Thrasher

```
gulp
```
Run gulp, you should now be running the thrasher locally at: //localhost:8000 
<br>To preview your thrasher use **Immersive Interactive** for DotCom or **Android Front Webview** for Apps.

**To update the code of your thrasher use:**

 * The **congif.json** file to set the title, data sources and folder location (just add your thrashers name)<br>
 * Add html to: **atoms/server/templates/main.html**<br>
 * Add css to: **atoms/client/css/main.scss**<br>
 * Add js to: **atoms/client/js/app.js**

<br>

## Compiling and Deploying

To push your thrasher to preview (pushes to a bucket in CAPI preview) run:

```
gulp deploypreview
```


To push your thrasher to live (pushes to a bucket in CAPI live) run:

```
gulp deploylive
```

To get the URL of your thrasher run:

```
gulp url
```













