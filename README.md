# Instabug web SDK

Instabug web sdk is a javascript library to add ability to report bugs from your website and report it to Instabug dashboard.

### Install Instabug
to include instabug web sdk to your website just copy the below lines into the end of your page `<body>` tag
```html
<script src='https://s3.amazonaws.com/instabug-pro/sdk_releases/instabugsdk-1.1.1.min.js'></script>
<script>
  ibgSdk.init({
     token: <INSTABUG_APP_TOKEN>
  });
</script>
```

### API Documentation

#### `.init(options)`
the init function is used to used to inintialize the sdk for the first time, it accepts the options object as parameter, 
the `options` object in now accept only the `token`.

#### `.disable()`
used to hide the report bug button

#### `.enable()`
used to show the report bug button
