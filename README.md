# fs-attach-record

Dialog for attaching a record to a person in the tree

## Usage

Configure the client:

```
<fs-client client-id="myclientid" redirect-uri="/fs-auth" environment="sandbox" save-access-token></fs-client>
```

Add the element:

```
<fs-attach-record person-id="PPPP-XYZ"></fs-attach-record>
```

## Installation

Choose one of the following three methods installation methods. All three methods
share the same usage instructions documented above.

### Bower

Install:

```
bower install fs-webcomponents/fs-attach-record
```

Import dependencies on your page (adjust the paths if necessary):

```
<script src="/bower_components/webcomponentsjs/webcomponents-lite.js"></script>
<link rel="import" href="/bower_components/fs-attach-record.html">
```

### Packaged with Vulcanize

This method packages polymer and all components into one file so that the browser
makes significantly fewer requests.

Install the component:

```
bower install fs-webcomponents/fs-attach-record
```

Install [vulcanize](https://github.com/polymer/vulcanize) for packaging:

```
npm install -g vulcanize
```

Run vulcanize:

```
vulcanize --inline-scripts --inline-css --strip-comments bower_components/fs-attach-record/fs-attach-record.html > components.html
```

Import the package on your page:

```
<link rel="import" href="components.html">
```

### Polygit

[Polygit](http://polygit.org/) is experimental. It allows usage of polymer components without bower.

Include these tags on your page:

````
<script src="https://cdn.jsdelivr.net/webcomponentsjs/0.7.14/webcomponents-lite.min.js"></script>
<link href="https://polygit.org/fs-*+fs-webcomponents+:master/components/fs-attach-record/fs-attach-record.html" rel="import">
<fs-client client-id="myclientid" redirect-uri="/" environment="sandbox"></fs-client>
<fs-attach-record person-id="KWCF-GK5" url="http://google.com"></fs-attach-record>
````

Here's a working [jsfiddle](http://jsfiddle.net/jyaq3yyk/1/) example.