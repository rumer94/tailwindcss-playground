# Tailwind CSS Playground

A simple starter project for playing around with Tailwind in a proper PostCSS environment.

This is my personal playground forked from https://github.com/tailwindcss/playground.git

To get started:

1. Clone the repository:

    ```bash
    git clone https://github.com/rumer94/tailwindcss-playground.git tailwindcss-playground

    cd tailwindcss-playground
    ```

2. Install the dependencies:

    ```bash
    # Using npm
    npm install
    ```

3. Start the development server:

    ```bash
    # Using npm
    npm run serve
    ```

    Now you should be able to see the project running at localhost:8080.

4. Open `public/index.html` in your editor and start experimenting!

## Building for production

This project includes an example of setting up both [Purgecss](https://www.purgecss.com/) and [cssnano](https://cssnano.co/) to optimize your CSS for production. It no longer includes [Concurrently](https://github.com/kimmobrunfeldt/concurrently) and [live-server](http://tapiov.net/live-server) because I use vscode [live server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).

To build an optimized version of your CSS, simply run:

```bash
# Using npm
npm run production
```

After that's done, check out `./public/build/tailwind.css` to see the optimized output.
