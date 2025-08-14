# sklearn-gradio-wasm-demo
A demo of running sklearn totally in-browser via gradio-lite.

This shows how scikit-learn can be used purely in the browser via [pyodide](https://pyodide.org/en/stable/), a library that transpiles Python code to Javascript. This allows someone to run PCA dimensional reduction in the browser.

This could theoretically be used to run pyodide-compatible Python in the browser, to drive Pol.is-like data pipelines without processing data on backend.

## Screenshot

<img width="80%" height="716" alt="Screenshot 2025-08-14 at 10 19 24 AM" src="https://github.com/user-attachments/assets/103d2968-f638-431f-ad78-9037ff36918d" />

## Attribution

Code came from this comment:

https://github.com/scikit-learn/scikit-learn/issues/24878#issuecomment-3156806200
