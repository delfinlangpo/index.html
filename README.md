
<html>
<head>
    <script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs"></script>
    <script>
        async function loadModel() {
            const model = await tf.loadLayersModel('https://delfinlangpo.github.io/alexnet-tfjs/model.json');
            console.log("Model Loaded!", model);
        }
        loadModel();
    </script>
</head>
<body>
    <h1>AlexNet Hosted on GitHub</h1>
    <p>Check the console to see if the model loads successfully.</p>
</body>
</html>
