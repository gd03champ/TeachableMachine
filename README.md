Teachable Machine
=================

TensorFlow.js
------------

This project is an attempt to recreate google's <b>Teachable Machine</b> using `tensorflow.js` 🙂<br><br>
Cick image and process image classification models in seconds without single line of code <br>
Deployed here 👉 [click here](https://teachablemachine-gd.glitch.me)

Project
------------

### ← index.html

We simply have a script tag in our HTML to grab the latest version of TensorFlow.js

In this case we simply reference the following:

```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs/dist/tf.min.js" type="text/javascript"></script>
```

However, if you want to pull in a particular version of TensorFlow.js you can do so like this:

```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.4.0/dist/tf.min.js" type="text/javascript"></script>
```

Optionally, if you want to include our TF.js visualization library you can do so using this import:

```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-vis/dist/tfjs-vis.umd.min.js" type="text/javascript"></script>
```
Visualizing Training ← [More details here](https://github.com/tensorflow/tfjs/tree/master/tfjs-vis).

### ← style.css

Nothing to see here. Just styles to make the demo look prettier. You can use or ignore these as you please.

### ← script.js

This simply grabs a reference to a paragraph in the DOM and then prints out the TensorFlow.js version number to it once loaded.


-------------------
