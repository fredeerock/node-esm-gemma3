# node-esm-gemma3

Since HuggingFace hasn't released Google's Gemma3 model on the main branch of `@huggingface/transformers` yet this shows you how to get it from their new-model branch in a Node.js environment using ECMAScript Modules (ESM). The example utilizes `import` statements for module loading.

## Instructions

1. Clone this repository:
   ```sh
   git clone https://github.com/fredeerock/node-esm-gemma3
   ```
2. Change directory to the `node-esm-gemma3` project:
   ```sh
   cd node-esm-gemma3
   ```
1. Install the `new-model` branch and build the dist folder from the huggingface/transformer.js repo:
   ```sh
   npm install https://github.com/huggingface/transformers.js/archive/new-model.tar.gz
   ```
   ```sh
   cd node_modules/@huggingface/transformers
   ```
   ```sh
   npm install
   ```
   ```sh
   npm run build
   ```
3. Install the dependencies in the top-level folder:
   ```sh
   cd ../../..
   ```
   ```sh
   npm install
   ```
4. Run the example:
   ```sh
   node index.js
   ```
