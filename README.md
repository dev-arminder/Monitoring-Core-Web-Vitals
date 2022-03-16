# Monitoring Core Web Vitals

This is an example project for showing how to implement a basic **performance monitoring script** to capture **Core Web Vitals**. This is for educational purposes and is not production ready.

## How it Works

- Each time a user visits the home page, a utility JS file calculates the Web Vitals Score using the [Performace Observer API](https://developer.mozilla.org/en-US/docs/Web/API/PerformanceObserver) and sends it in beacon form to the API on page unload
- These **Core Web Vitals Score** can then be saved in a CSV log file under the logs directory and used to improve the field score of each corresponding web vitals.

## How to use

```

npm install
npm start

```

Open a browser at [http://localhost:3000/](http://localhost:3000/) to view the website.
